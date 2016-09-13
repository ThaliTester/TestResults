#### Test 8506767965eb647_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
09-13 19:40:28.429  7195  7195 D AcmsService: Enter Oncreate
09-13 19:40:28.429  7195  7195 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:28.429  7195  7195 D AcmsService: creating AcmsCore
09-13 19:40:28.429  7195  7195 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-13 19:40:28.429  7195  7195 D AcmsCore: AcmsCore
09-13 19:40:28.429  7161  7161 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 111.704ms
09-13 19:40:28.429  7195  7195 D AcmsCore: init
09-13 19:40:28.429  7195  7195 D AcmsCore: Looper handler is not null
09-13 19:40:28.429  7195  7195 D AcmsCore: Post to AcmsCoreHandler
09-13 19:40:28.429  7195  7195 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:28.439  7195  7195 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-13 19:40:28.439  7195  7195 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-13 19:40:28.439  7195  7195 D AcmsService: onStartCommand
09-13 19:40:28.439  7195  7195 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-13 19:40:28.439  7195  7195 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-13 19:40:28.439  7195  7195 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-13 19:40:28.439  7195  7195 D AcmsService: Incremented Counter Value : onStartCommand
09-13 19:40:28.439  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:28.439  7195  7225 D AcmsCertificateMngr: AcmsCertificateMngr
09-13 19:40:28.439  7211  7211 D ActivityThread: Added TimaKeyStore provider
09-13 19:40:28.439  7195  7225 D AcmsRevocationMngr: AcmsRevocationMngr
--------- beginning of system
09-13 19:40:28.439  1018  1480 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-13 19:40:28.439  7195  7195 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-13 19:40:28.459  7211  7211 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:28.469  7195  7195 D AcmsService: Inside handle Intent
09-13 19:40:28.469  7195  7195 D AcmsService: App removed - package name: com.test.thalitest
09-13 19:40:28.469  7195  7195 D AcmsCore: Post to AcmsCoreHandler
09-13 19:40:28.469  7195  7195 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:28.469  7195  7195 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-13 19:40:28.469  7195  7195 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
09-13 19:40:28.469  7195  7195 D AcmsService: Decremented Counter Value : handleStartIntent
09-13 19:40:28.469  7195  7195 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-13 19:40:28.469  1018  1042 W libprocessgroup: failed to kill pid 6870: No such process
09-13 19:40:28.509  7161  7231 D Mms/ArtClassLoader: init before art
09-13 19:40:28.509  7161  7161 D Mms/TelephonyPermission: start operation mode monitor
09-13 19:40:28.519  7161  7161 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 19:40:28.529  7161  7161 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 19:40:28.529  7161  7161 D Mms/TelephonyPermission: isDefault true
09-13 19:40:28.529  7161  7161 D Mms/MmsApp: onCreate() com.android.mms
09-13 19:40:28.589  7161  7161 D Mms/MmsApp: [start]    initCountryIso consume time = 328.529531
09-13 19:40:28.609  1018  1481 D CountryDetector: The first listener is added
09-13 19:40:28.639  7161  7161 D Mms/MmsApp: [end]    initCountryIso consume time = 47.706563
09-13 19:40:28.639  7161  7161 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.118281
09-13 19:40:28.649  7161  7161 D Mms/MmsConfig: before partial update
09-13 19:40:28.659  7161  7161 D Mms/MmsConfig: Load Resize quality : 80
09-13 19:40:28.669  7161  7161 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
09-13 19:40:28.669  7161  7161 D EasySignUpManager_1.0.1: isAuth is false
09-13 19:40:28.669  7161  7161 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
09-13 19:40:28.679  1472  1489 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7161
09-13 19:40:28.679  1472  1489 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.147 ms
09-13 19:40:28.689  7161  7161 D EasySignUpManager_1.0.1: isAuth is false
09-13 19:40:28.689  7161  7161 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
09-13 19:40:28.689  7161  7161 E CscParser: mps_code.dat does not exist
09-13 19:40:28.689  7161  7161 E CscParser: customer_path =/system/csc/customer.xml
09-13 19:40:28.689  7161  7161 E CscParser: fileName + /system/csc/customer.xml
09-13 19:40:28.709  7161  7161 E CscParser: mps_code.dat does not exist
09-13 19:40:28.709  7161  7161 E CscParser: customer_path =/system/csc/customer.xml
09-13 19:40:28.709  7161  7161 E CscParser: fileName + /system/csc/customer.xml
09-13 19:40:28.729  7161  7161 D CscParser: getInstance fileName =/system/csc/customer.xml
09-13 19:40:28.729  7161  7161 D Mms/MmsConfig:  enable multiwindow = false
09-13 19:40:28.729  7161  7161 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-13 19:40:28.729  7161  7161 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-13 19:40:28.739  7161  7161 D Mms/MmsConfig: [end]    init() consume time = 100.176927
09-13 19:40:28.739  7161  7161 D Mms/Contact: [start]    init() consume time = 0.917344
09-13 19:40:28.769  1472  1668 D TP/MmsSmsProvider: query,matched:13, calling pid = 7161
09-13 19:40:28.769  1472  1668 D TP/MmsSmsProvider: match 13:Elapsed time : 3.226 ms
09-13 19:40:28.769  7161  7161 D Mms/Contact: [end]    init consume time = 35.680417
09-13 19:40:28.789  7161  7161 D Mms/MethodReflector: getSubId is called
09-13 19:40:28.789  7161  7161 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 19:40:28.789  7161  7161 D Mms/MethodReflector: getTelephonyProperty is called
09-13 19:40:28.789  7161  7161 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 19:40:28.789  7161  7161 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 19:40:28.789  7161  7161 D Mms/DownloadManager: auto download without roaming -> true
09-13 19:40:28.789  7161  7161 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 19:40:28.789  7161  7161 D Mms/MethodReflector: getSubId is called
09-13 19:40:28.789  7161  7161 D Mms/MethodReflector: getDefaultSmsSubId is called
09-13 19:40:28.799  7161  7161 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-13 19:40:28.799  7161  7241 D Mms/DraftCache: [start]    rebuildCache consume time = 23.634843
09-13 19:40:28.799  7161  7161 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-13 19:40:28.799  1472  1487 D TP/MmsSmsProvider: query,matched:12, calling pid = 7161
09-13 19:40:28.799  7235  7235 D AndroidRuntime: 
09-13 19:40:28.799  7235  7235 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 19:40:28.799  7161  7161 D Mms/MethodReflector: getTelephonyProperty is called
09-13 19:40:28.799  7161  7161 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-13 19:40:28.799  7161  7161 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 19:40:28.799  7161  7161 D Mms/DownloadManager: auto download without roaming -> true
09-13 19:40:28.799  7161  7161 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 19:40:28.799  7161  7161 D Mms/DownloadManager: auto download during roaming secondary -> false
09-13 19:40:28.799  1472  1487 D TP/MmsSmsProvider: match 12:Elapsed time : 2.361 ms
09-13 19:40:28.809  7235  7235 D AndroidRuntime: CheckJNI is OFF
09-13 19:40:28.809  7235  7235 D AndroidRuntime: readGMSProperty: start
09-13 19:40:28.809  7235  7235 D AndroidRuntime: readGMSProperty: already setted!!
09-13 19:40:28.809  7235  7235 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 19:40:28.809  7235  7235 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 19:40:28.809  7235  7235 D AndroidRuntime: readGMSProperty: end
09-13 19:40:28.809  7235  7235 D AndroidRuntime: addProductProperty: start
09-13 19:40:28.809  7161  7241 D Mms/DraftCache: [end]    rebuildCache consume time = 13.576615
09-13 19:40:28.809  7161  7161 D Mms/DownloadManager: mAutoDownload ------> true
09-13 19:40:28.859  7161  7161 D ComposerPerformance: 1473788428861 ms / [DONE] Composer constructor
09-13 19:40:28.859  7161  7161 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-13 19:40:28.859  7161  7161 I Mms/ReservationManager: ReservationManager()
09-13 19:40:28.859  7161  7161 I Mms/ReservationManager: resetAfterConnected()
09-13 19:40:28.859  1472  2022 D TP/MmsSmsProvider: query,matched:7, calling pid = 7161
09-13 19:40:28.859  1472  2022 D TP/MmsSmsProvider: match 7:Elapsed time : 3.304 ms
09-13 19:40:28.879  7161  7244 D Mms/Conversation: [start]    init() consume time = 64.6975
09-13 19:40:28.879  1018  1480 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gsf
09-13 19:40:28.879  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:28.879  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:28.879  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:28.879  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:28.889  7161  7161 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-13 19:40:28.889  1472  1487 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-13 19:40:28.889  1472  1487 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 19:40:28.889  1472  1487 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-13 19:40:28.889  7161  7161 D Mms/MmsApp: [end]    onCreate() consume time = 14.992448
09-13 19:40:28.889  1472  1487 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-13 19:40:28.889  7161  7161 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
09-13 19:40:28.899  1472  1487 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-13 19:40:28.899  7253  7253 E Zygote  : MountEmulatedStorage()
09-13 19:40:28.899  7253  7253 E Zygote  : v2
09-13 19:40:28.899  7253  7253 I libpersona: KNOX_SDCARD checking this for 10011
09-13 19:40:28.899  7253  7253 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:28.899  7253  7253 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:28.909  1472  1487 D TP/MmsSmsProvider: need read changed broadcast:false
09-13 19:40:28.909  1018  1480 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7253 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
09-13 19:40:28.909  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:28.909  1018  1481 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-13 19:40:28.909  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:28.909  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-13 19:40:28.909  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-13 19:40:28.909  7161  7244 D Mms/Conversation: [end]    init consume time = 18.127135
09-13 19:40:28.909  7161  7161 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
09-13 19:40:28.909  7161  7161 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-13 19:40:28.909  7161  7244 D Mms/MessagingNotification: [start]    init() consume time = 2.7725
09-13 19:40:28.909  7161  7161 D Mms/MethodReflector: getSubId is called
09-13 19:40:28.909  7161  7161 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 19:40:28.909  7161  7161 D Mms/MethodReflector: getTelephonyProperty is called
09-13 19:40:28.909  7161  7161 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 19:40:28.909  7161  7161 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 19:40:28.909  7161  7161 D Mms/DownloadManager: auto download without roaming -> true
09-13 19:40:28.909  7161  7161 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 19:40:28.909  7161  7161 D Mms/DownloadManager: mAutoDownload ------> true
09-13 19:40:28.909  7161  7244 D Mms/MessagingNotification: [end]    init consume time = 2.083698
09-13 19:40:28.919  7253  7253 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:28.919  7253  7253 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 19:40:28.919  1472  1668 D TP/MmsSmsProvider: query,matched:0, calling pid = 7161
09-13 19:40:28.919  1472  1668 V TP/MmsSmsProvider: getSimpleConversations entered.
09-13 19:40:28.919  1472  1668 D TP/MmsSmsProvider: match 0:Elapsed time : 1.037 ms
09-13 19:40:28.929  7161  7262 D Mms/Synchronizer: [start]    doSync consume time = 18.326667
09-13 19:40:28.929  7161  7261 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.578541
09-13 19:40:28.939  7161  7260 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
09-13 19:40:28.939  7161  7260 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
09-13 19:40:28.939  7253  7253 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:28.939  7253  7253 D ActivityThread: Added TimaKeyStore provider
09-13 19:40:28.949  1472  1487 D TP/MmsSmsProvider: update, matched:300, calling pid = 7161
09-13 19:40:28.949  1472  1487 V TP/MmsSmsProvider: syncDBData start
09-13 19:40:28.949  1472  1487 V TP/MmsSmsProvider: syncDBData sms end
09-13 19:40:28.949  1472  1487 V TP/MmsSmsProvider: syncDBData mms end
09-13 19:40:28.949  1472  1487 V TP/MmsSmsProvider: syncDBData end
09-13 19:40:28.949  7161  7262 D Mms/Synchronizer: [end]    doSync consume time = 19.157344
09-13 19:40:28.959  1018  1513 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-13 19:40:28.959  1472  2022 D TP/MmsSmsProvider: query,matched:400, calling pid = 7161
09-13 19:40:28.959  7235  7235 E AffinityControl: AffinityControl: registerfunction enter
09-13 19:40:28.959  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:28.959  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:28.959  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:28.959  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:28.969  7161  7231 D Mms/ArtClassLoader: init [DONE] art
09-13 19:40:28.979  7253  7253 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-13 19:40:28.989  7235  7235 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 19:40:28.999  7273  7273 E Zygote  : MountEmulatedStorage()
09-13 19:40:28.999  7273  7273 I libpersona: KNOX_SDCARD checking this for 10068
09-13 19:40:28.999  7273  7273 E Zygote  : v2
09-13 19:40:28.999  7273  7273 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:28.999  7273  7273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:28.999  1018  1513 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7273 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-13 19:40:28.999  7273  7273 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:28.999  7273  7273 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 19:40:29.009  7161  7261 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 56.427761
09-13 19:40:29.019  1018  1498 E PersonaManagerService: inState():  stateMachine is null !!
09-13 19:40:29.019  7273  7273 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:29.019  1018  1498 I PersonaManagerService: PersonaId don't exist
09-13 19:40:29.019  1018  1498 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-13 19:40:29.019  7273  7273 D ActivityThread: Added TimaKeyStore provider
09-13 19:40:29.019  1018  1539 I ActivityManager: Killing 6881:com.sec.android.app.themechooser/u0a145 (adj 15): empty #21
09-13 19:40:29.029  1018  1498 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 19:40:29.049  7253  7253 I GoogleHttpClient: GMS http client unavailable, use old client
09-13 19:40:29.189  1018  1512 I art     : Explicit concurrent mark sweep GC freed 26479(1532KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/37MB, paused 3.621ms total 156.322ms
09-13 19:40:29.189  1018  1498 W ActivityManager: mDVFSHelper.acquire()
09-13 19:40:29.199   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-13 19:40:29.199   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-13 19:40:29.209  7273  7273 D BadgeProvider: onCreate
09-13 19:40:29.209  7273  7273 D BadgeProvider: DatabaseHelper
09-13 19:40:29.219  1018  1498 D FocusedStackFrame: Set to : 0
09-13 19:40:29.229  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-13 19:40:29.229  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-13 19:40:29.239  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-13 19:40:29.239  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-13 19:40:29.239   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-13 19:40:29.239  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.239  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.239  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.239  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.249  7291  7291 E Zygote  : MountEmulatedStorage()
09-13 19:40:29.249  1018  1498 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-13 19:40:29.249  1018  1498 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7291 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 19:40:29.249  7291  7291 E Zygote  : v2
09-13 19:40:29.249  7291  7291 I libpersona: KNOX_SDCARD checking this for 10171
09-13 19:40:29.249  1018  1498 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 19:40:29.249  7291  7291 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:29.249  1018  1498 D InputDispatcher: Focused application set to: xxxx
09-13 19:40:29.249  1018  1498 D InputDispatcher: Focus left window: 1499
09-13 19:40:29.249  7291  7291 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:29.249  7235  7235 D AndroidRuntime: Shutting down VM
09-13 19:40:29.259  7291  7291 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:29.259  7291  7291 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-13 19:40:29.269  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 19:40:29.269  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 19:40:29.279  7161  7244 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-13 19:40:29.279  7291  7291 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:29.279  7291  7291 D ActivityThread: Added TimaKeyStore provider
09-13 19:40:29.289  1018  1331 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-13 19:40:29.289  1018  1018 V ActivityManager: Display changed displayId=0
09-13 19:40:29.299  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 19:40:29.309  7253  7253 I GoogleHttpClient: GMS http client unavailable, use old client
09-13 19:40:29.319  1018  1331 D PersonaManager: isKioskContainerExistOnDevice
09-13 19:40:29.319   258   446 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-13 19:40:29.319   258   598 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-13 19:40:29.329  1472  1487 D TP/SmsProvider: query,matched:26, calling pid = 7161
09-13 19:40:29.339  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-13 19:40:29.339  1472  1487 D TP/SmsProvider: match 26:Elapsed time : 2.776 ms
09-13 19:40:29.339  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{14e1ff token=android.os.BinderProxy@2ab74775 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 19:40:29.339  1499  1499 D Launcher: onTrimMemory. Level: 20
09-13 19:40:29.349  1472  1668 D TP/MmsSmsProvider: query,matched:6, calling pid = 7161
09-13 19:40:29.349  1472  1668 D TP/MmsSmsProvider: match 6:Elapsed time : 1.348 ms
09-13 19:40:29.359  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 19:40:29.359  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
09-13 19:40:29.359  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:29.359  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:29.359  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-13 19:40:29.379  1018  1136 I ActivityManager: Killing 6839:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-13 19:40:29.389  1018  1331 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 19:40:29.389  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
09-13 19:40:29.389  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:29.389  1018  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:29.389  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-13 19:40:29.399  1018  1266 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REMOVED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-13 19:40:29.399  1018  1136 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-13 19:40:29.409  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.409  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.409  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.409  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.419  7310  7310 E Zygote  : MountEmulatedStorage()
09-13 19:40:29.419  7310  7310 E Zygote  : v2
09-13 19:40:29.419  7310  7310 I libpersona: KNOX_SDCARD checking this for 10023
09-13 19:40:29.419  7310  7310 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:29.419  1018  1136 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7310 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-13 19:40:29.419  7310  7310 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:29.419  7310  7310 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:29.429  7310  7310 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 19:40:29.429  1454  1454 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
09-13 19:40:29.429  1018  1481 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=20, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
09-13 19:40:29.429  1018  1481 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
09-13 19:40:29.449  6334  6334 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
09-13 19:40:29.449  6334  6334 I AASAservice-TokenRule: parseToken()
09-13 19:40:29.449  6334  6334 W System.err: java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
09-13 19:40:29.449  6334  6334 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-13 19:40:29.449  6334  6334 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 19:40:29.449  6334  6334 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-13 19:40:29.449  6334  6334 W System.err: 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:86)
09-13 19:40:29.449  6334  6334 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:55)
09-13 19:40:29.449  6334  6334 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-13 19:40:29.449  6334  6334 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-13 19:40:29.449  6334  6334 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-13 19:40:29.449  6334  6334 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 19:40:29.449  6334  6334 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-13 19:40:29.449  6334  6334 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 19:40:29.449  6334  6334 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 19:40:29.449  6334  6334 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 19:40:29.449  6334  6334 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 19:40:29.449  6334  6334 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 19:40:29.449  6334  6334 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
09-13 19:40:29.449  6334  6334 W System.err: 	at libcore.io.Posix.open(Native Method)
09-13 19:40:29.449  6334  6334 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 19:40:29.449  6334  6334 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 19:40:29.449  6334  6334 W System.err: 	... 14 more
09-13 19:40:29.449  6334  6334 E AASAservice-TokenRule: parseToken() : TokenFile is null
09-13 19:40:29.449  6334  6334 E AASAservice-UpdateReceiver: AASARuleUpdateResult() : Rule file is not exist.
09-13 19:40:29.459  7161  7161 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-13 19:40:29.459  7235  7235 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-13 19:40:29.459  6334  6334 I art     : System.exit called, status: 0
09-13 19:40:29.459  6334  6334 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 19:40:29.469  1018  1266 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-13 19:40:29.469  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-13 19:40:29.469  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:29.469  1018  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:29.469  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-13 19:40:29.469  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast,
09-13 19:40:29.469  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.469  7310  7310 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:29.469  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.469  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.469  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.469  7310  7310 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:29.479  7161  7327 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,09-13 19:40:29.479  7161  7327 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,09-13 19:40:29.479  2784  2784 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected
,09-13 19:40:29.489  7328  7328 E Zygote  : MountEmulatedStorage()
09-13 19:40:29.489  7328  7328 I libpersona: KNOX_SDCARD checking this for 1000
09-13 19:40:29.489  7328  7328 E Zygote  : v2
09-13 19:40:29.489  7328  7328 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:29.489  7328  7328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:29.499  7328  7328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:29.499  7328  7328 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 19:40:29.499  1018  1483 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7328 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 19:40:29.499  7291  7291 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-13 19:40:29.499  1018  1480 I ActivityManager: Process com.samsung.aasaservice (pid 6334)(adj 0) has died(181,646)
09-13 19:40:29.499  1018  1480 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
09-13 19:40:29.509  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
09-13 19:40:29.509  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.509  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.509  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.509  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.519  7328  7328 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-13 19:40:29.519  7328  7328 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:29.529  7344  7344 E Zygote  : MountEmulatedStorage()
,09-13 19:40:29.529  7344  7344 E Zygote  : v2
09-13 19:40:29.539  7344  7344 I libpersona: KNOX_SDCARD checking this for 10014
09-13 19:40:29.539  7344  7344 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:29.539  7344  7344 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:29.539  7344  7344 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 19:40:29.539  7344  7344 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-13 19:40:29.539  1018  1043 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=7344 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,09-13 19:40:29.549  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-13 19:40:29.559  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.559  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.559  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.559  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.569  7291  7291 I cr.library_loader: Time to load native libraries: 6 ms (timestamps 965-971)
,09-13 19:40:29.569  7291  7291 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 19:40:29.569  7344  7344 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:29.569  7344  7344 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:29.579  7360  7360 E Zygote  : MountEmulatedStorage()
09-13 19:40:29.579  7360  7360 I libpersona: KNOX_SDCARD checking this for 10042
09-13 19:40:29.579  7360  7360 E Zygote  : v2
09-13 19:40:29.579  7360  7360 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:29.579  7360  7360 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:29.579  1018  1483 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7360 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,09-13 19:40:29.579  7360  7360 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:29.579  7360  7360 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,09-13 19:40:29.579  7328  7328 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,09-13 19:40:29.589  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-13 19:40:29.589  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.589  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.589  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.589  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.609  7360  7360 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:29.609  1018  1031 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7376 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 19:40:29.609  7376  7376 E Zygote  : MountEmulatedStorage()
09-13 19:40:29.609  7376  7376 I libpersona: KNOX_SDCARD checking this for 1000
09-13 19:40:29.609  7376  7376 E Zygote  : v2,
09-13 19:40:29.609  7376  7376 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:29.609  7360  7360 D ActivityThread: Added TimaKeyStore provider
09-13 19:40:29.609  1018  1031 I ActivityManager: Killing 6916:com.google.android.apps.docs/u0a87 (adj 15): empty #21
09-13 19:40:29.609  7376  7376 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 19:40:29.619  1018  1031 I ActivityManager: Killing 6941:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21,
,09-13 19:40:29.619  7376  7376 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:29.619  7376  7376 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:29.649  7376  7376 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:29.649  7376  7376 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:29.649  7310  7310 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-13 19:40:29.659  7328  7328 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.PackageEventReceiver.onReceive:182 android.app.ActivityThread.handleReceiver:3125 
,09-13 19:40:29.659  1018  1480 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,09-13 19:40:29.659  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,09-13 19:40:29.659  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:29.659  1018  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:29.659  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
09-13 19:40:29.659  7360  7360 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:29.659  7360  7360 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 19:40:29.659  7360  7360 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 19:40:29.669  7291  7291 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c9b087d}
,09-13 19:40:29.679  7291  7291 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 19:40:29.679  7161  7244 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-13 19:40:29.679  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-13 19:40:29.679  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,09-13 19:40:29.679  6981  6981 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-13 19:40:29.679  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:29.679  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:29.679  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,09-13 19:40:29.679  6981  6981 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,09-13 19:40:29.679  6981  6981 I TapandpayWidget:Utils: Clear T&P info.
,09-13 19:40:29.689  6981  6981 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-13 19:40:29.689  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-13 19:40:29.689  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.689  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.689  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.689  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.699  7376  7376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,09-13 19:40:29.709  7291  7291 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 19:40:29.709  7394  7394 E Zygote  : MountEmulatedStorage()
09-13 19:40:29.709  7394  7394 E Zygote  : v2
09-13 19:40:29.709  7394  7394 I libpersona: KNOX_SDCARD checking this for 10009
09-13 19:40:29.709  7394  7394 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:29.709  7394  7394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:29.709  7394  7394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:29.709  1018  1480 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7394 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-13 19:40:29.709  7394  7394 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-13 19:40:29.709  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-13 19:40:29.709  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
09-13 19:40:29.709  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:29.709  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:29.709  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,09-13 19:40:29.719  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-13 19:40:29.719  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-13 19:40:29.719  1018  1498 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-13 19:40:29.719  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-13 19:40:29.719  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-13 19:40:29.719  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:29.719  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:29.719  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-13 19:40:29.719  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-13 19:40:29.719  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false,
,09-13 19:40:29.719  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-13 19:40:29.729  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-13 19:40:29.729  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false,
09-13 19:40:29.729  7360  7360 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-13 19:40:29.729  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-13 19:40:29.729  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false,
,09-13 19:40:29.729  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-13 19:40:29.729  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.729  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.739  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-13 19:40:29.739  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.739  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.739  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-13 19:40:29.739  7310  7310 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-13 19:40:29.749   318   318 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 40.436ms
,09-13 19:40:29.759  7394  7394 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:29.759  7394  7394 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:29.769   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.791ms
,09-13 19:40:29.779  7291  7291 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 19:40:29.779   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 16.218ms
09-13 19:40:29.779  7291  7291 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 19:40:29.789  7291  7291 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-13 19:40:29.799  7413  7413 E Zygote  : MountEmulatedStorage(),
09-13 19:40:29.799  7413  7413 E Zygote  : v2
09-13 19:40:29.799  7413  7413 I libpersona: KNOX_SDCARD checking this for 1000
09-13 19:40:29.799  7413  7413 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:29.799  1018  1483 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7413 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 19:40:29.799  7413  7413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:29.799  7413  7413 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:29.809  7413  7413 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-13 19:40:29.809   290   290 E installd: system dir 0 : /system/app/
09-13 19:40:29.809   290   290 E installd: system dir 1 : /system/priv-app/
09-13 19:40:29.809   290   290 E installd: system dir 2 : /vendor/app/
09-13 19:40:29.809   290   290 E installd: system dir 3 : /oem/app/
09-13 19:40:29.809  1018  1483 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-13 19:40:29.809  1018  1483 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.apps.docs/com.google.android.apps.docs.receivers.AppPackageAddRemoveReceiver}
09-13 19:40:29.809  1018  1483 W BroadcastQueue: android.os.TransactionTooLargeException
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-13 19:40:29.809  1018  1483 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-13 19:40:29.809  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-13 19:40:29.809  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.809  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.809  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.809  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.819  7195  7225 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-13 19:40:29.829  7428  7428 E Zygote  : MountEmulatedStorage()
,09-13 19:40:29.829  7428  7428 E Zygote  : v2
09-13 19:40:29.829  7428  7428 I libpersona: KNOX_SDCARD checking this for 10087
09-13 19:40:29.829  7428  7428 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:29.839  1018  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-13 19:40:29.839  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 19:40:29.839  7413  7413 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:29.839  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:29.839  7413  7413 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:29.839  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 19:40:29.839  1018  1483 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7428 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
09-13 19:40:29.839  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{37761328 u0 com.test.thalitest/.MainActivity t2}
,09-13 19:40:29.849  7195  7225 I AcmsKeyStoreHelper: Key Store exist,
09-13 19:40:29.849  7195  7225 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-13 19:40:29.849  1018  1331 I ActivityManager: Killing 6965:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-13 19:40:29.859  1018  1331 I ActivityManager: Killing 6902:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-13 19:40:29.859  1018  1481 I TactileAssist: enable value -1
09-13 19:40:29.859  1018  1042 W libprocessgroup: failed to open /acct/uid_10087/pid_6916/cgroup.procs: No such file or directory
09-13 19:40:29.859  1018  1481 I TactileAssist: internal enable value -1
09-13 19:40:29.859  1018  1481 I TactileAssist: intensity value -1
09-13 19:40:29.859  1018  1481 I TactileAssist: saveAppList value true
,09-13 19:40:29.859  1018  1498 I ActivityManager: Killing 6996:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-13 19:40:29.859  1018  1481 I TactileAssist: List of disabled apps :
,09-13 19:40:29.869  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:29.869  7428  7428 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:29.869  1018  1031 I ActivityManager: Killing 7015:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #21
,09-13 19:40:29.879  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-13 19:40:29.889  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.889  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.889  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.889  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.899  7447  7447 E Zygote  : MountEmulatedStorage(),
,09-13 19:40:29.899  7447  7447 E Zygote  : v2
09-13 19:40:29.899  7447  7447 I libpersona: KNOX_SDCARD checking this for 10048
09-13 19:40:29.899  7447  7447 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:29.899  7447  7447 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:29.909  1018  1136 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7447 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a,
09-13 19:40:29.909  7447  7447 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:29.909  7447  7447 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 19:40:29.919  7413  7413 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-13 19:40:29.919  7413  7413 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-13 19:40:29.919  7413  7413 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
09-13 19:40:29.919  7291  7291 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 19:40:29.919  7291  7291 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 19:40:29.919  7291  7291 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 19:40:29.919  7291  7291 I Adreno-EGL: Local Branch: 
09-13 19:40:29.919  7291  7291 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 19:40:29.919  7291  7291 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 19:40:29.919  7291  7291 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 19:40:29.929  7447  7447 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:29.939  7447  7447 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:29.949  1018  1031 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-13 19:40:29.959  1018  1030 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-13 19:40:29.959  7413  7413 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-13 19:40:29.959  7413  7413 I PCWCLIENTTRACE_PushUtil: sales region : global
09-13 19:40:29.959  7413  7413 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 19:40:29.959  7413  7413 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,09-13 19:40:29.959  1018  1480 I ActivityManager: Killing 6767:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-13 19:40:29.969  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-13 19:40:29.969  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.969  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:29.969  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.969  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:29.989  7466  7466 E Zygote  : MountEmulatedStorage()
09-13 19:40:29.989  7466  7466 E Zygote  : v2
09-13 19:40:29.989  7466  7466 I libpersona: KNOX_SDCARD checking this for 10029
09-13 19:40:29.989  7466  7466 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:29.989  7466  7466 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:29.989  7195  7225 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-13 19:40:29.989  7195  7225 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-13 19:40:29.989  7195  7225 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-13 19:40:29.989  7195  7225 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:29.989  7195  7225 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-13 19:40:29.989  1018  1480 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7466 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-13 19:40:29.989  7195  7225 D AcmsCertificateMngr: handleAppRemoved() Enter com.test.thalitest
,09-13 19:40:29.989  7466  7466 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:29.989  7466  7466 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 19:40:29.989  1018  1480 I ActivityManager: Killing 5996:com.android.vending/u0a26 (adj 15): empty #21
09-13 19:40:29.989  1018  1512 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:29.989  1018  1512 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
09-13 19:40:29.989  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:29.989  1018  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:29.989  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 19:40:29.999  7447  7447 D Compatibility: onReceive() it will make start service
,09-13 19:40:29.999  1018  1481 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-13 19:40:29.999  4777  7032 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 19:40:29.999  7195  7225 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.provider: com.samsung.android.mirrorlink.acms.provider.AcmsDbProvider
09-13 19:40:30.009  4777  7031 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,09-13 19:40:30.009  1018  1266 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-13 19:40:30.009  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-13 19:40:30.009  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.009  1018  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:30.009  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-13 19:40:30.009  4777  4777 D AsyncTaskServiceImpl: Submit a task: nzm
,09-13 19:40:30.019  4777  7032 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 19:40:30.019  1018  1539 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:30.019  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.019  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.019  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.029  7466  7466 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:30.029  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-13 19:40:30.029  7466  7466 D ActivityThread: Added TimaKeyStore provider
09-13 19:40:30.029  7447  7478 D Compatibility: onHandleIntent()
09-13 19:40:30.029  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.029  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.029  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.029  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:30.029  7447  7478 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,09-13 19:40:30.029  7447  7478 D Compatibility: found: 2
,09-13 19:40:30.029  4777  4944 D nzm     : Processing package: com.test.thalitest
,09-13 19:40:30.039  7447  7478 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 19:40:30.039  7491  7491 E Zygote  : MountEmulatedStorage()
09-13 19:40:30.039  7491  7491 E Zygote  : v2
09-13 19:40:30.039  7491  7491 I libpersona: KNOX_SDCARD checking this for 10052
09-13 19:40:30.039  7491  7491 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:30.039  7491  7491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:30.049  1018  1483 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7491 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-13 19:40:30.049  7195  7225 D AcmsAppEntryInterface: App not found in DB Hence ignore
09-13 19:40:30.049  7195  7225 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>5
09-13 19:40:30.049  7195  7225 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:30.049  7195  7225 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-13 19:40:30.049  7195  7225 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-13 19:40:30.049  7491  7491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:30.049  7491  7491 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 19:40:30.049  7447  7478 D Compatibility: skipping ResolveInfo{3384d64b com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-13 19:40:30.049  1018  1266 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:30.049  7447  7478 D Compatibility: considering ResolveInfo{31dc4828 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-13 19:40:30.049  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 19:40:30.049  7447  7478 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
09-13 19:40:30.049  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.049  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.049  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 19:40:30.049  7447  7478 D Compatibility: enabling receiver ResolveInfo{fb71941 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 19:40:30.059  4777  4944 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-13 19:40:30.059  4777  4944 D nzm     : Found info for package com.test.thalitest in db.
,09-13 19:40:30.059  7447  7478 D Compatibility: enabling receiver ResolveInfo{3edbee6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 19:40:30.069  1018  1498 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:30.069  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.069  7195  7195 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-13 19:40:30.069  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.069  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.069  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 19:40:30.069  7195  7195 D AcmsService: Enter onDestroy
09-13 19:40:30.069  7195  7195 I AcmsService: cleanUp(): inside service clean up
09-13 19:40:30.069  7195  7195 D AcmsCore: AcmsCore: inside DeInit
09-13 19:40:30.069  7195  7195 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-13 19:40:30.069  7195  7195 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-13 19:40:30.069  7195  7195 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-13 19:40:30.069  7195  7195 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-13 19:40:30.069  7195  7195 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-13 19:40:30.069  7195  7195 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-13 19:40:30.079  7195  7195 D AcmsService: killing acms process
,09-13 19:40:30.079  7195  7195 I Process : Sending signal. PID: 7195 SIG: 9
,09-13 19:40:30.079  1018  1539 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:30.089  1018  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.089  7447  7478 D Compatibility: enabling receiver ResolveInfo{28488c27 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 19:40:30.099  1018  1539 W ActivityManager: userId = 0, bbcId = -10000,
09-13 19:40:30.099  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.099  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.099  7291  7291 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 19:40:30.099  7491  7491 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:30.099  7491  7491 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:30.109  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:30.109  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.109  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.109  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:30.109  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 19:40:30.109  7447  7478 D Compatibility: enabling receiver ResolveInfo{ec1bed4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 19:40:30.119  1018  1513 I ActivityManager: Process ACMS.Process (pid 7195)(adj 0) has died(184,657)
,09-13 19:40:30.119  4777  7032 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 19:40:30.129  7291  7291 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 19:40:30.129  7291  7291 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 19:40:30.139  7291  7291 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 19:40:30.139  7291  7291 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-13 19:40:30.139  7447  7478 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-13 19:40:30.139  4777  7032 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 19:40:30.139  1018  1266 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:30.139  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.139  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.139  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.149  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:30.149  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.149  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.149  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.149  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.159  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:30.159  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.159  1018  1136 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,09-13 19:40:30.159  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.159  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.159  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.179  1018  1266 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 19:40:30.179  1018  1266 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver}
09-13 19:40:30.179  1018  1266 W BroadcastQueue: android.os.TransactionTooLargeException
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-13 19:40:30.179  1018  1266 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-13 19:40:30.179  1018  1266 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,09-13 19:40:30.179  7466  7512 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-13 19:40:30.179  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.179  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.179  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.179  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:30.199  7515  7515 E Zygote  : MountEmulatedStorage()
09-13 19:40:30.199  7515  7515 E Zygote  : v2
09-13 19:40:30.199  7515  7515 I libpersona: KNOX_SDCARD checking this for 10026
09-13 19:40:30.199  7515  7515 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:30.199  7515  7515 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:30.199  1018  1266 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7515 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 19:40:30.199  7515  7515 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:30.199  7515  7515 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 19:40:30.209  7466  7512 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-13 19:40:30.209  7466  7512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:30.209  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:30.209  7466  7512 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 19:40:30.209  7466  7512 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-13 19:40:30.209  1018  1480 I ActivityManager: Killing 7061:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-13 19:40:30.219  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.219  7466  7512 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-13 19:40:30.219  7466  7512 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-13 19:40:30.219  7466  7512 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 19:40:30.219  7466  7512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:30.219  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:30.219  7466  7512 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 19:40:30.219  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.219  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.219  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.229  2784  2784 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,09-13 19:40:30.229  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:30.239  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.239  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.239  7515  7515 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:30.239  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.239  7515  7515 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:30.249  1018  1266 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-13 19:40:30.249  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.249  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.249  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.249  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:30.259  7466  7512 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 19:40:30.259  7466  7512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:30.259  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 19:40:30.259  7253  7264 E SQLiteLog: (283) recovered 324 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal,
,09-13 19:40:30.269  7466  7512 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
09-13 19:40:30.269  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:30.269  7466  7512 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-13 19:40:30.269  7531  7531 E Zygote  : MountEmulatedStorage()
09-13 19:40:30.269  7531  7531 I libpersona: KNOX_SDCARD checking this for 10032
09-13 19:40:30.269  7531  7531 E Zygote  : v2
09-13 19:40:30.269  7531  7531 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:30.279  7531  7531 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:30.279  7531  7531 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:30.279  7466  7512 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 19:40:30.279  7531  7531 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-13 19:40:30.279  7466  7512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:30.279  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:30.279  7466  7512 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-13 19:40:30.279  7466  7512 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 19:40:30.279  7466  7512 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 19:40:30.279  7466  7512 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 19:40:30.289  1018  1266 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7531 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 19:40:30.289  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 19:40:30.289  7466  7512 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 19:40:30.289  7466  7512 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 19:40:30.299  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:30.299  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.299  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.299  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.299  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.309  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-13 19:40:30.309  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.319  1018  1042 W libprocessgroup: failed to open /acct/uid_10026/pid_5996/cgroup.procs: No such file or directory
09-13 19:40:30.319  7466  7512 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-13 19:40:30.319  7466  7512 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 19:40:30.319  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:30.319  7466  7512 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 19:40:30.319  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.319  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.319  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 19:40:30.329  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,09-13 19:40:30.329  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.329  7531  7531 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:30.329  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.329  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.329  7531  7531 D ActivityThread: Added TimaKeyStore provider
09-13 19:40:30.329  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 19:40:30.339  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.349  1018  1266 W ActivityManager: userId = 0, bbcId = -10000,
09-13 19:40:30.349  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.349  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.359  1018  1513 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:30.359  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.359  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.359  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.359  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.369  7291  7291 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 19:40:30.369  1018  1480 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-13 19:40:30.389  7291  7291 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 19:40:30.389  7466  7512 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-13 19:40:30.389  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:30.389  7466  7512 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 19:40:30.389  7466  7512 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 19:40:30.399  1018  1513 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:30.399  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.399  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.399  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.399  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.399  7291  7291 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-13 19:40:30.399  7291  7291 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-13 19:40:30.419  7291  7291 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-13 19:40:30.419  7466  7512 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-13 19:40:30.419  7466  7512 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:30.419  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 19:40:30.419  7466  7512 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 19:40:30.429  7291  7291 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 19:40:30.429  7291  7291 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 19:40:30.439  7466  7512 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,09-13 19:40:30.449  1018  1483 I ActivityManager: Killing 7096:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-13 19:40:30.449  7531  7553 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-13 19:40:30.449  7531  7553 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-13 19:40:30.459  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:30.469  4777  7551 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-13 19:40:30.469  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.469  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:30.469  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.479  7531  7553 D SPPClientService: PushLog.txt file is not deleted.
,09-13 19:40:30.479  7531  7553 D SPPClientService: PushLog.txt file is not deleted.
,09-13 19:40:30.479  7531  7553 D SPPClientService: ============PushLog. stop!
,09-13 19:40:30.489  1018  1331 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-13 19:40:30.489  1018  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:30.489  1018  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.489  1018  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.489  1018  1331 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:30.499  7466  7512 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-13 19:40:30.499  7466  7512 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,09-13 19:40:30.499  7466  7512 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 19:40:30.499  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 19:40:30.499  7466  7512 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 19:40:30.509  1018  1331 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7560 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,09-13 19:40:30.509  7560  7560 E Zygote  : MountEmulatedStorage()
09-13 19:40:30.509  7560  7560 E Zygote  : v2
09-13 19:40:30.519  7560  7560 I libpersona: KNOX_SDCARD checking this for 10039
09-13 19:40:30.519  7560  7560 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:30.519  7560  7560 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-13 19:40:30.519  7466  7512 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-13 19:40:30.519  7466  7512 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 19:40:30.519  7560  7560 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 19:40:30.529  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:30.529  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:30.529  7560  7560 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:30.529  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:30.529  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:30.529  7466  7512 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,09-13 19:40:30.559  7579  7579 E Zygote  : MountEmulatedStorage(),
09-13 19:40:30.559  7579  7579 E Zygote  : v2
09-13 19:40:30.559  7579  7579 I libpersona: KNOX_SDCARD checking this for 1000,
09-13 19:40:30.559  7579  7579 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:30.559  7579  7579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:30.559  7579  7579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:30.559  7579  7579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-13 19:40:30.559  1018  1043 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=7579 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 19:40:30.569  7560  7560 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:30.569  7560  7560 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:30.609  7579  7579 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:30.619  7579  7579 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:30.619   296   296 E SMD     : DCD OFF,
09-13 19:40:30.619  7560  7560 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 19:40:30.619  7560  7560 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:30.619  7560  7560 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:30.619  7560  7560 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-13 19:40:30.619  7560  7560 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 19:40:30.619  7560  7560 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 19:40:30.619  7560  7560 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 19:40:30.619  1018  1331 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 19:40:30.619  7428  7465 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-13 19:40:30.619  7428  7465 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 19:40:30.619  7428  7465 I GAv4    :   adb logcat -s GAv4
,09-13 19:40:30.629  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.629  1018  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.629  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.639  7291  7599 D OpenGLRenderer: Render dirty regions requested: true
,09-13 19:40:30.639  1018  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:30.639  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.649  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:30.649  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.649  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.649  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 19:40:30.649  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 19:40:30.649  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-13 19:40:30.649  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-13 19:40:30.649  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 19:40:30.659  7291  7291 V ActivityThread: updateVisibility : ActivityRecord{1ccd3734 token=android.os.BinderProxy@2136a846 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-13 19:40:30.659  7291  7484 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-13 19:40:30.699  7291  7291 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-13 19:40:30.699  7291  7291 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-13 19:40:30.709  1018  1331 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:30.709  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:30.709  7579  7579 D AASAservice: onCreate()
,09-13 19:40:30.709  7579  7579 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
09-13 19:40:30.709  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.709  1018  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:30.709  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:30.719  2784  2784 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
,09-13 19:40:30.729  7428  7465 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:40:30.739  1018  1513 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-13 19:40:30.739   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-13 19:40:30.759  1018  1031 D InputDispatcher: Focus entered window: 7291
,09-13 19:40:30.799  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-13 19:40:30.799  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 19:40:30.799  7291  7291 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 19:40:30.799  7291  7599 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 19:40:30.809  7291  7599 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-13 19:40:30.809  7291  7599 D OpenGLRenderer: Enabling debug mode 0
,09-13 19:40:30.809  7428  7444 W art     : Suspending all threads took: 11.869ms
,09-13 19:40:30.839  7428  7465 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:40:30.859  7428  7611 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:40:30.889  7428  7465 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,09-13 19:40:30.889  7161  7161 I Mms/MmsApp:  start initViewCache mms
,09-13 19:40:30.889  7161  7161 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1882.99927
09-13 19:40:30.889  7161  7161 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-13 19:40:30.949  1018  1480 I art     : Explicit concurrent mark sweep GC freed 25766(1517KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/37MB, paused 2.786ms total 188.154ms
,09-13 19:40:30.959  1018  1498 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-13 19:40:30.959  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
09-13 19:40:30.959  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:30.959  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:30.959  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-13 19:40:30.959  1018  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-13 19:40:30.969  1018  1512 D LocationManagerService: getProviders()=[passive]
09-13 19:40:30.969  1018  7622 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-13 19:40:30.969  1174  1174 D PanelView: There is/are notification(s) 
09-13 19:40:30.979  1018  1048 I ActivityManager: Displayed Component not be shown by security: +1s658ms (total +1s750ms)
09-13 19:40:30.989  1018  1048 W ActivityManager: mDVFSHelper.release()
09-13 19:40:30.989  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37761328 u0 com.test.thalitest/.MainActivity t2} time:92390
09-13 19:40:30.989   258   446 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-13 19:40:30.989  7560  7560 D NearbySource: Nearby Source Create!
,09-13 19:40:30.999  7560  7560 D NearbyContext: Nearby Context Create!
,09-13 19:40:31.009  7291  7291 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-13 19:40:31.009  7291  7291 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2136a846 time:92411
,09-13 19:40:31.029  1018  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,09-13 19:40:31.029  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:31.029  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.029  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.029  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:31.039  7291  7291 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7291
,09-13 19:40:31.049  7633  7633 E Zygote  : MountEmulatedStorage()
09-13 19:40:31.049  7633  7633 E Zygote  : v2
09-13 19:40:31.049  7633  7633 I libpersona: KNOX_SDCARD checking this for 1000
09-13 19:40:31.049  7633  7633 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:31.049  7633  7633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:31.049  7633  7633 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:31.049  7633  7633 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:31.059  1018  1539 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7633 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 19:40:31.069  1018  1031 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 19:40:31.069  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.079  1877  1877 I SamsungIME: getCurrentCandidateView
,09-13 19:40:31.079  1949  1949 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 19:40:31.099  7633  7633 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:31.099  7633  7633 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:31.109  1018  1331 I ActivityManager: Killing 7116:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-13 19:40:31.109   257   542 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-13 19:40:31.109   257   542 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 19:40:31.109  7560  7560 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-13 19:40:31.119  7560  7560 D SLinkSource: Samsung link source created
,09-13 19:40:31.119  7491  7548 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 19:40:31.149  7161  7161 D AbsListView: Get MotionRecognitionManager
,09-13 19:40:31.149  1018  1483 D MotionRecognitionService:  ssp status : false
,09-13 19:40:31.159  7161  7161 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 267.54901
,09-13 19:40:31.159  7515  7515 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(225): No need to run daily hygiene.
09-13 19:40:31.159  7633  7633 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-13 19:40:31.169  7633  7633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-13 19:40:31.169  1018  1512 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-13 19:40:31.169  1018  1512 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.169  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.169  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:31.169  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-13 19:40:31.179  1018  1513 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 19:40:31.179  1018  1513 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver}
09-13 19:40:31.179  1018  1513 W BroadcastQueue: android.os.TransactionTooLargeException
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-13 19:40:31.179  1018  1513 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-13 19:40:31.179  1018  1513 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-13 19:40:31.179  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.179  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.179  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.179  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:31.189  7633  7633 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-13 19:40:31.199  7515  7515 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,09-13 19:40:31.199  7663  7663 E Zygote  : MountEmulatedStorage()
09-13 19:40:31.199  7663  7663 I libpersona: KNOX_SDCARD checking this for 10098
09-13 19:40:31.199  7663  7663 E Zygote  : v2
09-13 19:40:31.199  7663  7663 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:31.199  7663  7663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:31.199  7663  7663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:31.199  7663  7663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:31.209  7515  7515 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
09-13 19:40:31.209  1018  1513 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7663 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-13 19:40:31.219  7560  7660 D ContactProvider: getAllContactInfoList Start
,09-13 19:40:31.239   318   318 I art     : Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 647us total 29.670ms
09-13 19:40:31.239  1018  1042 W libprocessgroup: failed to open /acct/uid_10098/pid_7116/cgroup.procs: No such file or directory
,09-13 19:40:31.249  1018  1136 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-13 19:40:31.249  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.249  1018  1512 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 19:40:31.249  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.249  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.249  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 19:40:31.249   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 17.852ms
,09-13 19:40:31.259  7663  7663 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:31.259  7663  7663 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:31.269   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 17.924ms
,09-13 19:40:31.279  7560  7660 D ContactProvider: getAllContactInfoList End
,09-13 19:40:31.279  7560  7660 I syncContacts: thread: 1423, sync time = 73
,09-13 19:40:31.289  1018  3388 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 19:40:31.299  7515  7515 I Finsky  : [1] com.google.android.finsky.utils.bp.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,09-13 19:40:31.299  1018  1512 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 19:40:31.299  7560  7560 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-13 19:40:31.319  7663  7663 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
09-13 19:40:31.319  7663  7663 D PackageIntentReceiver: Not GearManger package! 
,09-13 19:40:31.329  1018  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-13 19:40:31.329  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:31.329  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.329  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:31.329  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:31.329  7633  7662 E FilterInstaller: installFilters
,09-13 19:40:31.339  7682  7682 E Zygote  : MountEmulatedStorage()
09-13 19:40:31.339  7682  7682 E Zygote  : v2
09-13 19:40:31.339  7682  7682 I libpersona: KNOX_SDCARD checking this for 1000
09-13 19:40:31.339  7682  7682 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:31.339  7682  7682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:31.349  7682  7682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 19:40:31.349  7682  7682 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:31.349  1018  1539 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7682 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 19:40:31.349  1018  1539 I ActivityManager: Killing 7129:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #21
09-13 19:40:31.349  7161  7161 D Mms/BubbleViewCache: fillCache bubble = 1
,09-13 19:40:31.359  1018  1498 I ActivityManager: Killing 7178:com.android.keychain/1000 (adj 15): empty #21
,09-13 19:40:31.369  1877  1877 D SamsungIME: Dismiss ExpandCandiate
,09-13 19:40:31.379  1018  1331 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 19:40:31.379  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.379  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.379  1018  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.379  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 19:40:31.399  7682  7682 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:31.399  7682  7682 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:31.409  1018  1266 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 19:40:31.409  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.409  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.409  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.409  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 19:40:31.419  7515  7515 I Finsky  : [1] com.google.android.finsky.receivers.j.a(1265): Installer kick - no action, not running yet
,09-13 19:40:31.429  7633  7662 E FilterInstaller: There is no requred permission
,09-13 19:40:31.429  1018  1030 I ActivityManager: Killing 7273:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-13 19:40:31.469  7291  7291 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 19:40:31.489  1018  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
09-13 19:40:31.489  7515  7697 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
,09-13 19:40:31.489  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.489  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.489  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.489  7515  7515 I Finsky  : [1] com.google.android.finsky.l.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,09-13 19:40:31.489  7515  7515 I Finsky  : [1] com.google.android.finsky.l.j.run(214): Finished loading 1 libraries.
,09-13 19:40:31.499  7682  7699 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
,09-13 19:40:31.499  1018  1030 I ActivityManager: Killing 6932:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-13 19:40:31.509  7682  7699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,09-13 19:40:31.509  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:31.509  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.509  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:31.509  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.519  1018  1483 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-13 19:40:31.519  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.529  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.529  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 19:40:31.529  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-13 19:40:31.529  1018  1539 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:31.539  7682  7682 D AcmsService: Enter Oncreate
,09-13 19:40:31.539  7682  7682 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,09-13 19:40:31.539  7682  7682 D AcmsService: creating AcmsCore
,09-13 19:40:31.539  7682  7682 D AcmsCore: AcmsCore.getAcmsCore() - Enter
,09-13 19:40:31.539  7682  7682 D AcmsCore: AcmsCore
,09-13 19:40:31.539  7682  7682 D AcmsCore: init
,09-13 19:40:31.549  7682  7682 D AcmsCore: Looper handler is not null
,09-13 19:40:31.549  7682  7682 D AcmsCore: Post to AcmsCoreHandler
,09-13 19:40:31.549  7682  7682 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:31.549  7682  7682 D AcmsServiceMonitor: Incrementing - Counter value: 1
,09-13 19:40:31.549  7682  7682 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,09-13 19:40:31.549  7682  7682 D AcmsService: onStartCommand
09-13 19:40:31.549  7682  7682 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-13 19:40:31.549  7682  7682 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-13 19:40:31.549  7682  7682 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-13 19:40:31.549  7682  7682 D AcmsService: Incremented Counter Value : onStartCommand
,09-13 19:40:31.549  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.549  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:31.549  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.559  1018  1331 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 19:40:31.559  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.559  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.559  1018  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.559  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-13 19:40:31.559  7682  7703 D AcmsCertificateMngr: AcmsCertificateMngr
,09-13 19:40:31.559  7682  7703 D AcmsRevocationMngr: AcmsRevocationMngr
,09-13 19:40:31.559  1949  1949 D WearableService: callingUid 10011, callindPid: 1949
,09-13 19:40:31.579  1018  1498 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:31.579  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.579  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.579  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:31.579  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.589  1018  1512 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 19:40:31.589  1018  1512 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.589  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.589  1018  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.589  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-13 19:40:31.589  7291  7610 D jxcore_app_log: JniHelper::setJavaVM(0xb8eb72b0), pthread_self() = -1186677984
,09-13 19:40:31.589  1018  1481 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-13 19:40:31.589  7515  7515 I Finsky  : [1] com.google.android.finsky.c.l.a(253): result=false type=4
,09-13 19:40:31.589  1018  1031 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 19:40:31.589  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.589  7682  7682 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,09-13 19:40:31.589  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.589  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:31.589  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 19:40:31.599  7291  7610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 19:40:31.599  7291  7610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 19:40:31.599  7291  7610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 19:40:31.599  7291  7610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 19:40:31.599  7291  7610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 19:40:31.599  7291  7610 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17a201b added. We now have 1 listener(s)
,09-13 19:40:31.599  7291  7610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-13 19:40:31.609  7291  7610 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-13 19:40:31.609  7291  7610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 19:40:31.609  7291  7610 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 19:40:31.609  7515  7515 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 19:40:31.609  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 19:40:31.619  7291  7610 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1faef6 added. We now have 1 listener(s)
,09-13 19:40:31.619  7291  7610 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 19:40:31.619  7428  7575 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 19:40:31.619  7428  7575 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 19:40:31.629  7291  7610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 19:40:31.629  7291  7610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 19:40:31.629  7291  7610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 19:40:31.629  7291  7610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-13 19:40:31.629  7291  7610 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 19:40:31.629  1877  1877 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 19:40:31.639  7491  7548 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 512 ms] updated apps [took 511 ms] 
,09-13 19:40:31.649  1018  1050 I PowerManagerService: [PWL] Off : 30s ago
09-13 19:40:31.649  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-13 19:40:31.649  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-13 19:40:31.649  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.auth.account.be.accountstate.LoginAccountsChangedIntentService' (uid=10011, pid=4777, ws=null) (elapsedTime=43130)
09-13 19:40:31.649  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=4777, ws=WorkSource{10011 com.google.android.gms, 10052 com.google.android.googlequicksearchbox}) (elapsedTime=1229)
,09-13 19:40:31.659  7291  7610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 19:40:31.659  7291  7610 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-13 19:40:31.669  7682  7682 D AcmsService: Inside handle Intent
09-13 19:40:31.669  7682  7682 D AcmsService: App added - package name: com.test.thalitest
09-13 19:40:31.669  7682  7682 D AcmsCore: Post to AcmsCoreHandler
09-13 19:40:31.669  7682  7682 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:31.669  7682  7682 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-13 19:40:31.669  7682  7682 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-13 19:40:31.669  7682  7682 D AcmsService: Decremented Counter Value : handleStartIntent
09-13 19:40:31.669  7682  7682 D AcmsServiceMonitor: Decrementing - Counter value: 2
,09-13 19:40:31.669  7291  7610 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 19:40:31.679  7291  7610 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 19:40:31.679  7291  7610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 19:40:31.679  7291  7610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 19:40:31.679  7291  7610 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 19:40:31.679  7291  7610 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 19:40:31.679  7291  7610 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 19:40:31.679  7291  7610 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 19:40:31.679  7291  7610 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 19:40:31.679  7291  7610 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 19:40:31.679  7291  7610 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 19:40:31.679  7291  7610 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 19:40:31.679  7291  7291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:40:31.679  7291  7291 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 19:40:31.689  7515  7515 I Finsky  : [1] com.google.android.finsky.services.bd.a(1075): Restore complete with 0 success and 0 failed.
,09-13 19:40:31.689  1018  1483 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-13 19:40:31.689  1877  1877 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 19:40:31.709  1877  1877 I SamsungIME: KeybaordView init() : load resources
,09-13 19:40:31.719  7291  7291 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 19:40:31.719  7413  7413 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-13 19:40:31.719  7413  7413 I PCWCLIENTTRACE_PushUtil: sales region : global
09-13 19:40:31.719  7413  7413 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 19:40:31.719  7413  7413 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REPLACED
09-13 19:40:31.719  7413  7413 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_PACKAGE_REPLACED_START
,09-13 19:40:31.719  1018  1030 I splitIntent: Split this intent : android.intent.action.PACKAGE_REPLACED, mSplitNum[0]=5, mSplitNum[1]=9, mSplitNum[2]=13, mBgSplitQueueNum=3 divideNum= 4 r.nextReceiver= 1 receivers.size=17
09-13 19:40:31.719  1018  1030 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REPLACED !! Enqueue -> schedule it!!
,09-13 19:40:31.729  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-13 19:40:31.729  7447  7447 D Compatibility: onReceive() it will make start service
,09-13 19:40:31.729  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.729  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.729  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:31.729  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:31.739  4777  4914 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-13 19:40:31.739  7711  7711 E Zygote  : MountEmulatedStorage()
09-13 19:40:31.739  7711  7711 E Zygote  : v2
,09-13 19:40:31.739  7711  7711 I libpersona: KNOX_SDCARD checking this for 10110
09-13 19:40:31.739  7711  7711 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:31.739  7711  7711 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 19:40:31.749  1018  1043 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=7711 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 19:40:31.749  1018  1498 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-13 19:40:31.749  1018  1498 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0,
,09-13 19:40:31.749  1018  1498 W ActivityManager: userId = 0, bbcId = -10000,
09-13 19:40:31.749  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:31.749  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-13 19:40:31.749  7711  7711 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 19:40:31.759  7711  7711 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 19:40:31.769  7447  7720 D Compatibility: onHandleIntent()
,09-13 19:40:31.769  7447  7720 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REPLACED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,09-13 19:40:31.779  7515  7515 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-13 19:40:31.779  7515  7515 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-13 19:40:31.789  7447  7720 D Compatibility: found: 2
09-13 19:40:31.789  7447  7720 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-13 19:40:31.789  7447  7720 D Compatibility: skipping ResolveInfo{ba7c3c3 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-13 19:40:31.789  7447  7720 D Compatibility: considering ResolveInfo{3fe5f440 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-13 19:40:31.789  7447  7720 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 19:40:31.789  7711  7711 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:31.789  7711  7711 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:31.809  7428  7575 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 19:40:31.819  1877  1877 I SamsungIME: getCurrentKeyboard
09-13 19:40:31.819  1877  1877 I SamsungIME: getTextKeyboard
,09-13 19:40:31.819  7447  7720 D Compatibility: enabling receiver ResolveInfo{2ed4af79 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 19:40:31.829  1018  1096 V AlarmManager: waitForAlarm result :4
,09-13 19:40:31.839  7447  7720 D Compatibility: enabling receiver ResolveInfo{2e9bc4be com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 19:40:31.839  7291  7306 I art     : Background partial concurrent mark sweep GC freed 9603(623KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/14MB, paused 7.928ms total 51.261ms
,09-13 19:40:31.839  7447  7720 D Compatibility: enabling receiver ResolveInfo{3738d91f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 19:40:31.839  7447  7720 D Compatibility: enabling receiver ResolveInfo{2256146c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 19:40:31.849  7447  7720 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-13 19:40:31.859  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:31.859  7515  7515 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-13 19:40:31.859  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.859  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.859  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:31.859  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.869  4777  7032 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-13 19:40:31.869  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:31.879  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.879  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.879  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.879  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.889  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:31.889  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.889  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.889  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.889  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.889  1877  1877 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-13 19:40:31.899  7376  7376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:168 android.app.ActivityThread.handleReceiver:3125 
,09-13 19:40:31.899  4777  4777 D AsyncTaskServiceImpl: Submit a task: nzm
,09-13 19:40:31.899  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-13 19:40:31.899  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.909  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.909  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 19:40:31.909  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-13 19:40:31.919  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:31.919  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.919  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.919  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:31.919  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.929  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:31.939  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:31.939  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:31.939  4777  7032 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-13 19:40:31.939  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.939  7428  7575 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 19:40:31.939  7428  7575 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11e1a551: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-13 19:40:31.939  7428  7575 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 19:40:31.949  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:31.949  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 19:40:31.949  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:31.949  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:31.949  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:31.949  1018  1498 I ActivityManager: Killing 7161:com.android.mms/u0a41 (adj 15): empty #21
,09-13 19:40:31.949  1018  3375 D SSRM:n  : SIOP:: AP = 450
,09-13 19:40:31.969  4777  4944 D nzm     : Processing package: com.test.thalitest
,09-13 19:40:31.969  1018  1498 I ActivityManager: Killing 7310:com.wsomacp/u0a23 (adj 15): empty #21
,09-13 19:40:31.979  1949  1949 E NetworkScheduler.SR: Invalid parameter app
,09-13 19:40:31.979  1949  1949 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-13 19:40:31.999  4777  4944 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-13 19:40:31.999  4777  4944 D nzm     : Found info for package com.test.thalitest in db.
,09-13 19:40:32.029  1018  1266 D CountryDetector: No listener is left
,09-13 19:40:32.069  1018  1266 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:32.069  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.gmsproc.GcmInGmsTaskService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.079  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:32.079  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:32.079  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.089  4777  7732 I GCM-GMS : Registering GMS 745476177629
,09-13 19:40:32.119  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:32.119  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.gmsproc.GcmInGmsTaskService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.119  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:32.119  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:32.119  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.129  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:32.129  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:32.129  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:32.129  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.139  1018  1512 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-13 19:40:32.139  1018  1512 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.139  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:32.139  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 19:40:32.139  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-13 19:40:32.149  1018  1331 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:32.149  1018  1331 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.149  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:32.149  1018  1331 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:32.149  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.219  1949  7735 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,09-13 19:40:32.249  1018  1136 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 19:40:32.299  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-13 19:40:32.299  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-13 19:40:32.309  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:32.309  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:32.309  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.319  1949  1949 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 19:40:32.319  1949  1949 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 19:40:32.349  1018  1539 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:32.349  1018  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.349  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:32.349  1018  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:32.349  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.359  1018  1512 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:32.359  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:32.359  1018  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:32.359  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.369  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 19:40:32.369  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.369  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:32.369  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:32.369  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.389  4777  4914 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-13 19:40:32.409  1018  1266 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-13 19:40:32.409  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.409  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:32.409  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:32.409  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.409  1949  7735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 19:40:32.419   278  1013 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 19:40:32.419   278  1013 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 19:40:32.419  1949  7735 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 19:40:32.429  1949  7735 I qtaguid : Tagging socket 63 with tag 1000040700000000{268436487,0} for uid -1, pid: 1949, getuid(): 10011
,09-13 19:40:32.439  1949  3044 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 19:40:32.439  1949  3044 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1949, getuid(): 10011
,09-13 19:40:32.459   257   542 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 19:40:32.459   257   542 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 19:40:32.459  7711  7742 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 19:40:32.469   257   542 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 19:40:32.469   257   542 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 19:40:32.469  7711  7742 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 19:40:32.469  1949  7735 I qtaguid : Tagging socket 66 with tag 1000040700000000{268436487,0} for uid -1, pid: 1949, getuid(): 10011
,09-13 19:40:32.489   257   542 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 19:40:32.489   257   542 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 19:40:32.489  7711  7743 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 19:40:32.489   257   542 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 19:40:32.489   257   542 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 19:40:32.489  7711  7743 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 19:40:32.499  7711  7711 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 19:40:32.499  7711  7711 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 19:40:32.499  7711  7711 I GAv4    :   adb logcat -s GAv4
,09-13 19:40:32.549  7711  7711 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:40:32.549  1018  1481 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 19:40:32.559  7711  7711 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:40:32.569  7711  7745 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 19:40:32.639  4777  4914 I Icing   : Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,09-13 19:40:32.719  1949  7735 I qtaguid : Untagging socket 63
,09-13 19:40:32.719  4777  7732 I GCM-GMS : Got GMS registration
,09-13 19:40:32.799  7291  7709 W jxcore-log: Initializing JXcore engine
09-13 19:40:32.799  7291  7709 W jxcore-log: JXcore engine is ready
,09-13 19:40:32.799  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:32.799  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.809  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:32.809  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:32.809  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:32.819  1018  1136 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-13 19:40:32.819  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 19:40:32.859  2023  2023 E audit   : type=1400 msg=audit(1473788432.859:205): avc:  denied  { ioctl } for  pid=7709 comm="Thread-1375" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 19:40:32.859  2023  2023 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:32.859  2023  2023 E audit   : type=1300 msg=audit(1473788432.859:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f4548f8 items=0 ppid=318 ppcomm=main pid=7709 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1375" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-13 19:40:32.859  2023  2023 E audit   : type=1320 msg=audit(1473788432.859:205): 
,09-13 19:40:32.869  7291  7709 W jxcore-log: Starting JXcore engine
,09-13 19:40:32.879  1949  1949 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 19:40:32.919  7682  7703 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-13 19:40:32.939  7682  7703 I AcmsKeyStoreHelper: Key Store exist
09-13 19:40:32.939  7682  7703 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-13 19:40:32.979  7711  7711 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-13 19:40:32.979  4777  4914 I Icing   : Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
,09-13 19:40:32.989  1018  1498 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 19:40:32.989  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:32.989  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:32.989  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-13 19:40:33.009  7291  7709 W jxcore-log: Platform android
09-13 19:40:33.009  7291  7709 W jxcore-log: 
,09-13 19:40:33.009  7291  7709 W jxcore-log: Process ARCH arm
09-13 19:40:33.009  7291  7709 W jxcore-log: 
,09-13 19:40:33.019  7711  7711 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4418-4420)
,09-13 19:40:33.019  7711  7711 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 19:40:33.029  7711  7711 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10c65232}
,09-13 19:40:33.029  7711  7711 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 19:40:33.039  7711  7711 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 19:40:33.039  7682  7703 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-13 19:40:33.039  7682  7703 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-13 19:40:33.039  7682  7703 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-13 19:40:33.039  7682  7703 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:33.039  7682  7703 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-13 19:40:33.039  7682  7703 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-13 19:40:33.049  7682  7703 D AcmsCore: This is NOT a valid MirrorLink app
09-13 19:40:33.049  7682  7703 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-13 19:40:33.049  7682  7703 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 19:40:33.049  7682  7703 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-13 19:40:33.049  7682  7703 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-13 19:40:33.049  7682  7682 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 19:40:33.049  7682  7682 D AcmsService: Enter onDestroy
09-13 19:40:33.049  7682  7682 I AcmsService: cleanUp(): inside service clean up
09-13 19:40:33.049  7682  7682 D AcmsCore: AcmsCore: inside DeInit
09-13 19:40:33.049  7682  7682 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-13 19:40:33.049  7682  7682 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-13 19:40:33.049  7682  7682 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-13 19:40:33.049  7682  7682 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-13 19:40:33.049  7682  7682 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-13 19:40:33.049  7682  7682 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 19:40:33.049  7682  7682 D AcmsService: killing acms process
09-13 19:40:33.049  7682  7682 I Process : Sending signal. PID: 7682 SIG: 9
,09-13 19:40:33.059  7711  7711 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 19:40:33.059  7711  7711 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 19:40:33.069  7711  7711 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 19:40:33.079  7711  7711 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 19:40:33.079  7711  7711 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 19:40:33.079  7711  7711 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 19:40:33.079  7711  7711 I Adreno-EGL: Local Branch: 
09-13 19:40:33.079  7711  7711 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 19:40:33.079  7711  7711 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 19:40:33.079  7711  7711 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 19:40:33.139  1018  1512 I ActivityManager: Process ACMS.Process (pid 7682)(adj 0) has died(83,707)
,09-13 19:40:33.149  7711  7711 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 19:40:33.159  7711  7711 I NSApplication: Starting up...
,09-13 19:40:33.169  1018  1030 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 19:40:33.169  7711  7776 W cr.media: Requires BLUETOOTH permission
,09-13 19:40:33.169  1018  1480 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 19:40:33.169  1018  1512 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-13 19:40:33.179  1018  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.179  1018  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.179  1018  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.179  1018  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:33.189  7781  7781 E Zygote  : MountEmulatedStorage(),
09-13 19:40:33.189  7781  7781 E Zygote  : v2
09-13 19:40:33.189  7781  7781 I libpersona: KNOX_SDCARD checking this for 10121
09-13 19:40:33.189  7781  7781 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:33.189  7781  7781 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-13 19:40:33.189  1018  1512 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7781 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-13 19:40:33.189  1018  1512 I ActivityManager: Killing 7360:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-13 19:40:33.199  7781  7781 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:33.199  7781  7781 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:33.219  7781  7781 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:33.229  7781  7781 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:33.239  7781  7781 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 19:40:33.239  7781  7781 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 19:40:33.239  7781  7781 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 19:40:33.249  7781  7781 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.PACKAGE_REPLACED
,09-13 19:40:33.259  6981  6981 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-13 19:40:33.259  6981  6981 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REPLACED / mCurIndex :-10
,09-13 19:40:33.269  6981  6981 I TapandpayWidget:Utils: Clear T&P info.
,09-13 19:40:33.269  6981  6981 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-13 19:40:33.269  1018  1498 I ActivityManager: Killing 7328:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-13 19:40:33.279  2609  2609 D daemonapp: [MSC_Daemon]>>> AWDCDS:28 [0:0] AWD CD Act : androidintentactionPACKAGE_REPLACED
,09-13 19:40:33.289  1018  1483 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REPLACED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-13 19:40:33.289  7291  7709 I jxcore-log: JXcore Cordova bridge is ready!
09-13 19:40:33.289  7291  7709 I jxcore-log: 
,09-13 19:40:33.289  7291  7709 W jxcore-log: JXcore engine is started
,09-13 19:40:33.289  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:33.289  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:33.289  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:33.289  7291  7610 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 19:40:33.299  7291  7291 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 19:40:33.299  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:33.299  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:33.299  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:33.309  7291  7709 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
09-13 19:40:33.309  7291  7709 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,09-13 19:40:33.309  1018  1513 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 19:40:33.309  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-13 19:40:33.309  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:33.309  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:33.309  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:33.319  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
,09-13 19:40:33.319  1018  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 19:40:33.319  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 19:40:33.319  1949  7796 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,09-13 19:40:33.319  7291  7291 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
09-13 19:40:33.319  7291  7291 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,09-13 19:40:33.319  1018  1031 D FocusedStackFrame: Set to : 0
09-13 19:40:33.329  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 19:40:33.329  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-13 19:40:33.329  1018  1031 D InputDispatcher: Focused application set to: xxxx
09-13 19:40:33.329  1018  1031 D InputDispatcher: Focus left window: 7291
09-13 19:40:33.329  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 19:40:33.329  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 19:40:33.339  1018  1031 I ActivityManager: Killing 7344:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-13 19:40:33.339  7291  7610 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,09-13 19:40:33.339  7291  7291 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 19:40:33.339  7291  7291 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
09-13 19:40:33.339  7291  7291 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 19:40:33.339  7291  7291 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 19:40:33.339  7291  7291 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 19:40:33.339  7291  7291 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 19:40:33.339  7291  7291 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17a201b removed from the list
09-13 19:40:33.339  7291  7291 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 19:40:33.339  7291  7291 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1faef6 removed from the list
09-13 19:40:33.339  7291  7291 D io.jxcore.node.ConnectivityMonitor: stop
09-13 19:40:33.339  7291  7291 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,09-13 19:40:33.349  1018  1513 W ActivityManager: mDVFSHelper.acquire()
,09-13 19:40:33.349  1018  1513 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-13 19:40:33.359  7291  7291 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 19:40:33.379   258   446 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-13 19:40:33.379  1499  1499 D Launcher: onRestart, Launcher: 1072034880
,09-13 19:40:33.379  1499  1499 D Launcher: onStart, Launcher: 1072034880
09-13 19:40:33.379  1499  1499 D Launcher.HomeView: onStart
,09-13 19:40:33.379   258   598 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-13 19:40:33.379  1499  1499 D Launcher: onResume, Launcher: 1072034880
,09-13 19:40:33.379  1018  1331 D SettingsProvider: name = kids_home_mode
09-13 19:40:33.379  1018  1331 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 19:40:33.379  1018  1331 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 19:40:33.379  1018  1331 D SettingsProvider: selectionArgs: false
09-13 19:40:33.379  1018  1331 D SettingsProvider: selectionArgs: 10006
09-13 19:40:33.379  1018  1331 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 19:40:33.379  1018  1331 D SettingsProvider: ret = -1
,09-13 19:40:33.379  1499  1499 D Launcher.HomeView: onResume
,09-13 19:40:33.389  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-13 19:40:33.389  1499  1499 D MenuAppsGridFragment: onResume
,09-13 19:40:33.399  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.399  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.399  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,09-13 19:40:33.399  4777  4914 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms,
09-13 19:40:33.399  4777  4914 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
09-13 19:40:33.399  1018  1539 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
09-13 19:40:33.399  1499  1499 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
09-13 19:40:33.399  1018  1539 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
09-13 19:40:33.399  1499  1499 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
09-13 19:40:33.399  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.399  1018  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.399  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,09-13 19:40:33.409  7560  7560 D GalleryCacheReady: Receive : home resume
,09-13 19:40:33.409  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.409  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.409  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,09-13 19:40:33.409  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.409  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
09-13 19:40:33.409  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.409  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
09-13 19:40:33.419  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.419  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.419  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:33.419  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:33.429  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7800 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,09-13 19:40:33.439  7800  7800 E Zygote  : MountEmulatedStorage(),
09-13 19:40:33.439  7800  7800 E Zygote  : v2
09-13 19:40:33.439  7800  7800 I libpersona: KNOX_SDCARD checking this for 10089,
09-13 19:40:33.439  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.439  7800  7800 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:33.439  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-13 19:40:33.439  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
09-13 19:40:33.439  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
09-13 19:40:33.439  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.439  7800  7800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:33.439  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.439  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.439  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:33.449  7800  7800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 19:40:33.449  7800  7800 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-13 19:40:33.469  7815  7815 E Zygote  : MountEmulatedStorage()
09-13 19:40:33.469  7815  7815 I libpersona: KNOX_SDCARD checking this for 10139
09-13 19:40:33.469  7815  7815 E Zygote  : v2
09-13 19:40:33.469  7815  7815 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:33.469  7815  7815 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:33.479  7815  7815 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:33.479  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7815 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
09-13 19:40:33.479  7815  7815 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:33.479  7800  7800 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:33.479  7800  7800 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:33.489  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.489  1018  1498 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
09-13 19:40:33.489  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.489  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,09-13 19:40:33.499  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.499  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.499  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.499  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:33.509  7815  7815 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:33.509  7815  7815 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:33.519  7830  7830 E Zygote  : MountEmulatedStorage(),
09-13 19:40:33.519  7830  7830 E Zygote  : v2
09-13 19:40:33.519  7830  7830 I libpersona: KNOX_SDCARD checking this for 10041
09-13 19:40:33.519  7830  7830 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:33.519  1018  1498 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=7830 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-13 19:40:33.529  7830  7830 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:33.529  7830  7830 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:33.529  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
09-13 19:40:33.529  1018  1512 D ActivityManager: handle home activity for 0
09-13 19:40:33.529  1018  1512 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-13 19:40:33.529  1018  1512 D KnoxTimeoutHandler: post home show event for user 0
09-13 19:40:33.529  1018  1512 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 19:40:33.529  1018  1512 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 19:40:33.529  1018  1512 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-13 19:40:33.529  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-13 19:40:33.529  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-13 19:40:33.529  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-13 19:40:33.529  7830  7830 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 19:40:33.549  1499  1499 D Launcher.HomeView: onPause,
09-13 19:40:33.549  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-13 19:40:33.559  7830  7830 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:33.559  7830  7830 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:33.569  7800  7800 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:33.569  7800  7800 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-13 19:40:33.569  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.569  1018  1483 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1499, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
09-13 19:40:33.569  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.569  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,09-13 19:40:33.579   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,09-13 19:40:33.579  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-13 19:40:33.579  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.579  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.579  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,09-13 19:40:33.579  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 19:40:33.579  7815  7815 V TaskCloserActivity: TaskCloserActivity enter()
,09-13 19:40:33.589  2557  2557 D Recents_RecreateReceiver: onReceive by home
,09-13 19:40:33.589  1018  1513 D InputDispatcher: Focus entered window: 1499
,09-13 19:40:33.599  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 19:40:33.599  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 19:40:33.599  1499  1499 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 19:40:33.599  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.599  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.599  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
09-13 19:40:33.599  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,09-13 19:40:33.599  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.599  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.599  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.599  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:33.599  7815  7815 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,09-13 19:40:33.609  1499  1499 D Launcher.HomeView: onStop
09-13 19:40:33.609  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{14e1ff token=android.os.BinderProxy@2ab74775 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,09-13 19:40:33.609  7830  7830 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-13 19:40:33.609  1018  1481 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-13 19:40:33.609  7830  7830 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:33.609  7830  7830 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 19:40:33.609  7830  7830 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 19:40:33.609  7830  7830 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.,
,09-13 19:40:33.619  1018  7847 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
09-13 19:40:33.619   296   296 E SMD     : DCD OFF
09-13 19:40:33.619  7291  7291 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-13 19:40:33.619  1877  1877 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-13 19:40:33.619  7848  7848 E Zygote  : MountEmulatedStorage()
09-13 19:40:33.619  7848  7848 I libpersona: KNOX_SDCARD checking this for 10084
09-13 19:40:33.619  7848  7848 E Zygote  : v2
09-13 19:40:33.619  7848  7848 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:33.619  7848  7848 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:33.629  1174  1174 D PanelView: There is/are notification(s) 
09-13 19:40:33.629  7848  7848 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 19:40:33.629  7798  7798 D AndroidRuntime: 
09-13 19:40:33.629  7798  7798 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 19:40:33.629  7848  7848 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-13 19:40:33.629  7798  7798 D AndroidRuntime: CheckJNI is OFF
09-13 19:40:33.629  1018  1030 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7848 uid=10084 gids={50084, 9997} abi=armeabi-v7a
09-13 19:40:33.629  7798  7798 D AndroidRuntime: readGMSProperty: start
09-13 19:40:33.629  7798  7798 D AndroidRuntime: readGMSProperty: already setted!!
09-13 19:40:33.629  7798  7798 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 19:40:33.629  7798  7798 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 19:40:33.629  7798  7798 D AndroidRuntime: readGMSProperty: end
09-13 19:40:33.629  7798  7798 D AndroidRuntime: addProductProperty: start
,09-13 19:40:33.639  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.639  1018  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.639  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,09-13 19:40:33.639  1018  1539 I ActivityManager: Killing 7428:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-13 19:40:33.649  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-13 19:40:33.659  1499  1499 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ab74775 time:95066
,09-13 19:40:33.669  7830  7830 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,09-13 19:40:33.669  7848  7848 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:33.669  7848  7848 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:33.679  1018  1539 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.679  1018  1539 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
09-13 19:40:33.679  1018  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:33.679  1018  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,09-13 19:40:33.689  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.689  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.689  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:33.689  1018  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:33.699  7848  7848 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 19:40:33.699  7871  7871 E Zygote  : MountEmulatedStorage()
09-13 19:40:33.699  7871  7871 E Zygote  : v2
09-13 19:40:33.699  7871  7871 I libpersona: KNOX_SDCARD checking this for 10135
09-13 19:40:33.699  7871  7871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:33.699  7871  7871 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:33.699  1018  1539 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7871 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
09-13 19:40:33.709  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{254d77dd u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:95110
09-13 19:40:33.699  1018  1539 I ActivityManager: Killing 7633:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
09-13 19:40:33.709  1018  1048 W ActivityManager: mDVFSHelper.release()
,09-13 19:40:33.709  7871  7871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 19:40:33.709  7871  7871 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:33.719  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 19:40:33.729  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:33.729  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 19:40:33.729  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 19:40:33.729  1018  1539 I ActivityManager: Killing 7663:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-13 19:40:33.739  7871  7871 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 19:40:33.739  7871  7871 D ActivityThread: Added TimaKeyStore provider
,09-13 19:40:33.749  1018  1480 D PersonaManager: isKioskContainerExistOnDevice
,09-13 19:40:33.759  7871  7871 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-13 19:40:33.759  7871  7871 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 19:40:33.759  7871  7871 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-13 19:40:33.759  7871  7871 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
09-13 19:40:33.759  7871  7871 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 19:40:33.789  7798  7798 E AffinityControl: AffinityControl: registerfunction enter
,09-13 19:40:33.799  1018  1031 I ActivityManager: Killing 7148:com.samsung.helphub/1000 (adj 15): empty #21
,09-13 19:40:33.809  7798  7798 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 19:40:33.819  1018  1030 D PackageManager: START PACKAGE DELETE: observer{244996476}
09-13 19:40:33.819  1018  1030 D PackageManager: pkg{<packageName>}
09-13 19:40:33.819  1018  1030 D PackageManager: user{0}
09-13 19:40:33.819  1018  1030 D PackageManager: caller{2000}
09-13 19:40:33.819  1018  1030 D PackageManager: flags{2}
,09-13 19:40:33.819  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-13 19:40:33.819  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 19:40:33.819  1018  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-13 19:40:33.819  1018  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 19:40:33.819  1018  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-13 19:40:33.829  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-13 19:40:33.829  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-13 19:40:33.829  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 19:40:33.829  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 19:40:33.829  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 19:40:33.829  1018  1058 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-13 19:40:33.829  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-13 19:40:33.829  1018  1043 I ActivityManager: Killing 7291:com.test.thalitest/u0a171 (adj 15): stop com.test.thalitest cause uninstall pkg
,09-13 19:40:33.839  7830  7830 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 122.723ms
,09-13 19:40:33.899  7830  7889 D Mms/ArtClassLoader: init before art
,09-13 19:40:33.909  7830  7830 D Mms/TelephonyPermission: start operation mode monitor
,09-13 19:40:33.909  1018  1058 W PackageSettings: Skipping PackageSetting{1c5cd18d com.example.hello/10168} due to missing metadata
,09-13 19:40:33.949  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-13 19:40:33.959  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-13 19:40:33.979  7830  7830 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 19:40:33.989  2659  2659 I art     : Explicit concurrent mark sweep GC freed 2497(121KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 892us total 28.682ms
,09-13 19:40:34.019  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,09-13 19:40:34.019  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-13 19:40:34.019  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-13 19:40:34.019  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 19:40:34.019  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-13 19:40:34.019  1018  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 19:40:34.029  1877  1877 E SamsungIME: mOCRHelper is null
,09-13 19:40:34.039  4777  4777 I art     : Explicit concurrent mark sweep GC freed 34978(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 12MB/20MB, paused 1.270ms total 82.270ms
,09-13 19:40:34.049  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,09-13 19:40:34.049  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-13 19:40:34.069  1018  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-13 19:40:34.069  1018  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 19:40:34.069  1018  1123 V NetworkStats: performPollLocked(flags=0x3)
,09-13 19:40:34.069  1018  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 19:40:34.069  1018  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 19:40:34.099  1018  1123 V NetworkStats: performPollLocked() took 32ms
,09-13 19:40:34.099  1018  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 19:40:34.109  1454  1454 D PersonaManager: isKioskContainerExistOnDevice
,09-13 19:40:34.119  1454  1454 D RegisteredServicesCache: empty dynamic service
,09-13 19:40:34.139  1454  1454 D RegisteredComponentCache: Collect Tech packages for Knox
,09-13 19:40:34.139  7830  7830 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 19:40:34.139  7830  7830 D Mms/TelephonyPermission: isDefault true
,09-13 19:40:34.139  1454  1454 D PersonaManager: isKioskContainerExistOnDevice
,09-13 19:40:34.139  7830  7830 D Mms/MmsApp: onCreate() com.android.mms
,09-13 19:40:34.169  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 19:40:34.169  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 19:40:34.189  7830  7830 D Mms/MmsApp: [start]    initCountryIso consume time = 520.733229
,09-13 19:40:34.259  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-13 19:40:34.259  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicy: uID is 10171
09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-13 19:40:34.259  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-13 19:40:34.259  1018  1018 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-13 19:40:34.279  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicy: uID is 10171
09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-13 19:40:34.279  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-13 19:40:34.289  1018  1162 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,09-13 19:40:34.289  1018  3375 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-13 19:40:34.329  1018  1058 I art     : Explicit concurrent mark sweep GC freed 58345(3MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 25MB/37MB, paused 6.554ms total 282.057ms
,09-13 19:40:34.329  1018  1480 I art     : WaitForGcToComplete blocked for 282.151ms for cause Explicit
,09-13 19:40:34.329  7830  7889 D Mms/ArtClassLoader: init [DONE] art
,09-13 19:40:34.339  1018  1058 D PackageManager: delete codoeFile: 
,09-13 19:40:34.349  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
09-13 19:40:34.349  1018  1058 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-13 19:40:34.349  1018  1058 D PackageManager: result of delete: 1{244996476}
,09-13 19:40:34.359  7798  7798 D AndroidRuntime: Shutting down VM
,09-13 19:40:34.359  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 19:40:34.359  1018  1058 D PackageManager: userId{-1}
09-13 19:40:34.359  1018  1058 D PackageManager: andCode{true}
,09-13 19:40:34.359  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-13 19:40:34.489  1018  1480 I art     : Explicit concurrent mark sweep GC freed 11186(605KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/37MB, paused 2.467ms total 157.658ms
,09-13 19:40:34.489  1018  1513 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-13 19:40:34.489  1018  1513 D SecContentProvider2: mCursor = null
09-13 19:40:34.489  1949  2160 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 19:40:34.489  1018  1483 D CountryDetector: The first listener is added
09-13 19:40:34.489  1018  1028 I art     : WaitForGcToComplete blocked for 301.768ms for cause HeapTrim
,09-13 19:40:34.499  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
09-13 19:40:34.499  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-13 19:40:34.499  1018  1042 W TextServicesManagerService: no available spell checker services found
,09-13 19:40:34.499  7830  7830 D Mms/MmsApp: [end]    initCountryIso consume time = 312.454375
,09-13 19:40:34.499  7830  7830 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.425469
,09-13 19:40:34.509  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.509  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.509  7830  7830 D Mms/MmsConfig: before partial update
,09-13 19:40:34.519  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.519  7830  7830 D Mms/MmsConfig: Load Resize quality : 80
,09-13 19:40:34.529  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.529  7830  7830 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,09-13 19:40:34.529  7830  7830 D EasySignUpManager_1.0.1: isAuth is false
,09-13 19:40:34.529  7830  7830 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,09-13 19:40:34.529  1472  1489 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7830
,09-13 19:40:34.529  1472  1489 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.127 ms
,09-13 19:40:34.539  7830  7830 D EasySignUpManager_1.0.1: isAuth is false
,09-13 19:40:34.539  7830  7830 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,09-13 19:40:34.539  7830  7830 E CscParser: mps_code.dat does not exist,
09-13 19:40:34.539  7830  7830 E CscParser: customer_path =/system/csc/customer.xml
09-13 19:40:34.539  7830  7830 E CscParser: fileName + /system/csc/customer.xml
,09-13 19:40:34.549  7830  7830 E CscParser: mps_code.dat does not exist
,09-13 19:40:34.549  7830  7830 E CscParser: customer_path =/system/csc/customer.xml
09-13 19:40:34.549  7830  7830 E CscParser: fileName + /system/csc/customer.xml
,09-13 19:40:34.559  7830  7830 D CscParser: getInstance fileName =/system/csc/customer.xml
09-13 19:40:34.559  7830  7830 D Mms/MmsConfig:  enable multiwindow = false
,09-13 19:40:34.569  7798  7798 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-13 19:40:34.569  7830  7830 E Mms/MessageUtils: setCountryDetector : update country detector info 
,09-13 19:40:34.569  7830  7830 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-13 19:40:34.579  7830  7830 D Mms/MmsConfig: [end]    init() consume time = 77.665885
,09-13 19:40:34.579  7830  7830 D Mms/Contact: [start]    init() consume time = 0.933333
,09-13 19:40:34.589  1472  2022 D TP/MmsSmsProvider: query,matched:13, calling pid = 7830
,09-13 19:40:34.589  1472  2022 D TP/MmsSmsProvider: match 13:Elapsed time : 1.207 ms
,09-13 19:40:34.589  7830  7830 D Mms/Contact: [end]    init consume time = 12.715157
,09-13 19:40:34.599  7830  7898 D Mms/DraftCache: [start]    rebuildCache consume time = 6.999843
,09-13 19:40:34.599  7830  7830 D Mms/MethodReflector: getSubId is called
09-13 19:40:34.599  7830  7830 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-13 19:40:34.599  1472  1489 D TP/MmsSmsProvider: query,matched:12, calling pid = 7830
,09-13 19:40:34.609  7830  7830 D Mms/MethodReflector: getTelephonyProperty is called
,09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: auto download without roaming -> true
09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-13 19:40:34.609  7830  7830 D Mms/MethodReflector: getSubId is called
09-13 19:40:34.609  7830  7830 D Mms/MethodReflector: getDefaultSmsSubId is called
09-13 19:40:34.609  7830  7830 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-13 19:40:34.609  7830  7830 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-13 19:40:34.609  7830  7830 D Mms/MethodReflector: getTelephonyProperty is called
,09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: auto download without roaming -> true
09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: auto download during roaming secondary -> false
09-13 19:40:34.609  7830  7830 D Mms/DownloadManager: mAutoDownload ------> true
,09-13 19:40:34.609  1472  1489 D TP/MmsSmsProvider: match 12:Elapsed time : 8.909 ms
09-13 19:40:34.609  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-13 19:40:34.619  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.619  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.619  7830  7898 D Mms/DraftCache: [end]    rebuildCache consume time = 22.971042
,09-13 19:40:34.629  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.629  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 19:40:34.629  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 19:40:34.629  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 19:40:34.629  1018  1030 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,09-13 19:40:34.639  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 19:40:34.639  1018  1030 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,09-13 19:40:34.639  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 19:40:34.639  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 19:40:34.639  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 19:40:34.639  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.639  1018  1030 D BatteryService: turn on LED for fully charged
09-13 19:40:34.639  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
09-13 19:40:34.639  1018  1078 E lights  : write_int failed to open -1
09-13 19:40:34.639  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,09-13 19:40:34.639  1018  1018 I MotionRecognitionService: Plugged
09-13 19:40:34.639  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 19:40:34.649  7830  7830 D ComposerPerformance: 1473788434652 ms / [DONE] Composer constructor,
,09-13 19:40:34.649  7830  7830 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.,
,09-13 19:40:34.649  7830  7830 I Mms/ReservationManager: ReservationManager()
09-13 19:40:34.649  7830  7830 I Mms/ReservationManager: resetAfterConnected()
,09-13 19:40:34.649  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 19:40:34.649  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 19:40:34.649  1472  2022 D TP/MmsSmsProvider: query,matched:7, calling pid = 7830
,09-13 19:40:34.649  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 19:40:34.649  1472  2022 D TP/MmsSmsProvider: match 7:Elapsed time : 2.073 ms
,09-13 19:40:34.649  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 19:40:34.649  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 19:40:34.659  7830  7901 D Mms/Conversation: [start]    init() consume time = 34.831563
,09-13 19:40:34.659  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.659  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-13 19:40:34.659  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 19:40:34.659  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 19:40:34.669  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 19:40:34.669  3172  3172 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 19:40:34.669  3172  3284 D HeadsetStateMachine: Disconnected process message: 10
,09-13 19:40:34.669  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 19:40:34.669  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 19:40:34.669  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-13 19:40:34.669  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-13 19:40:34.669  1018  1136 D SecContentProvider2: uri = 14 selection = getSealedState
09-13 19:40:34.669  1018  1136 D SecContentProvider2: mCursor = null
,09-13 19:40:34.679  7830  7830 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-13 19:40:34.679  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-13 19:40:34.679  1472  1489 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-13 19:40:34.679  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-13 19:40:34.679  1472  1489 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 19:40:34.679  1018  1331 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
09-13 19:40:34.679  1472  1489 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-13 19:40:34.679  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest,
09-13 19:40:34.679  7830  7830 D Mms/MmsApp: [end]    onCreate() consume time = 24.282864
09-13 19:40:34.679  7830  7830 D Mms/UIEventReceiver: ui event
09-13 19:40:34.679  7830  7830 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
09-13 19:40:34.679  1472  1489 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-13 19:40:34.679  7830  7830 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,09-13 19:40:34.689  1018  1331 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:34.689  1018  1331 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:34.689  1018  1331 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
09-13 19:40:34.689  1472  1489 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-13 19:40:34.689  1472  1489 D TP/MmsSmsProvider: need read changed broadcast:false
09-13 19:40:34.689  7830  7901 D Mms/Conversation: [end]    init consume time = 12.04724
09-13 19:40:34.689  7830  7830 D Mms/MethodReflector: getSubId is called
09-13 19:40:34.689  7830  7830 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-13 19:40:34.699  7830  7901 D Mms/MessagingNotification: [start]    init() consume time = 3.345416
,09-13 19:40:34.699  7830  7830 D Mms/MethodReflector: getTelephonyProperty is called
09-13 19:40:34.699  7830  7830 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 19:40:34.699  7830  7830 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 19:40:34.699  7830  7830 D Mms/DownloadManager: auto download without roaming -> true
09-13 19:40:34.699  7830  7830 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 19:40:34.699  7830  7830 D Mms/DownloadManager: mAutoDownload ------> true
,09-13 19:40:34.699  7815  7815 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,09-13 19:40:34.699  1018  1136 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
09-13 19:40:34.699  1018  1136 V ApplicationPolicy: isApplicationStateBlocked userId -1 pkgname com.android.systemui
09-13 19:40:34.699  2912  2912 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 13 19:40:34 GMT+02:00 2016
,09-13 19:40:34.699  1018  1018 I ValidateNoPeople: skipping global notification,
09-13 19:40:34.699  7830  7901 D Mms/MessagingNotification: [end]    init consume time = 8.735625
09-13 19:40:34.699  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false,
09-13 19:40:34.699  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:34.699  1018  1513 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-13 19:40:34.699  1018  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:34.699  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-13 19:40:34.699  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
09-13 19:40:34.709  1018  1539 D PowerManagerService: [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1174
09-13 19:40:34.709  1018  1539 I PowerManagerService: !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
09-13 19:40:34.709  1018  1539 I PowerManagerService: Waking up from sleep (uid 10049)...
,09-13 19:40:34.709  2912  2912 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-13 19:40:34.709  7830  7905 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 4.396459
09-13 19:40:34.709  1018  7893 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
09-13 19:40:34.709  1018  7893 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-13 19:40:34.709  1018  7893 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
09-13 19:40:34.709  7830  7906 D Mms/Synchronizer: [start]    doSync consume time = 3.541302
,09-13 19:40:34.709  1018  1539 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
09-13 19:40:34.709  1018  1539 D PowerManagerService: [s] UserActivityState : 0 -> 1
09-13 19:40:34.709  1018  1539 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
09-13 19:40:34.709  1018  1156 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@ce3695d)
,09-13 19:40:34.709  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-13 19:40:34.709  1174  1174 D SViewCoverView: level :100 plugged : 2
,09-13 19:40:34.719  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 19:40:34.719  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 19:40:34.719  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 19:40:34.719  1018  1046 D WindowOrientationListener: sensor enabled
09-13 19:40:34.719  1018  1050 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
09-13 19:40:34.719  1018  1046 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
09-13 19:40:34.719  1018  1050 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
09-13 19:40:34.719  1018  1050 D DisplayPowerController: animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
09-13 19:40:34.719  1174  1992 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
09-13 19:40:34.719  1018  1050 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
09-13 19:40:34.719  1174  1992 D KeyguardViewMediator: notifyScreenOnLocked
09-13 19:40:34.719  1018  1050 D DisplayPowerController: animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,09-13 19:40:34.719  1018  1055 I libsuspend: !@autosuspend_wakeup_count_disable
09-13 19:40:34.719  1018  1055 D DisplayManagerService: !@display_state: OFF -> ON
09-13 19:40:34.719  1018  1055 I libsuspend: !@autosuspend_wakeup_count_disable done
09-13 19:40:34.719  1174  1174 D KeyguardViewMediator: handleNotifyScreenOn
09-13 19:40:34.719  1174  1174 D StatusBarKeyguardViewManager: onScreenTurnedOn()
,09-13 19:40:34.719   258   258 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb8d49690
09-13 19:40:34.719   258   258 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
09-13 19:40:34.719  1018  1046 D SensorService: [SO] changed settle time [0]
09-13 19:40:34.719  1018  1046 D SensorService: [SO] setDelay [200000000],
09-13 19:40:34.719  1018  1046 D SensorService: [SO] activate (ident=0xb98fa0a0, enabled=1)
09-13 19:40:34.719  1018  1046 D SensorService: [SO] AR_init
09-13 19:40:34.719  1018  1046 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1,
09-13 19:40:34.719   258   258 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
09-13 19:40:34.719   258   258 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
09-13 19:40:34.719  2912  2912 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-13 19:40:34.719  1018  7893 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:34.719  1018  7893 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:34.719  1018  7893 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:34.719  1018  7893 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:34.729  1018  1048 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
09-13 19:40:34.729  1018  1018 V ActivityManager: Display changed displayId=0
,09-13 19:40:34.729  1018  1046 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,09-13 19:40:34.739  2912  2912 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 19:40:34.739  2912  2912 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 19:40:34.749  7909  7909 E Zygote  : MountEmulatedStorage()
09-13 19:40:34.749  7909  7909 I libpersona: KNOX_SDCARD checking this for 10090
09-13 19:40:34.749  7909  7909 E Zygote  : v2
09-13 19:40:34.749  7909  7909 I libpersona: KNOX_SDCARD not a persona
,09-13 19:40:34.749  2912  7907 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-13 19:40:34.749  2912  7907 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED,
09-13 19:40:34.749  7909  7909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 19:40:34.749  7909  7909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:34.759  2912  7907 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-13 19:40:34.759  1018  7893 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7909 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
09-13 19:40:34.759  7909  7909 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:34.759  1174  1174 D SecKeyguardClockSingleView: onScreenTurnedOn
,09-13 19:40:34.759  2912  7907 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
09-13 19:40:34.759  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 19:40:34.759  1018  1030 V KeyguardServiceDelegate: **** SHOWN CALLED ****
09-13 19:40:34.769  1174  1174 D StatusBarKeyguardViewManager: callback.onShown()
09-13 19:40:34.769  1018  1539 I TactileAssist: enable value -1
09-13 19:40:34.769  1018  1046 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
09-13 19:40:34.769  1018  1539 I TactileAssist: internal enable value -1
09-13 19:40:34.769  1018  1050 I DisplayPowerController: Unblocked screen on after 53 ms
09-13 19:40:34.769  1018  1539 I TactileAssist: intensity value -1
09-13 19:40:34.769  1018  1050 D DisplayPowerState: !@ ColorFade exit
09-13 19:40:34.769  1018  1539 I TactileAssist: saveAppList value true
,09-13 19:40:34.769  1018  1539 I TactileAssist: List of disabled apps :
,09-13 19:40:34.779  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,09-13 19:40:34.779  7376  7376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-13 19:40:34.779  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:34.779  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:34.779  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 19:40:34.779  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 19:40:34.779   258  1155 I SurfaceFlinger: id=9 Removed DolorFade (8/8)
09-13 19:40:34.779  1018  1050 D PowerManagerService: Excessive delay in ColorFade : dismiss: 13ms
09-13 19:40:34.779  7909  7909 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 19:40:34.779  1018  1050 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
09-13 19:40:34.779   258   442 I SurfaceFlinger: id=9 Removed DolorFade (-2/8)
09-13 19:40:34.779  1018  1050 D DisplayPowerController: animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
09-13 19:40:34.779  1018  1050 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-13 19:40:34.789  1018  1050 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
09-13 19:40:34.779  1018  1160 D lights  : lcd : 31 +
09-13 19:40:34.789  1018  1050 D DisplayPowerController: animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
09-13 19:40:34.779  1018  1160 D lights  : lcd : 31 -
09-13 19:40:34.789  1018  1050 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
09-13 19:40:34.789  7909  7909 D ActivityThread: Added TimaKeyStore provider
09-13 19:40:34.789  1018  1050 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
,09-13 19:40:34.799  7925  7925 E Zygote  : MountEmulatedStorage(),
09-13 19:40:34.799  7925  7925 I libpersona: KNOX_SDCARD checking this for 1000
09-13 19:40:34.799  7925  7925 E Zygote  : v2
09-13 19:40:34.799  7925  7925 I libpersona: KNOX_SDCARD not a persona
09-13 19:40:34.799  7925  7925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 19:40:34.799  7925  7925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 19:40:34.799  7925  7925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 19:40:34.809  1018  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 19:40:34.819  1018  1483 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,09-13 19:40:34.819  1018  1018 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
09-13 19:40:34.819  1018  1018 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
09-13 19:40:34.819  1018  1018 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
09-13 19:40:34.819  1018  1018 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
09-13 19:40:34.819  1018  1018 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
,09-13 19:40:34.819  1018  1018 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
09-13 19:40:34.819  1018  1018 D PalmMotion: [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
09-13 19:40:34.819  1018  1078 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
09-13 19:40:34.819  1018  1078 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
09-13 19:40:34.819  1877  1877 D SamsungIME: showDlgMsgBox : false true true
,09-13 19:40:34.819  1018  3375 D SSRM:a  : DeviceInfo:: 000000000000
09-13 19:40:34.819  1018  3375 D SSRM:a  : SettingsAirViewInfo:: 000000000
,09-13 19:40:34.829  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-13 19:40:34.829  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-13 19:40:34.829  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 19:40:34.829  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 19:40:34.829  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu

```
