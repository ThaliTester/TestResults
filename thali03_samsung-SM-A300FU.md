#### Test 81444731251ddd8_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-26 19:02:38.061  1455  1880 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-26 19:02:38.061  1455  1880 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-26 19:02:38.061  1455  1880 D TP/MmsSmsProvider: need read changed broadcast:false
08-26 19:02:38.061  6598  6798 D Mms/Conversation: [end]    init consume time = 17.258802
08-26 19:02:38.061  6598  6598 D Mms/MmsApp: [end]    onCreate() consume time = 0.267864
08-26 19:02:38.071  6598  6798 D Mms/MessagingNotification: [start]    init() consume time = 5.601511
08-26 19:02:38.081  6598  6798 D Mms/MessagingNotification: [end]    init consume time = 5.407135
08-26 19:02:38.081  6598  6598 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-26 19:02:38.081  6598  6598 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-26 19:02:38.081  6598  6598 D Mms/MethodReflector: getSubId is called
08-26 19:02:38.081  6598  6598 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-26 19:02:38.081  6598  6598 D Mms/MethodReflector: getTelephonyProperty is called
08-26 19:02:38.081  6598  6598 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-26 19:02:38.081  6598  6598 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-26 19:02:38.081  6598  6598 D Mms/DownloadManager: auto download without roaming -> true
08-26 19:02:38.081  6598  6598 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-26 19:02:38.081  6598  6598 D Mms/DownloadManager: mAutoDownload ------> true
08-26 19:02:38.091  6598  6801 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 16.668073
08-26 19:02:38.091  6598  6705 D Mms/ArtClassLoader: init [DONE] art
08-26 19:02:38.091  1455  2014 D TP/MmsSmsProvider: query,matched:0, calling pid = 6598
08-26 19:02:38.091  1455  2014 V TP/MmsSmsProvider: getSimpleConversations entered.
08-26 19:02:38.101  1455  1470 D TP/MmsSmsProvider: query,matched:400, calling pid = 6598
08-26 19:02:38.101  1455  2014 D TP/MmsSmsProvider: match 0:Elapsed time : 0.887 ms
08-26 19:02:38.101  6598  6801 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 9.074167
08-26 19:02:38.101  6598  6802 D Mms/Synchronizer: [start]    doSync consume time = 1.157343
--------- beginning of system
08-26 19:02:38.101  1018  4869 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-26 19:02:38.101  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.101  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.101  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.101  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.121  6803  6803 E Zygote  : MountEmulatedStorage()
08-26 19:02:38.121  6803  6803 E Zygote  : v2
08-26 19:02:38.121  6803  6803 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:38.121  6598  6598 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-26 19:02:38.121  6803  6803 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:38.121  1455  1484 D TP/MmsSmsProvider: update, matched:300, calling pid = 6598
08-26 19:02:38.121  1455  1484 V TP/MmsSmsProvider: syncDBData start
08-26 19:02:38.121  1455  1484 V TP/MmsSmsProvider: syncDBData sms end
08-26 19:02:38.121  1455  1484 V TP/MmsSmsProvider: syncDBData mms end
08-26 19:02:38.121  6803  6803 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 19:02:38.121  1455  1484 V TP/MmsSmsProvider: syncDBData end
08-26 19:02:38.121  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:38.121  1018  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:38.121  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-26 19:02:38.121  6803  6803 I libpersona: KNOX_SDCARD checking this for 10068
08-26 19:02:38.121  6803  6803 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:38.121  1018  4869 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6803 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-26 19:02:38.121  1018  1565 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-26 19:02:38.121  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-26 19:02:38.131  1018  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-26 19:02:38.131  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.131  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.131  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.131  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.141  6598  6802 D Mms/Synchronizer: [end]    doSync consume time = 33.020417
08-26 19:02:38.141  1018  1481 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6815 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-26 19:02:38.151  6815  6815 E Zygote  : MountEmulatedStorage()
08-26 19:02:38.151  6815  6815 E Zygote  : v2
08-26 19:02:38.151  6815  6815 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:38.151  6815  6815 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:38.151  6815  6815 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-26 19:02:38.151  6815  6815 I libpersona: KNOX_SDCARD checking this for 10042
08-26 19:02:38.151  6815  6815 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:38.161  6598  6812 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-26 19:02:38.161  6598  6812 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-26 19:02:38.161  1018  3824 I ActivityManager: Killing 6369:com.android.calendar/u0a131 (adj 15): empty #21
08-26 19:02:38.171  6582  6637 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-26 19:02:38.171  6803  6803 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:38.181  6803  6803 D ActivityThread: Added TimaKeyStore provider
08-26 19:02:38.181  1018  1030 I ActivityManager: Killing 6453:com.android.defcontainer/u0a3 (adj 15): empty #21
08-26 19:02:38.181  6815  6815 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:38.191  6582  6637 I AcmsKeyStoreHelper: Key Store exist
08-26 19:02:38.191  6815  6815 D ActivityThread: Added TimaKeyStore provider
08-26 19:02:38.191  6582  6637 I AcmsKeyStoreHelper: Hence loading the keystore file
08-26 19:02:38.211  6815  6815 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 19:02:38.211  6815  6815 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 19:02:38.211  6815  6815 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 19:02:38.241  6803  6803 D BadgeProvider: onCreate
08-26 19:02:38.241  6803  6803 D BadgeProvider: DatabaseHelper
08-26 19:02:38.261  1899  6661 I qtaguid : Untagging socket 101
08-26 19:02:38.261  1899  1899 I ConfigFetchService: fetch service done; releasing wakelock
08-26 19:02:38.261  1899  1899 I ConfigFetchService: stopping self
08-26 19:02:38.271  6598  6798 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-26 19:02:38.271  6582  6637 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-26 19:02:38.271  6582  6637 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-26 19:02:38.271  6582  6637 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-26 19:02:38.271  6582  6637 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 19:02:38.271  6582  6637 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-26 19:02:38.271  6582  6637 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-26 19:02:38.271  6582  6637 D AcmsCore: This is NOT a valid MirrorLink app
08-26 19:02:38.271  6582  6637 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-26 19:02:38.271  6582  6637 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-26 19:02:38.271  6582  6637 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-26 19:02:38.271  6582  6637 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-26 19:02:38.281  6582  6582 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 19:02:38.281  6582  6582 D AcmsService: Enter onDestroy
08-26 19:02:38.281  6582  6582 I AcmsService: cleanUp(): inside service clean up
08-26 19:02:38.281  6582  6582 D AcmsCore: AcmsCore: inside DeInit
08-26 19:02:38.281  6582  6582 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-26 19:02:38.281  6582  6582 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-26 19:02:38.281  6582  6582 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-26 19:02:38.281  6582  6582 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-26 19:02:38.281  6582  6582 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-26 19:02:38.281  6582  6582 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-26 19:02:38.281  6582  6582 D AcmsService: killing acms process
08-26 19:02:38.281  6582  6582 I Process : Sending signal. PID: 6582 SIG: 9
08-26 19:02:38.291  1455  1470 D TP/SmsProvider: query,matched:26, calling pid = 6598
08-26 19:02:38.291  1455  1470 D TP/SmsProvider: match 26:Elapsed time : 1.962 ms
08-26 19:02:38.301  1455  1880 D TP/MmsSmsProvider: query,matched:6, calling pid = 6598
08-26 19:02:38.301  1455  1880 D TP/MmsSmsProvider: match 6:Elapsed time : 1.042 ms
08-26 19:02:38.311  1018  1481 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 19:02:38.321  1018  1564 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-26 19:02:38.321  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.321  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.321  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.321  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.361  6839  6839 E Zygote  : MountEmulatedStorage()
08-26 19:02:38.361  6839  6839 E Zygote  : v2
08-26 19:02:38.361  1018  1564 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6839 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-26 19:02:38.361  1018  3824 I ActivityManager: Process ACMS.Process (pid 6582)(adj 0) has died(68,755)
08-26 19:02:38.361  6839  6839 I libpersona: KNOX_SDCARD checking this for 10023
08-26 19:02:38.361  6839  6839 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:38.361  6839  6839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:38.361  6839  6839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:38.371  6839  6839 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:38.391  6839  6839 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:38.391  6839  6839 D ActivityThread: Added TimaKeyStore provider
08-26 19:02:38.401  6815  6815 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-26 19:02:38.401  1018  1495 I ActivityManager: Killing 6201:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-26 19:02:38.411  1018  1031 I ActivityManager: Killing 6513:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-26 19:02:38.411  1018  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-26 19:02:38.411  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-26 19:02:38.421  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.421  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.421  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.421  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.431  6836  6836 D AndroidRuntime: 
08-26 19:02:38.431  6836  6836 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 19:02:38.431  6836  6836 D AndroidRuntime: CheckJNI is OFF
08-26 19:02:38.431  6836  6836 D AndroidRuntime: readGMSProperty: start
08-26 19:02:38.431  6836  6836 D AndroidRuntime: readGMSProperty: already setted!!
08-26 19:02:38.431  6836  6836 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 19:02:38.431  6836  6836 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 19:02:38.431  6836  6836 D AndroidRuntime: readGMSProperty: end
08-26 19:02:38.431  6836  6836 D AndroidRuntime: addProductProperty: start
08-26 19:02:38.451  6856  6856 E Zygote  : MountEmulatedStorage()
08-26 19:02:38.451  6856  6856 E Zygote  : v2
08-26 19:02:38.451  6856  6856 I libpersona: KNOX_SDCARD checking this for 10003
08-26 19:02:38.451  6856  6856 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:38.451  6856  6856 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:38.451  1018  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6856 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 19:02:38.451  6856  6856 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:38.451  6856  6856 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:38.481  6856  6856 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:38.481  6856  6856 D ActivityThread: Added TimaKeyStore provider
08-26 19:02:38.521   284   284 E installd: system dir 0 : /system/app/
08-26 19:02:38.521   284   284 E installd: system dir 1 : /system/priv-app/
08-26 19:02:38.521   284   284 E installd: system dir 2 : /vendor/app/
08-26 19:02:38.521   284   284 E installd: system dir 3 : /oem/app/
08-26 19:02:38.541  6839  6839 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-26 19:02:38.541  6598  6798 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-26 19:02:38.571  1018  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-26 19:02:38.591  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-26 19:02:38.591  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-26 19:02:38.591  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-26 19:02:38.591  6836  6836 E AffinityControl: AffinityControl: registerfunction enter
08-26 19:02:38.601  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-26 19:02:38.601  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-26 19:02:38.601  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-26 19:02:38.601  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-26 19:02:38.601  1018  1221 I art     : Explicit concurrent mark sweep GC freed 142343(8MB) AllocSpace objects, 6(1895KB) LOS objects, 33% free, 23MB/34MB, paused 3.909ms total 210.612ms
08-26 19:02:38.611  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-26 19:02:38.611  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-26 19:02:38.611  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-26 19:02:38.611  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-26 19:02:38.611  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-26 19:02:38.611  6839  6839 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-26 19:02:38.621  6836  6836 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 19:02:38.651  6639  6687 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-26 19:02:38.651  6639  6687 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 19:02:38.651  6639  6687 I GAv4    :   adb logcat -s GAv4
08-26 19:02:38.681  6639  6687 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-26 19:02:38.681  1018  1221 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 19:02:38.701  6639  6687 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-26 19:02:38.711  1018  1481 E PersonaManagerService: inState():  stateMachine is null !!
08-26 19:02:38.711  1018  1481 I PersonaManagerService: PersonaId don't exist
08-26 19:02:38.711  1018  1481 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 19:02:38.711  1899  4305 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-26 19:02:38.721  1018  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 19:02:38.731  1018  1481 W ActivityManager: mDVFSHelper.acquire()
08-26 19:02:38.731  1018  1481 D FocusedStackFrame: Set to : 0
08-26 19:02:38.751  6639  6885 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-26 19:02:38.751  6639  6687 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-26 19:02:38.761  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.761  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.761  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.761  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.761  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 19:02:38.761  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 19:02:38.771  6888  6888 E Zygote  : MountEmulatedStorage()
08-26 19:02:38.771  6888  6888 E Zygote  : v2
08-26 19:02:38.771  6888  6888 I libpersona: KNOX_SDCARD checking this for 10170
08-26 19:02:38.771  6888  6888 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:38.771  1018  1481 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6888 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 19:02:38.771  1018  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 19:02:38.771  1018  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 19:02:38.771  1018  1481 D InputDispatcher: Focused application set to: xxxx
08-26 19:02:38.771  1018  1481 D InputDispatcher: Focus left window: 1487
08-26 19:02:38.771  6888  6888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:38.781  6888  6888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:38.781  6888  6888 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 19:02:38.781  6836  6836 D AndroidRuntime: Shutting down VM
08-26 19:02:38.781  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 19:02:38.781  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 19:02:38.781   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-26 19:02:38.801   326   326 I art     : Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 25.102ms
08-26 19:02:38.801  6888  6888 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:38.801  6888  6888 D ActivityThread: Added TimaKeyStore provider
08-26 19:02:38.811  1018  1338 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 19:02:38.811  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 19:02:38.821  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 19:02:38.821  1018  1018 V ActivityManager: Display changed displayId=0
08-26 19:02:38.821  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 19:02:38.831   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 29.822ms
08-26 19:02:38.841  1018  1338 D PersonaManager: isKioskContainerExistOnDevice
08-26 19:02:38.861  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 19:02:38.861   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 853us total 21.248ms
08-26 19:02:38.881   258   437 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-26 19:02:38.891  1487  1487 V ActivityThread: updateVisibility : ActivityRecord{157c7b02 token=android.os.BinderProxy@23f233a9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 19:02:38.891  1487  1487 D Launcher: onTrimMemory. Level: 20
08-26 19:02:38.921  1899  4305 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-26 19:02:38.951  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-26 19:02:38.951  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.951  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.951  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.951  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:38.961  6907  6907 E Zygote  : MountEmulatedStorage()
08-26 19:02:38.961  6907  6907 E Zygote  : v2
08-26 19:02:38.961  6907  6907 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:02:38.961  6907  6907 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:38.961  6907  6907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:38.961  1018  1136 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:02:38.961  6907  6907 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:38.971  6907  6907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:38.981  1018  1031 I ActivityManager: Killing 6537:com.sec.spp.push/u0a32 (adj 15): empty #21
08-26 19:02:38.991  6836  6836 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 19:02:39.001  6907  6907 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:39.001  6907  6907 D ActivityThread: Added TimaKeyStore provider
08-26 19:02:39.001  1899  4305 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-26 19:02:39.031  6888  6888 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 19:02:39.041  1018  1221 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-26 19:02:39.051  6907  6907 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-26 19:02:39.051  1018  1221 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:39.051  1018  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:39.051  1018  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:02:39.051  6907  6907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-26 19:02:39.051  1018  1560 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-26 19:02:39.051  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-26 19:02:39.051  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:39.051  1018  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:39.051  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-26 19:02:39.051  1018  4869 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-26 19:02:39.061  6907  6907 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-26 19:02:39.061  6888  6888 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4683-4685)
08-26 19:02:39.061  6888  6888 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 19:02:39.071  6907  6923 E FilterInstaller: installFilters
08-26 19:02:39.081  1018  1018 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-26 19:02:39.081  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-26 19:02:39.081  6907  6923 E FilterInstaller: There is no requred permission
08-26 19:02:39.081  6888  6888 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19f642d8}
08-26 19:02:39.081  6888  6888 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 19:02:39.081  6888  6888 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 19:02:39.091  1018  1393 D NtpTrustedTime: forceRefresh() from cache miss
08-26 19:02:39.091   278   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:02:39.091   278   988 D Netd    : getNetworkForDns: using netid 502 for uid 1000
08-26 19:02:39.091  1018  1563 I ActivityManager: Killing 6525:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-26 19:02:39.111  1018  1018 I BackgroundCompactionService: onStart. jobID=801
08-26 19:02:39.111  1018  1018 I BackgroundCompactionService: onStart done. jobID=801
08-26 19:02:39.111  1018  6928 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-26 19:02:39.121  1018  6928 I BackgroundCompactionService: compact_memory command done
08-26 19:02:39.131  6639  6905 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 19:02:39.131  6639  6905 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 19:02:39.131  6888  6888 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-26 19:02:39.141  6888  6888 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:02:39.141  1018  1393 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1472230959774 mCachedNtpElapsedRealtime : 94765 mCachedNtpCertainty : 7
08-26 19:02:39.141  1018  1393 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:39.141  1018  1393 D AlarmManagerService: Setting time of day to sec=1472230959
08-26 19:02:39.141  1018  1393 D AlarmManagerService: Trying to open a file
08-26 19:02:39.151  1018  1393 D AlarmManagerService: File Open Success
08-26 19:02:39.151  6888  6888 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 19:02:39.151  1018  1393 D AlarmManagerService: File Close Success
08-26 19:02:39.151  1018  1393 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-26 19:02:39.774  1018  1096 V AlarmManager: waitForAlarm result :65536
08-26 19:02:39.774  1018  1393 W AlarmManagerService: Unable to set rtc to 1472230959: Invalid argument
08-26 19:02:39.774  1018  1096 V AlarmManager: No more alarm at this time.nowELAPSED=94781 batch.start=107929
08-26 19:02:39.774  1018  1018 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472230959788
08-26 19:02:39.774  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-26 19:02:39.774  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
08-26 19:02:39.783  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-26 19:02:39.783  1018  1018 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
08-26 19:02:39.783  1018  1018 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
08-26 19:02:39.793  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
08-26 19:02:39.803  6888  6888 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 19:02:39.803  6888  6888 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 19:02:39.803  6888  6888 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 19:02:39.803  6888  6888 I Adreno-EGL: Local Branch: 
08-26 19:02:39.803  6888  6888 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 19:02:39.803  6888  6888 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 19:02:39.803  6888  6888 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-26 19:02:39.803  1018  1018 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:02:39.813  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 19:02:39.813  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
08-26 19:02:39.813  1018  1018 I DrmEventService:  no response from SecureClock 
08-26 19:02:39.823  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 19:02:39.823  1018  1018 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-26 19:02:39.823  1018  1018 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-26 19:02:39.823  1018  1018 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-26 19:02:39.823  1018  1018 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
08-26 19:02:39.823  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 19:02:39.823  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 19:02:39.823  6639  6905 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-26 19:02:39.833  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-26 19:02:39.833  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-26 19:02:39.833  1018  1563 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-26 19:02:39.833  1018  1563 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:02:39.833  1018  1563 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:02:39.833  1018  1563 D SettingsProvider: selectionArgs: false
08-26 19:02:39.833  1018  1563 D SettingsProvider: selectionArgs: 10049
08-26 19:02:39.833  1018  1563 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:02:39.833  1018  1563 D SettingsProvider: ret = -1
08-26 19:02:39.833  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:39.833  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:39.833  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:39.833  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:39.843  1178  1178 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
08-26 19:02:39.843  1178  1178 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-26 19:02:39.843  1178  1178 I GeometricMosaic_Keyguard: update
08-26 19:02:39.853  1178  1178 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
08-26 19:02:39.853  6935  6935 E Zygote  : MountEmulatedStorage()
08-26 19:02:39.853  6935  6935 E Zygote  : v2
08-26 19:02:39.853  6935  6935 I libpersona: KNOX_SDCARD checking this for 10008
08-26 19:02:39.853  6935  6935 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:39.853  6935  6935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:39.853  1018  1018 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6935 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:39.853  6935  6935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:39.853  6935  6935 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 19:02:39.873  6935  6935 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:39.873  6935  6935 D ActivityThread: Added TimaKeyStore provider
08-26 19:02:39.873   297   297 E SMD     : DCD OFF
08-26 19:02:39.893  6888  6888 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 19:02:39.903  6639  6905 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-26 19:02:39.903  6639  6905 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33ad5b2f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 19:02:39.903  6639  6905 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-26 19:02:39.913  6888  6888 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-26 19:02:39.913  6888  6888 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-26 19:02:39.923  6888  6888 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 19:02:39.923  6888  6888 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 19:02:39.933  1178  1178 I KeyguardEffectViewUtil: set current wallpaper info
08-26 19:02:39.933  1018  3824 D SettingsProvider: name = keyguard_current_wallpaper_type
08-26 19:02:39.933  1018  3824 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:02:39.933  1018  3824 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:02:39.933  1018  3824 D SettingsProvider: selectionArgs: false
08-26 19:02:39.933  1018  3824 D SettingsProvider: selectionArgs: 10049
08-26 19:02:39.933  1018  3824 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:02:39.933  1018  3824 D SettingsProvider: ret = -1
08-26 19:02:39.933  1018  1564 D SettingsProvider: name = keyguard_current_wallpaper_file_path
08-26 19:02:39.933  1018  1564 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:02:39.933  1018  1564 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:02:39.933  1018  1564 D SettingsProvider: selectionArgs: false
08-26 19:02:39.943  1018  1564 D SettingsProvider: selectionArgs: 10049
08-26 19:02:39.943  1018  1564 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:02:39.943  1018  1564 D SettingsProvider: ret = -1
08-26 19:02:39.943  1018  1338 D SettingsProvider: name = keyguard_current_wallpaper_res_id
08-26 19:02:39.943  1018  1338 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:02:39.943  1018  1338 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:02:39.943  1018  1338 D SettingsProvider: selectionArgs: false
08-26 19:02:39.943  1018  1338 D SettingsProvider: selectionArgs: 10049
08-26 19:02:39.943  1018  1338 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:02:39.943  1018  1338 D SettingsProvider: ret = -1
08-26 19:02:39.953  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{16303e9f u0 com.test.thalitest/.MainActivity t163}
08-26 19:02:39.973  6935  6935 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
08-26 19:02:39.993  6935  6935 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
08-26 19:02:39.993  1018  1031 I ActivityManager: Killing 5131:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-26 19:02:40.003  1018  1560 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 19:02:40.003  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
08-26 19:02:40.003  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:40.003  1018  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:40.003  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:02:40.023  1178  1689 D TEST    : run!!!
08-26 19:02:40.043  1178  1689 I GeometricMosaic_Renderer: setBackgroundBitmap
08-26 19:02:40.053  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 19:02:40.053  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
08-26 19:02:40.053  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:40.053  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:40.053  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:02:40.063  6888  6888 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:02:40.063  2824  2824 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Aug 26 19:02:40 GMT+02:00 2016
08-26 19:02:40.063  1018  3824 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 19:02:40.063  1018  3824 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-26 19:02:40.063  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:40.063  1018  3824 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:40.063  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-26 19:02:40.073  6888  6888 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 19:02:40.083  2824  2824 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-26 19:02:40.083  2824  2824 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-26 19:02:40.093  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
08-26 19:02:40.093  2824  2824 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-26 19:02:40.093  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.093  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.093  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.093  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.093  6888  6888 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 19:02:40.093  6888  6888 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-26 19:02:40.093  2824  2824 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-26 19:02:40.093  2824  6966 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
08-26 19:02:40.103  2824  6966 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
08-26 19:02:40.103  2824  6966 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Fri Aug 26 19:02:40 GMT+02:00 2016
08-26 19:02:40.103  6888  6888 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-26 19:02:40.103  6967  6967 E Zygote  : MountEmulatedStorage()
08-26 19:02:40.103  6967  6967 I libpersona: KNOX_SDCARD checking this for 10036
08-26 19:02:40.103  6967  6967 E Zygote  : v2
08-26 19:02:40.103  6967  6967 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:40.103  6967  6967 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:40.113  1018  1136 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6967 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:40.113  6967  6967 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:40.113  6967  6967 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 19:02:40.113  2824  6966 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
08-26 19:02:40.113  2824  2824 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-26 19:02:40.113  6888  6888 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:02:40.113  6888  6888 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:02:40.133  6967  6967 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:40.133  6967  6967 D ActivityThread: Added TimaKeyStore provider
08-26 19:02:40.173  6967  6967 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@9f4bbc0
08-26 19:02:40.183  6967  6967 I SA      : [SSP] onCreated
08-26 19:02:40.193  6967  6967 I SA      : [TPM] There is no property file
08-26 19:02:40.203  6967  6967 I SA      : [SCU] isHaveSA() - false
08-26 19:02:40.203  6967  6967 I SA      : [TPM] getModelProperty : null
08-26 19:02:40.203  6967  6967 I SA      : [TPM] getCSCProperty : null
08-26 19:02:40.203  6967  6967 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 19:02:40.203  6967  6967 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 19:02:40.203  6967  6967 I SA      : [DM] TFT FEATURE: false
08-26 19:02:40.213  6967  6967 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-26 19:02:40.213  6967  6967 I SA      : [DM] init START
08-26 19:02:40.213  6967  6967 I SA      : [DM] This device is not a Vodafone
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-26 19:02:40.223  6967  6967 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 19:02:40.233  6967  6967 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
08-26 19:02:40.233  6888  6989 D OpenGLRenderer: Render dirty regions requested: true
08-26 19:02:40.243  6967  6967 I SA      : [SCU] isHaveSA() - false
08-26 19:02:40.243  1018  3824 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 19:02:40.243  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 19:02:40.243  1018  3824 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 19:02:40.243  1018  3824 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 19:02:40.243  6967  6967 I SA      : support phone number id : false
08-26 19:02:40.243  6967  6967 I SA      : [DM] Supports Ref Jpn : true
08-26 19:02:40.243  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 19:02:40.243  6967  6967 I SA      : [DM] init END
08-26 19:02:40.243  6888  6955 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-26 19:02:40.243  6888  6888 V ActivityThread: updateVisibility : ActivityRecord{2d13459b token=android.os.BinderProxy@a6ed095 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 19:02:40.253  6888  6888 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 19:02:40.253  6888  6888 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 19:02:40.263   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-26 19:02:40.273  1018  1380 D InputDispatcher: Focus entered window: 6888
08-26 19:02:40.283  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 19:02:40.283  6888  6888 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 19:02:40.283  6888  6989 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 19:02:40.283  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 19:02:40.283  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
08-26 19:02:40.293  6888  6989 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-26 19:02:40.293  6888  6989 D OpenGLRenderer: Enabling debug mode 0
08-26 19:02:40.293  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.293  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.293  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.293  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.303  6994  6994 E Zygote  : MountEmulatedStorage()
08-26 19:02:40.303  6994  6994 I libpersona: KNOX_SDCARD checking this for 10058
08-26 19:02:40.303  6994  6994 E Zygote  : v2
08-26 19:02:40.303  6994  6994 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:40.303  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:40.303  1018  1495 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6994 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:40.303  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:40.303  1018  1495 I ActivityManager: Killing 6560:com.samsung.helphub/1000 (adj 15): empty #21
08-26 19:02:40.303  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:40.313  1018  1221 I ActivityManager: Killing 6035:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-26 19:02:40.323  1018  1564 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 19:02:40.323  1178  1178 D PanelView: There is/are notification(s) 
,08-26 19:02:40.333  1018  7007 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 19:02:40.333  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:40.333  6994  6994 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:40.343  1018  1048 I ActivityManager: Displayed Component not be shown by security: +887ms (total +974ms)
,08-26 19:02:40.343  1018  1048 W ActivityManager: mDVFSHelper.release()
,08-26 19:02:40.343  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16303e9f u0 com.test.thalitest/.MainActivity t163} time:95357
,08-26 19:02:40.353  6888  6888 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 19:02:40.353  6888  6888 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a6ed095 time:95363
,08-26 19:02:40.353   258  1102 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 19:02:40.353   258   437 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 19:02:40.363  1962  1962 I SamsungIME: getCurrentCandidateView
,08-26 19:02:40.403  6994  6994 I ExternalOEMControlProvider: onCreate
,08-26 19:02:40.423  1018  1481 I ActivityManager: Killing 6225:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-26 19:02:40.423  1752  1752 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-26 19:02:40.423  1752  1752 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 19:02:40.433  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-26 19:02:40.433  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.433  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.433  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.433  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:40.443  6994  7014 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-26 19:02:40.443  6888  6888 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6888,
,08-26 19:02:40.443  7015  7015 E Zygote  : MountEmulatedStorage()
,08-26 19:02:40.443  7015  7015 E Zygote  : v2
08-26 19:02:40.443  7015  7015 I libpersona: KNOX_SDCARD checking this for 10081
08-26 19:02:40.443  7015  7015 I libpersona: KNOX_SDCARD not a persona,
08-26 19:02:40.453  7015  7015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:40.453  7015  7015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:02:40.453  1018  1495 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7015 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:40.453  7015  7015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:02:40.473  7015  7015 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:40.473  7015  7015 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:40.493  7015  7015 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 19:02:40.493  7015  7015 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 19:02:40.493  7015  7015 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:02:40.493  7015  7015 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 19:02:40.493  7015  7015 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-26 19:02:40.513  1962  1962 D SamsungIME: Dismiss ExpandCandiate
,08-26 19:02:40.543  1018  1136 D SettingsProvider: name = next_alarm_formatted
08-26 19:02:40.543  1018  1136 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:02:40.543  1018  1136 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:02:40.543  1018  1136 D SettingsProvider: selectionArgs: false
08-26 19:02:40.543  1018  1136 D SettingsProvider: selectionArgs: 10081
08-26 19:02:40.543  1018  1136 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:02:40.543  1018  1136 D SettingsProvider: ret = -1
,08-26 19:02:40.663  6888  6888 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,08-26 19:02:40.673  6598  6598 I Mms/MmsApp:  start initViewCache mms
,08-26 19:02:40.673  6598  6598 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1928.191405
08-26 19:02:40.673  1962  1962 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 19:02:40.673  6598  6598 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-26 19:02:40.723  1962  1962 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 19:02:40.733  1962  1962 I SamsungIME: KeybaordView init() : load resources
,08-26 19:02:40.743  6888  7008 D jxcore_app_log: JniHelper::setJavaVM(0xb88972b0), pthread_self() = -1193133624
,08-26 19:02:40.753  6888  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 19:02:40.753  6888  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 19:02:40.753  6888  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 19:02:40.753  6888  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 19:02:40.753  6888  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 19:02:40.753  6888  7008 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39881a4e added. We now have 1 listener(s)
,08-26 19:02:40.763  6888  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-26 19:02:40.763  6888  7008 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 19:02:40.763  6888  7008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:02:40.763  6888  7008 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 19:02:40.773  6888  7008 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fa60905 added. We now have 1 listener(s)
,08-26 19:02:40.773  6888  7008 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:02:40.773  1018  4869 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 19:02:40.773  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.773  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.773  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.773  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:40.783  1962  1962 I SamsungIME: getCurrentKeyboard
08-26 19:02:40.783  1962  1962 I SamsungIME: getTextKeyboard
,08-26 19:02:40.783  6888  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:02:40.783  6888  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 19:02:40.783  6888  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 19:02:40.783  6888  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 19:02:40.783  6888  7008 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 19:02:40.793  7035  7035 E Zygote  : MountEmulatedStorage(),
08-26 19:02:40.793  7035  7035 E Zygote  : v2
08-26 19:02:40.793  7035  7035 I libpersona: KNOX_SDCARD checking this for 10090
08-26 19:02:40.793  7035  7035 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:40.793  7035  7035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:40.793  7035  7035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:40.793  7035  7035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:40.803  1018  4869 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7035 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-26 19:02:40.803  1018  4869 I ActivityManager: Killing 6612:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21,
,08-26 19:02:40.803  6888  7008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:40.803  6888  7008 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-26 19:02:40.813  6888  7008 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 19:02:40.813  6888  7008 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:40.813  6888  7008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:40.813  6888  7008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:40.813  6888  7008 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:40.813  6888  7008 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:40.813  6888  7008 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:40.813  6888  7008 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:40.813  6888  7008 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:40.813  6888  7008 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 19:02:40.813  6888  7008 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:40.813  6888  7008 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 19:02:40.813  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:40.823  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:40.823  6598  6598 D AbsListView: Get MotionRecognitionManager
,08-26 19:02:40.833  1018  1563 D MotionRecognitionService:  ssp status : false
,08-26 19:02:40.843  6598  6598 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 163.971719
,08-26 19:02:40.853  6888  6888 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 19:02:40.863  1962  1962 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 19:02:40.863  7035  7035 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:40.863  7035  7035 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:40.893  1018  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 19:02:40.893  1018  1495 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4223, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 19:02:40.893  1018  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 19:02:40.893  1018  1495 D BatteryService: stay LED for charging
,08-26 19:02:40.893  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 19:02:40.903  1018  1018 I MotionRecognitionService: Plugged
08-26 19:02:40.903  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 19:02:40.913  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 19:02:40.913  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 19:02:40.913  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 19:02:40.913  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 19:02:40.923  3257  3257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 19:02:40.923  3257  3416 D HeadsetStateMachine: Disconnected process message: 10
,08-26 19:02:40.943  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:02:40.943  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 19:02:40.943  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:02:40.953  7035  7035 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-26 19:02:40.953  7035  7035 D elm:15121: ELMEngine.ELMEngine( context ).
,08-26 19:02:40.963  7035  7035 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-26 19:02:40.963  1018  1565 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-26 19:02:40.963  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-26 19:02:40.963  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:40.963  1018  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:40.963  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-26 19:02:40.963  7035  7035 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-26 19:02:40.963  1018  4869 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-26 19:02:40.973  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.973  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.973  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:40.973  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:40.973  7035  7035 D elm:15121: ElmAgentService : onCreate(),
,08-26 19:02:40.983  7035  7052 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-26 19:02:40.983  7053  7053 E Zygote  : MountEmulatedStorage(),
08-26 19:02:40.983  7053  7053 E Zygote  : v2
,08-26 19:02:40.983  7053  7053 I libpersona: KNOX_SDCARD checking this for 10130
08-26 19:02:40.983  7053  7053 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:40.983  1018  4869 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7053 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-26 19:02:40.983  7053  7053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:40.993  7035  7052 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).,
08-26 19:02:40.993  7035  7035 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). ,
,08-26 19:02:40.993  7035  7035 D elm:15121: ModuleBase.ModifySetAlarm()
08-26 19:02:40.993  7035  7035 D elm:15121: MDMBridge.getInstance()
08-26 19:02:40.993  7035  7035 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-26 19:02:40.993  7053  7053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:40.993  7053  7053 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-26 19:02:41.003  7035  7035 D elm:15121: ElmAgentService : onDestroy().
,08-26 19:02:41.013  1018  1560 I ActivityManager: Killing 6639:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-26 19:02:41.013  7053  7053 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:41.023  7053  7053 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:41.033  6598  6598 D Mms/BubbleViewCache: fillCache bubble = 1
,08-26 19:02:41.043  7053  7053 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 19:02:41.043  7053  7053 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-26 19:02:41.063  1018  1560 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-26 19:02:41.063  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.063  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.063  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.063  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:41.073  7070  7070 E Zygote  : MountEmulatedStorage()
,08-26 19:02:41.073  7070  7070 I libpersona: KNOX_SDCARD checking this for 10131
08-26 19:02:41.073  7070  7070 E Zygote  : v2
08-26 19:02:41.073  7070  7070 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:41.083  7070  7070 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:41.083  7070  7070 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:02:41.083  7070  7070 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:41.083  1018  1560 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7070 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-26 19:02:41.083  1018  1560 I ActivityManager: Killing 6138:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-26 19:02:41.103  7070  7070 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:41.103  7070  7070 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:41.113  7070  7070 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 19:02:41.113  7070  7070 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:02:41.123  7070  7070 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 19:02:41.143  2517  5226 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 19:02:41.153  1018  1563 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 19:02:41.163  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-26 19:02:41.163  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:41.163  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:41.163  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 19:02:41.173  1018  1495 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-26 19:02:41.173  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-26 19:02:41.183  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:41.183  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:41.183  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 19:02:41.183  1018  1481 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar,
08-26 19:02:41.183  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.183  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.183  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:41.183  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 19:02:41.193  7091  7091 E Zygote  : MountEmulatedStorage(),
08-26 19:02:41.193  7091  7091 E Zygote  : v2
08-26 19:02:41.193  7091  7091 I libpersona: KNOX_SDCARD checking this for 10037
08-26 19:02:41.193  7091  7091 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:41.193  7091  7091 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:41.203  1018  1481 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7091 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:02:41.203  1018  1380 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-26 19:02:41.203  1018  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:41.203  7091  7091 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:41.203  1018  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.203  1018  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.203  1018  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:41.203  7091  7091 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 19:02:41.223  7091  7091 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 19:02:41.223  7091  7091 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:41.223  7103  7103 E Zygote  : MountEmulatedStorage()
08-26 19:02:41.223  7103  7103 E Zygote  : v2
08-26 19:02:41.223  7103  7103 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:02:41.223  7103  7103 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:41.223  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:41.233  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:41.233  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:41.233  1018  1380 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7103 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 19:02:41.253  7091  7091 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-26 19:02:41.273  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:41.273  7103  7103 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:41.283  7091  7091 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-26 19:02:41.303  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:02:41.303  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 19:02:41.303  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 19:02:41.323  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-26 19:02:41.323  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.323  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.323  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.323  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:41.343  7124  7124 E Zygote  : MountEmulatedStorage(),
,08-26 19:02:41.343  7124  7124 E Zygote  : v2,
08-26 19:02:41.343  7124  7124 I libpersona: KNOX_SDCARD checking this for 10153
08-26 19:02:41.343  7124  7124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:41.343  7124  7124 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:41.343  1018  1495 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7124 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-26 19:02:41.353  1018  1495 I ActivityManager: Killing 6655:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-26 19:02:41.353  7124  7124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:41.353  7124  7124 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:02:41.373   326   326 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 30.930ms
,08-26 19:02:41.383  7124  7124 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:41.383  7124  7124 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:41.393   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 16.893ms
,08-26 19:02:41.403  7124  7124 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 19:02:41.413   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.671ms
,08-26 19:02:41.423  1018  1030 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,08-26 19:02:41.423  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-26 19:02:41.423  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:41.423  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:41.423  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-26 19:02:41.423  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-26 19:02:41.423  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:41.423  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.423  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:41.423  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:41.453  7145  7145 E Zygote  : MountEmulatedStorage()
,08-26 19:02:41.453  7145  7145 E Zygote  : v2
08-26 19:02:41.453  7145  7145 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:02:41.453  7145  7145 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:41.453  7145  7145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 19:02:41.453  7145  7145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:41.453  1018  1136 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:02:41.453  1018  1136 I ActivityManager: Killing 6690:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
08-26 19:02:41.453  7145  7145 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:02:41.483  7145  7145 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:41.483  7145  7145 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:41.513  7145  7145 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472230961524
,08-26 19:02:41.513  1018  1031 I ActivityManager: Killing 6720:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
08-26 19:02:41.513  7145  7145 D         : TimeServiceNative: User Time to be set is 1472230961525
08-26 19:02:41.513  7145  7145 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-26 19:02:41.513  7145  7145 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-26 19:02:41.513  7145  7145 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472230961525
,08-26 19:02:41.513   342   417 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-26 19:02:41.513   342  7160 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472230961525
08-26 19:02:41.513   342  7160 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472230961525, operation = 0
,08-26 19:02:41.513   342  7160 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/21/71 10:45:32
08-26 19:02:41.513   342  7160 D QC-time-services: Daemon:Value read from RTC seconds = 35981132000
08-26 19:02:41.513   342  7160 D QC-time-services: Daemon:new time 1472230961525 
08-26 19:02:41.513   342  7160 D QC-time-services: Daemon: delta 1436249829525 genoff 1436249829525 
08-26 19:02:41.513   342  7160 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249829525 to memory
08-26 19:02:41.513   342  7160 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-26 19:02:41.513   342  7160 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-26 19:02:41.513  7145  7145 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-26 19:02:41.543   342  7160 D QC-time-services: Updating the TOD offset
08-26 19:02:41.543   342  7160 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249829525 to memory
08-26 19:02:41.543   342  7160 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-26 19:02:41.543   342  7160 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-26 19:02:41.543   342  7160 E QC-time-services: Daemon:Update to modem bit set
08-26 19:02:41.543   342  7160 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-26 19:02:41.543   342  7160 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285029525
,08-26 19:02:41.543  7145  7145 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-26 19:02:41.543   342   412 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-26 19:02:41.543   342   417 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-26 19:02:41.543  1018  1565 I ActivityManager: Killing 6706:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-26 19:02:41.553  2517  2517 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 19:02:41.563  2517  2517 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-26 19:02:41.563  2517  2517 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 19:02:41.563  2517  2517 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-26 19:02:41.573  2517  2517 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-26 19:02:41.573  2517  2517 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-26 19:02:41.573  2517  2517 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-26 19:02:41.573  2517  2517 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,08-26 19:02:41.573  2517  2517 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-26 19:02:41.573  2517  2517 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-26 19:02:41.573  2517  2517 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-26 19:02:41.583  2517  2517 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 19:02:41.583  2517  2517 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-26 19:02:41.583  2517  2517 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-26 19:02:41.583  2517  2517 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-26 19:02:41.583  2517  2517 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-26 19:02:41.583  6888  7046 W jxcore-log: Initializing JXcore engine
08-26 19:02:41.583  6888  7046 W jxcore-log: JXcore engine is ready
08-26 19:02:41.583  2517  2517 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-26 19:02:41.593  2517  2517 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-26 19:02:41.603  2517  2517 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-26 19:02:41.603  2517  2517 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-26 19:02:41.643  2051  2051 E audit   : type=1400 msg=audit(1472230961.643:205): avc:  denied  { ioctl } for  pid=7046 comm="Thread-1296" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 19:02:41.643  2051  2051 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:41.643  2051  2051 E audit   : type=1300 msg=audit(1472230961.643:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f36c8f8 items=0 ppid=326 ppcomm=main pid=7046 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1296" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 19:02:41.643  2051  2051 E audit   : type=1320 msg=audit(1472230961.643:205): 
,08-26 19:02:41.653  6888  7046 W jxcore-log: Starting JXcore engine
,08-26 19:02:41.763  6888  7046 W jxcore-log: Platform android
08-26 19:02:41.763  6888  7046 W jxcore-log: 
08-26 19:02:41.763  6888  7046 W jxcore-log: Process ARCH arm
08-26 19:02:41.763  6888  7046 W jxcore-log: 
,08-26 19:02:41.973  6888  7046 I jxcore-log: JXcore Cordova bridge is ready!
08-26 19:02:41.973  6888  7046 I jxcore-log: 
,08-26 19:02:41.973  6888  7046 W jxcore-log: JXcore engine is started
08-26 19:02:41.983  6888  7008 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 19:02:41.983  6888  6888 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 19:02:42.423  7091  7091 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar },
08-26 19:02:42.433  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:42.433  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:42.433  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
08-26 19:02:42.433  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-26 19:02:42.433  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:42.433  1018  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:42.433  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
08-26 19:02:42.433  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:42.433  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:42.443  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
08-26 19:02:42.443  1018  1136 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-26 19:02:42.443  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
08-26 19:02:42.453  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:42.453  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:42.453  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-26 19:02:42.453  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:42.453  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:42.453  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
08-26 19:02:42.463  1018  1221 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-26 19:02:42.463  1018  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
08-26 19:02:42.463  1018  1221 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:42.463  1018  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:42.463  1018  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-26 19:02:42.473  1018  1338 I ActivityManager: Killing 6761:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 19:02:42.483   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8bf37c8
08-26 19:02:42.483   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,08-26 19:02:42.483   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 19:02:42.483   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1195428552)
,08-26 19:02:42.523   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
08-26 19:02:42.523   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 19:02:42.523   273   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1195428552) wakelock released: 1, error no: 0
08-26 19:02:42.523   273   312 I rmt_storage: 
,08-26 19:02:42.523   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8bf37c8
,08-26 19:02:42.873   297   297 E SMD     : DCD OFF
,08-26 19:02:43.513  1018  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 19:02:43.893  1714  1714 I ConfigService: onDestroy
,08-26 19:02:45.883   297   297 E SMD     : DCD OFF,
,08-26 19:02:48.243  1018  3423 D SSRM:n  : SIOP:: AP = 410
,08-26 19:02:48.513  1018  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 19:02:48.883   297   297 E SMD     : DCD OFF
,08-26 19:02:49.233  1018  1057 D PackageManager: [MSG] MCS_UNBIND
,08-26 19:02:49.233  1018  1495 I ActivityManager: Killing 6770:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-26 19:02:49.373  1018  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 19:02:50.933  1018  1565 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 19:02:50.933  1018  1565 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 19:02:50.933  1018  1565 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 19:02:50.933  1018  1565 D BatteryService: stay LED for charging
08-26 19:02:50.933  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 19:02:50.943  1018  1018 I MotionRecognitionService: Plugged
,08-26 19:02:50.943  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 19:02:50.943  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 19:02:50.943  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 19:02:50.943  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 19:02:50.943  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 19:02:50.953  3257  3257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 19:02:50.953  3257  3416 D HeadsetStateMachine: Disconnected process message: 10
,08-26 19:02:50.963  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:02:50.963  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:02:50.973  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:02:51.883   297   297 E SMD     : DCD OFF,
,08-26 19:02:52.913  1018  1096 V AlarmManager: waitForAlarm result :4
,08-26 19:02:52.913  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-26 19:02:53.143  6085  6196 D Finsky  : [1114] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-26 19:02:53.143  6085  6085 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 19:02:53.163  1018  1319 E Watchdog: !@Sync 3
,08-26 19:02:54.543  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 19:02:54.543  6888  7046 I jxcore-log: 
,08-26 19:02:54.543  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 19:02:54.543  6888  7046 I jxcore-log: 
,08-26 19:02:54.543  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:54.543  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:54.543  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:54.543  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:54.543  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:54.543  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:54.543  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:54.543  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:54.553  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:54.553  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 19:02:54.553  6888  7046 I jxcore-log: 
,08-26 19:02:54.553  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 19:02:54.553  6888  7046 I jxcore-log: 
,08-26 19:02:54.583   340   340 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 19:02:54.583   340   340 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 19:02:54.883   297   297 E SMD     : DCD OFF,
,08-26 19:02:55.233  6888  7046 D executeNativeTests: Running unit tests,
,08-26 19:02:55.323  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:02:55.323  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e added. We now have 2 listener(s)
,08-26 19:02:55.323  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:02:55.323  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:02:55.323  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:02:55.323  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:55.323  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f added. We now have 2 listener(s)
08-26 19:02:55.323  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:02:55.323  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:02:55.333  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:55.333  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:55.333  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:55.333  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:55.333  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:55.333  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:55.333  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:55.333  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:55.333  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:55.333  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:55.333  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:55.333  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:02:55.343  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:55.343  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 19:02:55.343  6888  7046 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 19:02:55.343  6888  7046 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:02:55.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:02:55.343  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:55.343  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 19:02:55.343  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.343  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.343  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.343  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.343  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:55.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:02:55.343  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e removed from the list
08-26 19:02:55.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.343  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f removed from the list
,08-26 19:02:55.343  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:55.343  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.343  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.343  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.343  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:02:55.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.343  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 19:02:55.353  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:02:55.353  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.353  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.353  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:55.353  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.353  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.353  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:02:55.353  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.353  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.353  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:55.353  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:02:55.353  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110],
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:02:55.353  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.353  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 19:02:55.353  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 19:02:55.353  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.353  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.353  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
,08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.353  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.353  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.353  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:55.353  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 19:02:55.353  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.353  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.353  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.363  6888  7046 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:02:55.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:55.363  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:55.363  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:55.363  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:55.363  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:55.363  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:55.363  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:55.363  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:55.363  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:55.373  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:55.373  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:02:55.373  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:02:55.373  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:02:55.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:02:55.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:55.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:02:55.373  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.373  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:02:55.373  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.383  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:02:55.383  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:02:55.393  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 19:02:55.393  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage,
,08-26 19:02:55.393  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:02:55.393  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:02:55.393  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:02:55.393  3257  3276 D BtGatt.GattService: registerClient() - UUID=75104636-2ad5-428b-917e-cb39e51b8c04
,08-26 19:02:55.443  3257  3339 D BtGatt.GattService: onClientRegistered() - UUID=75104636-2ad5-428b-917e-cb39e51b8c04, clientIf=6
,08-26 19:02:55.443  6888  6902 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 19:02:55.443  3257  3444 D BtGatt.GattService: start scan with filters
,08-26 19:02:55.443  3257  3414 D BtGatt.ScanManager: handling starting scan
,08-26 19:02:55.443  3257  3414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:02:55.453  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:02:55.453  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:02:55.453  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:02:55.453  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:02:55.453  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:55.453  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:55.453  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:02:55.453  3257  3339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 19:02:55.453  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.453  3257  3414 D BtGatt.ScanManager: allow scan with filters
08-26 19:02:55.453  3257  3414 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 19:02:55.453  3257  3414 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 19:02:55.463  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-26 19:02:55.463  6888  7046 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:02:55.463  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 19:02:55.463  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.463  3257  3414 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:02:55.463  3257  3414 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:02:55.473  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-26 19:02:55.473  6888  7046 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:02:55.473  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:55.473  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 19:02:55.473  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:55.473  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:02:55.473  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 19:02:55.473  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:02:55.473  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:02:55.473  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,08-26 19:02:55.473  3257  3339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 19:02:55.473  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.473  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:02:55.473  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:02:55.483  3257  3410 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:02:55.483  3257  3276 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:02:55.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:55.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:02:55.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:02:55.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:02:55.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:02:55.483  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 19:02:55.483  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:02:55.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:02:55.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:02:55.493  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:02:55.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:02:55.493  3257  3414 D BtGatt.ScanManager: filter size is 1
,08-26 19:02:55.493  3257  3414 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 19:02:55.493  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.493  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:55.493  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:55.493  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:55.493  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.493  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.493  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.493  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.493  6888  7046 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:02:55.493  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:02:55.493  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:55.503  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 19:02:55.503  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.503  3257  3414 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:02:55.503  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 19:02:55.503  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:55.503  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:55.503  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:55.503  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:55.503  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:55.503  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:55.503  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:55.503  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 19:02:55.503  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.513  3257  3414 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 19:02:55.513  3257  3339 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 19:02:55.513  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.513  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:55.513  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:55.513  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.523  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:02:55.523  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 19:02:55.523  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:02:55.523  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:55.523  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:02:55.523  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:02:55.523  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.533  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:02:55.533  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:02:55.533  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:02:55.533  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:02:55.533  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:02:55.533  3257  3276 D BtGatt.GattService: registerClient() - UUID=f2c7d11f-9452-4e60-a564-20ff81cb2264
,08-26 19:02:55.583  3257  3339 D BtGatt.GattService: onClientRegistered() - UUID=f2c7d11f-9452-4e60-a564-20ff81cb2264, clientIf=6
,08-26 19:02:55.583  6888  6897 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 19:02:55.583  3257  3444 D BtGatt.GattService: start scan with filters
,08-26 19:02:55.583  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:02:55.583  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 19:02:55.583  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:02:55.583  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:02:55.583  3257  3414 D BtGatt.ScanManager: handling starting scan
,08-26 19:02:55.593  3257  3339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 19:02:55.593  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:02:55.593  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:02:55.593  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:02:55.593  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.593  3257  3414 D BtGatt.ScanManager: allow scan with filters
08-26 19:02:55.593  3257  3414 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 19:02:55.593  3257  3414 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 19:02:55.593  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:02:55.593  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 19:02:55.593  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.593  3257  3414 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 19:02:55.593  3257  3414 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:02:55.603  3257  3339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 19:02:55.603  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.603  6888  7046 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:02:55.613  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 19:02:55.613  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.613  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:02:55.613  6888  7046 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:02:55.613  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:55.613  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:02:55.623  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.623  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:02:55.623  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 19:02:55.623  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:02:55.623  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:02:55.623  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:02:55.623  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:02:55.623  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:02:55.623  3257  3410 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:02:55.623  3257  3414 D BtGatt.ScanManager: filter size is 1
,08-26 19:02:55.623  3257  3414 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 19:02:55.623  3257  3276 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:02:55.623  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 19:02:55.623  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.623  3257  3414 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:02:55.623  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:55.623  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:02:55.623  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:02:55.623  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:02:55.623  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:02:55.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-26 19:02:55.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 19:02:55.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:02:55.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:02:55.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:02:55.633  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 19:02:55.633  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.633  3257  3414 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 19:02:55.633  3257  3339 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 19:02:55.633  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.633  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:55.633  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.633  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.633  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.633  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:55.633  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 19:02:55.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:02:55.633  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.633  6888  7046 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:02:55.643  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-26 19:02:55.643  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:02:55.643  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:55.643  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:55.643  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:55.643  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:55.643  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:55.643  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:02:55.643  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:55.643  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:55.643  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:55.643  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:55.653  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:55.653  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.653  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.653  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:02:55.653  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:02:55.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 19:02:55.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:55.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:02:55.663  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:02:55.663  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:02:55.663  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:02:55.663  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:02:55.673  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 19:02:55.673  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:02:55.673  3257  3444 D BtGatt.GattService: registerClient() - UUID=acf95b77-8388-45aa-ad0b-6c88e66134af
,08-26 19:02:55.723  3257  3339 D BtGatt.GattService: onClientRegistered() - UUID=acf95b77-8388-45aa-ad0b-6c88e66134af, clientIf=6
,08-26 19:02:55.723  6888  6902 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 19:02:55.723  3257  3268 D BtGatt.GattService: start scan with filters
,08-26 19:02:55.723  3257  3414 D BtGatt.ScanManager: handling starting scan
,08-26 19:02:55.723  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:02:55.723  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:02:55.723  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:02:55.723  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:02:55.723  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:55.723  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:02:55.723  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:02:55.723  3257  3339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 19:02:55.723  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.723  3257  3414 D BtGatt.ScanManager: allow scan with filters
08-26 19:02:55.723  3257  3414 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 19:02:55.723  3257  3414 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 19:02:55.723  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-26 19:02:55.723  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 19:02:55.723  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.723  3257  3414 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:02:55.723  3257  3414 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:02:55.733  6888  7046 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:02:55.733  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.733  6888  7046 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:02:55.733  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.733  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:02:55.733  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:55.733  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:02:55.733  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:02:55.733  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:02:55.733  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 19:02:55.733  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:02:55.733  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 19:02:55.733  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:02:55.733  3257  3339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 19:02:55.733  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.733  3257  3444 D BtGatt.GattService: stopScan() - queue size =1
08-26 19:02:55.733  3257  3268 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:02:55.743  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:02:55.743  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:02:55.743  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:02:55.743  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:02:55.743  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:02:55.743  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:02:55.743  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 19:02:55.743  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:02:55.743  3257  3414 D BtGatt.ScanManager: filter size is 1
,08-26 19:02:55.743  3257  3414 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 19:02:55.743  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 19:02:55.743  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.743  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:02:55.743  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:02:55.743  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:02:55.743  3257  3414 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:02:55.743  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:02:55.753  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:02:55.753  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:02:55.753  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:55.753  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.753  6888  7046 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:02:55.753  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.753  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.753  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:02:55.753  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.753  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.753  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.753  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.753  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-26 19:02:55.753  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.753  3257  3414 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.753  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.753  6888  7046 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 19:02:55.753  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.753  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.753  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.753  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.753  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.753  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.753  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:02:55.753  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.753  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.753  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.753  3257  3339 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-26 19:02:55.753  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:02:55.753  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:02:55.753  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.753  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:55.753  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.753  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.753  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
,08-26 19:02:55.753  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.753  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.753  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.753  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.753  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.753  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.763  6888  7046 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 19:02:55.763  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.763  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.763  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.763  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.763  6888  7046 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 19:02:55.763  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.763  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:55.763  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
,08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.763  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-26 19:02:55.763  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 19:02:55.763  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:02:55.763  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:02:55.763  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.763  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:55.763  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.763  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.763  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:55.763  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.763  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.763  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.763  6888  7046 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:55.763  6888  7046 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 19:02:55.763  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:02:55.773  6888  7046 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:55.773  6888  7046 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:02:55.773  6888  7046 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 19:02:55.773  6888  7046 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:55.773  6888  7046 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-26 19:02:55.773  6888  7046 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:55.773  6888  7046 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:55.773  6888  7046 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 19:02:55.773  6888  7046 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:55.773  6888  7046 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:02:55.773  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 19:02:55.773  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-26 19:02:55.773  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 19:02:55.773  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 19:02:55.773  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 19:02:55.773  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 19:02:55.773  6888  7046 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 19:02:55.773  6888  7046 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:02:55.773  6888  7046 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 19:02:55.773  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:02:55.773  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.773  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.773  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.773  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.773  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.773  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 19:02:55.773  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.773  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:02:55.773  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.773  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.773  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.773  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.773  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.773  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.783  6888  7171 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1360)
08-26 19:02:55.783  6888  7046 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 19:02:55.783  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.783  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.783  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.783  6888  7046 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 19:02:55.783  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.783  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:02:55.783  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.783  6888  7172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1360
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 19:02:55.783  6888  7046 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:02:55.783  6888  7046 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-26 19:02:55.783  6888  7046 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:02:55.783  6888  7046 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:02:55.783  6888  7046 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:02:55.783  6888  7046 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 19:02:55.783  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:02:55.783  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.783  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7171 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.783  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.783  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.783  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.783  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.783  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.783  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.783  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.783  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.793  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.793  6888  7171 D BluetoothSocket: connect(): myUserId = 0
08-26 19:02:55.793  6888  7171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:02:55.793  3257  3276 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:02:55.793  6888  6888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 19:02:55.793  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:02:55.793  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.793  6888  6888 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 19:02:55.793  6888  7171 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:02:55.793  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:55.793  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.793  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:02:55.793  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:02:55.793  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.793  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.793  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.793  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.793  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.793  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.793  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.793  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.793  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.793  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.793  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.803  6888  7046 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 19:02:55.803  6888  7046 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:02:55.803  6888  7173 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 19:02:55.803  6888  7173 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 19:02:55.803  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:02:55.803  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.803  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.803  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.803  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
,08-26 19:02:55.803  6888  6888 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-26 19:02:55.803  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 19:02:55.803  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.803  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list,
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.803  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.803  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:02:55.803  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:02:55.803  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2ac19e not in the list
08-26 19:02:55.803  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.803  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.803  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:02:55.803  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:02:55.803  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:02:55.813  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:02:55.813  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:02:55.813  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:02:55.813  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d66c47f not in the list
08-26 19:02:55.813  6888  7046 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:02:55.813  6888  7046 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 19:02:55.813  6888  7046 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 19:02:55.813  6888  7046 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-26 19:02:55.813  6888  7046 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:02:55.813  6888  7046 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing,
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 19:02:55.813  6888  7046 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-26 19:02:55.813  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:55.813  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26c0a549 added. We now have 2 listener(s)
08-26 19:02:55.813  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:02:55.813  6888  7046 D BluetoothAdapter: enable()
,08-26 19:02:55.813  6888  7046 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 19:02:55.823  1018  1136 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:02:55.823  1018  1136 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:02:55.823  1018  1136 D SecContentProvider2: mCursor = null
,08-26 19:02:55.823  1018  1136 D WifiService: setWifiEnabled: true pid=6888, uid=10170
08-26 19:02:55.823  1018  1136 W ActivityManager: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 19:02:55.823  1018  1136 W WifiService: Failed getting userId using ActivityManagerNative,
08-26 19:02:55.823  1018  1136 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:02:55.823  1018  1136 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:02:55.823  1018  1136 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 19:02:55.823  1018  1136 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 19:02:55.823  1018  1136 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 19:02:55.823  1018  1136 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 19:02:55.823  1018  1136 D SettingsProvider: name = wifi_on
08-26 19:02:55.823  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:55.823  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11d8ce4e added. We now have 3 listener(s)
08-26 19:02:55.823  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:02:55.833  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:02:55.833  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67fcb6f added. We now have 4 listener(s)
08-26 19:02:55.833  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:02:55.833  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:02:55.833  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b3fa07c added. We now have 5 listener(s)
08-26 19:02:55.833  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:02:55.833  1018  1380 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:02:55.833  1018  1380 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:02:55.833  1018  1380 D SecContentProvider2: mCursor = null
,08-26 19:02:55.833  1018  1380 D WifiService: setWifiEnabled: false pid=6888, uid=10170
,08-26 19:02:55.833  1018  1380 D SettingsProvider: name = wifi_on
,08-26 19:02:55.843  1018  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
08-26 19:02:55.843  1392  1392 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 19:02:55.843  1392  1392 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 19:02:55.843  6888  7046 D BluetoothAdapter: disable()
08-26 19:02:55.843  1392  1392 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 19:02:55.843  1392  1392 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 19:02:55.843  1018  3824 D SettingsProvider: name = bluetooth_on
,08-26 19:02:55.853  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-26 19:02:55.863  3257  3336 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-26 19:02:55.863  3257  3336 D BluetoothAdapterProperties: Setting state to 13
08-26 19:02:55.863  3257  3336 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:02:55.863  3257  3336 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:02:55.863  3257  3336 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 19:02:55.863  1018  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:02:55.863  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:02:55.863  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:02:55.863  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:55.863  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:55.863  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:02:55.863  3257  3257 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 19:02:55.863  3257  3257 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@72bad7b, channel: 19, state: LISTENING
08-26 19:02:55.863  3257  3336 D BluetoothAdapterService: Autoconnection is available 
08-26 19:02:55.863  3257  3336 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 19:02:55.863  3257  3336 D BluetoothAdapterService: terminating service from this receiver
,08-26 19:02:55.863  3257  3257 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@72bad7b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f912103, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4968798mSocket: android.net.LocalSocket@8f83bf1 impl:android.net.LocalSocketImpl@15b23d6 fd:FileDescriptor[80]
08-26 19:02:55.863  3257  3257 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@8f83bf1 impl:android.net.LocalSocketImpl@15b23d6 fd:FileDescriptor[80]
,08-26 19:02:55.863  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 19:02:55.873  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:55.873  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:02:55.873  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:55.873  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:55.873  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:55.873  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:55.873  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:55.873  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:55.873  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:55.873  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:55.873  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:55.873  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:02:55.873  1018  1128 E WifiNative-wlan0: do suspend true
,08-26 19:02:55.873  3257  3336 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:02:55.873  3257  3336 D BluetoothAdapterProperties: mDiscovering is false
08-26 19:02:55.873  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:55.873  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:55.873  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:02:55.873  4832  4832 D BluetoothPbap: Proxy object disconnected
08-26 19:02:55.873  4832  4832 D PbapServerProfile: Bluetooth service disconnected
,08-26 19:02:55.873  1018  1565 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 19:02:55.873  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:55.873  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-26 19:02:55.883  3257  3336 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 19:02:55.883  1962  1962 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 19:02:55.883  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 19:02:55.883  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.883  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:02:55.883  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:55.883  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-26 19:02:55.893  4832  4832 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:02:55.903  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:02:55.903  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.913  3257  3339 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 19:02:55.913  3257  3339 D BluetoothAdapterProperties: Scan Mode:20
,08-26 19:02:55.913  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 19:02:55.913  3257  3336 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 19:02:55.913  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:02:55.913  3257  3336 E bt-btif : cmd socket is not created
,08-26 19:02:55.923  6888  7171 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2df7815a, channel: -1, state: INIT
08-26 19:02:55.923  3257  3341 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
08-26 19:02:55.923  6888  7171 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2df7815a, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2167af8b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21244868mSocket: android.net.LocalSocket@12f2b481 impl:android.net.LocalSocketImpl@211c5926 fd:FileDescriptor[106]
08-26 19:02:55.923  6888  7171 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@12f2b481 impl:android.net.LocalSocketImpl@211c5926 fd:FileDescriptor[106]
08-26 19:02:55.923  3257  5302 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:02:55.923  6888  7171 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1360)
,08-26 19:02:55.923  3257  3336 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 19:02:55.923  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:55.923  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:55.923  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:55.923  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:55.923  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:02:55.923  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:55.923  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:02:55.923  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:02:55.923  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:02:55.923  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:02:55.923  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:02:55.933  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.933  1018  1481 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:02:55.933  1018  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:02:55.933  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:02:55.933  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 19:02:55.933  3257  3341 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-26 19:02:55.933  3257  3341 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-26 19:02:55.933  3257  3341 W bt-btif : invalid rfc slot id: 4
,08-26 19:02:55.933  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.933  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:55.943  3257  3341 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 19:02:55.943  3257  3341 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 19:02:55.943  3257  3341 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:02:55.943  3257  3341 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 19:02:55.943  3257  3341 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:02:55.943  3257  3341 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 19:02:55.953  1392  1392 I wpa_supplicant: nl80211: Received scan results (16 BSSes),
,08-26 19:02:55.953  1018  1127 D WifiP2pService: InactiveState{ what=147461 }
,08-26 19:02:55.953  1018  1127 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-26 19:02:55.953  1018  1127 D WifiP2pService: DefaultState{ what=147461 }
,08-26 19:02:55.963  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-26 19:02:55.963  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:02:55.963   278   992 D CommandListener: Clearing all IP addresses on wlan0,
,08-26 19:02:55.963  1714  2548 V NativeCrypto: Read error: ssl=0xb8db3330: I/O error during system call, Connection timed out
,08-26 19:02:55.973  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 19:02:55.973  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-26 19:02:55.973  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 19:02:55.973  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-26 19:02:55.973  1018  1130 E ConnectivityService: updateNetworkInfo()
08-26 19:02:55.973  1018  1130 E ConnectivityService: updateNetworkInfo()
08-26 19:02:55.973  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:55.973  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:55.973  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:55.973  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:55.973  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 19:02:55.983  1018  1127 D WifiP2pService: InactiveState{ what=131204 },
08-26 19:02:55.983  1018  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-26 19:02:55.983  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 19:02:55.983  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 19:02:55.983  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-26 19:02:55.983  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:55.983  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler },
,08-26 19:02:55.983  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:02:55.983  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:02:55.993  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:02:55.993  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:02:55.993  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 19:02:55.993  1018  1127 D WifiP2pService: P2pDisablingState
,08-26 19:02:55.993  1018  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 19:02:55.993  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 19:02:55.993  1018  1127 D WifiP2pService: p2p socket connection lost
,08-26 19:02:55.993  1018  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:02:55.993  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 19:02:55.993  1018  1127 D WifiP2pService: P2pDisabledState
08-26 19:02:55.993  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:02:55.993  1018  1048 D WifiDisplayController: disconnect
08-26 19:02:55.993  1018  1048 D WifiDisplayController: updateConnection
08-26 19:02:55.993  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:02:55.993  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:02:56.003  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:02:56.003  1018  1128 E WifiNative-wlan0: do suspend true
08-26 19:02:56.003  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:02:56.003  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:02:56.003  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:02:56.003  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.003  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.003  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:02:56.003  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-26 19:02:56.003  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:02:56.003  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:02:56.003  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:02:56.023  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 19:02:56.023  1018  1564 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 19:02:56.023  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 19:02:56.043  1018  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 19:02:56.043  1018  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-26 19:02:56.053  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-26 19:02:56.053  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 19:02:56.053  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 19:02:56.053  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:02:56.053  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.053  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.053  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:02:56.063  1018  1030 I art     : Explicit concurrent mark sweep GC freed 34006(1927KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 3.283ms total 183.048ms
,08-26 19:02:56.073  1714  2548 V NativeCrypto: SSL shutdown failed: ssl=0xb8db3330: I/O error during system call, Broken pipe
,08-26 19:02:56.073   278   992 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:02:56.073  1018  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 19:02:56.073  1018  1130 V NetworkStats: updateIfacesLocked()
08-26 19:02:56.073  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.073  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:02:56.073  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:02:56.073  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:02:56.073  1392  1392 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-26 19:02:56.073  4832  4832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:02:56.073  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 19:02:56.073  1018  1380 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-26 19:02:56.073  1018  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.073  1018  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.083  1018  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-26 19:02:56.083  1018  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:02:56.083  1018  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-26 19:02:56.083  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.083  1018  1130 V NetworkStats: performPollLocked() took 11ms
08-26 19:02:56.083  1018  1777 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 19:02:56.083  1018  1777 I qtaguid : Tagging socket 357 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,08-26 19:02:56.083  1018  3824 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 19:02:56.083  1018  3824 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:02:56.083  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.083  1018  3824 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.083  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:02:56.093  1018  1777 I qtaguid : Untagging socket 357
,08-26 19:02:56.093  1018  1777 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 19:02:56.093  1018  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-26 19:02:56.093  3257  3257 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f388544, channel: 5, state: LISTENING
,08-26 19:02:56.093  3257  3257 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f388544, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@42c2880, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a43a62dmSocket: android.net.LocalSocket@2f3da762 impl:android.net.LocalSocketImpl@3e0c50f3 fd:FileDescriptor[82]
08-26 19:02:56.093  3257  3257 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f3da762 impl:android.net.LocalSocketImpl@3e0c50f3 fd:FileDescriptor[82]
,08-26 19:02:56.093  3257  3257 I BtOppRfcommListener: stopping Accept Thread
08-26 19:02:56.093  3257  3257 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3adab1b0, channel: 12, state: LISTENING
08-26 19:02:56.093  3257  3257 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3adab1b0, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20d6010a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f617829mSocket: android.net.LocalSocket@17d2d7ae impl:android.net.LocalSocketImpl@2111094f fd:FileDescriptor[87]
08-26 19:02:56.093  3257  3257 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@17d2d7ae impl:android.net.LocalSocketImpl@2111094f fd:FileDescriptor[87]
08-26 19:02:56.093  3257  5302 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 19:02:56.093  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:02:56.093  1018  1128 D SecContentProvider2: mCursor = null
08-26 19:02:56.093  1018  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 19:02:56.093  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 19:02:56.093  1018  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 19:02:56.093  1018  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 19:02:56.093  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:02:56.093  1178  1785 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 19:02:56.093   278   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:02:56.093   278   988 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-26 19:02:56.093  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 19:02:56.093  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 19:02:56.103  1018  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 19:02:56.103  1018  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 19:02:56.103  1018  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 19:02:56.103  1018  1777 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:02:56.103  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:02:56.103  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:02:56.103  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:02:56.103  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.103  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.103  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.103  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.113  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:02:56.113  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:02:56.113  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:02:56.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:02:56.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.113  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.113  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:02:56.113  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.113  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:02:56.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:02:56.113  1178  1178 D HotspotTile: onReceive : 0, 0
08-26 19:02:56.113  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.113  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:02:56.113  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:02:56.113  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0),
08-26 19:02:56.113  1018  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 19:02:56.113  1018  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 19:02:56.113  1018  1130 E ConnectivityService: updateNetworkInfo()
08-26 19:02:56.113  1018  1130 E ConnectivityService: updateNetworkInfo()
08-26 19:02:56.113  3257  3257 V BluetoothOppManager: cleanUp...
08-26 19:02:56.113  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 19:02:56.113  1018  1131 D Tethering: MasterInitialState.processMessage what=3
08-26 19:02:56.113  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.113  1018  1125 V NetworkStats: updateIfacesLocked()
08-26 19:02:56.113  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:02:56.113  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:02:56.113  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:02:56.113  1018  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 19:02:56.123  4832  4832 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:02:56.123  4832  4832 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 19:02:56.123  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 19:02:56.123  1018  1125 V NetworkStats: performPollLocked() took 5ms
08-26 19:02:56.123  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.123  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.123  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:56.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:56.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:02:56.123  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.123  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:02:56.123  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-26 19:02:56.123  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 19:02:56.123  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 19:02:56.123  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-26 19:02:56.123  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.123  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.123  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:02:56.133  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.133  1018  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 19:02:56.133  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.133  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.133  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.133  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:56.133  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:56.133  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.133  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.133  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.133  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:02:56.133  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 19:02:56.133  3257  3336 D BtConfig.SecureMode: isSecureModeOn:false
08-26 19:02:56.133  3257  3336 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 19:02:56.133  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-26 19:02:56.133  3257  3336 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-26 19:02:56.133  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 19:02:56.133  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 19:02:56.133  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.133  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:02:56.133  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 19:02:56.133  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:02:56.133  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 19:02:56.133  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.133  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:02:56.133  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-26 19:02:56.133  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 19:02:56.133  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-26 19:02:56.133  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-26 19:02:56.133  1018  1338 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:02:56.133  1018  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 19:02:56.143  1392  1392 I wpa_supplicant: Blacklist: Clear (all) 
08-26 19:02:56.143  1018  1338 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.143  1018  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.143  1018  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:02:56.143  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 19:02:56.143  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:02:56.143  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-26 19:02:56.143  1714  1714 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:02:56.143  3257  3257 D HeadsetService: Received stop request...Stopping profile...
,08-26 19:02:56.143  1018  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:02:56.143  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:02:56.143  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.143  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.143  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:02:56.143  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:02:56.143  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:02:56.143  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:02:56.143  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.143  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.143  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.143  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:02:56.143  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 19:02:56.143  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:02:56.143  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:02:56.153  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 19:02:56.153  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 19:02:56.153  4832  4832 D HeadsetProfile: Bluetooth service disconnected
,08-26 19:02:56.153  1018  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:02:56.153  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:02:56.153  3257  3257 D A2dpService: Received stop request...Stopping profile...
08-26 19:02:56.153  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.153  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.153  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:02:56.153  3257  3418 D A2dpStateMachine: Exit Disconnected: -1
,08-26 19:02:56.153  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-26 19:02:56.153  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 19:02:56.153  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 19:02:56.153  1018  4869 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:02:56.153  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 19:02:56.153  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.153  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.153  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:02:56.163  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 19:02:56.163  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 19:02:56.163  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 19:02:56.163  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:02:56.173  1018  1338 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:02:56.173  1018  1338 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:02:56.173  1018  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.173  1018  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:02:56.173  1018  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:02:56.173  4832  4832 D BluetoothA2dp: Proxy object disconnected
,08-26 19:02:56.173  4832  4832 D A2dpProfile: Bluetooth service disconnected
08-26 19:02:56.173  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.173  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.173  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.173  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-26 19:02:56.173  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 19:02:56.183  1018  4869 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:02:56.183  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 19:02:56.183  4832  4832 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:02:56.183  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.183  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.183  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:02:56.183  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 19:02:56.183  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 19:02:56.183  3257  3336 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 19:02:56.193  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:02:56.193  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:02:56.193  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.193  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.193  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:02:56.193  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:02:56.193  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:02:56.193  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:02:56.193  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:02:56.193  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:02:56.193  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:02:56.193  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 19:02:56.193  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:02:56.193  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 19:02:56.193  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 19:02:56.193  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 19:02:56.193  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 19:02:56.193  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 19:02:56.193  3257  3336 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 19:02:56.193  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:02:56.193  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 19:02:56.193  3257  3257 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 19:02:56.193  3257  3257 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:02:56.193  3257  3257 D HidService: Received stop request...Stopping profile...
08-26 19:02:56.193  3257  3257 D HidService: Stopping Bluetooth HidService
08-26 19:02:56.193  3257  3257 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:02:56.193  3257  3257 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 19:02:56.193  3257  3257 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:02:56.193  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:02:56.203  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:02:56.203  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 19:02:56.203  3257  3257 D HealthService: Received stop request...Stopping profile...
,08-26 19:02:56.203  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb,
08-26 19:02:56.203  4832  4832 D BluetoothInputDevice: Proxy object disconnected
08-26 19:02:56.203  4832  4832 D HidProfile: Bluetooth service disconnected
,08-26 19:02:56.203  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 19:02:56.203  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:02:56.203  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 19:02:56.203  3257  3257 D PanService: Received stop request...Stopping profile...
08-26 19:02:56.203  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:02:56.213  3257  3257 D BluetoothA2dp: Proxy object disconnected
,08-26 19:02:56.213  3257  3257 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 19:02:56.213  3257  3419 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 19:02:56.213  3257  3257 I GKI_LINUX: GKI_exit_task 2 done
08-26 19:02:56.213  3257  3257 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 19:02:56.213  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 19:02:56.213  4832  4832 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 19:02:56.213  3257  3257 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 19:02:56.213  4832  4832 D PanProfile: Bluetooth service disconnected
,08-26 19:02:56.213  1018  1564 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 19:02:56.213  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:56.213  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:56.213  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.213  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:56.233  7186  7186 E Zygote  : MountEmulatedStorage()
,08-26 19:02:56.233  1018  1564 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7186 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
08-26 19:02:56.233  7186  7186 E Zygote  : v2
08-26 19:02:56.233  7186  7186 I libpersona: KNOX_SDCARD checking this for 10055
08-26 19:02:56.233  7186  7186 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:56.233  7186  7186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 19:02:56.233  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:02:56.233  3257  3257 D SapService: Received stop request...Stopping profile...
08-26 19:02:56.233  3257  3257 D SapService: Stopping Bluetooth SapService
08-26 19:02:56.233  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:02:56.233  4832  4832 D BluetoothMap: Proxy object disconnected
08-26 19:02:56.233  4832  4832 D MapProfile: Bluetooth service disconnected
08-26 19:02:56.233  7186  7186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:56.233  4832  4832 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 19:02:56.233  4832  4832 D SapProfile: Bluetooth service disconnected
,08-26 19:02:56.233  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 19:02:56.233  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:02:56.233  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.233  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.233  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 19:02:56.233  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:02:56.233  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.233  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.233  3257  3257 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:02:56.233  3257  3257 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:02:56.233  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-26 19:02:56.233  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:02:56.233  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.233  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 19:02:56.233  3257  3257 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:02:56.233  3257  3257 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 19:02:56.243  7186  7186 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:56.243  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 19:02:56.243  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:02:56.243  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:02:56.243  3257  3257 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 19:02:56.243  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 19:02:56.243  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:02:56.243  3257  3257 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 19:02:56.243  3257  3257 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 19:02:56.243  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 19:02:56.243  3257  3336 D BluetoothAdapterProperties: Setting state to 10
08-26 19:02:56.243  3257  3336 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 19:02:56.243  3257  3336 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:02:56.243  3257  3336 D BluetoothAdapterService: updateAdapterState state is 10
08-26 19:02:56.243  3257  3336 D BluetoothAdapterService: Autoconnection is available 
08-26 19:02:56.243  3257  3336 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 19:02:56.243  3257  3336 I BluetoothAdapterState: Entering OffState
08-26 19:02:56.243  4832  4842 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.243  4832  4842 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:02:56.243  1680  4652 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.243  1680  4652 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:02:56.243  4832  4856 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:02:56.243  6888  6902 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.243  6888  6902 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:02:56.243  6888  6902 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 19:02:56.243  6888  6902 D BluetoothLeAdvertiser: Exit stop advertising
08-26 19:02:56.243  6888  6902 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 19:02:56.243  6888  6902 D BluetoothLeScanner: Exiting stopAllScan
08-26 19:02:56.243  1455  3369 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.243  1455  3369 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:02:56.253  1714  2707 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.253  1714  2707 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:02:56.253  4832  4842 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 19:02:56.253  4832  4856 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:02:56.253  1392  1392 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 19:02:56.253  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:02:56.253  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:02:56.253  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:02:56.253  4832  4842 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 19:02:56.253  4832  4842 D Bluetoothsap: Unbinding service...
,08-26 19:02:56.263  1429  1445 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.263  1429  1445 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:02:56.263  1442  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.263  1442  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:02:56.263  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:02:56.273  7186  7186 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:56.273  1178  2150 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.273  1178  2150 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:02:56.273  7186  7186 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:56.273  3257  3444 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:02:56.273  3257  3444 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.273  3257  3444 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:02:56.273  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:02:56.273  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 19:02:56.273  4832  4842 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 19:02:56.273  1392  1392 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 19:02:56.283  1392  1392 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 19:02:56.283  1392  1392 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 19:02:56.283  1392  1392 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 19:02:56.283  1392  1392 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 19:02:56.283  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:02:56.283  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:02:56.283  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:02:56.283  1018  1131 D Tethering: InitialState.processMessage what=4
,08-26 19:02:56.283  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:02:56.283  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-26 19:02:56.283  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:02:56.283  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.293  1018  1131 E Tethering: No numeric data
,08-26 19:02:56.293  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:02:56.293  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:02:56.293  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:02:56.293  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:02:56.293  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:02:56.293  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:56.293  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-26 19:02:56.293  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-26 19:02:56.293  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:02:56.293  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.293  6888  6888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:02:56.303  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:02:56.303  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.303  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 19:02:56.303  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:56.303  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-26 19:02:56.303  1962  1962 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:02:56.303  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:02:56.303  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.303  4832  4832 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:02:56.313  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:02:56.313  1018  1131 D Tethering: clearTetheredNotification()
,08-26 19:02:56.313  1018  1380 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 19:02:56.313  1018  1136 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 19:02:56.313  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:02:56.313  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.313  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:02:56.313  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:02:56.313  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 19:02:56.313  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:02:56.313  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:02:56.313  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:02:56.313  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.323  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.323  1018  1125 V NetworkStats: performPollLocked() took 5ms
,08-26 19:02:56.323  7186  7186 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 19:02:56.323  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:02:56.323  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:56.323  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:02:56.323  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:56.323  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:02:56.323  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:02:56.323  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:02:56.323  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:02:56.333  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:02:56.333  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.333  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 19:02:56.333  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:02:56.333  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:02:56.333  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.333  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 19:02:56.333  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.333  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 19:02:56.333  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 19:02:56.343  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 19:02:56.343  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.343  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-26 19:02:56.343  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 19:02:56.343  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 19:02:56.353  7186  7186 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-26 19:02:56.353  7186  7186 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-26 19:02:56.353  7186  7186 D UserAnalysis: Create SecureDbHelper
,08-26 19:02:56.363  7186  7186 D IntelligenceServiceApplication: onCreate()
,08-26 19:02:56.363  1018  1221 I ActivityManager: Killing 6803:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-26 19:02:56.363  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 19:02:56.363  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.363  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.363  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.363  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:56.373  7186  7186 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 19:02:56.383  7219  7219 E Zygote  : MountEmulatedStorage()
08-26 19:02:56.383  7219  7219 I libpersona: KNOX_SDCARD checking this for 10105
08-26 19:02:56.383  7219  7219 E Zygote  : v2
08-26 19:02:56.383  7219  7219 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:56.383  7219  7219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:56.383  7219  7219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:56.383  7219  7219 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-26 19:02:56.383  1018  1136 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7219 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 19:02:56.393  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 19:02:56.393  7186  7186 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 19:02:56.393  7186  7186 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 19:02:56.403  7219  7219 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:56.413  7219  7219 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:56.463  1392  1392 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 19:02:56.553   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
,08-26 19:02:56.553   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:02:56.553  7219  7238 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 19:02:56.553   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 19:02:56.553   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:02:56.553  7219  7238 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 19:02:56.603  1392  1392 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 19:02:56.603  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:02:56.603  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:02:56.603  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:02:56.613  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:56.613  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-26 19:02:56.623  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:56.633  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:56.643  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:56.713  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 19:02:56.713  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 19:02:56.723  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:02:56.723  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:02:56.723  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:02:56.723  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.723  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.723  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.723  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:56.723  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:02:56.723  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:02:56.723  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 19:02:56.723  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 19:02:56.723  1178  1178 D HotspotTile: onReceive : 1, 0
,08-26 19:02:56.723  4832  4832 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:02:56.723  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:56.723  1680  2158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:02:56.723  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:56.733  7219  7219 D StrictMode: StrictMode policy violation; ~duration=182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:02:56.733  7219  7219 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:02:56.733  7219  7219 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:02:56.733  7219  7219 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:02:56.733  7219  7219 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:02:56.733  7219  7219 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:02:56.733  7219  7219 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:02:56.733  7219  7219 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:02:56.733  7219  7219 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:02:56.743  1018  1565 I ActivityManager: Killing 6815:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
08-26 19:02:56.753  1018  4869 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:02:56.753  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:02:56.753  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.753  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.753  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:02:56.753  1636  1636 I Hs20UtilService: Starting #8
08-26 19:02:56.753  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 19:02:56.753  1636  1651 I Hs20UtilService: Message received 5007
08-26 19:02:56.763  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 19:02:56.763  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 19:02:56.763  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:02:56.763  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:02:56.763  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:02:56.763  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 19:02:56.773  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 19:02:56.773  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 19:02:56.773  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 19:02:56.783  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:02:56.783  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:02:56.783  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:02:56.783  1018  1563 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-26 19:02:56.783  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:02:56.783  1018  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.783  1018  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.783  1018  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.783  1018  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.793  7249  7249 E Zygote  : MountEmulatedStorage()
08-26 19:02:56.793  7249  7249 I libpersona: KNOX_SDCARD checking this for 10064
08-26 19:02:56.793  7249  7249 E Zygote  : v2
08-26 19:02:56.793  7249  7249 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:56.793  7249  7249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:56.793  7219  7244 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-26 19:02:56.793  1018  1563 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7249 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:56.803  7249  7249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:56.803  7249  7249 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:56.813  7249  7249 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:56.823  7249  7249 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:56.823  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:02:56.823  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.823  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:56.823  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 19:02:56.843  7249  7249 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 19:02:56.853  7249  7249 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:02:56.863  7249  7249 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 19:02:56.883  7249  7249 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 19:02:56.893  1018  1565 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 19:02:56.893  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:56.893  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.893  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:56.893  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:56.903  7266  7266 E Zygote  : MountEmulatedStorage()
08-26 19:02:56.903  1018  1565 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7266 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:56.903  7266  7266 E Zygote  : v2
08-26 19:02:56.903  7266  7266 I libpersona: KNOX_SDCARD checking this for 10065
08-26 19:02:56.903  7266  7266 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:56.903  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:56.903  1018  1565 I ActivityManager: Killing 6839:com.wsomacp/u0a23 (adj 15): empty #21
,08-26 19:02:56.913  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:56.913  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:02:56.933  7266  7266 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:56.933  7266  7266 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:56.953  7266  7266 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:02:56.963  1018  1564 I ActivityManager: Killing 6907:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-26 19:02:56.963  1018  1560 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:02:56.963  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:02:56.963  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:56.963  1018  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.963  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:02:56.963  1636  1636 I Hs20UtilService: Starting #9
08-26 19:02:56.963  1636  1651 I Hs20UtilService: Message received 5007
,08-26 19:02:56.973  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:02:56.973  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:02:56.973  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:02:56.973  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:02:56.973  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:02:56.973  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:02:56.973  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:02:56.983  1018  4869 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:02:56.983  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:02:56.983  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:56.983  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.983  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:02:56.983  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 19:02:56.983  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:02:56.983  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 19:02:56.983  1636  1636 I Hs20UtilService: Starting #10
08-26 19:02:56.983  1636  1651 I Hs20UtilService: Message received 5011
,08-26 19:02:56.983  7103  7103 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:02:56.993  1018  1560 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:02:56.993  1018  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:56.993  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.003  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.003  1018  1018 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:57.003  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-26 19:02:57.003  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-26 19:02:57.003  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 19:02:57.003  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.003  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.003  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 19:02:57.013  7281  7281 E Zygote  : MountEmulatedStorage()
,08-26 19:02:57.013  7281  7281 E Zygote  : v2
08-26 19:02:57.013  7281  7281 I libpersona: KNOX_SDCARD checking this for 10102
08-26 19:02:57.013  7281  7281 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:57.013  7281  7281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:57.013  1018  1018 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7281 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 19:02:57.023  7281  7281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:57.023  7281  7281 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 19:02:57.033  7281  7281 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:57.033  7281  7281 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:57.053  7281  7281 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 19:02:57.273  7281  7301 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 19:02:57.273  7281  7301 I Babel_SMS: MmsConfig.loadMmsSettings
,08-26 19:02:57.273  7281  7301 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 19:02:57.273  7281  7301 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 19:02:57.293  7281  7301 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-26 19:02:57.293  7281  7301 I Babel_SMS: MmsConfig.loadFromResources
,08-26 19:02:57.293  7281  7301 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 19:02:57.293  7281  7301 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 19:02:57.313  1018  1495 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 19:02:57.313  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 19:02:57.313  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.313  1018  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:02:57.313  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 19:02:57.333  7281  7281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:02:57.343  7281  7281 I Babel_Crash: startup - clean
,08-26 19:02:57.343  1018  1045 D Tethering: interfaceRemoved wlan0
,08-26 19:02:57.343  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 19:02:57.363  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:57.363  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.363  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.373  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:57.373  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.373  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.373  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:57.373  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.373  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.373  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:57.373  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.373  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.383  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.383  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.383  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.383  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:57.383  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:02:57.383  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.383  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:57.393  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.393  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 19:02:57.393  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.393  7281  7281 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 19:02:57.393  7281  7281 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 19:02:57.393  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.393  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.393  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.393  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.393  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.393  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.403  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.403  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.403  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.403  7281  7281 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 19:02:57.403  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.403  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.403  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.403  7281  7281 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 19:02:57.403  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.403  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.403  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.413  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.413  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.413  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.413  7281  7281 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 19:02:57.413  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:57.413  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.413  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 19:02:57.413  7281  7281 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 19:02:57.413  7281  7281 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 19:02:57.413  7281  7281 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 19:02:57.413  4832  4832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:02:57.413  1018  1481 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 19:02:57.423  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:02:57.423  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:57.423  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:02:57.423  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:02:57.423  1714  1714 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:02:57.433  7281  7281 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 19:02:57.433  7281  7281 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 19:02:57.443  7281  7281 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 19:02:57.443  4832  4832 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:02:57.443  7281  7281 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 19:02:57.443  7281  7281 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 19:02:57.443  4832  4832 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:02:57.443  7281  7281 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 19:02:57.443  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:02:57.443  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 19:02:57.453  7281  7281 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 19:02:57.453  7281  7281 W VideoCapabilities: Unsupported mime video/mp43
,08-26 19:02:57.463  1018  1338 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 19:02:57.463  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:57.463  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:57.463  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:57.463  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.463  7281  7281 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 19:02:57.463  7281  7281 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 19:02:57.473  7306  7306 E Zygote  : MountEmulatedStorage()
08-26 19:02:57.473  7306  7306 E Zygote  : v2
08-26 19:02:57.473  7306  7306 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:02:57.473  7306  7306 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:57.473  7306  7306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:57.473  1018  1338 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7306 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:02:57.473  7306  7306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:57.473  7306  7306 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:02:57.483  1018  1045 D Tethering: interfaceRemoved p2p0
08-26 19:02:57.483  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 19:02:57.493  7281  7281 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 19:02:57.503  7306  7306 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:57.503  7306  7306 D ActivityThread: Added TimaKeyStore provider,
,08-26 19:02:57.523  7306  7306 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 19:02:57.523  7306  7306 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 19:02:57.523  7306  7306 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 19:02:57.523  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:57.533  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:57.533  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:57.533  7281  7281 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:02:57.543  7306  7306 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 19:02:57.543  7306  7306 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-26 19:02:57.543  7306  7306 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 19:02:57.543  1018  1560 I ActivityManager: Killing 6935:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
08-26 19:02:57.543  7306  7306 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:57.543  7281  7281 I vclib   : onServiceConnected
,08-26 19:02:57.543  1018  1380 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-26 19:02:57.543  1018  1380 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-26 19:02:57.543  1018  1380 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-26 19:02:57.543  1018  1380 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
08-26 19:02:57.543  7306  7321 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 19:02:57.543  1018  1380 I ActivityManager: Killing 1899:com.google.android.gms/u0a11 (adj 15): empty #21
,08-26 19:02:57.553  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 19:02:57.553  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.553  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.553  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.553  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.563  7323  7323 E Zygote  : MountEmulatedStorage()
08-26 19:02:57.563  7323  7323 E Zygote  : v2
,08-26 19:02:57.563  7323  7323 I libpersona: KNOX_SDCARD checking this for 10001
,08-26 19:02:57.563  7323  7323 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:57.573  7323  7323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:02:57.573  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7323 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:02:57.573  7323  7323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:02:57.573  7323  7323 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:02:57.583  7323  7323 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:57.583  7323  7323 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:57.663  1018  1565 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 19:02:57.663  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.663  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:57.663  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.663  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.693  7342  7342 E Zygote  : MountEmulatedStorage(),
08-26 19:02:57.693  7342  7342 E Zygote  : v2
08-26 19:02:57.693  7342  7342 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:02:57.693  7342  7342 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:57.693  7342  7342 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:57.693  7342  7342 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:02:57.693  7342  7342 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:57.693  1018  1565 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7342 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:02:57.693  1018  1565 I ActivityManager: Killing 6967:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 19:02:57.713  7342  7342 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:57.713  7342  7342 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:57.753  7342  7342 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 19:02:57.873  7342  7342 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 19:02:57.883   297   297 E SMD     : DCD OFF,
08-26 19:02:57.883  7342  7342 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
08-26 19:02:57.883  7342  7342 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:57.883  7342  7342 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 19:02:57.883  7342  7342 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 19:02:57.893  7342  7342 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 19:02:57.893  1018  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
,08-26 19:02:57.893  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.893  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:57.893  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.893  1018  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:57.903  7357  7357 E Zygote  : MountEmulatedStorage()
,08-26 19:02:57.903  7357  7357 E Zygote  : v2
08-26 19:02:57.903  7357  7357 I libpersona: KNOX_SDCARD checking this for 10008
08-26 19:02:57.903  7357  7357 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:57.903  7357  7357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:57.903  1018  1495 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7357 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:57.903  1018  1495 I ActivityManager: Killing 6598:com.android.mms/u0a41 (adj 15): empty #21
,08-26 19:02:57.913  7357  7357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:57.913  7357  7357 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 19:02:57.953  7357  7357 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:57.953  7357  7357 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:58.003  1018  4869 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gms, hostingType: broadcast
,08-26 19:02:58.003  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.003  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:58.003  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.003  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.013  1018  1481 D CountryDetector: No listener is left
,08-26 19:02:58.033  7373  7373 E Zygote  : MountEmulatedStorage(),
08-26 19:02:58.033  7373  7373 E Zygote  : v2,
08-26 19:02:58.033  1018  4869 I ActivityManager: Start proc com.google.android.gms for broadcast com.google.android.gms/.gcm.gmsproc.GmsAutoStarter: pid=7373 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 19:02:58.033  7373  7373 I libpersona: KNOX_SDCARD checking this for 10011
,08-26 19:02:58.033  7373  7373 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:58.033  1018  4869 I ActivityManager: Killing 6994:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-26 19:02:58.033  7373  7373 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:58.043  7373  7373 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:02:58.043  7373  7373 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 19:02:58.073   326   326 I art     : Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.029ms total 37.419ms
,08-26 19:02:58.083  7373  7373 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:58.083  7373  7373 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:58.093   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 683us total 19.583ms
,08-26 19:02:58.113   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 685us total 19.497ms
,08-26 19:02:58.113  7373  7373 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 19:02:58.113  7373  7373 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 19:02:58.153  7373  7373 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-26 19:02:58.153  7373  7373 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 19:02:58.163  7373  7373 I MultiDex: VM with version 2.1.0 has multidex support
08-26 19:02:58.163  7373  7373 I MultiDex: install
08-26 19:02:58.163  7373  7373 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 19:02:58.193  1018  1050 I PowerManagerService: [PWL] Off : 50s ago
,08-26 19:02:58.193  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-26 19:02:58.193  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-26 19:02:58.193  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=2082)
,08-26 19:02:58.263  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 19:02:58.263  1018  3423 D SSRM:n  : SIOP:: AP = 400
,08-26 19:02:58.293  7373  7373 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 19:02:58.343  7373  7373 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 19:02:58.343  7373  7373 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14e9c774: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 19:02:58.343  7373  7373 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 19:02:58.353  1018  1221 I ActivityManager: Killing 6253:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 19:02:58.353  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 19:02:58.353  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 19:02:58.363  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:58.363  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:58.363  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:02:58.383  7373  7391 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-26 19:02:58.403  7373  7395 I iu.SyncManager: SYNC; picasa accounts
,08-26 19:02:58.433  7373  7373 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-26 19:02:58.453  1018  1565 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:02:58.453  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-26 19:02:58.453  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:58.453  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:58.453  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:02:58.473  7373  7373 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 19:02:58.503  7373  7373 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-26 19:02:58.503  2824  2824 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 19:02:58 GMT+02:00 2016
,08-26 19:02:58.503  1018  1380 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 19:02:58.503  1018  1380 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 19:02:58.513  1018  1380 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:58.513  1018  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:02:58.513  1018  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 19:02:58.513  2824  2824 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 19:02:58.513  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 19:02:58.523  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.523  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:58.523  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:58.523  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.523  2824  2824 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
,08-26 19:02:58.523  2824  2824 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,08-26 19:02:58.523  2824  2824 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 19:02:58.533  1018  1136 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7400 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
08-26 19:02:58.533  2824  7399 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-26 19:02:58.533  7400  7400 E Zygote  : MountEmulatedStorage()
08-26 19:02:58.533  7400  7400 E Zygote  : v2
08-26 19:02:58.533  7400  7400 I libpersona: KNOX_SDCARD checking this for 10031
08-26 19:02:58.533  7400  7400 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:58.533  7400  7400 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:58.533  2824  7399 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 19:02:58.543  7400  7400 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:58.543  2824  7399 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-26 19:02:58.543  7400  7400 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:02:58.543  2824  7399 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
08-26 19:02:58.543  2824  2824 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 19:02:58.563  7400  7400 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 19:02:58.563  7400  7400 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:58.593  7400  7400 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 19:02:58.603  1018  1136 I ActivityManager: Killing 7015:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-26 19:02:58.613  1018  1565 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 19:02:58.613  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.613  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:58.613  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.613  1018  1565 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.623  2763  7415 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false,
,08-26 19:02:58.633  7416  7416 E Zygote  : MountEmulatedStorage()
,08-26 19:02:58.633  7416  7416 E Zygote  : v2
08-26 19:02:58.633  7416  7416 I libpersona: KNOX_SDCARD checking this for 10032
08-26 19:02:58.633  7416  7416 I libpersona: KNOX_SDCARD not a persona,
,08-26 19:02:58.633  7416  7416 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 19:02:58.633  1018  1565 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7416 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:58.633  2763  7415 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 19:02:58.633  2763  7415 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-26 19:02:58.633  7416  7416 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:58.633  2763  7415 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-26 19:02:58.633  2763  7415 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 19:02:58.643  7416  7416 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 19:02:58.663  7416  7416 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:02:58.663  7416  7416 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:58.723  7416  7431 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-26 19:02:58.723  7416  7431 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 19:02:58.723  7416  7416 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 19:02:58.733  7416  7431 D SPPClientService: PushLog.txt file is not deleted.
,08-26 19:02:58.733  1018  1338 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 19:02:58.733  7416  7431 D SPPClientService: PushLog.txt file is not deleted.
,08-26 19:02:58.733  7416  7431 D SPPClientService: ============PushLog. stop!
,08-26 19:02:58.733  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:58.733  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:58.733  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:58.733  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.763  7434  7434 E Zygote  : MountEmulatedStorage(),
08-26 19:02:58.763  7434  7434 E Zygote  : v2
,08-26 19:02:58.763  7434  7434 I libpersona: KNOX_SDCARD checking this for 10036
,08-26 19:02:58.763  7434  7434 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:58.763  7434  7434 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 19:02:58.763  1018  1338 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7434 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:58.763  1018  1338 I ActivityManager: Killing 7035:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-26 19:02:58.773  7434  7434 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:58.773  7434  7434 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 19:02:58.773  1018  1563 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 19:02:58.773  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:58.773  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-26 19:02:58.773  1018  1563 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 19:02:58.773  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-26 19:02:58.793  7434  7434 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:58.793  7434  7434 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:58.803  7416  7442 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 19:02:58.833  7434  7434 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@9f4bbc0
,08-26 19:02:58.843  7434  7434 I SA      : [SSP] onCreated
,08-26 19:02:58.853  7434  7434 I SA      : [TPM] There is no property file
,08-26 19:02:58.853  7434  7434 I SA      : [SCU] isHaveSA() - false
,08-26 19:02:58.853  7434  7434 I SA      : [TPM] getModelProperty : null
,08-26 19:02:58.853  7434  7434 I SA      : [TPM] getCSCProperty : null
,08-26 19:02:58.853  7434  7434 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-26 19:02:58.853  7434  7434 I SA      : [DM] PRODUCT AMOLED FEATURE: false
,08-26 19:02:58.863  7434  7434 I SA      : [DM] TFT FEATURE: false
,08-26 19:02:58.863  7434  7434 I SA      : [DM] init START
,08-26 19:02:58.863  7434  7434 I SA      : [DM] This device is not a Vodafone
,08-26 19:02:58.863  7434  7434 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 19:02:58.873  7434  7434 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 19:02:58.883  7434  7434 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75),
08-26 19:02:58.883  7434  7434 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 19:02:58.883  7434  7434 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 19:02:58.883  7434  7434 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-26 19:02:58.883  7434  7434 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-26 19:02:58.883  7434  7434 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 19:02:58.883  7434  7434 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 19:02:58.883  1018  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:02:58.883  1018  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:02:58.883  1018  1495 D SecContentProvider2: mCursor = null
,08-26 19:02:58.883  1018  1495 D WifiService: setWifiEnabled: true pid=6888, uid=10170
,08-26 19:02:58.883  1018  1495 W ActivityManager: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 19:02:58.883  1018  1495 W WifiService: Failed getting userId using ActivityManagerNative
08-26 19:02:58.883  1018  1495 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:02:58.883  1018  1495 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:02:58.883  1018  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 19:02:58.883  1018  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 19:02:58.883  1018  1495 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 19:02:58.883  1018  1495 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 19:02:58.883  1018  1495 D SettingsProvider: name = wifi_on
,08-26 19:02:58.883  7434  7434 I SA      : [SCU] isHaveSA() - false
,08-26 19:02:58.883  7434  7434 I SA      : support phone number id : false
08-26 19:02:58.883  7434  7434 I SA      : [DM] Supports Ref Jpn : true
08-26 19:02:58.883  7434  7434 I SA      : [DM] init END
,08-26 19:02:58.883  7434  7434 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 19:02:58.893  1018  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 19:02:58.893  7434  7434 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 19:02:58.893  7434  7434 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 19:02:58.933  7434  7434 I SA      : [SLFUCHKMGR] constructor called
,08-26 19:02:58.943  7434  7434 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 19:02:58.943  7434  7434 I SA      : [OR] == isSIMCardReady false ==
,08-26 19:02:58.943  7434  7434 I SA      : [SCU] == networkStateCheck == false
,08-26 19:02:58.943  7434  7434 I SA      : [OR] onReceive END
,08-26 19:02:58.943  1018  1221 I ActivityManager: Killing 7124:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-26 19:02:58.953  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:02:58.953  1752  1752 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 19:02:58.973  2517  5226 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,08-26 19:02:58.973  1752  1752 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-26 19:02:58.973  1752  1752 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-26 19:02:58.973  1752  1752 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-26 19:02:58.973  1752  1752 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 19:02:58.983  1752  1752 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 19:02:58.983  1752  1752 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 19:02:58.983  1018  1564 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 19:02:58.983  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.983  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:58.983  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.983  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:58.993  7457  7457 E Zygote  : MountEmulatedStorage()
08-26 19:02:58.993  1018  1564 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7457 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:02:58.993  7457  7457 E Zygote  : v2
08-26 19:02:58.993  7457  7457 I libpersona: KNOX_SDCARD checking this for 10077
08-26 19:02:58.993  7457  7457 I libpersona: KNOX_SDCARD not a persona
,08-26 19:02:59.003  7457  7457 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:59.003  7457  7457 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:02:59.003  7457  7457 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-26 19:02:59.013  7457  7457 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:59.013  7457  7457 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:59.223  1018  1565 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-26 19:02:59.223  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 19:02:59.223  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:59.223  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:02:59.223  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 19:02:59.233  1018  4869 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 19:02:59.233  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:59.233  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:02:59.233  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:59.233  1018  4869 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:02:59.243  1018  4869 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7482 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-26 19:02:59.243  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:02:59.243  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 19:02:59.243  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:59.243  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-26 19:02:59.243  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-26 19:02:59.253  7482  7482 E Zygote  : MountEmulatedStorage()
08-26 19:02:59.253  7482  7482 E Zygote  : v2
08-26 19:02:59.253  7482  7482 I libpersona: KNOX_SDCARD checking this for 10110
08-26 19:02:59.253  7482  7482 I libpersona: KNOX_SDCARD not a persona
08-26 19:02:59.253  7281  7481 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 19:02:59.253  7482  7482 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:02:59.253  7482  7482 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:02:59.253  7482  7482 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 19:02:59.253  1018  1563 I ActivityManager: Killing 7091:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-26 19:02:59.273  1018  1045 D Tethering: interfaceAdded wlan0
,08-26 19:02:59.273  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:02:59.273  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 19:02:59.273  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:02:59.283  7482  7482 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:02:59.283  7482  7482 D ActivityThread: Added TimaKeyStore provider
,08-26 19:02:59.283  1018  1131 E Tethering: No numeric data
08-26 19:02:59.283  1018  1045 D Tethering: interfaceAdded p2p0,
08-26 19:02:59.283  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 19:02:59.283  1018  1131 D Tethering: clearTetheredNotification()
08-26 19:02:59.283  1018  1131 D Tethering: InitialState.processMessage what=4
,08-26 19:02:59.283  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:59.283  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:02:59.293  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:02:59.293  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:02:59.293  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:02:59.293  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 19:02:59.293  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 19:02:59.293  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:59.293  1018  1125 V NetworkStats: performPollLocked() took 4ms
,08-26 19:02:59.293  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:02:59.293  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:02:59.293  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:02:59.293  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:59.293  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:02:59.293  1018  1131 E Tethering: No numeric data
08-26 19:02:59.293   278   992 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 19:02:59.293  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:02:59.293  1018  1131 D Tethering: clearTetheredNotification()
,08-26 19:02:59.293   278   992 D SoftapController: Softap fwReload - Ok
,08-26 19:02:59.293  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:59.293  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:02:59.293   278   992 D CommandListener: Setting iface cfg
08-26 19:02:59.293   278   992 D CommandListener: Trying to bring down wlan0
08-26 19:02:59.303  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:02:59.303  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:02:59.303   278   992 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:02:59.303  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:02:59.303  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 19:02:59.303  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 19:02:59.303  1018  1125 V NetworkStats: performPollLocked() took 4ms
,08-26 19:02:59.303  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:02:59.303  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:02:59.303  1018  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 19:02:59.373  7498  7498 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 19:02:59.373  7498  7498 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 19:02:59.373  7498  7498 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 19:02:59.403  1018  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-26 19:02:59.413  4832  4832 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:02:59.423  1018  4869 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 19:02:59.423  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:02:59.423  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:02:59.423  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:02:59.423  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:02:59.423  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:02:59.423  1178  1178 D HotspotTile: onReceive : 2, 0
08-26 19:02:59.423  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:59.423  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:59.423  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:59.423  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:02:59.423  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:02:59.423  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 19:02:59.423  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:02:59.423  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:02:59.433  7498  7498 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-26 19:02:59.433   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7498
08-26 19:02:59.433   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-26 19:02:59.433  7498  7498 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 19:02:59.433  7498  7498 I wpa_supplicant: ssSupport state is = 1
08-26 19:02:59.433  7498  7498 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 19:02:59.433  7498  7498 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 19:02:59.433   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7498
08-26 19:02:59.433   398   398 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-26 19:02:59.573  7482  7482 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 19:02:59.573  7482  7482 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 19:02:59.573  7482  7482 I GAv4    :   adb logcat -s GAv4
,08-26 19:02:59.583   340   340 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 19:02:59.593  7482  7482 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:02:59.593  1018  1565 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 19:02:59.593   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 19:02:59.593   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:02:59.593  7482  7503 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 19:02:59.603   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 19:02:59.603   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:02:59.603  7482  7503 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 19:02:59.613   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-26 19:02:59.613  7482  7482 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:02:59.613  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-26 19:02:59.613   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 19:02:59.613   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:02:59.613  7482  7505 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 19:02:59.613   257   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 19:02:59.613   257   518 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:02:59.613  7482  7505 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 19:02:59.623  7482  7506 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:02:59.663  7498  7498 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 19:02:59.663  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 19:02:59.673  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-26 19:02:59.673   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7498,
08-26 19:02:59.673   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 19:02:59.673  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-26 19:02:59.673  7498  7498 I wpa_supplicant: ssSupport state is = 1
08-26 19:02:59.673  7498  7498 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 19:02:59.673  7498  7498 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:02:59.673  7498  7498 E wpa_supplicant: SIM READ ERROR
08-26 19:02:59.673  7498  7498 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:02:59.673  7498  7498 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:02:59.673  7498  7498 E wpa_supplicant: SIM READ ERROR,
08-26 19:02:59.673  7498  7498 I wpa_supplicant: Blacklist: Clear (all) 
08-26 19:02:59.673  7498  7498 I wpa_supplicant: wpa_default_ap_write_once
08-26 19:02:59.673  7498  7498 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-26 19:02:59.673  7498  7498 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:02:59.673  7498  7498 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,08-26 19:02:59.673  7498  7498 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:02:59.673  7498  7498 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 19:02:59.683  7498  7498 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 19:02:59.683  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 19:02:59.683  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:02:59.683  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:02:59.773  7498  7498 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 19:02:59.853  1018  4869 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:02:59.853  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:02:59.853  1018  4869 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:02:59.853  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 19:02:59.883  7482  7482 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 19:02:59.903  7482  7482 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4913-4915),
08-26 19:02:59.903  7482  7482 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 19:02:59.933  7482  7482 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {72bad7b}
,08-26 19:02:59.933  7482  7482 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 19:02:59.933  7482  7482 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:02:59.943  7498  7498 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 19:02:59.943  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage,
,08-26 19:02:59.953  7482  7482 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 19:02:59.953  7482  7482 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-26 19:02:59.953  7482  7482 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 19:02:59.963  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-26 19:02:59.963  7482  7482 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 19:02:59.963  7482  7482 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 19:02:59.963  7482  7482 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 19:02:59.963  7482  7482 I Adreno-EGL: Local Branch: 
08-26 19:02:59.963  7482  7482 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 19:02:59.963  7482  7482 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 19:02:59.963  7482  7482 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 19:02:59.973   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7498
08-26 19:02:59.973   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 19:02:59.973  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 19:02:59.973  7498  7498 I wpa_supplicant: ssSupport state is = 1
,08-26 19:02:59.973  7498  7498 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 19:02:59.973  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 19:02:59.983  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 19:02:59.983   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7498
,08-26 19:02:59.983   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-26 19:02:59.983  7498  7498 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 19:02:59.983  7498  7498 I wpa_supplicant: ssSupport state is = 1
08-26 19:02:59.983  7498  7498 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:02:59.983  7498  7498 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 19:02:59.983  7498  7498 E wpa_supplicant: SIM READ ERROR
08-26 19:02:59.983  7498  7498 I wpa_supplicant: wpa_default_ap_write_once
08-26 19:02:59.983  7498  7498 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 19:02:59.983  7498  7498 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 19:02:59.983  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:02:59.983  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:02:59.983  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-26 19:02:59.983  1018  1096 V AlarmManager: waitForAlarm result :8
,08-26 19:02:59.983  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:02:59.983  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:02:59.983  1018  1045 D Tethering: interfaceStatusChanged p2p0, false,
,08-26 19:03:00.023  7482  7537 W cr.media: Requires BLUETOOTH permission
,08-26 19:03:00.033  7482  7482 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 19:03:00.043  7482  7482 I NSApplication: Starting up...
,08-26 19:03:00.043  1018  1136 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 19:03:00.053  1018  1221 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 19:03:00.053  7498  7498 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-26 19:03:00.053  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 19:03:00.053  1018  1560 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 19:03:00.053  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.053  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:00.053  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.053  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.063  7542  7542 E Zygote  : MountEmulatedStorage()
,08-26 19:03:00.063  7542  7542 E Zygote  : v2
08-26 19:03:00.063  7542  7542 I libpersona: KNOX_SDCARD checking this for 10117
08-26 19:03:00.063  7542  7542 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:00.063  7542  7542 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:03:00.073  1018  1560 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7542 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 19:03:00.073  7542  7542 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:03:00.073  7542  7542 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 19:03:00.073  1018  1560 I ActivityManager: Killing 7145:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-26 19:03:00.093  7542  7542 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:03:00.093  7542  7542 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:00.113  7542  7542 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:03:00.173  7498  7498 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 19:03:00.173  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 19:03:00.173  7498  7498 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 19:03:00.173  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 19:03:00.183  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 19:03:00.183  7498  7498 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 19:03:00.183  7498  7498 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:03:00.183  7498  7498 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:03:00.183  7498  7498 E wpa_supplicant: SIM READ ERROR
08-26 19:03:00.183  7498  7498 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 19:03:00.203  7498  7498 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 19:03:00.223  7498  7498 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 19:03:00.223  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:00.233  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:03:00.233  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:00.233  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:00.233  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:00.233  1018  1128 D WifiConfigStore: Loading config and enabling all networks 
08-26 19:03:00.233  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:00.233  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:00.233  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-26 19:03:00.233  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 19:03:00.233  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:00.233  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 19:03:00.233  1178  1178 D HotspotTile: onReceive : 3, 0
,08-26 19:03:00.243  4832  4832 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:00.243  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:03:00.243  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:00.243  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:00.243  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:00.243  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:00.243  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:00.243  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:00.243  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:00.243  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:00.243  1018  1128 E WifiConfigStore: Not a HS20
,08-26 19:03:00.243  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:03:00.243  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:00.253  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:03:00.253  1018  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 19:03:00.253  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:00.253  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:00.253  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:00.253  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:00.253  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:00.253  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:00.253  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:00.253  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:00.253  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:03:00.253  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:00.253  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 19:03:00.253  7498  7498 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 19:03:00.253  7498  7498 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 19:03:00.253  7498  7498 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 19:03:00.253  7498  7498 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 19:03:00.253  7498  7498 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 19:03:00.253  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 19:03:00.253  7498  7498 I wpa_supplicant: First Scan Start
08-26 19:03:00.253  7498  7498 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 19:03:00.253  1018  1128 D WifiNative-wlan0: Setting external_sim to 1,
08-26 19:03:00.253  1018  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:03:00.253  1018  1128 I WifiNative-HAL: startHal
08-26 19:03:00.253  7281  7281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:03:00.253  1018  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f42e88c
08-26 19:03:00.253  1018  1128 I WifiNative-HAL: Could not start hal
,08-26 19:03:00.263  1018  1128 E WifiNative-wlan0: do suspend true
,08-26 19:03:00.263  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 19:03:00.263  1018  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 19:03:00.263  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 19:03:00.263  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
08-26 19:03:00.263  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 19:03:00.263  1018  1128 E WifiNative-wlan0: invaild command id : 215
08-26 19:03:00.263  1018  1018 D RttService: SCAN_AVAILABLE : 3
,08-26 19:03:00.263  1018  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:03:00.263   278   992 D CommandListener: Setting iface cfg
08-26 19:03:00.263   278   992 D CommandListener: Trying to bring up p2p0
08-26 19:03:00.263  7498  7498 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 19:03:00.273  1018  1152 D WifiScanningService: DefaultState got{ when=-6ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:00.273  1018  1152 I WifiNative-HAL: startHal
,08-26 19:03:00.273  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e2f09bc
08-26 19:03:00.273  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:03:00.273  1018  1152 I WifiNative-HAL: Could not start hal
08-26 19:03:00.273  1018  1152 E WifiScanningService: could not start HAL
08-26 19:03:00.273  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:03:00.273  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-26 19:03:00.273  7498  7498 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 19:03:00.273  1018  1128 E WifiStateMachine: Failed to set frequency band 0
,08-26 19:03:00.273  7498  7498 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 19:03:00.273  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:00.273  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:00.273  1018  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
,08-26 19:03:00.273  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:00.273  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:00.273  1018  1127 D WifiP2pService: P2pEnablingState
,08-26 19:03:00.273  1018  1127 D WifiP2pService: P2pEnablingState{ what=143376 }
,08-26 19:03:00.273  1018  1127 D WifiP2pService: DefaultState{ what=143376 }
08-26 19:03:00.273  1018  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 19:03:00.273  1018  1127 D WifiP2pService: P2p socket connection successful
08-26 19:03:00.273  1018  1127 D WifiP2pService: P2pEnabledState
,08-26 19:03:00.273  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-26 19:03:00.283  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-26 19:03:00.283  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 19:03:00.283  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-26 19:03:00.283  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 19:03:00.283  1018  1048 D WifiDisplayController: disconnect
,08-26 19:03:00.283  1018  1048 D WifiDisplayController: updateConnection
,08-26 19:03:00.283  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 19:03:00.283  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:03:00.283  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:00.283  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:03:00.283  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:03:00.283  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:03:00.293  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 19:03:00.293  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-26 19:03:00.293  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 19:03:00.293  1018  1564 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 19:03:00.293  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 19:03:00.293  1018  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,08-26 19:03:00.293  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  secondary type: null
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  wps: 0
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  grpcapab: 0
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  devcapab: 0
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  status: 3
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  wfdInfo: null
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-26 19:03:00.293  1018  1048 D WifiDisplayController:  SConnectInfo : null
,08-26 19:03:00.313  1018  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
08-26 19:03:00.313  1018  1127 D WifiP2pService: InactiveState
08-26 19:03:00.313  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
08-26 19:03:00.313  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 19:03:00.313  7498  7498 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-26 19:03:00.483  1018  1560 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 19:03:00.483  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:00.483  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:00.483  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:00.483  1018  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.493  7568  7568 E Zygote  : MountEmulatedStorage()
08-26 19:03:00.493  1018  1560 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7568 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-26 19:03:00.493  7568  7568 E Zygote  : v2
,08-26 19:03:00.493  1018  1560 I ActivityManager: Killing 7053:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-26 19:03:00.493  7568  7568 I libpersona: KNOX_SDCARD checking this for 10121
08-26 19:03:00.493  7568  7568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:03:00.493  7568  7568 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:00.503  7568  7568 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:03:00.503  7568  7568 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:03:00.513  7568  7568 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:03:00.513  7568  7568 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:00.533  7568  7568 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:00.533  7568  7568 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 19:03:00.533  7568  7568 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 19:03:00.543  7568  7568 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:00.543  7568  7568 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 19:03:00.543  7568  7568 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 19:03:00.553  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-26 19:03:00.553  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.553  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 19:03:00.553  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 19:03:00.553  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 19:03:00.573  7586  7586 E Zygote  : MountEmulatedStorage()
,08-26 19:03:00.573  7586  7586 E Zygote  : v2
08-26 19:03:00.573  7586  7586 I libpersona: KNOX_SDCARD checking this for 10141
08-26 19:03:00.573  7586  7586 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:00.573  1018  1136 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7586 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-26 19:03:00.573  7586  7586 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:03:00.573  1018  1136 I ActivityManager: Killing 7070:com.android.calendar/u0a131 (adj 15): empty #21
,08-26 19:03:00.583  7586  7586 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:03:00.583  7586  7586 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:03:00.583   340   340 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 19:03:00.603  7586  7586 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:03:00.603  7586  7586 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:00.623  7586  7586 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-26 19:03:00.623  7586  7586 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:00.623  7586  7586 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 19:03:00.623  7586  7586 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 19:03:00.673  1018  1564 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:03:00.683  1018  1481 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:03:00.723  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:03:00.733  1018  1563 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:03:00.793  1018  1338 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 19:03:00.793  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.793  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.793  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:00.793  1018  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.803  1018  4869 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:03:00.803  1018  1560 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:03:00.813  7609  7609 E Zygote  : MountEmulatedStorage(),
08-26 19:03:00.813  7609  7609 I libpersona: KNOX_SDCARD checking this for 10068,
08-26 19:03:00.813  7609  7609 E Zygote  : v2
08-26 19:03:00.813  7609  7609 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:00.813  7609  7609 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:03:00.823  1018  1338 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7609 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-26 19:03:00.823  7609  7609 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:03:00.823  7609  7609 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 19:03:00.843  7609  7609 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:03:00.843  7609  7609 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:00.853  1018  1565 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 19:03:00.853  1018  1564 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 19:03:00.863  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.863  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.863  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.863  1018  1564 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:00.873  7624  7624 E Zygote  : MountEmulatedStorage()
08-26 19:03:00.873  7624  7624 E Zygote  : v2
08-26 19:03:00.873  7624  7624 I libpersona: KNOX_SDCARD checking this for 10009
08-26 19:03:00.873  7624  7624 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:00.873  7624  7624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:03:00.873  1018  1564 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7624 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 19:03:00.883  7624  7624 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:03:00.883  1018  1564 I ActivityManager: Killing 6085:com.android.vending/u0a26 (adj 15): empty #21
,08-26 19:03:00.883  1018  1564 I ActivityManager: Killing 6856:com.android.defcontainer/u0a3 (adj 15): empty #22
08-26 19:03:00.883  7624  7624 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-26 19:03:00.883  7609  7609 D BadgeProvider: onCreate
08-26 19:03:00.883  7609  7609 D BadgeProvider: DatabaseHelper
08-26 19:03:00.883   297   297 E SMD     : DCD OFF
,08-26 19:03:00.923  7624  7624 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:03:00.923  7624  7624 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:00.983  1018  4869 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 19:03:00.983  1018  4869 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4250, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 19:03:00.983  1018  4869 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 19:03:00.983  1018  4869 D BatteryService: stay LED for charging
,08-26 19:03:00.983  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 19:03:00.983  1018  1018 I MotionRecognitionService: Plugged,
08-26 19:03:00.983  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 19:03:00.993  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 19:03:00.993  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 19:03:00.993  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 19:03:00.993  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 19:03:01.013  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:03:01.013  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-26 19:03:01.013  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:03:01.033  1018  1221 I art     : Explicit concurrent mark sweep GC freed 55935(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 22MB/34MB, paused 2.483ms total 150.582ms
,08-26 19:03:01.043  7609  7617 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 19:03:01.063  7609  7617 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-26 19:03:01.063  7609  7617 D BadgeProvider: sendNotify, [notify] : null
08-26 19:03:01.063  7609  7617 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 19:03:01.063  7609  7617 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 19:03:01.063  7609  7617 D BadgeProvider: update, [UpdateCount] : 1
,08-26 19:03:01.063  1487  1487 D Launcher.Model: reloadBadges entered.
,08-26 19:03:01.083  1018  3824 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-26 19:03:01.083  1018  3824 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 19:03:01.083  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.083  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.123  1018  1481 I ActivityManager: Killing 7249:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-26 19:03:01.133  1018  1563 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:03:01.133  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:01.133  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.133  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:01.133  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:01.133  1636  1636 I Hs20UtilService: Starting #11
,08-26 19:03:01.133  1636  1651 I Hs20UtilService: Message received 5011
,08-26 19:03:01.133  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 19:03:01.133  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:03:01.133  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:03:01.133  7103  7103 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:03:01.143  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.143  1018  4869 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.143  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.143  1018  1560 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 19:03:01.143  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.143  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.143  1018  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.143  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.143  1018  1030 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,08-26 19:03:01.143  1018  1030 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-26 19:03:01.143  1018  1030 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,08-26 19:03:01.143  1018  1030 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
08-26 19:03:01.143  1714  4211 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-26 19:03:01.153  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.153  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.153  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.163  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.163  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.163  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.163  1714  1714 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 19:03:01.173  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.173  1018  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.173  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.173  1018  1565 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-26 19:03:01.173  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.173  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.173  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.173  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.183  1018  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.183  1018  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.183  1018  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.183  1714  1714 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:03:01.183  1714  1714 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:03:01.183  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.183  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.183  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.193  7373  7373 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-26 19:03:01.193  1018  4869 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:03:01.193  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.193  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.193  1018  4869 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.193  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.203  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.203  1018  3824 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.203  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.203  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.203  1018  3824 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.203  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.213  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.213  1018  1563 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.213  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.213  1018  1380 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:03:01.223  1018  1380 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.223  1018  1380 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.223  1018  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.223  1018  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:01.223  1018  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:01.223  1018  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:01.223  1018  1380 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:01.233  7642  7642 E Zygote  : MountEmulatedStorage(),
08-26 19:03:01.233  7642  7642 E Zygote  : v2
08-26 19:03:01.233  7642  7642 I libpersona: KNOX_SDCARD checking this for 10011,
08-26 19:03:01.233  7642  7642 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:01.233  7642  7642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 19:03:01.243  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.243  1018  1380 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7642 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-26 19:03:01.243  1018  1563 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.243  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.243  7642  7642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:03:01.243  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.243  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.243  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.253  7642  7642 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 19:03:01.253   326   326 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 22.347ms
,08-26 19:03:01.273  7642  7642 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:03:01.273  7642  7642 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:01.273   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.430ms
,08-26 19:03:01.283  7642  7642 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 19:03:01.283  7642  7642 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 19:03:01.293   326   326 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.539ms
,08-26 19:03:01.323  7642  7642 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-26 19:03:01.323  7642  7642 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-26 19:03:01.323  1455  1470 D TP/SmsProvider: query,matched:0, calling pid = 7373
,08-26 19:03:01.323  7642  7642 I MultiDex: VM with version 2.1.0 has multidex support
08-26 19:03:01.323  7642  7642 I MultiDex: install
08-26 19:03:01.333  7642  7642 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-26 19:03:01.333  1455  1470 D TP/SmsProvider: match 0:Elapsed time : 1.355 ms
,08-26 19:03:01.333  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.333  1018  1564 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.333  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.343  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.343  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.343  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.343  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:03:01.343  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.343  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.343  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.353  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.353  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.353  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.353  1455  2014 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7373
,08-26 19:03:01.353  1018  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:03:01.363  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-26 19:03:01.363  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.363  1018  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:03:01.363  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.363  1018  1380 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:03:01.363  1018  1380 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:01.363  1018  1380 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.363  1018  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:01.363  1018  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:01.363  1636  1636 I Hs20UtilService: Starting #12
,08-26 19:03:01.363  1636  1651 I Hs20UtilService: Message received 5011
08-26 19:03:01.363  7642  7642 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-26 19:03:01.373  7373  7662 D LocationInitializer: Restart initialization of location
,08-26 19:03:01.373  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:03:01.373  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:03:01.373  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:03:01.373  7103  7103 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:03:01.383  1455  1880 D TP/SmsProvider: query,matched:0, calling pid = 7373
,08-26 19:03:01.383  1455  1880 D TP/SmsProvider: match 0:Elapsed time : 1.627 ms
,08-26 19:03:01.383  1018  3824 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:03:01.383  1018  3824 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.383  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.383  1018  3824 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.383  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.383  1018  1481 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:01.393  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:01.393  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.393  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:01.393  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:01.393  1636  1636 I Hs20UtilService: Starting #13
,08-26 19:03:01.393  1636  1651 I Hs20UtilService: Message received 5011
,08-26 19:03:01.393  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 19:03:01.393  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 19:03:01.393  1018  1128 E WifiNative-wlan0: invaild command id : 215
,08-26 19:03:01.393  1018  1565 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:03:01.403  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 19:03:01.403  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:03:01.403  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:03:01.403  7103  7103 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:03:01.403  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.403  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.403  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.413  1455  1484 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7373
,08-26 19:03:01.423  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 19:03:01.423  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:03:01.433  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:03:01.433  7642  7642 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 19:03:01.433  7642  7642 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e12f14: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-26 19:03:01.433  7642  7642 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 19:03:01.433  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:03:01.433  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:03:01.433  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:03:01.433  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:03:01.433  1018  1221 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 19:03:01.443  1018  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 19:03:01.443  1018  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:01.443  1018  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:01.443  1018  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:01.463  7664  7664 E Zygote  : MountEmulatedStorage()
08-26 19:03:01.463  7664  7664 E Zygote  : v2
08-26 19:03:01.463  7664  7664 I libpersona: KNOX_SDCARD checking this for 10064
08-26 19:03:01.463  7664  7664 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:01.463  7664  7664 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 19:03:01.463  7498  7498 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
08-26 19:03:01.463  1018  1221 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7664 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:03:01.463  7498  7498 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 19:03:01.463  7498  7498 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 19:03:01.463  7498  7498 I wpa_supplicant: Trying to associate with  'G700'
08-26 19:03:01.463  7498  7498 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 19:03:01.463  1018  7561 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-26 19:03:01.463  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-26 19:03:01.463  7664  7664 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 19:03:01.463  7664  7664 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:03:01.473  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:01.473  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:01.483  7642  7642 D WearableService: callingUid 10011, callindPid: 7642
,08-26 19:03:01.493  7664  7664 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:03:01.493  7664  7664 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:01.513  7642  7672 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-26 19:03:01.513  7664  7664 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 19:03:01.523  7664  7664 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:03:01.533  7664  7664 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 19:03:01.563  7664  7664 D FileShare-Client: Outbound.stopDelayTimer - ,
,08-26 19:03:01.563  7266  7266 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:03:01.573  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.573  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.573  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.573  1018  1564 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 19:03:01.573  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.573  7498  7498 E wpa_supplicant: Cmd 35605 not handled
08-26 19:03:01.573  7498  7498 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 19:03:01.573  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 19:03:01.573  7498  7498 I wpa_supplicant: Associated with F4.99.3E
08-26 19:03:01.573  7498  7498 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 19:03:01.573  7498  7498 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 19:03:01.573  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-26 19:03:01.583  1018  1564 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:03:01.583  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 19:03:01.583  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 19:03:01.583  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:03:01.583  1018  1564 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.583  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:03:01.583  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.583  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:03:01.583  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:01.583  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:03:01.583  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:03:01.583  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:01.583   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:03:01.583  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 19:03:01.583  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 19:03:01.583  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-26 19:03:01.593  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:01.593  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:01.593  1018  1131 E Tethering: No numeric data
,08-26 19:03:01.593  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 19:03:01.593  1018  1131 D Tethering: clearTetheredNotification()
,08-26 19:03:01.593  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:03:01.593  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 19:03:01.593  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 19:03:01.593  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:01.593  7498  7498 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 19:03:01.593  7498  7498 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-26 19:03:01.593  7498  7498 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 19:03:01.593  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 19:03:01.593  1714  2707 I art     : Explicit concurrent mark sweep GC freed 12041(578KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.355ms total 64.922ms
,08-26 19:03:01.593  7498  7498 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:03:01.593  7498  7498 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-26 19:03:01.593  7498  7498 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-26 19:03:01.603  7498  7498 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 19:03:01.603  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-26 19:03:01.603  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:01.603  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:01.603  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 19:03:01.603  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 19:03:01.603  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-26 19:03:01.603  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:03:01.603  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:03:01.603  1018  1031 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-26 19:03:01.603  1018  1031 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-26 19:03:01.603  1018  1031 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-26 19:03:01.603  1018  1031 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-26 19:03:01.603  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:01.603  1018  1125 V NetworkStats: performPollLocked() took 8ms
,08-26 19:03:01.603  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.603  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.603  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.603  1714  5127 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 19:03:01.613  1018  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 19:03:01.613  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:01.613  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:01.613  1018  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 19:03:01.613  1680  3128 E MDM     : [165] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-26 19:03:01.613  1018  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 19:03:01.613  1018  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 19:03:01.613  1018  1130 E ConnectivityService: updateNetworkInfo()
08-26 19:03:01.613  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 19:03:01.623  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.623  1018  3824 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.623  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:03:01.623  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:03:01.623  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:01.623  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:01.623  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.623  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.623  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.623  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:01.623  1714  1714 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-26 19:03:01.623  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:03:01.623  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.623  1018  1564 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.623  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.633  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:03:01.633  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-26 19:03:01.633  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.633  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.633  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.633  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.633  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.633  1018  1563 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.633  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.643  1714  1714 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:03:01.643  1714  1714 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:03:01.643  1018  4869 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:03:01.643  1018  4869 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.643  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.643  7373  7373 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-26 19:03:01.643   278   992 D CommandListener: Setting iface cfg
08-26 19:03:01.643  1018  1338 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 19:03:01.643  1018  1338 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-26 19:03:01.643  1018  1338 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.643  1018  1338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.643  1018  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-26 19:03:01.653  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.653  1018  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.653  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.653  1018  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 19:03:01.653  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:01.653  1018  1128 D SecContentProvider2: mCursor = null
08-26 19:03:01.653  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.653  1018  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:03:01.653  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.663  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.663  1018  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.663  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.673  1680  3133 E MDM     : [166] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null},
08-26 19:03:01.673  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.673  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.673  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.673  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.683  1018  4869 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.683  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 19:03:01.683  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:01.683  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:01.683  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:01.683  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.683  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.683  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.683  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:01.683  1018  1128 E WifiNative-wlan0: do suspend false
,08-26 19:03:01.683  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:01.683  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:01.683  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-26 19:03:01.683  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:03:01.693  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.693  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:03:01.693  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.693  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.693  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:03:01.693  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.703  1018  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 19:03:01.703  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:01.703  1018  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.703  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.713  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.713  1018  1565 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.713  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.713  1018  4869 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:03:01.713  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-26 19:03:01.713  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.713  1018  4869 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.713  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.723  1018  1563 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:03:01.723  7373  7686 D LocationInitializer: Restart initialization of location
08-26 19:03:01.723  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:01.723  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.723  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:01.723  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:01.723  1018  1560 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 19:03:01.723  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
08-26 19:03:01.723  1636  1636 I Hs20UtilService: Starting #14
,08-26 19:03:01.723  1636  1651 I Hs20UtilService: Message received 5007
08-26 19:03:01.723  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.723  1018  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:01.723  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 19:03:01.723  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:03:01.723  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
08-26 19:03:01.733  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:03:01.733  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:03:01.733  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:03:01.733  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:03:01.733  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:03:01.903  1018  1565 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 19:03:01.903  1018  1565 D WifiService: setWifiEnabled: false pid=6888, uid=10170
,08-26 19:03:01.903  1018  1565 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 19:03:01.903  1018  1565 D SecContentProvider2: mCursor = null
08-26 19:03:01.903  1018  1565 D SettingsProvider: name = wifi_on
,08-26 19:03:01.903  7688  7688 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 19:03:01.913  7688  7688 I dhcpcd  : version 5.5.6 starting
,08-26 19:03:01.913  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:03:01.913  7688  7688 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 19:03:01.923  1018  1128 E WifiNative-wlan0: do suspend true,
,08-26 19:03:01.943  1018  1127 D WifiP2pService: InactiveState{ what=143375 },
08-26 19:03:01.943  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:03:01.953   278   992 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:03:01.963  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-26 19:03:01.963  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:03:01.963  1018  1130 E ConnectivityService: updateNetworkInfo()
08-26 19:03:01.963  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0,
08-26 19:03:01.973   278   992 E Netd    : no such netId 503
,08-26 19:03:01.973  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 19:03:01.973  1018  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)',
08-26 19:03:01.973  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:01.973  1018  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 19:03:01.973  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:03:01.973  1018  1130 V NetworkStats: updateIfacesLocked()
,08-26 19:03:01.973  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:03:01.973  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:03:01.973  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:01.973  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:01.973  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.973  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.973  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.973  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.973  1018  1130 V NetworkStats: performPollLocked() took 5ms
08-26 19:03:01.973  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:03:01.973  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:01.983  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 19:03:01.983  1018  1127 D WifiP2pService: InactiveState{ what=131204 }
08-26 19:03:01.983  1018  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:03:01.983  1018  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-26 19:03:01.983  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 19:03:01.983  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-26 19:03:01.983  1018  1564 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:01.983  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.983  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:03:01.983  1018  1152 D WifiScanningService: DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:01.983  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:03:01.983  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:01.983  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:01.983  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.983  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.983  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:01.983  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:01.983  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:01.983  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:01.983  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:01.993  1636  1636 I Hs20UtilService: Starting #15
08-26 19:03:01.993  1636  1651 I Hs20UtilService: Message received 5007
,08-26 19:03:01.993  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:01.993  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:03:01.993  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:03:01.993  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:03:02.003  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:02.003  1018  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-26 19:03:02.003  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:02.003  1018  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 19:03:02.003  1018  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:02.003  1018  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 19:03:02.003  1018  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 19:03:02.003  1018  1130 E ConnectivityService: updateNetworkInfo()
08-26 19:03:02.003  1018  7683 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-26 19:03:02.003  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 19:03:02.003  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 19:03:02.003  1018  1130 E ConnectivityService: updateNetworkInfo()
08-26 19:03:02.003  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 19:03:02.003  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:03:02.003  1018  1048 D WifiDisplayController: disconnect
08-26 19:03:02.003  1018  1048 D WifiDisplayController: updateConnection
08-26 19:03:02.003  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:03:02.003  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:03:02.013  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 19:03:02.013  1018  1127 D WifiP2pService: P2pDisablingState
08-26 19:03:02.013  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 19:03:02.013  1018  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 19:03:02.013  7688  7688 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 19:03:02.013  1018  1127 D WifiP2pService: p2p socket connection lost
08-26 19:03:02.013  7688  7688 E dhcpcd  : wlan0: sendmsg: Network is unreachable
08-26 19:03:02.013  7688  7688 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-26 19:03:02.013  1018  1127 D WifiP2pService: P2pDisabledState
08-26 19:03:02.013  1018  1128 E WifiNative-wlan0: do suspend true
,08-26 19:03:02.013  7688  7688 I dhcpcd  : bssid match
08-26 19:03:02.013  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:03:02.013  7688  7688 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-26 19:03:02.023  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:03:02.023  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:03:02.023  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:03:02.023  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:03:02.023  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 19:03:02.023  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:03:02.023  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:03:02.023  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:03:02.023  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 19:03:02.023  1018  1481 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 19:03:02.023  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 19:03:02.033  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 19:03:02.033  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:03:02.033  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:03:02.033  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:03:02.033  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:03:02.033  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:03:02.043  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 19:03:02.043  7664  7664 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:03:02.043  7664  7664 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 19:03:02.043  7664  7664 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 19:03:02.043  7688  7688 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
08-26 19:03:02.043  7688  7688 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-26 19:03:02.043  7266  7266 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:03:02.053  1018  1127 D WifiP2pService: P2pDisabledState{ what=143375 },
08-26 19:03:02.053  1018  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-26 19:03:02.053   278   992 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:03:02.063  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-26 19:03:02.063  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 19:03:02.063  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 19:03:02.063  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.063  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.063  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.063  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.063  7498  7498 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-26 19:03:02.073  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 19:03:02.083  1018  1338 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:02.083  1018  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:02.083  1018  1338 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,08-26 19:03:02.083  1018  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:02.083  1018  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:02.083  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:02.083  1018  1128 D SecContentProvider2: mCursor = null
08-26 19:03:02.083  1636  1636 I Hs20UtilService: Starting #16
08-26 19:03:02.083  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:02.083  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:02.083  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:02.083  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.083  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.083  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.083  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.083  1636  1651 I Hs20UtilService: Message received 5007
,08-26 19:03:02.093  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:02.093  4832  4832 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:02.093  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:02.093  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:03:02.093  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.093  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.093  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:02.093  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.093  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:02.093  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:02.093  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 19:03:02.093  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 19:03:02.103  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:02.103  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:03:02.103  1178  1178 D HotspotTile: onReceive : 0, 0
08-26 19:03:02.103  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 19:03:02.103  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:02.103  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:02.103  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:02.103  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:02.103  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 19:03:02.103  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:02.103  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:02.113  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:03:02.113  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:03:02.113  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 19:03:02.113  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:03:02.123  1018  1563 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:02.123  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:02.123  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:02.123  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 19:03:02.123  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:03:02.123  1636  1636 I Hs20UtilService: Starting #17
08-26 19:03:02.123  1636  1651 I Hs20UtilService: Message received 5011
,08-26 19:03:02.133  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 19:03:02.133  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 19:03:02.133  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 19:03:02.133  7103  7103 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:03:02.143  7498  7498 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 19:03:02.203  7498  7498 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 19:03:02.203  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 19:03:02.203  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:03:02.203  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:03:02.223  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 19:03:02.223  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 19:03:02.223  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:02.223  7498  7498 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-26 19:03:02.223  7498  7498 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 19:03:02.233  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 19:03:02.223  7498  7498 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-26 19:03:02.223  1018  1131 D Tethering: InitialState.processMessage what=4
08-26 19:03:02.233  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:03:02.233  7498  7498 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 19:03:02.233  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:03:02.233  7498  7498 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 19:03:02.233  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 19:03:02.233  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:03:02.233  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 19:03:02.233  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:02.233  1018  1131 E Tethering: No numeric data
08-26 19:03:02.233  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:03:02.233  1018  1131 D Tethering: clearTetheredNotification()
08-26 19:03:02.233  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:02.233  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:03:02.233  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 19:03:02.233  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:02.233  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:03:02.243  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:02.243  1018  1125 V NetworkStats: performPollLocked() took 7ms
,08-26 19:03:02.243  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 19:03:02.243  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:02.453  7498  7498 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 19:03:02.573  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-26 19:03:02.573  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:03:02.573  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:02.573  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:03:02.573  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 19:03:02.573  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:02.583  7498  7498 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 19:03:02.583   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:03:02.683  7281  7281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-26 19:03:02.683  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-26 19:03:02.683  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 19:03:02.693  1680  2158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:03:02.693  4832  4832 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:02.703  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:02.703  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:02.703  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:03:02.703  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.703  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.703  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.703  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:02.703  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:02.703  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 19:03:02.703  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:03:02.703  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:02.703  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:02.703  1178  1178 D HotspotTile: onReceive : 1, 0
,08-26 19:03:02.703  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:02.713  1018  1564 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:02.713  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:02.713  1018  1564 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:03:02.713  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:02.713  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:03:02.713  1636  1636 I Hs20UtilService: Starting #18
08-26 19:03:02.713  1636  1651 I Hs20UtilService: Message received 5011
,08-26 19:03:02.713  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:03:02.713  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:03:02.713  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:03:02.713  7103  7103 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:03:02.833  5956  5956 D FactoryTest: Not factory mode
,08-26 19:03:02.833  5956  5956 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 19:03:02.833  5956  5956 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-26 19:03:02.833  5956  5956 D MTPRx   : still no open session command from host, so toast
,08-26 19:03:02.833  5956  5956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-26 19:03:02.833  5956  5956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 19:03:02.833  5956  5956 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:117847
,08-26 19:03:02.833  1018  1136 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 19:03:02.833  1018  1136 I PersonaManagerService: PersonaId don't exist
,08-26 19:03:02.833  1018  1136 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 19:03:02.843  1018  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-26 19:03:02.843  1018  1136 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:03:02.843  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:02.843  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 19:03:02.853  1018  1136 W ActivityManager: mDVFSHelper.acquire()
,08-26 19:03:02.863  1018  1136 D PersonaManager: isKioskContainerExistOnDevice
,08-26 19:03:02.883  1018  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 19:03:02.883  1018  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 19:03:02.883  1018  1136 D InputDispatcher: Focused application set to: xxxx
08-26 19:03:02.883  1018  1136 D InputDispatcher: Focus left window: 6888
,08-26 19:03:02.893  5956  5956 E MTPRx   : started activity for popup
,08-26 19:03:02.893  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 19:03:02.893  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 19:03:02.913  5956  5956 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-26 19:03:02.913  5956  5956 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 19:03:02.913  5956  5956 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 19:03:02.913  5956  5956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:02.913  5956  5956 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 19:03:02.913  5956  5956 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 19:03:02.933  5956  5956 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 19:03:02.933  1018  1380 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 19:03:02.933  1018  1380 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 19:03:02.933  1018  1380 D InputDispatcher: Focused application set to: xxxx
,08-26 19:03:02.933  1018  1380 D InputDispatcher: Focus entered window: 6888
,08-26 19:03:02.933  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 19:03:02.943  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 19:03:02.943  1018  1565 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 19:03:02.943  1018  1565 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1c43fa8c attribute=null, token = android.os.BinderProxy@3c9a513
,08-26 19:03:02.983  5956  5956 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-26 19:03:02.993  5956  5956 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-26 19:03:02.993  5956  5956 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 19:03:03.013  6888  6888 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 19:03:03.013  6888  6888 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-26 19:03:03.013  6888  6888 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 19:03:03.013  6888  6888 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 19:03:03.013  1018  1481 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 19:03:03.013  1018  1481 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 19:03:03.013  1018  1481 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 19:03:03.013  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 19:03:03.013  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 19:03:03.033  6888  6888 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 19:03:03.033  6888  6888 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 19:03:03.033  6888  6888 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21b24da1 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@159fb967, 16908290=android.view.AbsSavedState$1@159fb967}, android:focusedViewId=100}]}]
,08-26 19:03:03.033  6888  6888 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 19:03:03.033  6888  6888 V ActivityThread: updateVisibility : ActivityRecord{2d13459b token=android.os.BinderProxy@a6ed095 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 19:03:03.033  6888  6888 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 19:03:03.033  6888  6888 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 19:03:03.033  6888  6888 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@a6ed095 time:118049
,08-26 19:03:03.043  1018  1495 D PersonaManager: isKioskContainerExistOnDevice
,08-26 19:03:03.113  1018  1096 V AlarmManager: waitForAlarm result :4
,08-26 19:03:03.113  1018  1018 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-26 19:03:03.113  1018  1018 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-26 19:03:03.113  1018  1018 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-26 19:03:03.123  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-26 19:03:03.123  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 19:03:03.123   278   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:03:03.123   278   988 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 19:03:03.123  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 19:03:03.123  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 19:03:03.133  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 19:03:03.133  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-26 19:03:03.133  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 19:03:03.143  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:03.143  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 19:03:03.143  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 19:03:03.163  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 19:03:03.163  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 19:03:03.163  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 19:03:03.183  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 19:03:03.393  1018  1045 D Tethering: interfaceRemoved wlan0
,08-26 19:03:03.393  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 19:03:03.543  1018  1045 D Tethering: interfaceRemoved p2p0
,08-26 19:03:03.543  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 19:03:03.593   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:03:03.893   297   297 E SMD     : DCD OFF
,08-26 19:03:04.373  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 19:03:04.593   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-26 19:03:04.913  6888  7046 D BluetoothAdapter: enable()
,08-26 19:03:04.913  1018  1338 W ActivityManager: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 19:03:04.913  1018  1338 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-26 19:03:04.913  1018  1338 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:03:04.913  1018  1338 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:03:04.913  1018  1338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 19:03:04.913  1018  1338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688),
08-26 19:03:04.913  1018  1338 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 19:03:04.913  1018  1338 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 19:03:04.913  1018  1338 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 19:03:04.913  1018  1338 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 19:03:04.923  1018  1338 D SettingsProvider: name = bluetooth_on,
,08-26 19:03:04.923  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-26 19:03:04.923  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 19:03:04.933  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 19:03:04.933  3257  3336 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-26 19:03:04.933  3257  3336 D BluetoothAdapterProperties: Setting state to 11
08-26 19:03:04.933  3257  3336 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11,
08-26 19:03:04.933  3257  3336 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:03:04.933  3257  3336 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 19:03:04.933  3257  3336 D BluetoothAdapterService: Autoconnection is available 
08-26 19:03:04.933  3257  3336 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-26 19:03:04.933  3257  3336 D BtConfig.SecureMode: isSecureModeOn:false
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12,
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10,
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10,
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10,
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:04.943  1018  3824 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-26 19:03:04.943  1018  3824 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 19:03:04.933  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:03:04.933  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 19:03:04.943  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:04.943  1018  3824 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:04.943  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:04.943  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 19:03:04.943  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:03:04.943  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 19:03:04.943  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:04.943  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-26 19:03:04.943  3257  3257 D HeadsetService: Received start request. Starting profile...
08-26 19:03:04.943  3257  3257 D HeadsetService: start()
08-26 19:03:04.943  3257  3257 D HeadsetStateMachine: make
,08-26 19:03:04.953  3257  3257 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 19:03:04.963  1962  1962 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:03:04.963  4832  4832 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:04.963  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:04.963  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 19:03:04.963  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-26 19:03:04.963  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:04.963  1018  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:04.963  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 19:03:04.963  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:04.963  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:04.963  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:04.963  1018  1338 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 19:03:04.963  1018  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 19:03:04.963  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService,
08-26 19:03:04.963  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:03:04.973  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:03:04.963  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 19:03:04.973  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-26 19:03:04.973  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:04.973  1018  1338 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:04.973  1018  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:04.973  1018  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 19:03:04.973  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:04.973  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:03:04.973  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:04.973  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:04.973  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:04.973  1018  1564 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 19:03:04.973  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-26 19:03:04.973  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 19:03:04.973  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 19:03:04.973  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-26 19:03:04.973  1018  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:04.973  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:04.973  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:04.973  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 19:03:04.973  3257  3257 I bluedroid: get_profile_interface handsfree
,08-26 19:03:04.983  1018  1565 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:03:04.983  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 19:03:04.983  1018  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:04.983  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 19:03:04.983  1714  1714 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:04.983  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:04.983  1018  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:04.983  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:04.983  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-26 19:03:04.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:03:04.983  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 19:03:04.983  1018  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:04.983  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:03:04.993  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:04.993  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:04.993  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:03:04.993  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 19:03:04.993  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:04.993  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 19:03:04.993  3257  3257 E DualScoManager: Dual Sco Manager already instantiated
08-26 19:03:04.993  3257  3257 I DualScoManager: Set HeadsetServiceHelper
,08-26 19:03:04.993  3257  3257 D BluetoothAtMessage: createCMTIContentObservers
,08-26 19:03:04.993  1018  3824 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 19:03:04.993  1018  3824 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:03:04.993  1018  3824 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:03:04.993  1018  3824 D SettingsProvider: selectionArgs: false
08-26 19:03:04.993  1018  3824 D SettingsProvider: selectionArgs: 1002
08-26 19:03:04.993  1018  3824 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:03:04.993  1018  3824 D SettingsProvider: ret = -1
08-26 19:03:04.993  3257  7724 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 19:03:04.993  1018  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:04.993  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:03:04.993  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:04.993  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:04.993  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.003  4832  4832 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:03:05.003  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-26 19:03:05.003  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 19:03:05.003  3257  3336 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 19:03:05.003  3257  3257 D HeadsetService: mStartError = false
08-26 19:03:05.003  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:05.003  3257  3257 D A2dpService: Received start request. Starting profile...
08-26 19:03:05.003  3257  3257 D A2dpService: start()
08-26 19:03:05.003  3257  3257 I bluedroid: get_profile_interface avrcp
,08-26 19:03:05.003  1018  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:03:05.003  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.003  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:05.003  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-26 19:03:05.003  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.003  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.003  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.013  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 19:03:05.013  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:05.013  3257  3257 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 19:03:05.013  3257  3257 D Avrcp   : Initialize Media Controller
08-26 19:03:05.013  3257  3257 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-26 19:03:05.013  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:05.013  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-26 19:03:05.013  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:05.013  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:05.013  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 19:03:05.013  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:03:05.013  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 19:03:05.013  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 19:03:05.013  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:03:05.013  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 19:03:05.013  3257  3336 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 19:03:05.013  3257  3257 E Avrcp   : getActiveSessions
08-26 19:03:05.013  3257  7724 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 19:03:05.013  3257  3257 D Avrcp   : pick active media Controller
08-26 19:03:05.013  3257  3257 D Avrcp   : Get the active Media Controller 
,08-26 19:03:05.013  3257  7724 D HeadsetStateMachine: map size, before remove : 0
08-26 19:03:05.013  3257  7724 D HeadsetStateMachine: map size, after remove: 0
,08-26 19:03:05.023  3257  3257 I Avrcp   :  Updating now playing list upon AVRCP Start
08-26 19:03:05.023  3257  3257 D A2dpStateMachine: make
08-26 19:03:05.023  3257  3257 I bluedroid: get_profile_interface a2dp
08-26 19:03:05.023  3257  7727 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 19:03:05.023  3257  3257 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 19:03:05.023  3257  3257 D A2dpService: mStartError = false
08-26 19:03:05.023  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:05.023  3257  3257 D HeadsetStateMachine: Try to query the phonestate on bind
08-26 19:03:05.023  3257  7726 D A2dpStateMachine: Enter Disconnected: -2
,08-26 19:03:05.023  3257  7725 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 19:03:05.023  1429  1451 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 19:03:05.023  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 19:03:05.023  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 19:03:05.023  1429  1451 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 19:03:05.033  3257  3257 D HidService: Received start request. Starting profile...
08-26 19:03:05.033  3257  3257 D HidService: start()
08-26 19:03:05.033  3257  3257 I bluedroid: get_profile_interface hidhost
08-26 19:03:05.033  3257  3257 D HidService: setHidService(): set to: null
08-26 19:03:05.033  3257  3257 D HidService: mStartError = false
08-26 19:03:05.033  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:05.033  3257  3257 D HeadsetStateMachine: Proxy object connected
08-26 19:03:05.033  3257  3257 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-26 19:03:05.033  3257  7724 D HeadsetStateMachine: Disconnected process message: 11
,08-26 19:03:05.033  3257  3257 D HealthService: Received start request. Starting profile...
08-26 19:03:05.033  3257  3257 D HealthService: start()
,08-26 19:03:05.033  3257  3257 I bluedroid: get_profile_interface health
08-26 19:03:05.033  3257  3257 D HealthService: mStartError = false
08-26 19:03:05.033  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:05.033  3257  3257 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 19:03:05.033  3257  3257 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-26 19:03:05.033  3257  7724 D HeadsetStateMachine: Disconnected process message: 18
,08-26 19:03:05.033  3257  3257 D PanService: Received start request. Starting profile...
,08-26 19:03:05.033  3257  3257 D PanService: start()
08-26 19:03:05.033  3257  3257 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:03:05.033  3257  3257 I bluedroid: get_profile_interface pan
08-26 19:03:05.033  3257  3257 D PanService: mStartError = false
08-26 19:03:05.033  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:05.033  3257  3257 D BluetoothMapService: Received start request. Starting profile...
08-26 19:03:05.033  3257  3257 D BluetoothMapService: start()
,08-26 19:03:05.033  3257  3257 D BluetoothMapService: mStartError = false
08-26 19:03:05.033  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:05.033  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 19:03:05.033  3257  3257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 19:03:05.033  3257  7724 D HeadsetStateMachine: Disconnected process message: 10
08-26 19:03:05.033  3257  7724 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:03:05.033  3257  7724 D HeadsetStateMachine: Disconnected process message: 11
,08-26 19:03:05.043  3257  3257 D SapService: Received start request. Starting profile...
,08-26 19:03:05.043  3257  3257 D SapService: start()
08-26 19:03:05.043  3257  3257 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 19:03:05.043  3257  3257 I bluedroid: get_profile_interface sap
08-26 19:03:05.043  3257  3257 D SapService: mStartError = false
08-26 19:03:05.043  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:05.043  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 19:03:05.043  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-26 19:03:05.043  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 19:03:05.043  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 19:03:05.063  3257  7725 D BluetoothMediaBrowser: no now playing list
08-26 19:03:05.063  3257  7725 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 19:03:05.063  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 19:03:05.063  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 19:03:05.063  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 19:03:05.063  3257  3336 I bluedroid: enable
,08-26 19:03:05.073  3257  3339 E bt-btif :                : sec
,08-26 19:03:05.073  3257  3339 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 19:03:05.073  3257  3339 E bt-btif :                : sec: 0x1086, service name [] (up to 21o, chan_id 2
08-26 19:03:05.073  3257  3339 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 19:03:05.073  3257  3339 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-26 19:03:05.073  3257  3339 E BluetoothServiceJni: populateRssiValuesNative
,08-26 19:03:05.073  3257  3339 I bluedroid: getModelRssiValues
,08-26 19:03:05.073  3257  3339 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 19:03:05.073  3257  3339 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 19:03:05.073  1018  1018 D SettingsProvider: name = bluetooth_name
,08-26 19:03:05.073  3257  3339 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-26 19:03:05.083  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:05.083  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:05.083  3257  3339 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 19:03:05.083  3257  3339 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:05.083  3257  3339 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 19:03:05.083  3257  3339 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-26 19:03:05.083  3257  3339 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
,08-26 19:03:05.083  3257  3339 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-26 19:03:05.083  3257  3339 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 19:03:05.083  3257  3339 E bt-btif : JVenable fails
,08-26 19:03:05.083  3257  3339 D bte_conf: Device ID record 1 : primary
,08-26 19:03:05.083  3257  3339 D bte_conf:   vendorId            = 0075
08-26 19:03:05.083  3257  3339 D bte_conf:   vendorIdSource      = 0001
,08-26 19:03:05.093  3257  3339 D bte_conf:   product             = 0100
,08-26 19:03:05.093  3257  3339 D bte_conf:   version             = 0200
08-26 19:03:05.093  3257  3339 D bte_conf:   clientExecutableURL = 
08-26 19:03:05.093  3257  3339 D bte_conf:   serviceDescription  = 
,08-26 19:03:05.093  3257  3339 D bte_conf:   documentationURL    = 
,08-26 19:03:05.093  3257  3339 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 19:03:05.093  3257  3339 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-26 19:03:05.093  3257  3339 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 19:03:05.093  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 19:03:05.093  3257  3336 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:03:05.093  3257  3336 D BluetoothAdapterProperties: State =  11
,08-26 19:03:05.093  1018  1481 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 19:03:05.093  3257  3336 D BluetoothAdapterProperties: Setting state to 12
,08-26 19:03:05.093  3257  3336 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 19:03:05.093  3257  3339 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 19:03:05.093  3257  3339 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:03:05.093  3257  3339 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 19:03:05.093  1018  1565 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 19:03:05.093  1018  1565 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:03:05.093  1018  1565 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:03:05.093  1018  1565 D SettingsProvider: selectionArgs: false
08-26 19:03:05.093  1018  1565 D SettingsProvider: selectionArgs: 1002
08-26 19:03:05.093  1018  1565 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:03:05.093  1018  1565 D SettingsProvider: ret = -1
08-26 19:03:05.103  3257  3336 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:03:05.103  3257  3336 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 19:03:05.103  1018  4869 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:05.103  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.103  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.103  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:05.103  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.103  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:05.103  3257  3336 D BluetoothAdapterService: Autoconnection is available 
08-26 19:03:05.103  3257  3336 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 19:03:05.103  3257  3336 D BluetoothAdapterService: starting service from this receiver
,08-26 19:03:05.103  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:03:05.103  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 19:03:05.103  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 19:03:05.103  1018  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:05.103  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.103  4832  4856 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:05.103  4832  4856 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:05.113  1018  1564 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.113  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.113  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.113  1680  4652 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:03:05.113  1680  4652 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:05.113  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:05.113  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:05.113  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:05.113  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:05.113  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:05.113  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:05.113  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:05.113  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:05.113  4832  4842 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:05.113  4832  4842 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:05.113  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:05.123  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 19:03:05.123  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.123  3257  3336 I BluetoothAdapterState: Entering On State from state = 11
08-26 19:03:05.123  3257  3257 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-26 19:03:05.123  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.123  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.123  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 19:03:05.123  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:05.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:05.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:05.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:05.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:05.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:05.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:05.123  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:05.123  6888  6902 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:05.123  6888  6902 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:05.123  1455  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:05.123  1455  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:05.123  7219  7233 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:05.123  7219  7233 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:05.133  3257  3257 I BluetoothPbapService: Handler(): got msg=1
,08-26 19:03:05.133  1714  2707 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:05.133  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:05.133  1714  2707 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:05.133  1018  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 19:03:05.133  1018  1047 D BluetoothPan: Binding service...
,08-26 19:03:05.133  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 19:03:05.133  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.133  4832  4856 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 19:03:05.133  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 19:03:05.143  3257  7733 V BluetoothPbapService: PBAP Service initSocket try: 0
08-26 19:03:05.143  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 19:03:05.143  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 19:03:05.143  4832  4832 D BluetoothA2dp: Proxy object connected
08-26 19:03:05.143  4832  4832 D A2dpProfile: Bluetooth service connected
,08-26 19:03:05.143  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.143  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.143  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.143  4832  4842 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 19:03:05.143  4832  4832 D BluetoothPbap: Proxy object connected
08-26 19:03:05.143  4832  4832 D PbapServerProfile: Bluetooth service connected
,08-26 19:03:05.143  3257  7733 D BluetoothSocket: bindListen(): myUserId = 0
08-26 19:03:05.143  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 19:03:05.143  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.143  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.143  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.143  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 19:03:05.143  3257  7733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:05.143  4832  4856 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 19:03:05.143  4832  4856 D Bluetoothsap: Binding service...
,08-26 19:03:05.143  4832  4832 D BluetoothInputDevice: Proxy object connected
,08-26 19:03:05.143  4832  4832 D HidProfile: Bluetooth service connected
08-26 19:03:05.143  3257  7733 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-26 19:03:05.143  3257  7733 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:03:05.143  3257  7733 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:03:05.143  3257  7733 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4660fd4
08-26 19:03:05.143  3257  7733 D BluetoothSocket: channel: 19
08-26 19:03:05.143  3257  7733 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 19:03:05.153  4832  4856 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 19:03:05.153  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 19:03:05.153  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.153  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.153  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.153  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.153  4832  4856 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 19:03:05.153  4832  4832 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-26 19:03:05.153  4832  4832 D SapProfile: Bluetooth service connected
,08-26 19:03:05.153  1455  1484 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:05.153  4832  4832 D Bluetoothsap: getConnectedDevices()
08-26 19:03:05.153  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:03:05.153  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:05.153  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.153  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.153  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.163  1455  1484 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:03:05.163  1429  1445 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:03:05.163  1429  1445 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:05.163  1442  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:05.163  1442  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:05.163  1429  7184 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:05.163  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:03:05.163  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:05.163  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:05.163  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.163  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.163  1429  7184 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:03:05.163  1429  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:05.173  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:03:05.173  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:05.173  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:05.173  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.173  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.173  1429  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:03:05.173  4832  7734 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:05.173  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:03:05.173  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:05.173  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:05.173  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.173  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.173  4832  7734 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:03:05.173  4832  4832 D HeadsetProfile: Bluetooth service connected
08-26 19:03:05.173  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:05.173  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 19:03:05.173  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 19:03:05.173  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.173  1018  1018 D BluetoothA2dp: Proxy object connected
,08-26 19:03:05.183  1429  7184 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:05.183  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:03:05.183  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:05.183  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.183  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.183  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.183  1429  7184 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 19:03:05.183  1178  1868 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:03:05.183  1178  1868 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:05.183  3257  3410 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:03:05.183  3257  3410 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:05.183  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 19:03:05.183  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.183  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.183  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:05.183  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.183  3257  3257 D BluetoothA2dp: Proxy object connected
08-26 19:03:05.183  3257  3257 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-26 19:03:05.183  3257  3276 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:05.183  3257  3276 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:05.183  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:05.183  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:05.183  4832  4856 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:03:05.193  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-26 19:03:05.193  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.193  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:05.193  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.193  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.193  4832  7734 D BluetoothPan: Binding service...
,08-26 19:03:05.193  4832  4832 D BluetoothMap: Proxy object connected
08-26 19:03:05.193  4832  4832 D MapProfile: Bluetooth service connected
,08-26 19:03:05.193  4832  4832 D BluetoothMap: getConnectedDevices()
08-26 19:03:05.193  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 19:03:05.193  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.193  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.193  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.193  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:05.193  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 19:03:05.193  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 19:03:05.193  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:05.193  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-26 19:03:05.193  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 19:03:05.203  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 19:03:05.203  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:03:05.203  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:03:05.203  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:03:05.213  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@39881a4e, true
,08-26 19:03:05.213  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:05.213  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-26 19:03:05.213  1429  1429 D BluetoothHeadset: registerMessageListener
,08-26 19:03:05.213  1962  1962 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:03:05.213  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:03:05.213  3257  3268 D HeadsetService: registerMessageListener
,08-26 19:03:05.213  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:05.223  3257  3268 D HeadsetService: registerMessageListener
08-26 19:03:05.223  3257  7724 D HeadsetStateMachine: Disconnected process message: 70
08-26 19:03:05.223  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 19:03:05.223  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 19:03:05.223  3257  7724 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@a3f857d
,08-26 19:03:05.223  4832  4832 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:03:05.223  4832  4832 D PanProfile: Bluetooth service connected
,08-26 19:03:05.223  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:05.223  1018  1560 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:05.223  3257  7735 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-26 19:03:05.223  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 19:03:05.223  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-26 19:03:05.223  1018  1564 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 19:03:05.223  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 19:03:05.223  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:05.223  4832  4832 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:05.233  3257  7724 D HeadsetStateMachine: Disconnected process message: 9,
08-26 19:03:05.233  3257  7724 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6,
,08-26 19:03:05.233   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 19:03:05.233   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 19:03:05.233   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-26 19:03:05.233   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 19:03:05.233   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 19:03:05.233   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 19:03:05.233   283   283 V audio_hw_primary: adev_set_parameters: exit
08-26 19:03:05.233  3257  7724 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 19:03:05.233  4832  4832 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 19:03:05.233  4832  4832 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 19:03:05.233  4832  4832 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 19:03:05.233  4832  4832 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 19:03:05.233  3257  7735 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 19:03:05.233  3257  7735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:05.233  3257  7735 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-26 19:03:05.233  3257  7735 D BluetoothSocket: bindListen(), new LocalSocket ,
08-26 19:03:05.233  3257  7735 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:03:05.233  3257  7735 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33661c72
08-26 19:03:05.233  3257  7735 D BluetoothSocket: channel: 5
,08-26 19:03:05.243  4832  4832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:03:05.243  1018  4869 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 19:03:05.243  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.243  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:05.243  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:05.243  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:03:05.253  1714  1714 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:05.253  4832  4832 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:05.253  4832  4832 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:03:05.263  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:05.263  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 19:03:05.263  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:05.263  3257  3257 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 19:03:05.263  1018  1380 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:05.263  1018  1380 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 19:03:05.263  1018  1380 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:05.263  1018  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:05.263  1018  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-26 19:03:05.283  1018  1136 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 19:03:05.283  3257  7740 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 19:03:05.283  3257  7740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:05.283  3257  7740 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-26 19:03:05.283  3257  7740 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:03:05.283  3257  7740 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:03:05.283  3257  7740 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ef58dbe
,08-26 19:03:05.293  3257  7740 D BluetoothSocket: channel: 12
,08-26 19:03:05.293  3257  7740 I BtOppRfcommListener: Accept thread started.
,08-26 19:03:05.853  1018  1043 W ActivityManager: mDVFSHelper.release()
,08-26 19:03:06.683  1018  1560 I ActivityManager: Killing 7306:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 19:03:06.743  1018  1031 I ActivityManager: Killing 7323:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-26 19:03:06.883   297   297 E SMD     : DCD OFF
,08-26 19:03:07.933  6888  7046 D BluetoothAdapter: disable(),
,08-26 19:03:07.933  1018  1563 D SettingsProvider: name = bluetooth_on,
,08-26 19:03:07.943  3257  3336 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
,08-26 19:03:07.943  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:07.943  3257  3336 D BluetoothAdapterProperties: Setting state to 13
08-26 19:03:07.943  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 19:03:07.943  3257  3336 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
08-26 19:03:07.943  3257  3336 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:03:07.943  3257  3336 D BluetoothAdapterService: updateAdapterState state is 13
08-26 19:03:07.953  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:07.953  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 19:03:07.953  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:03:07.953  3257  3257 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 19:03:07.953  3257  3257 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@eb16e1f, channel: 19, state: LISTENING
,08-26 19:03:07.953  3257  3257 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@eb16e1f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4660fd4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c13856cmSocket: android.net.LocalSocket@47ee735 impl:android.net.LocalSocketImpl@1c78c7ca fd:FileDescriptor[80]
,08-26 19:03:07.953  3257  3257 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@47ee735 impl:android.net.LocalSocketImpl@1c78c7ca fd:FileDescriptor[80]
,08-26 19:03:07.953  3257  3336 D BluetoothAdapterService: Autoconnection is available 
08-26 19:03:07.953  3257  3336 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 19:03:07.953  3257  3336 D BluetoothAdapterService: terminating service from this receiver
,08-26 19:03:07.963  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:07.963  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-26 19:03:07.963  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 19:03:07.973  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:07.973  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 19:03:07.973  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-26 19:03:07.973  1962  1962 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-26 19:03:07.973  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:03:07.973  4832  4832 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:07.973  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:03:07.983  1018  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:07.983  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:07.983  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:03:07.983  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:07.983  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:07.983  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:07.983  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 19:03:07.993  6888  6888 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:03:07.993  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:07.993  1018  4869 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:03:07.993  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 19:03:07.993  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:03:07.993  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 19:03:07.993  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:07.993  1018  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:07.993  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:07.993  3257  3336 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:03:07.993  3257  3336 D BluetoothAdapterProperties: mDiscovering is false
,08-26 19:03:08.003  1018  1136 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 19:03:08.003  3257  3336 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 19:03:08.003  4832  4832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:03:08.003  1018  1221 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 19:03:08.003  1018  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:03:08.003  3257  3339 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 19:03:08.003  3257  3339 D BluetoothAdapterProperties: Scan Mode:20
,08-26 19:03:08.013  1018  1221 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:08.013  1018  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:08.013  1018  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:03:08.013  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:08.013  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 19:03:08.013  3257  3336 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-26 19:03:08.013  3257  3336 E bt-btif : cmd socket is not created
,08-26 19:03:08.013  3257  7740 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:03:08.013  3257  3336 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 19:03:08.013  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:08.013  4832  4832 D BluetoothPbap: Proxy object disconnected
08-26 19:03:08.013  4832  4832 D PbapServerProfile: Bluetooth service disconnected
,08-26 19:03:08.023  3257  3341 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-26 19:03:08.023  1714  1714 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:08.023  4832  4832 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:08.033  3257  3257 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c88cd3b, channel: 5, state: LISTENING
,08-26 19:03:08.033  3257  3341 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:03:08.033  3257  3341 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:03:08.033  3257  3341 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 19:03:08.033  3257  3341 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:03:08.033  3257  3257 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c88cd3b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33661c72, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b698c58mSocket: android.net.LocalSocket@8c3c1b1 impl:android.net.LocalSocketImpl@20439696 fd:FileDescriptor[82]
,08-26 19:03:08.033  3257  3341 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:03:08.033  3257  3341 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 19:03:08.033  3257  3257 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@8c3c1b1 impl:android.net.LocalSocketImpl@20439696 fd:FileDescriptor[82]
08-26 19:03:08.033  3257  3257 I BtOppRfcommListener: stopping Accept Thread
08-26 19:03:08.033  3257  3257 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22ad0217, channel: 12, state: LISTENING
08-26 19:03:08.033  3257  3257 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@22ad0217, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ef58dbe, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f171604mSocket: android.net.LocalSocket@20a1c7ed impl:android.net.LocalSocketImpl@3e1a8622 fd:FileDescriptor[86]
08-26 19:03:08.033  3257  3257 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@20a1c7ed impl:android.net.LocalSocketImpl@3e1a8622 fd:FileDescriptor[86]
,08-26 19:03:08.033  3257  7740 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 19:03:08.033  4832  4832 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:03:08.043  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:08.043  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 19:03:08.043  3257  3257 V BluetoothOppManager: cleanUp...
,08-26 19:03:08.223  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 19:03:08.223  3257  3336 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 19:03:08.223  3257  3336 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-26 19:03:08.223  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,08-26 19:03:08.223  3257  3336 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-26 19:03:08.223  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,08-26 19:03:08.223  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:03:08.223  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 19:03:08.223  1018  4869 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:03:08.223  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 19:03:08.223  1018  4869 W ActivityManager: userId = 0, bbcId = -10000,
,08-26 19:03:08.233  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 19:03:08.233  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:08.233  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 19:03:08.233  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 19:03:08.233  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 19:03:08.233  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:08.233  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:03:08.233  1018  1031 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:03:08.233  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:08.233  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:03:08.243  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-26 19:03:08.243  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:03:08.243  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService,
08-26 19:03:08.243  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:03:08.243  3257  3257 D HeadsetService: Received stop request...Stopping profile...
08-26 19:03:08.243  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:03:08.243  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:08.243  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:08.243  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:08.243  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-26 19:03:08.243  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 19:03:08.243  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:08.243  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 19:03:08.243  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 19:03:08.243  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:08.243  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:08.243  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:08.243  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:08.243  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 19:03:08.253  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 19:03:08.253  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:03:08.253  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 19:03:08.253  1018  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:08.253  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:03:08.253  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:08.253  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:08.253  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:08.253  4832  4832 D HeadsetProfile: Bluetooth service disconnected
,08-26 19:03:08.253  3257  3257 D A2dpService: Received stop request...Stopping profile...
08-26 19:03:08.253  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 19:03:08.253  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:08.253  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 19:03:08.253  1018  1338 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:08.253  1018  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:03:08.253  3257  7726 D A2dpStateMachine: Exit Disconnected: -1
,08-26 19:03:08.253  1018  1338 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:08.253  1018  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:08.253  1018  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:08.253  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-26 19:03:08.253  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:03:08.253  3257  3336 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 19:03:08.263  1018  1380 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:08.263  1018  1380 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 19:03:08.263  1018  1380 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:08.263  1018  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:08.263  1018  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:08.263  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:08.263  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 19:03:08.263  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:08.263  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 19:03:08.263  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:08.263  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 19:03:08.263  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:08.263  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 19:03:08.263  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:03:08.263  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 19:03:08.263  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService,
08-26 19:03:08.263  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:03:08.263  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 19:03:08.263  3257  3336 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 19:03:08.263  1018  1018 D BluetoothA2dp: Proxy object disconnected
08-26 19:03:08.263  3257  3257 D HidService: Received stop request...Stopping profile...
08-26 19:03:08.263  3257  3257 D HidService: Stopping Bluetooth HidService
08-26 19:03:08.263  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 19:03:08.263  3257  3257 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:03:08.263  3257  3257 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 19:03:08.263  3257  3257 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:03:08.263  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:08.263  4832  4832 D BluetoothA2dp: Proxy object disconnected
08-26 19:03:08.263  4832  4832 D A2dpProfile: Bluetooth service disconnected
,08-26 19:03:08.263  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 19:03:08.263  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:03:08.263  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 19:03:08.273  4832  4832 D BluetoothInputDevice: Proxy object disconnected
,08-26 19:03:08.273  3257  3257 D HealthService: Received stop request...Stopping profile...
08-26 19:03:08.273  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:08.273  4832  4832 D HidProfile: Bluetooth service disconnected
,08-26 19:03:08.273  3257  3257 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 19:03:08.273  3257  3257 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 19:03:08.273  3257  3257 D PanService: Received stop request...Stopping profile...
,08-26 19:03:08.273  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:08.273  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 19:03:08.273  3257  3257 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 19:03:08.283  4832  4832 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 19:03:08.283  4832  4832 D PanProfile: Bluetooth service disconnected
,08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:08.283  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 19:03:08.283  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 19:03:08.283  3257  3257 D SapService: Received stop request...Stopping profile...
08-26 19:03:08.283  3257  3257 D SapService: Stopping Bluetooth SapService
08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:08.283  4832  4832 D BluetoothMap: Proxy object disconnected
08-26 19:03:08.283  4832  4832 D MapProfile: Bluetooth service disconnected
,08-26 19:03:08.283  3257  3257 D BluetoothA2dp: Proxy object disconnected
,08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 19:03:08.283  3257  7727 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 19:03:08.283  3257  3257 I GKI_LINUX: GKI_exit_task 2 done
08-26 19:03:08.283  3257  3257 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 19:03:08.283  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:03:08.283  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:08.283  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:03:08.283  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:08.283  3257  3257 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-26 19:03:08.283  3257  3257 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:03:08.283  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:03:08.283  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:08.283  3257  3257 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 19:03:08.283  3257  3257 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:03:08.283  3257  3257 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 19:03:08.293  4832  4832 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 19:03:08.293  4832  4832 D SapProfile: Bluetooth service disconnected
,08-26 19:03:08.293  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 19:03:08.293  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-26 19:03:08.293  3257  3257 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:03:08.293  3257  3257 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 19:03:08.293  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 19:03:08.293  3257  3257 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-26 19:03:08.293  3257  3257 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-26 19:03:08.293  3257  3257 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 19:03:08.293  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 19:03:08.293  3257  3336 D BluetoothAdapterProperties: Setting state to 10
08-26 19:03:08.293  3257  3336 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 19:03:08.293  3257  3336 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:03:08.293  3257  3336 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 19:03:08.293  3257  3336 D BluetoothAdapterService: Autoconnection is available 
08-26 19:03:08.293  3257  3336 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 19:03:08.293  3257  3336 I BluetoothAdapterState: Entering OffState
,08-26 19:03:08.293  4832  4842 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.293  4832  4842 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.293  1680  1851 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.293  1680  1851 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.293  4832  4856 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:03:08.293  6888  6902 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 19:03:08.293  1018  3423 D SSRM:n  : SIOP:: AP = 380
,08-26 19:03:08.293  6888  6902 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.303  6888  6902 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 19:03:08.303  6888  6902 D BluetoothLeAdvertiser: Exit stop advertising
,08-26 19:03:08.303  6888  6902 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 19:03:08.303  6888  6902 D BluetoothLeScanner: Exiting stopAllScan
,08-26 19:03:08.303  1455  1484 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.303  1455  1484 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.303  7219  7233 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.303  7219  7233 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.303  1714  2707 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.303  1714  2707 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.303  4832  7734 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 19:03:08.303  4832  4842 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:03:08.303  4832  4856 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 19:03:08.303  4832  4856 D Bluetoothsap: Unbinding service...
,08-26 19:03:08.313  1429  7184 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.313  1429  7184 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.313  1442  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.313  1442  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.313  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:03:08.313  1178  2150 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.313  1178  2150 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.313  3257  7207 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:03:08.313  3257  3276 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.313  3257  3276 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.313  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 19:03:08.323  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 19:03:08.323  4832  4842 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 19:03:08.323  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:08.323  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
,08-26 19:03:08.323  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 19:03:08.333  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:03:08.333  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:08.333  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-26 19:03:08.333  1018  1481 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:08.333  1018  1565 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:03:08.333  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:03:08.343  1962  1962 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:03:08.343  4832  4832 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:08.343  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:08.343  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:08.343  4832  4832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:03:08.353  1018  1338 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 19:03:08.353  1018  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:03:08.353  1018  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:08.353  1018  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:08.353  1018  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:03:08.353  1714  1714 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:08.363  4832  4832 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:08.363  4832  4832 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:03:08.363  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:08.363  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 19:03:08.523  1018  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 19:03:09.593   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:03:09.893   297   297 E SMD     : DCD OFF,
,08-26 19:03:10.593   340   340 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 19:03:10.943  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 19:03:10.943  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:11.033  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 19:03:11.043  1018  1481 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4308, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 19:03:11.043  1018  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 19:03:11.043  1018  1481 D BatteryService: stay LED for charging
,08-26 19:03:11.043  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 19:03:11.043  1018  1018 I MotionRecognitionService: Plugged
,08-26 19:03:11.043  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 19:03:11.053  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 19:03:11.053  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 19:03:11.053  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 19:03:11.053  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 19:03:11.073  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:03:11.073  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:03:11.073  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-26 19:03:11.603   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:03:12.593   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 19:03:12.903   297   297 E SMD     : DCD OFF,
,08-26 19:03:13.603   340   340 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 19:03:13.953  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:13.953  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c298314 added. We now have 6 listener(s)
,08-26 19:03:13.953  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:13.953  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:13.953  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@291517bd added. We now have 7 listener(s)
,08-26 19:03:13.953  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:13.953  6888  7046 I System.out: IsBluetoothEnabled
,08-26 19:03:13.953  6888  7046 D BluetoothAdapter: disable()
,08-26 19:03:13.953  1018  1221 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 19:03:13.963  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:13.963  6888  7046 D BluetoothAdapter: enable()
,08-26 19:03:13.963  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 19:03:13.963  1018  1031 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 19:03:13.963  1018  1031 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:03:13.963  1018  1031 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:03:13.963  1018  1031 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 19:03:13.963  1018  1031 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 19:03:13.963  1018  1031 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 19:03:13.963  1018  1031 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 19:03:13.963  1018  1031 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 19:03:13.963  1018  1031 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 19:03:13.973  1018  1031 D SettingsProvider: name = bluetooth_on
,08-26 19:03:13.973  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 19:03:13.973  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 19:03:13.983  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
08-26 19:03:13.983  3257  3336 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 19:03:13.983  3257  3336 D BluetoothAdapterProperties: Setting state to 11
08-26 19:03:13.983  3257  3336 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11,
08-26 19:03:13.983  3257  3336 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 19:03:13.993  1018  1563 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:13.983  3257  3336 D BluetoothAdapterService: updateAdapterState state is 11
08-26 19:03:13.993  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 19:03:13.983  3257  3336 D BluetoothAdapterService: Autoconnection is available 
08-26 19:03:13.983  3257  3336 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-26 19:03:13.983  3257  3336 D BtConfig.SecureMode: isSecureModeOn:false
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid ,state: 12
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 19:03:13.983  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 19:03:13.983  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 19:03:13.993  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:13.993  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:13.993  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:13.993  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 19:03:13.993  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 19:03:13.993  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 19:03:13.993  1018  1565 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:13.993  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:03:13.993  3257  3257 D HeadsetService: Received start request. Starting profile...
08-26 19:03:13.993  3257  3257 D HeadsetService: start()
08-26 19:03:13.993  3257  3257 D HeadsetStateMachine: make
,08-26 19:03:13.993  1018  1565 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:13.993  1018  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:13.993  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:13.993  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-26 19:03:14.003  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 19:03:14.003  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 19:03:14.003  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:14.003  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-26 19:03:14.003  3257  3257 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 19:03:14.013  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:03:14.013  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:14.013  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-26 19:03:14.013  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
08-26 19:03:14.013  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 19:03:14.013  1018  1563 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:14.013  1018  1221 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 19:03:14.013  1962  1962 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:03:14.023  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:14.023  4832  4832 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:14.023  1018  4869 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:14.023  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.023  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:14.023  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:14.023  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.023  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.033  1018  1560 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 19:03:14.033  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.033  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-26 19:03:14.033  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 19:03:14.033  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 19:03:14.033  1018  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:14.033  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.033  1018  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0,
08-26 19:03:14.033  1018  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.033  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 19:03:14.033  1018  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:14.033  1018  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:14.033  1018  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.033  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 19:03:14.043  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-26 19:03:14.043  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 19:03:14.043  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 19:03:14.043  1714  1714 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:14.043  1018  1565 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:03:14.043  1018  1565 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 19:03:14.043  1018  1565 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.043  1018  1565 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0,
08-26 19:03:14.043  1018  1565 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 19:03:14.043  1018  3824 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:14.043  3257  3257 I bluedroid: get_profile_interface handsfree
,08-26 19:03:14.043  1018  3824 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 19:03:14.043  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.043  1018  3824 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.043  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 19:03:14.053  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 19:03:14.053  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 19:03:14.053  3257  3336 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 19:03:14.053  1018  1221 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:14.053  1018  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.053  1018  1221 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.053  1018  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.053  1018  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.053  4832  4832 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:03:14.053  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-26 19:03:14.053  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 19:03:14.053  3257  3336 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 19:03:14.053  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:14.053  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 19:03:14.063  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.063  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:14.063  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.063  3257  3257 E DualScoManager: Dual Sco Manager already instantiated
08-26 19:03:14.063  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:14.063  3257  3257 I DualScoManager: Set HeadsetServiceHelper
08-26 19:03:14.063  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:14.063  3257  3257 D BluetoothAtMessage: createCMTIContentObservers
08-26 19:03:14.063  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 19:03:14.063  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:14.063  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:14.063  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 19:03:14.063  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 19:03:14.063  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 19:03:14.063  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 19:03:14.063  3257  3336 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-26 19:03:14.063  3257  3336 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 19:03:14.063  3257  3336 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 19:03:14.063  3257  3336 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 19:03:14.063  1018  1030 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 19:03:14.063  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 19:03:14.063  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:03:14.063  1018  1030 D SettingsProvider: selectionArgs: false
08-26 19:03:14.063  1018  1030 D SettingsProvider: selectionArgs: 1002
08-26 19:03:14.063  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 19:03:14.063  1018  1030 D SettingsProvider: ret = -1
08-26 19:03:14.063  3257  7753 D HeadsetStateMachine: Enter Disconnected: -2
08-26 19:03:14.063  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:14.063  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-26 19:03:14.073  3257  3257 D HeadsetService: mStartError = false
08-26 19:03:14.073  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:14.073  3257  3257 D A2dpService: Received start request. Starting profile...
08-26 19:03:14.073  3257  3257 D A2dpService: start()
08-26 19:03:14.073  3257  3257 I bluedroid: get_profile_interface avrcp
,08-26 19:03:14.073  3257  7753 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 19:03:14.073  3257  7753 D HeadsetStateMachine: map size, before remove : 0
08-26 19:03:14.073  3257  7753 D HeadsetStateMachine: map size, after remove: 0
,08-26 19:03:14.073  3257  3257 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 19:03:14.073  3257  3257 D Avrcp   : Initialize Media Controller
08-26 19:03:14.073  3257  3257 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 19:03:14.073  3257  3257 E Avrcp   : getActiveSessions
08-26 19:03:14.073  3257  3257 D Avrcp   : pick active media Controller
08-26 19:03:14.073  3257  3257 D Avrcp   : Get the active Media Controller 
,08-26 19:03:14.083  3257  3257 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 19:03:14.083  3257  7754 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 19:03:14.083  3257  3257 D A2dpStateMachine: make
,08-26 19:03:14.083  3257  3257 I bluedroid: get_profile_interface a2dp
,08-26 19:03:14.083  3257  7756 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 19:03:14.083  3257  3257 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 19:03:14.083  3257  3257 D A2dpService: mStartError = false
08-26 19:03:14.093  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:14.093  3257  7755 D A2dpStateMachine: Enter Disconnected: -2
,08-26 19:03:14.093  3257  3257 D HidService: Received start request. Starting profile...
,08-26 19:03:14.093  3257  3257 D HidService: start()
08-26 19:03:14.093  3257  3257 I bluedroid: get_profile_interface hidhost
08-26 19:03:14.093  3257  3257 D HidService: setHidService(): set to: null
08-26 19:03:14.093  3257  3257 D HidService: mStartError = false
08-26 19:03:14.093  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:14.093  3257  3257 D HeadsetStateMachine: Try to query the phonestate on bind
08-26 19:03:14.093  1429  7184 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 19:03:14.093  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 19:03:14.093  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 19:03:14.093  1429  7184 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 19:03:14.093  3257  3257 D HealthService: Received start request. Starting profile...
08-26 19:03:14.093  3257  3257 D HealthService: start()
,08-26 19:03:14.093  3257  7754 D BluetoothMediaBrowser: no now playing list
,08-26 19:03:14.093  3257  7754 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-26 19:03:14.093  3257  3257 I bluedroid: get_profile_interface health
,08-26 19:03:14.093  3257  3257 D HealthService: mStartError = false
08-26 19:03:14.093  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:14.093  3257  3257 D HeadsetStateMachine: Proxy object connected
08-26 19:03:14.093  3257  3257 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-26 19:03:14.093  3257  7753 D HeadsetStateMachine: Disconnected process message: 11
,08-26 19:03:14.093  3257  3257 D PanService: Received start request. Starting profile...
08-26 19:03:14.093  3257  3257 D PanService: start()
08-26 19:03:14.093  3257  3257 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:03:14.093  3257  3257 I bluedroid: get_profile_interface pan
08-26 19:03:14.093  3257  3257 D PanService: mStartError = false
08-26 19:03:14.093  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:14.093  3257  3257 D BluetoothMapService: Received start request. Starting profile...
08-26 19:03:14.093  3257  3257 D BluetoothMapService: start()
,08-26 19:03:14.103  3257  3257 D BluetoothMapService: mStartError = false
08-26 19:03:14.103  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:14.103  3257  3257 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 19:03:14.103  3257  3257 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-26 19:03:14.103  3257  7753 D HeadsetStateMachine: Disconnected process message: 18
,08-26 19:03:14.103  3257  3257 D SapService: Received start request. Starting profile...
08-26 19:03:14.103  3257  3257 D SapService: start()
08-26 19:03:14.103  3257  3257 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 19:03:14.103  3257  3257 I bluedroid: get_profile_interface sap
08-26 19:03:14.103  3257  3257 D SapService: mStartError = false
08-26 19:03:14.103  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
08-26 19:03:14.103  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 19:03:14.103  3257  3257 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 19:03:14.103  3257  7753 D HeadsetStateMachine: Disconnected process message: 10
08-26 19:03:14.103  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 19:03:14.103  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-26 19:03:14.103  3257  7753 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:03:14.103  3257  7753 D HeadsetStateMachine: Disconnected process message: 11
,08-26 19:03:14.103  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-26 19:03:14.103  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 19:03:14.123  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 19:03:14.123  3257  3257 E BluetoothAdapterService(672419259): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 19:03:14.123  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 19:03:14.123  3257  3336 I bluedroid: enable
,08-26 19:03:14.133  3257  3339 E bt-btif : Calling BTA_HhEnable
,08-26 19:03:14.133  3257  3339 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-26 19:03:14.133  3257  3339 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-26 19:03:14.133  3257  3339 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 19:03:14.133  3257  3339 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-26 19:03:14.133  3257  3339 E BluetoothServiceJni: populateRssiValuesNative
08-26 19:03:14.133  3257  3339 I bluedroid: getModelRssiValues
08-26 19:03:14.133  3257  3339 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 19:03:14.133  3257  3339 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 19:03:14.133  1018  1018 D SettingsProvider: name = bluetooth_name
,08-26 19:03:14.133  3257  3339 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-26 19:03:14.143  3257  3339 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 19:03:14.143  3257  3339 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:03:14.143  3257  3339 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:03:14.143  3257  3339 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-26 19:03:14.143  3257  3339 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-26 19:03:14.143  3257  3339 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-26 19:03:14.143  3257  3339 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 19:03:14.143  3257  3339 E bt-btif : JVenable fails
,08-26 19:03:14.143  3257  3339 D bte_conf: Device ID record 1 : primary
08-26 19:03:14.143  3257  3339 D bte_conf:   vendorId            = 0075
08-26 19:03:14.143  3257  3339 D bte_conf:   vendorIdSource      = 0001
08-26 19:03:14.143  3257  3339 D bte_conf:   product             = 0100
08-26 19:03:14.143  3257  3339 D bte_conf:   version             = 0200
08-26 19:03:14.143  3257  3339 D bte_conf:   clientExecutableURL = 
08-26 19:03:14.143  3257  3339 D bte_conf:   serviceDescription  = 
08-26 19:03:14.143  3257  3339 D bte_conf:   documentationURL    = 
08-26 19:03:14.143  3257  3339 D bte_conf: bte_load_did_conf no section named DID2.
08-26 19:03:14.143  3257  3339 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-26 19:03:14.143  3257  3339 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 19:03:14.143  3257  3336 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 19:03:14.143  3257  3336 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:03:14.143  3257  3336 D BluetoothAdapterProperties: State =  11
,08-26 19:03:14.143  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:14.143  1018  1136 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 19:03:14.143  3257  3336 D BluetoothAdapterProperties: Setting state to 12
08-26 19:03:14.143  3257  3336 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 19:03:14.143  3257  3339 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 19:03:14.153  3257  3339 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:03:14.153  3257  3339 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 19:03:14.153  1018  1564 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 19:03:14.153  1018  1564 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 19:03:14.153  1018  1564 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 19:03:14.153  1018  1564 D SettingsProvider: selectionArgs: false
,08-26 19:03:14.153  1018  1564 D SettingsProvider: selectionArgs: 1002
08-26 19:03:14.153  1018  1564 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 19:03:14.153  1018  1564 D SettingsProvider: ret = -1
,08-26 19:03:14.153  3257  3336 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 19:03:14.153  3257  3336 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 19:03:14.153  1018  3824 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:03:14.153  1018  3824 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.153  1018  3824 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:14.153  1018  3824 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.153  1018  3824 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.163  3257  3336 D BluetoothAdapterService: Autoconnection is available 
08-26 19:03:14.163  3257  3336 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 19:03:14.163  3257  3336 D BluetoothAdapterService: starting service from this receiver
,08-26 19:03:14.163  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 19:03:14.163  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:03:14.163  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 19:03:14.163  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 19:03:14.163  4832  4842 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.163  1018  1380 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 19:03:14.163  4832  4842 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:14.163  1018  1380 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.163  1018  1380 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.163  1018  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.163  1018  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.163  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:14.163  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:14.163  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:14.163  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:14.163  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:14.163  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:14.163  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-26 19:03:14.163  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:03:14.163  1680  1702 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.163  1680  1702 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:14.163  3257  3336 I BluetoothAdapterState: Entering On State from state = 11
08-26 19:03:14.163  3257  3257 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 19:03:14.163  4832  4856 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:03:14.173  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:14.173  3257  3257 I BluetoothPbapService: Handler(): got msg=1
,08-26 19:03:14.183  4832  4856 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:14.183  1018  1481 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 19:03:14.203  3257  7761 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 19:03:14.203  3257  7761 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 19:03:14.203  3257  7761 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:14.203  3257  7761 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-26 19:03:14.203  3257  7761 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:03:14.203  3257  7761 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-26 19:03:14.203  3257  7761 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2605eb0b
08-26 19:03:14.203  3257  7761 D BluetoothSocket: channel: 19
,08-26 19:03:14.203  3257  7761 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 19:03:14.333  1018  1047 I art     : Explicit concurrent mark sweep GC freed 60030(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.326ms total 150.144ms
08-26 19:03:14.333  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 19:03:14.333  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 19:03:14.333  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.333  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.333  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.333  6888  6897 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:03:14.333  6888  6897 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:14.333  1455  1880 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.333  4832  4832 D BluetoothA2dp: Proxy object connected
08-26 19:03:14.333  1455  1880 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:14.333  4832  4832 D A2dpProfile: Bluetooth service connected
,08-26 19:03:14.333  7219  7227 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.333  7219  7227 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:14.333  1714  1812 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.333  1714  1812 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:14.333  1018  1047 D BluetoothPan: Binding service...
08-26 19:03:14.333  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 19:03:14.333  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 19:03:14.333  4832  4842 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:03:14.333  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 19:03:14.343  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 19:03:14.343  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.343  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.343  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.343  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.343  4832  7734 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 19:03:14.343  4832  4832 D BluetoothPbap: Proxy object connected
,08-26 19:03:14.343  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 19:03:14.343  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 19:03:14.343  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.343  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.343  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.343  4832  4832 D PbapServerProfile: Bluetooth service connected
08-26 19:03:14.343  4832  4842 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 19:03:14.343  4832  4842 D Bluetoothsap: Binding service...
,08-26 19:03:14.343  4832  4842 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 19:03:14.343  4832  4832 D BluetoothInputDevice: Proxy object connected
08-26 19:03:14.343  4832  4832 D HidProfile: Bluetooth service connected
,08-26 19:03:14.343  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 19:03:14.343  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 19:03:14.353  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.353  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.353  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.353  4832  4842 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 19:03:14.353  1455  2014 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:14.353  4832  4832 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 19:03:14.353  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:03:14.353  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:14.353  4832  4832 D SapProfile: Bluetooth service connected
08-26 19:03:14.353  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.353  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.353  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-26 19:03:14.353  4832  4832 D Bluetoothsap: getConnectedDevices()
,08-26 19:03:14.353  1455  2014 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 19:03:14.353  1429  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.353  1429  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:14.353  1442  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.353  1442  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:14.353  1429  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:14.353  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:03:14.353  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:14.353  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.353  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.353  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 19:03:14.363  1429  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:03:14.363  1429  1451 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:14.363  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:03:14.363  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:14.363  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:14.363  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.363  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.363  1429  1451 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:03:14.363  4832  7734 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:14.363  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 19:03:14.363  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:14.363  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:14.363  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.363  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.373  4832  4832 D HeadsetProfile: Bluetooth service connected
08-26 19:03:14.373  4832  7734 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:03:14.373  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:03:14.373  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:14.373  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 19:03:14.373  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.373  1018  1018 D BluetoothA2dp: Proxy object connected
,08-26 19:03:14.373  1429  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:14.373  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 19:03:14.373  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 19:03:14.373  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:14.373  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.373  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.373  1429  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 19:03:14.373  1178  4511 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 19:03:14.373  1178  4511 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 19:03:14.373  3257  3410 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:03:14.383  3257  3410 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 19:03:14.383  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 19:03:14.383  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.383  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:14.383  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:14.383  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.383  3257  3257 D BluetoothA2dp: Proxy object connected,
08-26 19:03:14.383  3257  3257 D BluetoothAdapterService: Bluetooth A2dp source service connected,
08-26 19:03:14.383  3257  7206 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.383  3257  7206 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:14.383  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 19:03:14.383  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 19:03:14.383  4832  4856 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:03:14.383  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 19:03:14.383  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.393  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.393  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.393  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.393  4832  4842 D BluetoothPan: Binding service...
,08-26 19:03:14.393  4832  4832 D BluetoothMap: Proxy object connected,
08-26 19:03:14.393  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 19:03:14.393  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.393  4832  4832 D MapProfile: Bluetooth service connected
08-26 19:03:14.393  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:14.393  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.393  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.393  4832  4832 D BluetoothMap: getConnectedDevices()
08-26 19:03:14.393  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 19:03:14.393  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 19:03:14.393  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:14.393  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-26 19:03:14.393  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 19:03:14.403  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1d4b276f, true
,08-26 19:03:14.403  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 19:03:14.403  1429  1429 D BluetoothHeadset: registerMessageListener
,08-26 19:03:14.403  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 19:03:14.413  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:14.413  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-26 19:03:14.413  1962  1962 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 19:03:14.413  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:03:14.423  1018  1565 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:14.423  1018  1563 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 19:03:14.423  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:14.423  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 19:03:14.423  3257  7762 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 19:03:14.423  3257  3268 D HeadsetService: registerMessageListener
,08-26 19:03:14.423  3257  3268 D HeadsetService: registerMessageListener
08-26 19:03:14.423  3257  7753 D HeadsetStateMachine: Disconnected process message: 70
,08-26 19:03:14.423  3257  7753 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@13a49de8
08-26 19:03:14.423  4832  4832 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:03:14.423  4832  4832 D PanProfile: Bluetooth service connected
08-26 19:03:14.423  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 19:03:14.423  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 19:03:14.423  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 19:03:14.433  3257  7762 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 19:03:14.433  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 19:03:14.433  3257  7762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:03:14.433  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 19:03:14.433  4832  4832 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:03:14.433  1178  1810 D BluetoothTile:  handleUpdatestate:false name:null
08-26 19:03:14.433  3257  7753 D HeadsetStateMachine: Disconnected process message: 9
08-26 19:03:14.433  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 19:03:14.433  3257  7753 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-26 19:03:14.433  3257  7762 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-26 19:03:14.433  3257  7762 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:03:14.433  3257  7762 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:03:14.433  3257  7762 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ea41c01
08-26 19:03:14.433  3257  7762 D BluetoothSocket: channel: 5
,08-26 19:03:14.433   283   695 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 19:03:14.433   283   695 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-26 19:03:14.433   283   695 V voice   : voice_set_parameters: exit with code(-2)
,08-26 19:03:14.433   283   695 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 19:03:14.433   283   695 V msm8974_platform: platform_set_parameters: exit with code(-2)
,08-26 19:03:14.433   283   695 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 19:03:14.433   283   695 V audio_hw_primary: adev_set_parameters: exit
08-26 19:03:14.433  4832  4832 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 19:03:14.433  4832  4832 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 19:03:14.433  4832  4832 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-26 19:03:14.433  4832  4832 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 19:03:14.433  3257  7753 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 19:03:14.443  4832  4832 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:03:14.443  1018  1338 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 19:03:14.443  1018  1338 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.443  1018  1338 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:14.443  1018  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 19:03:14.443  1018  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 19:03:14.453  1714  1714 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:03:14.463  4832  4832 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:03:14.463  4832  4832 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 19:03:14.473  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:03:14.473  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 19:03:14.473  3257  3257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28144dbb
,08-26 19:03:14.473  3257  3257 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 19:03:14.483  1018  1564 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 19:03:14.483  1018  1564 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 19:03:14.483  1018  1564 W ActivityManager: userId = 0, bbcId = -10000,
08-26 19:03:14.483  1018  1564 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:14.483  1018  1564 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 19:03:14.493  1018  1495 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 19:03:14.503  3257  7767 D BluetoothSocket: bindListen(): myUserId = 0
08-26 19:03:14.503  3257  7767 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:03:14.503  3257  7767 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-26 19:03:14.503  3257  7767 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 19:03:14.503  3257  7767 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 19:03:14.503  3257  7767 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f35773d
08-26 19:03:14.503  3257  7767 D BluetoothSocket: channel: 12
08-26 19:03:14.503  3257  7767 I BtOppRfcommListener: Accept thread started.
,08-26 19:03:14.593   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 19:03:14.993  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:14.993  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:14.993  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:14.993  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:03:14.993  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:14.993  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:14.993  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:14.993  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:14.993  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:14.993  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:14.993  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@464e1b2 added. We now have 8 listener(s)
,08-26 19:03:14.993  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:14.993  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 19:03:14.993  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 19:03:14.993  1018  1030 D SecContentProvider2: mCursor = null
,08-26 19:03:15.003  1018  1030 D WifiService: setWifiEnabled: false pid=6888, uid=10170
,08-26 19:03:15.003  1018  1030 D SettingsProvider: name = wifi_on
,08-26 19:03:15.003  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:15.003  1018  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 19:03:15.003  1018  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 19:03:15.013  1018  1031 D SecContentProvider2: mCursor = null
,08-26 19:03:15.013  1018  1031 D WifiService: setWifiEnabled: true pid=6888, uid=10170
,08-26 19:03:15.013  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-26 19:03:15.013  1018  1031 W WifiService: Failed getting userId using ActivityManagerNative
08-26 19:03:15.013  1018  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6888, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-26 19:03:15.013  1018  1031 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 19:03:15.013  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 19:03:15.013  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 19:03:15.013  1018  1031 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 19:03:15.013  1018  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 19:03:15.013  1018  1031 D SettingsProvider: name = wifi_on
,08-26 19:03:15.023  1018  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 19:03:15.353  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-26 19:03:15.353  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 19:03:15.353  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:03:15.353  1018  1045 D Tethering: interfaceAdded wlan0
,08-26 19:03:15.363  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:03:15.363  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:03:15.363  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-26 19:03:15.363  1018  1131 E Tethering: No numeric data
,08-26 19:03:15.363   278   992 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 19:03:15.363  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 19:03:15.363  1018  1131 D Tethering: clearTetheredNotification()
08-26 19:03:15.363   278   992 D SoftapController: Softap fwReload - Ok
,08-26 19:03:15.363  1018  1045 D Tethering: interfaceAdded p2p0
08-26 19:03:15.363  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 19:03:15.373   278   992 D CommandListener: Setting iface cfg
08-26 19:03:15.373   278   992 D CommandListener: Trying to bring down wlan0
,08-26 19:03:15.373  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:03:15.373  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:15.373   278   992 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:03:15.373  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:03:15.373  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 19:03:15.383  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:03:15.383  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:03:15.383  1018  1125 V NetworkStats: performPollLocked() took 11ms
,08-26 19:03:15.383  1018  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 19:03:15.383  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:15.393  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:15.393  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:15.443  7778  7778 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-26 19:03:15.443  7778  7778 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 19:03:15.443  7778  7778 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-26 19:03:15.463  7778  7778 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-26 19:03:15.463   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7778
,08-26 19:03:15.463   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-26 19:03:15.463  7778  7778 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-26 19:03:15.463  7778  7778 I wpa_supplicant: ssSupport state is = 1
08-26 19:03:15.463  7778  7778 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-26 19:03:15.463  7778  7778 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 19:03:15.463   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7778,
08-26 19:03:15.463   398   398 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 19:03:15.483  1018  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 19:03:15.493  4832  4832 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:15.503  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:03:15.503  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:15.503  1018  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:15.503  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 19:03:15.503  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:03:15.503  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:15.503  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:15.503  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:15.503  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:15.503  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 19:03:15.503  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:15.503  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:15.503  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 19:03:15.503  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:15.503  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:15.503  1178  1178 D HotspotTile: onReceive : 2, 0
08-26 19:03:15.503  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:15.503  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:03:15.503  1636  1636 I Hs20UtilService: Starting #19
,08-26 19:03:15.503  1636  1651 I Hs20UtilService: Message received 5011
,08-26 19:03:15.513  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:03:15.513  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 19:03:15.513  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:03:15.513  7103  7103 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:03:15.633   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-26 19:03:15.633  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-26 19:03:15.683  7778  7778 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 19:03:15.683  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 19:03:15.693  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 19:03:15.693   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7778
08-26 19:03:15.693   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-26 19:03:15.693  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 19:03:15.693  7778  7778 I wpa_supplicant: ssSupport state is = 1
08-26 19:03:15.693  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 19:03:15.693  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:03:15.693  7778  7778 E wpa_supplicant: SIM READ ERROR
08-26 19:03:15.693  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 19:03:15.693  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:03:15.693  7778  7778 E wpa_supplicant: SIM READ ERROR
08-26 19:03:15.693  7778  7778 I wpa_supplicant: Blacklist: Clear (all) ,
08-26 19:03:15.693  7778  7778 I wpa_supplicant: wpa_default_ap_write_once
08-26 19:03:15.693  7778  7778 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 19:03:15.693  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 19:03:15.693  7778  7778 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 19:03:15.693  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:03:15.693  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 19:03:15.693  7778  7778 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 19:03:15.693  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 19:03:15.693  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:03:15.693  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:15.693  1018  1131 D Tethering: InitialState.processMessage what=4
,08-26 19:03:15.693  1018  1131 E Tethering: No numeric data
08-26 19:03:15.693  1018  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:03:15.693  1018  1131 D Tethering: clearTetheredNotification()
08-26 19:03:15.703  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:03:15.703  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:15.703  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 19:03:15.703  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 19:03:15.703  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 19:03:15.703  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:03:15.703  1018  1125 V NetworkStats: performPollLocked() took 2ms
08-26 19:03:15.703  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:15.703  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:15.703  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:15.783  7778  7778 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 19:03:15.903   297   297 E SMD     : DCD OFF,
,08-26 19:03:15.993  7778  7778 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 19:03:15.993  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 19:03:16.003  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-26 19:03:16.003   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7778
08-26 19:03:16.003   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 19:03:16.003  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 19:03:16.003  7778  7778 I wpa_supplicant: ssSupport state is = 1,
08-26 19:03:16.003  7778  7778 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 19:03:16.003  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 19:03:16.023  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 19:03:16.023  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:03:16.023   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7778
08-26 19:03:16.023  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 19:03:16.023   398   398 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 19:03:16.023  7778  7778 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-26 19:03:16.023  7778  7778 I wpa_supplicant: ssSupport state is = 1
08-26 19:03:16.023  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 19:03:16.023  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:03:16.023  7778  7778 E wpa_supplicant: SIM READ ERROR
08-26 19:03:16.023  7778  7778 I wpa_supplicant: wpa_default_ap_write_once
08-26 19:03:16.023  7778  7778 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-26 19:03:16.023  7778  7778 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 19:03:16.023  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:03:16.023  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-26 19:03:16.023  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 19:03:16.023  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:03:16.103  7778  7778 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 19:03:16.103  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 19:03:16.143  7778  7778 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 19:03:16.143  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 19:03:16.143  7778  7778 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-26 19:03:16.153  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-26 19:03:16.153  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-26 19:03:16.153  7778  7778 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 19:03:16.153  7778  7778 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 19:03:16.153  7778  7778 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 19:03:16.153  7778  7778 E wpa_supplicant: SIM READ ERROR,
,08-26 19:03:16.153  7778  7778 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 19:03:16.163  7778  7778 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 19:03:16.173  7778  7778 I wpa_supplicant: Skip scan - bUseNetwork false,
08-26 19:03:16.173  1018  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-26 19:03:16.183  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:16.183  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-26 19:03:16.183  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:16.183  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 19:03:16.183  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:16.183  1178  1178 D HotspotTile: onReceive : 3, 0
08-26 19:03:16.183  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 19:03:16.183  1178  1810 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 19:03:16.183  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:16.183  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:16.183  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:16.183  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 19:03:16.183  4832  4832 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:03:16.193  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:16.193  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:16.193  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:16.193  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:16.193  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:16.193  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:16.193  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:16.193  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:16.193  1018  1128 E WifiConfigStore: Not a HS20
,08-26 19:03:16.193  1018  1380 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:03:16.193  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:16.193  1018  1380 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:16.193  1018  1380 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:16.193  1018  1380 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:16.193  1018  1380 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:16.193  1018  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 19:03:16.203  1018  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 19:03:16.203  7778  7778 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 19:03:16.203  7778  7778 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 19:03:16.203  7778  7778 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 19:03:16.203  7778  7778 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 19:03:16.203  7778  7778 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 19:03:16.203  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 19:03:16.203  7778  7778 I wpa_supplicant: First Scan Start
,08-26 19:03:16.203  7778  7778 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 19:03:16.203  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 19:03:16.203  1018  1128 D WifiNative-wlan0: Setting external_sim to 1
08-26 19:03:16.203  1636  1636 I Hs20UtilService: Starting #20
08-26 19:03:16.203  1018  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:03:16.203  1018  1128 I WifiNative-HAL: startHal
08-26 19:03:16.203  1018  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f42e88c
08-26 19:03:16.203  1018  1128 I WifiNative-HAL: Could not start hal
,08-26 19:03:16.203  1636  1651 I Hs20UtilService: Message received 5011
,08-26 19:03:16.203  7103  7103 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 19:03:16.203  7103  7103 D SecurityLogAgent: StateMachine : Current State = 1
08-26 19:03:16.203  7281  7281 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:03:16.203  7103  7103 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 19:03:16.213  1018  1128 E WifiNative-wlan0: do suspend true
,08-26 19:03:16.213  1018  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 19:03:16.213  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 19:03:16.213  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:16.213  1018  1152 I WifiNative-HAL: startHal
08-26 19:03:16.213  1018  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
08-26 19:03:16.213  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e2f09bc
08-26 19:03:16.213  1018  1152 I WifiNative-HAL: Could not start hal
08-26 19:03:16.213  1018  1152 E WifiScanningService: could not start HAL
,08-26 19:03:16.213  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 19:03:16.213  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 19:03:16.213  1018  1128 E WifiNative-wlan0: invaild command id : 215
,08-26 19:03:16.213  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-26 19:03:16.213   278   992 D CommandListener: Setting iface cfg
08-26 19:03:16.213   278   992 D CommandListener: Trying to bring up p2p0
08-26 19:03:16.213  1018  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:03:16.213  1018  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 19:03:16.213  7778  7778 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 19:03:16.213  1018  1127 D WifiP2pService: P2pEnablingState
08-26 19:03:16.213  7778  7778 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 19:03:16.213  1018  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 19:03:16.213  1018  1127 D WifiP2pService: P2p socket connection successful
08-26 19:03:16.223  7778  7778 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 19:03:16.213  1018  1127 D WifiP2pService: P2pEnabledState
08-26 19:03:16.223  1018  1128 E WifiStateMachine: Failed to set frequency band 0
,08-26 19:03:16.223  1018  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 19:03:16.223  1018  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 19:03:16.223  1018  1128 E WifiNative-wlan0: invaild command id : 215
,08-26 19:03:16.223  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:16.223  1018  1128 D SecContentProvider2: mCursor = null
08-26 19:03:16.223  1018  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 19:03:16.223  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-26 19:03:16.223  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 19:03:16.223  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 19:03:16.223  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:03:16.223  1018  1048 D WifiDisplayController: disconnect
08-26 19:03:16.223  1018  1048 D WifiDisplayController: updateConnection
08-26 19:03:16.223  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 19:03:16.223  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:03:16.233  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:03:16.233  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:16.233  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:03:16.233  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-26 19:03:16.233  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 19:03:16.233  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 19:03:16.233  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 19:03:16.233  1018  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-26 19:03:16.233  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 19:03:16.233  1018  1560 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 19:03:16.233  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 19:03:16.233  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 19:03:16.233  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:03:16.243  1018  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,08-26 19:03:16.243  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  secondary type: null
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  wps: 0
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  grpcapab: 0
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  devcapab: 0
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  status: 3
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  wfdInfo: null
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-26 19:03:16.243  1018  1048 D WifiDisplayController:  SConnectInfo : null
,08-26 19:03:16.243  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:03:16.243  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 19:03:16.243  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:03:16.243  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:03:16.243  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:03:16.253  7664  7664 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:03:16.253  7664  7664 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 19:03:16.253  7664  7664 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 19:03:16.253  7266  7266 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 19:03:16.263  1018  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 19:03:16.263  1018  1127 D WifiP2pService: InactiveState
,08-26 19:03:16.263  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
08-26 19:03:16.263  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 19:03:16.263  7778  7778 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 19:03:16.263  1018  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-26 19:03:16.263  1018  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 19:03:16.343  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 19:03:16.343  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 19:03:16.343  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-26 19:03:17.043  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:17.043  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:17.043  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:17.043  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:17.043  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:17.043  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:17.043  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:17.043  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:17.043  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:17.043  6888  7046 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 19:03:17.043  6888  7046 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 19:03:17.043  6888  7046 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21b24da1 Bundle[{}]
,08-26 19:03:17.043  6888  7046 I io.jxcore.node.LifeCycleMonitor: start: OK,
08-26 19:03:17.043  6888  7046 I io.jxcore.node.LifeCycleMonitor: stop: OK,
08-26 19:03:17.053  6888  7046 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 19:03:17.053  6888  7046 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 19:03:17.053  6888  7046 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 19:03:17.053  6888  7046 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 19:03:17.053  6888  7046 I System.out: Running OutgoingSocketThread
,08-26 19:03:17.053  6888  7788 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1390)
,08-26 19:03:17.053  6888  7788 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58213
,08-26 19:03:17.053  6888  7788 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 19:03:17.203  1018  1096 V AlarmManager: waitForAlarm result :4
,08-26 19:03:17.203   278   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:03:17.203   278   988 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-26 19:03:17.213  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:17.213  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 19:03:17.213  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-26 19:03:17.413  7778  7778 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
,08-26 19:03:17.413  7778  7778 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 19:03:17.413  7778  7778 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 19:03:17.413  7778  7778 I wpa_supplicant: Trying to associate with  'G700'
08-26 19:03:17.413  7778  7778 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 19:03:17.413  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-26 19:03:17.423  1018  7784 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-26 19:03:17.433  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:17.433  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:17.543  7778  7778 E wpa_supplicant: Cmd 35605 not handled
,08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 19:03:17.543  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 19:03:17.543  7778  7778 I wpa_supplicant: Associated with F4.99.3E
08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 19:03:17.543  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:03:17.543  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:03:17.543  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-26 19:03:17.543  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 19:03:17.543  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 19:03:17.543  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 19:03:17.543  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-26 19:03:17.543  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 19:03:17.543  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,08-26 19:03:17.543  1018  1045 D Tethering: interfaceStatusChanged wlan0, true,
,08-26 19:03:17.543  1018  1131 E Tethering: No numeric data
,08-26 19:03:17.543  1018  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-26 19:03:17.543  1018  1131 D Tethering: clearTetheredNotification()
,08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-26 19:03:17.543  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:03:17.543  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:17.543  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 19:03:17.543  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-26 19:03:17.543  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:03:17.543  7778  7778 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 19:03:17.543  7778  7778 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 19:03:17.553  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 19:03:17.553  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:03:17.553  7778  7778 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 19:03:17.553  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 19:03:17.553  7778  7778 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 19:03:17.553  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 19:03:17.553  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-26 19:03:17.553  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 19:03:17.553  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:17.553  1018  1125 V NetworkStats: performPollLocked() took 13ms
,08-26 19:03:17.563  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:17.563  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:17.563  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:17.563  1018  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 19:03:17.573  1018  1128 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-26 19:03:17.573  1018  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 19:03:17.573  1018  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 19:03:17.573  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-26 19:03:17.573  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 19:03:17.573  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:03:17.583  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:17.583  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:17.583  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:17.583  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:17.583  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:17.583  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:17.583  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:17.583  1018  1563 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:17.583  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:17.583  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:17.583  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:17.583  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:17.583  1636  1636 I Hs20UtilService: Starting #21
,08-26 19:03:17.583  1636  1651 I Hs20UtilService: Message received 5007
,08-26 19:03:17.583  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-26 19:03:17.583  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:03:17.593  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 19:03:17.593  1018  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:03:17.593  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:03:17.593  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 19:03:17.593  4832  4832 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 19:03:17.593  4832  4892 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 19:03:17.603   278   992 D CommandListener: Setting iface cfg
,08-26 19:03:17.603  1018  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 19:03:17.603  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:03:17.613  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:17.613  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:03:17.613  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:17.623  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:17.623  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:03:17.623  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 19:03:17.623  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:17.623  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:17.623  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:17.623  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:17.633  1018  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 19:03:17.633  1018  1128 D SecContentProvider2: mCursor = null
,08-26 19:03:17.633  1018  1128 E WifiNative-wlan0: do suspend false
,08-26 19:03:17.633  1018  1127 D WifiP2pService: InactiveState{ what=143375 },
08-26 19:03:17.633  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:03:17.843  7794  7794 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 19:03:17.853  7794  7794 I dhcpcd  : version 5.5.6 starting,
,08-26 19:03:17.853  7794  7794 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 19:03:17.903  7794  7794 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-26 19:03:17.903  7794  7794 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 19:03:17.903  7794  7794 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-26 19:03:17.903  7794  7794 I dhcpcd  : bssid match
08-26 19:03:17.903  7794  7794 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116,
,08-26 19:03:18.053  7794  7794 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-26 19:03:18.053  6888  7046 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1391)
08-26 19:03:18.053  6888  7046 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1391)
,08-26 19:03:18.063  6888  7046 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1396)
,08-26 19:03:18.063  6888  7046 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
08-26 19:03:18.063  6888  7046 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1397)
,08-26 19:03:18.063  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:18.063  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d648503 added. We now have 2 listener(s)
,08-26 19:03:18.063  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:03:18.063  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:18.063  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.063  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:18.063  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5bc80 added. We now have 9 listener(s)
08-26 19:03:18.063  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:18.073  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:18.073  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-26 19:03:18.083  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:18.083  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:18.083  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:18.083  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:18.083  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:18.083  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:18.083  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:18.083  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:18.083  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:03:18.083  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:03:18.083  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:18.083  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:18.083  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:18.093  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@333b66fe added. We now have 3 listener(s)
,08-26 19:03:18.093  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 19:03:18.093  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:03:18.093  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.093  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:18.093  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10206e5f added. We now have 10 listener(s)
08-26 19:03:18.093  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:18.093  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:03:18.093  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:18.093  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:03:18.093  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:03:18.093  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.093  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:18.093  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 19:03:18.093  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d648503 removed from the list
08-26 19:03:18.093  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.103  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5bc80 removed from the list,
08-26 19:03:18.103  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:18.103  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:18.103  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.103  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.103  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a5bc80 not in the list
,08-26 19:03:18.103  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.103  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.103  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10206e5f removed from the list,
08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 19:03:18.103  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.103  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.103  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@333b66fe removed from the list
08-26 19:03:18.103  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:03:18.103  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bea20ac added. We now have 2 listener(s)
08-26 19:03:18.103  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:03:18.103  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-26 19:03:18.103  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.103  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:18.103  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ac8175 added. We now have 9 listener(s)
08-26 19:03:18.103  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:18.103  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:18.113  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:18.113  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:18.113  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:18.113  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:18.113  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:18.113  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:18.113  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:18.113  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:18.113  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:18.113  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:18.113  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:18.113  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:18.113  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2787917b added. We now have 3 listener(s)
,08-26 19:03:18.123  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 19:03:18.123  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:18.123  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 19:03:18.123  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:18.123  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.123  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:18.123  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232e9b98 added. We now have 10 listener(s)
,08-26 19:03:18.123  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:18.123  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:18.123  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:18.123  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:03:18.123  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:18.123  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:03:18.123  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:03:18.133  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-26 19:03:18.133  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:03:18.133  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:03:18.133  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:03:18.133  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:03:18.133  3257  3276 D BtGatt.GattService: registerClient() - UUID=d8f23fe5-0d9a-4136-8947-2594fd4b81f2
,08-26 19:03:18.143  7794  7794 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-26 19:03:18.183  3257  3339 D BtGatt.GattService: onClientRegistered() - UUID=d8f23fe5-0d9a-4136-8947-2594fd4b81f2, clientIf=6
,08-26 19:03:18.183  6888  6902 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 19:03:18.183  3257  7207 D BtGatt.GattService: start scan with filters
08-26 19:03:18.183  3257  3414 D BtGatt.ScanManager: handling starting scan
08-26 19:03:18.183  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:03:18.183  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:03:18.183  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:03:18.183  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:03:18.193  3257  3339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 19:03:18.193  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-26 19:03:18.193  3257  3414 D BtGatt.ScanManager: allow scan with filters,
08-26 19:03:18.193  3257  3414 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 19:03:18.193  3257  3414 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
08-26 19:03:18.193  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 19:03:18.193  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:03:18.193  3257  3414 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:03:18.193  3257  3414 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-26 19:03:18.193  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:03:18.193  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:03:18.193  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:03:18.193  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:03:18.203  3257  3339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-26 19:03:18.203  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.203  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 19:03:18.203  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.213  6888  7046 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:03:18.213  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:18.213  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:03:18.213  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.213  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:03:18.213  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:03:18.213  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:03:18.213  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:03:18.213  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 19:03:18.213  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:03:18.213  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:03:18.213  3257  7206 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:03:18.213  3257  3414 D BtGatt.ScanManager: filter size is 1
,08-26 19:03:18.213  3257  3410 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:03:18.213  3257  3414 D BtGatt.ScanManager: delete FilterIndex - 6
,08-26 19:03:18.223  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:03:18.223  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:03:18.223  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:03:18.223  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 19:03:18.223  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:03:18.223  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 19:03:18.223  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:03:18.223  3257  3414 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:03:18.223  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:18.233  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 19:03:18.233  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:03:18.233  3257  3414 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 19:03:18.233  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 19:03:18.233  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:03:18.233  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:03:18.233  3257  3339 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 19:03:18.233  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.233  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:18.233  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:03:18.233  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:03:18.233  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:18.233  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:18.233  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:03:18.233  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:18.233  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:18.233  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.233  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:18.233  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.233  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bea20ac removed from the list
08-26 19:03:18.233  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.233  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ac8175 removed from the list
08-26 19:03:18.233  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:18.233  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.243  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:03:18.243  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.243  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.243  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.243  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.243  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ac8175 not in the list
,08-26 19:03:18.243  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.243  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.243  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.243  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.243  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.243  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232e9b98 removed from the list
08-26 19:03:18.243  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:18.243  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.243  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.243  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.243  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2787917b removed from the list
08-26 19:03:18.243  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:18.243  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13dd944 added. We now have 2 listener(s)
,08-26 19:03:18.253  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:03:18.253  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:03:18.253  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.253  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:18.253  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e206a2d added. We now have 9 listener(s),
08-26 19:03:18.253  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:18.253  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:18.253  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:18.263  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 19:03:18.263  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:18.263  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:18.263  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:18.263  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:18.263  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:18.263  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:18.263  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:18.263  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:18.263  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:18.263  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:18.263  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@980b4f3 added. We now have 3 listener(s)
,08-26 19:03:18.263  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 19:03:18.263  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:18.263  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.263  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:18.263  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e145b0 added. We now have 10 listener(s)
08-26 19:03:18.263  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:18.263  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:18.273  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:18.273  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:18.273  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:18.273  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:03:18.273  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:18.273  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:03:18.273  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:03:18.273  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:18.283  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:03:18.283  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:03:18.283  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:03:18.293  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:03:18.293  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:03:18.303  3257  3410 D BtGatt.GattService: registerClient() - UUID=3e40d248-9a18-45db-aaee-1130f5d8dbcd
,08-26 19:03:18.323  1018  3423 D SSRM:n  : SIOP:: AP = 350,
,08-26 19:03:18.343  3257  3339 D BtGatt.GattService: onClientRegistered() - UUID=3e40d248-9a18-45db-aaee-1130f5d8dbcd, clientIf=6
08-26 19:03:18.343  6888  6902 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 19:03:18.343  3257  3444 D BtGatt.GattService: start scan with filters
08-26 19:03:18.343  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:03:18.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:03:18.343  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:03:18.343  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 19:03:18.343  3257  3414 D BtGatt.ScanManager: handling starting scan
,08-26 19:03:18.343  3257  3339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 19:03:18.343  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.343  3257  3414 D BtGatt.ScanManager: allow scan with filters
08-26 19:03:18.343  3257  3414 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 19:03:18.343  3257  3414 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-26 19:03:18.353  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-26 19:03:18.353  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:03:18.353  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:03:18.353  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 19:03:18.353  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:03:18.353  3257  3414 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:03:18.353  3257  3414 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:03:18.353  3257  3339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 19:03:18.353  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:03:18.353  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:03:18.353  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 19:03:18.353  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.363  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:18.363  6888  7046 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 19:03:18.363  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:18.363  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:18.363  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:18.363  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.363  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.363  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13dd944 removed from the list
08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.363  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e206a2d removed from the list
08-26 19:03:18.363  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:18.363  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:18.363  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.363  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 19:03:18.363  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.363  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.363  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e206a2d not in the list
08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 19:03:18.363  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:03:18.363  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:03:18.363  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:03:18.363  3257  3276 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:03:18.363  3257  3414 D BtGatt.ScanManager: filter size is 1
,08-26 19:03:18.363  3257  3414 D BtGatt.ScanManager: delete FilterIndex - 7
,08-26 19:03:18.373  3257  7207 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:03:18.373  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 19:03:18.373  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.373  3257  3414 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:03:18.373  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:03:18.373  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:03:18.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:03:18.373  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:03:18.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:03:18.373  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:18.373  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 19:03:18.373  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:03:18.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 19:03:18.373  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 19:03:18.373  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.373  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.373  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:03:18.373  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:03:18.373  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:18.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.373  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e145b0 removed from the list
08-26 19:03:18.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:18.373  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.373  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.373  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.373  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@980b4f3 removed from the list
,08-26 19:03:18.383  3257  3414 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 19:03:18.383  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:18.383  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220d0cdc added. We now have 2 listener(s)
,08-26 19:03:18.383  3257  3339 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 19:03:18.383  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.383  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:03:18.383  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:18.383  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.383  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:18.383  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1b1e5 added. We now have 9 listener(s)
08-26 19:03:18.383  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:18.383  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:18.393  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:18.393  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:18.393  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:18.393  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:18.393  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:18.393  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:18.393  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:18.393  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:18.393  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:18.393  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-26 19:03:18.393  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:18.393  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:03:18.393  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:18.393  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171bcf6b added. We now have 3 listener(s)
08-26 19:03:18.393  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:03:18.393  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:03:18.403  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:18.403  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.403  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:03:18.403  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cc1ac8 added. We now have 10 listener(s)
08-26 19:03:18.403  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:18.403  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:18.403  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:03:18.403  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 19:03:18.403  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:03:18.403  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:03:18.403  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:03:18.403  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:03:18.403  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:03:18.413  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:03:18.413  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:03:18.413  6888  7046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:03:18.413  3257  7206 D BtGatt.GattService: registerClient() - UUID=e634910a-f55f-4915-9fc5-52c46d9d0a80
,08-26 19:03:18.453  1018  1128 E WifiNative-wlan0: do suspend true
,08-26 19:03:18.453  3257  3339 D BtGatt.GattService: onClientRegistered() - UUID=e634910a-f55f-4915-9fc5-52c46d9d0a80, clientIf=6
08-26 19:03:18.453  6888  6897 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 19:03:18.453  3257  3410 D BtGatt.GattService: start scan with filters
08-26 19:03:18.453  3257  3414 D BtGatt.ScanManager: handling starting scan
08-26 19:03:18.453  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:03:18.453  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:03:18.453  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:03:18.453  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:03:18.463  3257  3339 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-26 19:03:18.463  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:03:18.463  3257  3414 D BtGatt.ScanManager: allow scan with filters
08-26 19:03:18.463  3257  3414 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 19:03:18.463  3257  3414 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
08-26 19:03:18.463  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 19:03:18.463  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 19:03:18.463  3257  3414 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:03:18.463  3257  3414 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 19:03:18.463  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:03:18.463  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:03:18.463  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:03:18.463  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:03:18.473  3257  3339 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 19:03:18.473  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.473  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 19:03:18.473  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.483  1018  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-26 19:03:18.483  1018  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 19:03:18.483  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:18.483  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:18.483  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:18.483  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.483  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220d0cdc removed from the list
08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.483  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1b1e5 removed from the list
08-26 19:03:18.483  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:18.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:18.483  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 19:03:18.483  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.483  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a1b1e5 not in the list
08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:03:18.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:03:18.483  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:03:18.483  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:03:18.483  1018  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 19:03:18.483  1018  1128 E WifiStateMachine: VerifyingLinkState enter
,08-26 19:03:18.493  3257  7206 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:03:18.493  3257  3410 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 19:03:18.493  3257  3414 D BtGatt.ScanManager: filter size is 1
08-26 19:03:18.493  3257  3414 D BtGatt.ScanManager: delete FilterIndex - 8
,08-26 19:03:18.493  3257  3339 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 19:03:18.493  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.493  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:03:18.493  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:18.493  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:18.493  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.493  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.493  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.493  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:03:18.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:03:18.493  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:03:18.493  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:03:18.493  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:03:18.503  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-26 19:03:18.503  3257  3414 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:03:18.503  1018  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 19:03:18.503  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:18.503  1018  1130 D ConnectivityService: Adding iface wlan0 to network 504
08-26 19:03:18.503  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:03:18.503  6888  7046 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 19:03:18.503  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:03:18.513  3257  3339 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 19:03:18.513  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.513  3257  3414 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 19:03:18.523  3257  3339 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 19:03:18.523  3257  3339 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 19:03:18.533  1018  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-26 19:03:18.533  1018  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 19:03:18.533  1018  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 19:03:18.533  1018  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 19:03:18.533  1018  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 19:03:18.533  1018  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-26 19:03:18.533  1018  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-26 19:03:18.543  1018  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-26 19:03:18.543  1018  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 19:03:18.543  1018  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-26 19:03:18.543  1018  1130 D ConnectivityService: LTETest block dns file not exists
,08-26 19:03:18.543  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:18.543  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:18.543  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 19:03:18.543  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.543  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.543  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.543  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:18.543  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:18.543  1018  4869 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:18.543  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.543  1018  1130 V NetworkStats: updateIfacesLocked()
08-26 19:03:18.543  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:03:18.553  1018  4869 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 19:03:18.553  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:03:18.553  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:03:18.553  1018  4869 W ActivityManager: userId = 0, bbcId = -10000
,08-26 19:03:18.553  1018  4869 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:18.553  1018  1130 V NetworkStats: performPollLocked() took 4ms
08-26 19:03:18.553  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.553  1018  4869 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:18.553  1636  1636 I Hs20UtilService: Starting #22
,08-26 19:03:18.553  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.553  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.553  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.553  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27cc1ac8 removed from the list
08-26 19:03:18.553  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:18.553  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.553  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.553  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.553  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171bcf6b removed from the list
,08-26 19:03:18.553  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:03:18.553  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:18.553  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cec1b74 added. We now have 2 listener(s)
08-26 19:03:18.553  1018  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-26 19:03:18.553  1636  1651 I Hs20UtilService: Message received 5007
08-26 19:03:18.553  6888  6888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:03:18.553  6888  6888 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:03:18.563  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:03:18.563  4832  4832 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 19:03:18.563  1018  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-26 19:03:18.573  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-26 19:03:18.573  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-26 19:03:18.573  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:18.573  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.573  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:18.573  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@209d389d added. We now have 9 listener(s)
08-26 19:03:18.573  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:03:18.573  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.573  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:18.573  1018  1130 E ConnectivityService: updateNetworkInfo()
,08-26 19:03:18.573  1018  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 19:03:18.573  1018  1130 V NetworkStats: updateIfacesLocked()
08-26 19:03:18.573  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:03:18.573  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:18.573  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:03:18.583  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:03:18.583  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 19:03:18.583  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 19:03:18.583  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.583  1018  1130 V NetworkStats: performPollLocked() took 6ms
,08-26 19:03:18.583  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:18.583  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:18.593  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 19:03:18.593  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:18.593  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.593  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.593  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:18.603  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:03:18.603  6888  7046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:03:18.603  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:18.603  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:18.603  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:18.603  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:18.603  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:18.603  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:18.603  6888  7046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:03:18.603  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 19:03:18.603  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:03:18.603  1018  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-26 19:03:18.603  1018  7792 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.603  1018  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-26 19:03:18.603  1018  7792 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 19:03:18.603  1018  7792 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:03:18.603  1018  7792 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-26 19:03:18.603  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:18.603  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:18.603  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 19:03:18.603  1018  7792 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 19:03:18.613  1018  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:03:18.613  1018  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:03:18.613  6888  7046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:03:18.613  6888  7046 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:03:18.613  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:03:18.613  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c0c0e3 added. We now have 3 listener(s)
,08-26 19:03:18.613  1018  1130 D ConnectivityService:    accepting network in place of null
08-26 19:03:18.613  1018  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 19:03:18.613  1018  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-26 19:03:18.613  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 19:03:18.613  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 19:03:18.613   278   988 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 19:03:18.613   278   988 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-26 19:03:18.613  1636  1636 I Hs20UtilService: Starting #23
,08-26 19:03:18.613  1636  1651 I Hs20UtilService: Message received 5007
,08-26 19:03:18.613  1018  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 19:03:18.613  1018  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-26 19:03:18.613  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 19:03:18.613  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 19:03:18.613  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 19:03:18.613  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
,08-26 19:03:18.623  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:18.623  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:18.623  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:18.623  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:18.623  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:18.623  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:03:18.623  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:03:18.623  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:03:18.623  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:03:18.633  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 19:03:18.633  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.633  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.633  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:18.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-26 19:03:18.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:03:18.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:03:18.633  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:03:18.633  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10697ae0 added. We now have 10 listener(s)
08-26 19:03:18.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:03:18.633  6888  7046 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:03:18.633  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:18.633  6888  7046 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:03:18.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:18.633  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.633  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:03:18.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.633  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cec1b74 removed from the list
08-26 19:03:18.633  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.633  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@209d389d removed from the list
,08-26 19:03:18.633  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:03:18.633  1018  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-26 19:03:18.633  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.633  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 19:03:18.633  1018  1131 D Tethering: MasterInitialState.processMessage what=3
08-26 19:03:18.643  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.643  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.643  4832  4832 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 19:03:18.643  1018  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-26 19:03:18.643  1178  1785 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 19:03:18.643  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:18.643  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:18.643  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:18.643  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:18.643  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:18.643  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:18.643  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:18.643  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:03:18.643  1018  1125 V NetworkStats: updateIfacesLocked()
08-26 19:03:18.643  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.643  1018  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-26 19:03:18.653  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:03:18.653  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:03:18.653  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:18.653  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-26 19:03:18.653  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 19:03:18.653  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 19:03:18.653  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-26 19:03:18.653  6888  7046 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:03:18.653  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.653  1018  1125 V NetworkStats: performPollLocked() took 5ms
08-26 19:03:18.653  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.653  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.653  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.653  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-26 19:03:18.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:03:18.653  6888  7046 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@209d389d not in the list
08-26 19:03:18.653  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.653  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:03:18.653  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.653  1018  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 19:03:18.653  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.653  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:03:18.653  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 19:03:18.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:03:18.653  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:03:18.653  6888  7046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10697ae0 removed from the list
08-26 19:03:18.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:03:18.653  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:18.653  6888  7046 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:03:18.653  6888  7046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:03:18.653  6888  7046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:03:18.653  6888  7046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15c0c0e3 removed from the list
08-26 19:03:18.663  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
08-26 19:03:18.663  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 19:03:18.663  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 19:03:18.663  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:03:18.663  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 19:03:18.663  6888  7046 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-26 19:03:18.663  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0,
08-26 19:03:18.663  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 19:03:18.663  4832  4832 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-26 19:03:18.663  4832  4832 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 19:03:18.663  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.663  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:18.673  6888  7830 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1404, name: My test thread name)
08-26 19:03:18.673  6888  7830 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1404, thread name: My test thread name)
08-26 19:03:18.673  6888  7830 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1404, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 19:03:18.673  1018  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 19:03:18.673  1018  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 19:03:18.673  1018  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 19:03:18.673  1018  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 19:03:18.673  1018  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 19:03:18.673  1636  1636 I Hs20UtilService: Starting #24
,08-26 19:03:18.673  1636  1651 I Hs20UtilService: Message received 5007
08-26 19:03:18.673  4832  4832 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 19:03:18.673  4832  4832 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 19:03:18.683  1018  1221 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 19:03:18.683  6888  7831 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1406, name: My test thread name)
,08-26 19:03:18.683  6888  7831 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1406, thread name: My test thread name)
08-26 19:03:18.683  6888  7831 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1406, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 19:03:18.683  1018  1031 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-26 19:03:18.683  1018  1031 D SecContentProvider2: mCursor = null
,08-26 19:03:18.683  6888  7046 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 19:03:18.683  6888  7046 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 19:03:18.683  6888  7046 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 19:03:18.683  6888  7046 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 19:03:18.683  6888  7046 D com.test.thalitest.ThaliTestRunner: Total duration: 23365 ms
,08-26 19:03:18.683  6888  7046 I jxcore-log: *Native tests were executed*
08-26 19:03:18.683  6888  7046 I jxcore-log: 
08-26 19:03:18.683  6888  7046 I jxcore-log: Total number of executed tests:  80
08-26 19:03:18.683  6888  7046 I jxcore-log: 
,08-26 19:03:18.693  6888  7046 I jxcore-log: Number of passed tests:  80
08-26 19:03:18.693  6888  7046 I jxcore-log: 
08-26 19:03:18.693  1018  1380 D SecContentProvider2: uri = 15 selection = getToastGravity
08-26 19:03:18.693  1018  1380 D SecContentProvider2: mCursor = null
08-26 19:03:18.693  6888  7046 I jxcore-log: Number of failed tests:  0
08-26 19:03:18.693  6888  7046 I jxcore-log: 
,08-26 19:03:18.693  6888  7046 I jxcore-log: Number of ignored tests:  0
08-26 19:03:18.693  6888  7046 I jxcore-log: 
08-26 19:03:18.693  6888  7046 I jxcore-log: Total duration:  23365
08-26 19:03:18.693  6888  7046 I jxcore-log: 
08-26 19:03:18.693  6888  7046 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 19:03:18.693  6888  7046 I jxcore-log: 
08-26 19:03:18.693  1018  1338 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 19:03:18.693  1018  1338 D SecContentProvider2: mCursor = null
08-26 19:03:18.693  1018  1564 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 19:03:18.693  1018  1564 D SecContentProvider2: mCursor = null
08-26 19:03:18.693  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:18.693  6888  7046 I jxcore-log: 
,08-26 19:03:18.693  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:18.693  6888  7046 I jxcore-log: 
08-26 19:03:18.693  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:18.693  6888  7046 I jxcore-log: 
08-26 19:03:18.693  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:18.693  6888  7046 I jxcore-log: 
08-26 19:03:18.703  1018  1495 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-26 19:03:18.703  1018  1495 D SecContentProvider2: mCursor = null
08-26 19:03:18.703  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:18.703  6888  7046 I jxcore-log: 
08-26 19:03:18.703  1018  1136 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-26 19:03:18.703  1018  1136 D SecContentProvider2: mCursor = null
08-26 19:03:18.703  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:18.703  6888  7046 I jxcore-log: 
08-26 19:03:18.703  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:18.703  6888  7046 I jxcore-log: 
08-26 19:03:18.703  6888  6888 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 19:03:18.703  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.703  6888  7046 I jxcore-log: 
08-26 19:03:18.703  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.703  6888  7046 I jxcore-log: 
08-26 19:03:18.703  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:18.703  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.713  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.713  6888  7046 I jxcore-log: 
08-26 19:03:18.723  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.723  6888  7046 I jxcore-log: 
08-26 19:03:18.723  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:18.723  6888  7046 I jxcore-log: 
08-26 19:03:18.723  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:03:18.723  6888  7046 I jxcore-log: 
,08-26 19:03:18.723   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 19:03:18.733  6888  6888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:03:18.733  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:18.733  6888  7046 I jxcore-log: 
,08-26 19:03:18.743  1018  7792 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 19:03:18.743  1018  1221 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,08-26 19:03:18.753  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,08-26 19:03:18.793  1018  7792 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:03:18 GMT], X-Android-Received-Millis=[1472230998810], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472230998777]}
,08-26 19:03:18.793  1018  7792 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.,
08-26 19:03:18.793  1018  7792 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 19:03:18.793  1018  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,08-26 19:03:18.803  1018  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 19:03:18.803  1018  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
,08-26 19:03:18.803  1018  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-26 19:03:18.803  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 19:03:18.803  1178  1785 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 19:03:18.803  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
,08-26 19:03:18.803  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 19:03:18.803  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-26 19:03:18.803  1178  1178 D StatusBar.NetworkController: updateDataNetType()
,08-26 19:03:18.813  1178  1178 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-26 19:03:18.813  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 19:03:18.813  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-26 19:03:18.813  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-26 19:03:18.813  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
,08-26 19:03:18.813  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-26 19:03:18.813  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 19:03:18.813  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 19:03:18.813  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:18.813  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 19:03:18.823  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:18.823  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 19:03:18.883  6888  6888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:03:18.883  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:18.883  6888  7046 I jxcore-log: 
,08-26 19:03:18.893   297   297 E SMD     : DCD OFF,
,08-26 19:03:19.013  7833  7833 D AndroidRuntime: ,
08-26 19:03:19.013  7833  7833 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 19:03:19.013  7833  7833 D AndroidRuntime: CheckJNI is OFF,
,08-26 19:03:19.013  7833  7833 D AndroidRuntime: readGMSProperty: start
08-26 19:03:19.013  7833  7833 D AndroidRuntime: readGMSProperty: already setted!!
08-26 19:03:19.013  7833  7833 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-26 19:03:19.013  7833  7833 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 19:03:19.013  7833  7833 D AndroidRuntime: readGMSProperty: end
08-26 19:03:19.013  7833  7833 D AndroidRuntime: addProductProperty: start
,08-26 19:03:19.053  6888  6888 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 19:03:19.053  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:03:19.053  6888  7046 I jxcore-log: 
,08-26 19:03:19.133  1018  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:19.163  7833  7833 E AffinityControl: AffinityControl: registerfunction enter,
08-26 19:03:19.163  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:19.173  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 19:03:19.173  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:19.173  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:19.173  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:19.173  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:19.183  6888  6888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:03:19.183  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:03:19.183  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:03:19.183  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:03:19.183  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:03:19.183  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:03:19.183  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:03:19.183  6888  6888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:03:19.183  6888  6888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:03:19.183  6888  7046 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:03:19.183  6888  7046 I jxcore-log: 
,08-26 19:03:19.193  7841  7841 E Zygote  : MountEmulatedStorage(),
08-26 19:03:19.193  7841  7841 E Zygote  : v2,
08-26 19:03:19.193  7841  7841 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:03:19.193  7833  7833 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 19:03:19.193  7841  7841 I libpersona: KNOX_SDCARD not a persona,
,08-26 19:03:19.193  1018  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7841 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 19:03:19.203  7841  7841 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:03:19.203  7841  7841 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:03:19.203  1018  3824 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-26 19:03:19.203  1018  3824 D PackageManager: START PACKAGE DELETE: observer{1059651122}
08-26 19:03:19.203  1018  3824 D PackageManager: pkg{<packageName>}
08-26 19:03:19.203  1018  3824 D PackageManager: user{0}
08-26 19:03:19.203  1018  3824 D PackageManager: caller{2000}
08-26 19:03:19.203  1018  3824 D PackageManager: flags{2}
08-26 19:03:19.203  1018  3824 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 19:03:19.203  1018  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 19:03:19.203  1018  3824 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-26 19:03:19.203  1018  3824 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 19:03:19.203  1018  3824 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 19:03:19.203  7841  7841 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:03:19.203  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-26 19:03:19.203  1018  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-26 19:03:19.203  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 19:03:19.203  1018  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 19:03:19.213  1018  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-26 19:03:19.213  6888  6898 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2df7815a, channel: -1, state: CLOSED
,08-26 19:03:19.223  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-26 19:03:19.223  1018  1043 I ActivityManager: Killing 6888:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 19:03:19.223  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{16303e9f u0 com.test.thalitest/.MainActivity t163}
,08-26 19:03:19.233  1018  1043 D InputDispatcher: Focus left window: 6888
,08-26 19:03:19.233   258  1164 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-26 19:03:19.233   258   437 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 19:03:19.243  7841  7841 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:03:19.253  7841  7841 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:19.263  1018  1043 D InputDispatcher: Focused application released,
08-26 19:03:19.263  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 19:03:19.263  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 19:03:19.373  7841  7841 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 19:03:19.373  7841  7841 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-26 19:03:19.373  7841  7841 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-26 19:03:19.373  1018  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-26 19:03:19.393  1018  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 19:03:19.433  2840  2840 I art     : Explicit concurrent mark sweep GC freed 17391(1024KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 957us total 40.705ms
,08-26 19:03:19.443  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 19:03:19.453  1962  1962 E SamsungIME: mOCRHelper is null
,08-26 19:03:19.453  1680  1999 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 19:03:19.483  1442  1442 D PersonaManager: isKioskContainerExistOnDevice,
,08-26 19:03:19.493  7841  7841 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-26 19:03:19.493  7841  7841 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 19:03:19.493  7841  7841 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 19:03:19.493  7841  7841 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:03:19.493  1018  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
,08-26 19:03:19.503  1018  1125 V NetworkStats: performPollLocked(flags=0x3)
08-26 19:03:19.503  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:19.503  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 19:03:19.503  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:03:19.503  1018  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 19:03:19.503  1018  1560 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-26 19:03:19.503  1018  1560 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-26 19:03:19.503  1018  1560 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-26 19:03:19.503  1018  1560 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-26 19:03:19.503  1442  1442 D RegisteredServicesCache: empty dynamic service
,08-26 19:03:19.513  1018  1560 I ActivityManager: Killing 7342:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-26 19:03:19.533  1018  1125 V NetworkStats: performPollLocked() took 29ms
08-26 19:03:19.533  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:19.553  1442  1442 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 19:03:19.553  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,08-26 19:03:19.573  1018  1130 V NetworkStats: updateIfacesLocked()
,08-26 19:03:19.573  1018  1130 V NetworkStats: performPollLocked(flags=0x1)
08-26 19:03:19.573  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:19.573  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 19:03:19.573  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 19:03:19.573  1018  1130 V NetworkStats: performPollLocked() took 6ms
08-26 19:03:19.573  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:19.583  1018  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-26 19:03:19.583  1018  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-26 19:03:19.583  1178  1785 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 19:03:19.593  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:19.593  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:19.593  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 19:03:19.593  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 19:03:19.593  1178  1785 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 19:03:19.593  1018  1018 I art     : Explicit concurrent mark sweep GC freed 66754(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 4.583ms total 202.333ms
,08-26 19:03:19.593  1018  1057 I art     : WaitForGcToComplete blocked for 105.831ms for cause Explicit
,08-26 19:03:19.603  1018  1380 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-26 19:03:19.603  1018  1380 D SecContentProvider2: mCursor = null
,08-26 19:03:19.603  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 19:03:19.603  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-26 19:03:19.613  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-26 19:03:19.623  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.633  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.643  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-26 19:03:19.643  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 19:03:19.643  1018  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 19:03:19.643  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 19:03:19.643  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 19:03:19.643  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-26 19:03:19.653  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.653  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-26 19:03:19.653  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.653  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 19:03:19.733  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 19:03:19.743  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.743  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.743  1018  1057 I art     : Explicit concurrent mark sweep GC freed 12075(651KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.843ms total 150.475ms
,08-26 19:03:19.783  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.803  1018  1057 D PackageManager: delete codoeFile: 
,08-26 19:03:19.803  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 19:03:19.803  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:03:19.803  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 19:03:19.803  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.813  1018  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-26 19:03:19.813  1018  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-26 19:03:19.813  1018  1057 D PackageManager: result of delete: 1{1059651122}
,08-26 19:03:19.813  7833  7833 D AndroidRuntime: Shutting down VM
,08-26 19:03:19.823  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.833  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.833  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 19:03:19.833  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 19:03:19.833  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.843  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 19:03:19.843  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 19:03:19.843  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 19:03:19.843  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 19:03:19.843  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 19:03:19.843  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 19:03:19.843  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 19:03:19.843  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 19:03:19.843  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: uID is 10170
,08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 19:03:19.853  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 19:03:19.853  1018  3423 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 19:03:19.853  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 19:03:19.853  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-26 19:03:19.863  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-26 19:03:19.923  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 19:03:19.923  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:19.933  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:19.933  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:19.933  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:19.943  7860  7860 E Zygote  : MountEmulatedStorage()
08-26 19:03:19.943  7860  7860 E Zygote  : v2
08-26 19:03:19.943  7860  7860 I libpersona: KNOX_SDCARD checking this for 10001
08-26 19:03:19.943  7860  7860 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:19.943  7860  7860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:03:19.943  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7860 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:03:19.943  7860  7860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:03:19.943  7860  7860 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:03:19.963  7860  7860 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 19:03:19.963  7860  7860 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:20.003  1018  3824 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 19:03:20.003  1018  3824 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:20.003  1018  3824 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:20.003  1018  3824 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:20.003  1018  3824 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 19:03:20.023  7877  7877 E Zygote  : MountEmulatedStorage(),
08-26 19:03:20.023  1018  3824 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7877 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 19:03:20.023  1018  3824 I ActivityManager: Killing 7357:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 19:03:20.023  7877  7877 E Zygote  : v2
08-26 19:03:20.033  7877  7877 I libpersona: KNOX_SDCARD checking this for 1000
08-26 19:03:20.033  7833  7833 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-26 19:03:20.033  7877  7877 I libpersona: KNOX_SDCARD not a persona
08-26 19:03:20.033  7877  7877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:03:20.033  7877  7877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 19:03:20.033  7877  7877 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 19:03:20.043  1018  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 19:03:20.043  1018  1057 D PackageManager: userId{-1}
08-26 19:03:20.043  1018  1057 D PackageManager: andCode{true}
,08-26 19:03:20.043  1018  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 19:03:20.043  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 19:03:20.043  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:20.043  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 19:03:20.043  1018  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 19:03:20.063  7886  7886 E Zygote  : MountEmulatedStorage()
08-26 19:03:20.063  7886  7886 I libpersona: KNOX_SDCARD checking this for 10003
08-26 19:03:20.063  7886  7886 E Zygote  : v2
08-26 19:03:20.063  7886  7886 I libpersona: KNOX_SDCARD not a persona
,08-26 19:03:20.063  7886  7886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 19:03:20.063  7877  7877 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 19:03:20.063  7877  7877 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:20.063  7886  7886 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 19:03:20.073  7886  7886 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 19:03:20.073  1018  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7886 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
,08-26 19:03:20.103  7886  7886 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 19:03:20.103  7886  7886 D ActivityThread: Added TimaKeyStore provider
,08-26 19:03:20.143  7877  7877 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 19:03:20.143  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 19:03:20.153  3257  3337 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 19:03:20.153  1018  1565 I ActivityManager: Killing 7400:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-26 19:03:20.153  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.153  7877  7877 E SQLit,eOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543),
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	,at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.153  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode,
08-26 19:03:20.153  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 19:03:20.153  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.153  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.153  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.153  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-26 19:03:20.163  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 19:03:20.163  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.163  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.163  7877  7877 E SQLit,eOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.163  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.163  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-26 19:03:20.163  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 19:03:20.173  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.173  7877  7877 E, SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.173  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-26 19:03:20.173  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 19:03:20.173  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.173  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.173  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.173  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-26 19:03:20.183  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 19:03:20.183  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.183  7877  7877 E, SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.183  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
,08-26 19:03:20.183  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 19:03:20.183  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.,
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: ,	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
,08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,08-26 19:03:20.183  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
,08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: ,	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	,at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.183  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.183  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-26 19:03:20.183  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 19:03:20.193  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
,08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
,08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:345)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:389)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55),
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
,08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.193  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-26 19:03:20.193  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	,at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145),
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.193  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: ,	at IlIIIIlllIIlllIIlIIl.<init>(llIIIIlllllIIllIIllI:25)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:97)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,08-26 19:03:20.193  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 19:03:20.193  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-26 19:03:20.193  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: Couldn't open diagmondm.db for writing (will try read-only):
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelp,er: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:98)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at llllIIIIlllIIIlIllIl.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:932)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:384)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:111)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:55)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543),
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 19:03:20.203  7877  7877 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 19:03:20.203  7877  7877 W SQLiteOpenHelper: Opened diagmondm.db in read-only mode
08-26 19:03:20.203  7877  7877 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.diagmonagent/databases/diagmondm.db" with flag (131138) and mode_t (0) due to error (30)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.diagmonagent/databases/diagmondm.db'.
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 19:03:20.203  7877  7877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
```
