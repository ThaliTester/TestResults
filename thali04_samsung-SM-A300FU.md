#### Test 836273370459b7a_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
09-13 16:33:17.574  5939  6024 I qtaguid : Tagging socket 53 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5939, getuid(): 10026
,09-13 16:33:17.614  6798  6822 D Mms/ArtClassLoader: init before art
09-13 16:33:17.614  6798  6798 D Mms/TelephonyPermission: start operation mode monitor
--------- beginning of system
09-13 16:33:17.614  6798  6798 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 16:33:17.624  6798  6798 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 16:33:17.624  6798  6798 D Mms/TelephonyPermission: isDefault true
09-13 16:33:17.624  6798  6798 D Mms/MmsApp: onCreate() com.android.mms
09-13 16:33:17.664  6798  6798 D Mms/MmsApp: [start]    initCountryIso consume time = 245.856458
09-13 16:33:17.664  1018  1481 D CountryDetector: The first listener is added
09-13 16:33:17.664  6798  6798 D Mms/MmsApp: [end]    initCountryIso consume time = 8.093646
09-13 16:33:17.664  6798  6798 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.118542
09-13 16:33:17.684  6798  6798 D Mms/MmsConfig: before partial update
09-13 16:33:17.704  6798  6798 D Mms/MmsConfig: Load Resize quality : 80
09-13 16:33:17.704  6798  6798 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
09-13 16:33:17.704  6798  6798 D EasySignUpManager_1.0.1: isAuth is false
09-13 16:33:17.704  6798  6798 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
09-13 16:33:17.724  1455  1650 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6798
09-13 16:33:17.724  1455  1650 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.502 ms
09-13 16:33:17.734  6798  6798 D EasySignUpManager_1.0.1: isAuth is false
09-13 16:33:17.734  6798  6798 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
09-13 16:33:17.734  6798  6798 E CscParser: mps_code.dat does not exist
09-13 16:33:17.734  6798  6798 E CscParser: customer_path =/system/csc/customer.xml
09-13 16:33:17.734  6798  6798 E CscParser: fileName + /system/csc/customer.xml
09-13 16:33:17.744  6798  6798 E CscParser: mps_code.dat does not exist
09-13 16:33:17.744  6798  6798 E CscParser: customer_path =/system/csc/customer.xml
09-13 16:33:17.744  6798  6798 E CscParser: fileName + /system/csc/customer.xml
09-13 16:33:17.754  6798  6798 D CscParser: getInstance fileName =/system/csc/customer.xml
09-13 16:33:17.754  6798  6798 D Mms/MmsConfig:  enable multiwindow = false
09-13 16:33:17.764  6798  6798 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-13 16:33:17.764  6798  6798 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-13 16:33:17.764  6798  6798 D Mms/MmsConfig: [end]    init() consume time = 99.756406
09-13 16:33:17.774  6798  6798 D Mms/Contact: [start]    init() consume time = 1.295833
09-13 16:33:17.784  1455  1470 D TP/MmsSmsProvider: query,matched:13, calling pid = 6798
09-13 16:33:17.784  1455  1470 D TP/MmsSmsProvider: match 13:Elapsed time : 1.161 ms
09-13 16:33:17.784  6798  6798 D Mms/Contact: [end]    init consume time = 13.526511
09-13 16:33:17.794  6798  6830 D Mms/DraftCache: [start]    rebuildCache consume time = 3.887604
09-13 16:33:17.794   289   289 E SMD     : DCD OFF
09-13 16:33:17.794  6798  6798 D Mms/MethodReflector: getSubId is called
09-13 16:33:17.794  6798  6798 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 16:33:17.804  1455  1862 D TP/MmsSmsProvider: query,matched:12, calling pid = 6798
09-13 16:33:17.804  1455  1862 D TP/MmsSmsProvider: match 12:Elapsed time : 1.352 ms
09-13 16:33:17.804  6798  6798 D Mms/MethodReflector: getTelephonyProperty is called
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: auto download without roaming -> true
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 16:33:17.804  6798  6798 D Mms/MethodReflector: getSubId is called
09-13 16:33:17.804  6798  6798 D Mms/MethodReflector: getDefaultSmsSubId is called
09-13 16:33:17.804  6798  6798 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-13 16:33:17.804  6798  6798 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-13 16:33:17.804  6798  6798 D Mms/MethodReflector: getTelephonyProperty is called
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: auto download without roaming -> true
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: auto download during roaming secondary -> false
09-13 16:33:17.804  6798  6798 D Mms/DownloadManager: mAutoDownload ------> true
09-13 16:33:17.814  6798  6830 D Mms/DraftCache: [end]    rebuildCache consume time = 27.891042
09-13 16:33:17.824   327   327 I ServiceManager: Waiting for service AtCmdFwd...
09-13 16:33:17.854  6798  6798 D ComposerPerformance: 1473777197872 ms / [DONE] Composer constructor
09-13 16:33:17.864  6798  6798 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-13 16:33:17.864  6798  6798 I Mms/ReservationManager: ReservationManager()
09-13 16:33:17.864  6798  6798 I Mms/ReservationManager: resetAfterConnected()
09-13 16:33:17.864  1455  1862 D TP/MmsSmsProvider: query,matched:7, calling pid = 6798
09-13 16:33:17.864  1455  1862 D TP/MmsSmsProvider: match 7:Elapsed time : 2.026 ms
09-13 16:33:17.864  6798  6798 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-13 16:33:17.874  6798  6798 D Mms/MmsApp: [end]    onCreate() consume time = 56.204479
09-13 16:33:17.874  6798  6798 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
09-13 16:33:17.874  1018  1306 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-13 16:33:17.874  1018  1306 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-13 16:33:17.874  1018  1306 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:17.874  1018  1306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:17.874  1018  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-13 16:33:17.874  6798  6832 D Mms/Conversation: [start]    init() consume time = 7.369166
09-13 16:33:17.884  6825  6825 D AndroidRuntime: 
09-13 16:33:17.884  6825  6825 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 16:33:17.884  6825  6825 D AndroidRuntime: CheckJNI is OFF
09-13 16:33:17.884  6825  6825 D AndroidRuntime: readGMSProperty: start
09-13 16:33:17.884  6825  6825 D AndroidRuntime: readGMSProperty: already setted!!
09-13 16:33:17.884  6825  6825 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 16:33:17.884  6825  6825 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 16:33:17.884  6825  6825 D AndroidRuntime: readGMSProperty: end
09-13 16:33:17.884  6825  6825 D AndroidRuntime: addProductProperty: start
09-13 16:33:17.894  6798  6798 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
09-13 16:33:17.894  6798  6798 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-13 16:33:17.904  6798  6798 D Mms/MethodReflector: getSubId is called
09-13 16:33:17.904  6798  6798 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 16:33:17.904  6798  6798 D Mms/MethodReflector: getTelephonyProperty is called
09-13 16:33:17.904  6798  6798 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 16:33:17.904  6798  6798 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 16:33:17.904  6798  6798 D Mms/DownloadManager: auto download without roaming -> true
09-13 16:33:17.904  6798  6798 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 16:33:17.904  6798  6798 D Mms/DownloadManager: mAutoDownload ------> true
09-13 16:33:17.904  1455  1470 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-13 16:33:17.904  1455  1470 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 16:33:17.904  1455  1470 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-13 16:33:17.904  1455  1470 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-13 16:33:17.904  1455  1470 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-13 16:33:17.904  1455  1470 D TP/MmsSmsProvider: need read changed broadcast:false
09-13 16:33:17.914  6798  6832 D Mms/Conversation: [end]    init consume time = 31.191927
09-13 16:33:17.914  6798  6832 D Mms/MessagingNotification: [start]    init() consume time = 2.882969
09-13 16:33:17.924  6798  6833 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
09-13 16:33:17.924  6798  6833 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
09-13 16:33:17.994  6798  6822 D Mms/ArtClassLoader: init [DONE] art
09-13 16:33:18.014  1018  3349 D SSRM:n  : SIOP:: AP = 440
09-13 16:33:18.024  6825  6825 E AffinityControl: AffinityControl: registerfunction enter
09-13 16:33:18.054  6825  6825 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 16:33:18.054  1018  1499 I art     : Explicit concurrent mark sweep GC freed 140883(8MB) AllocSpace objects, 5(1873KB) LOS objects, 33% free, 24MB/37MB, paused 2.513ms total 174.200ms
09-13 16:33:18.054  1018  1480 I splitIntent: Queue : background intent android.intent.action.PACKAGE_REMOVED is finished at BG and BG split queue. set mSplitStart  false.
09-13 16:33:18.064  1018  1499 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 16:33:18.064  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-13 16:33:18.064  6798  6832 D Mms/MessagingNotification: [end]    init consume time = 154.480261
09-13 16:33:18.064  1018  1481 I ActivityManager: Killing 6319:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-13 16:33:18.074  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 16:33:18.074  1018  4349 E PersonaManagerService: inState():  stateMachine is null !!
09-13 16:33:18.074  1018  4349 I PersonaManagerService: PersonaId don't exist
09-13 16:33:18.074  1018  4349 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-13 16:33:18.074  1438  1438 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
09-13 16:33:18.074  6798  6842 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 11.128645
09-13 16:33:18.084  1455  1470 D TP/MmsSmsProvider: query,matched:0, calling pid = 6798
09-13 16:33:18.084  1455  1470 V TP/MmsSmsProvider: getSimpleConversations entered.
09-13 16:33:18.084  1455  1470 D TP/MmsSmsProvider: match 0:Elapsed time : 0.993 ms
09-13 16:33:18.084  1018  4349 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 16:33:18.084  6798  6843 D Mms/Synchronizer: [start]    doSync consume time = 4.888438
09-13 16:33:18.104  1018  4349 W ActivityManager: mDVFSHelper.acquire()
09-13 16:33:18.104   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-13 16:33:18.104   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-13 16:33:18.124  1018  4349 D FocusedStackFrame: Set to : 0
09-13 16:33:18.134  1018  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-13 16:33:18.134  1018  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-13 16:33:18.134  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.134  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.134  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.134  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.154  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-13 16:33:18.154  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-13 16:33:18.154   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-13 16:33:18.154  6845  6845 E Zygote  : MountEmulatedStorage()
09-13 16:33:18.154  6845  6845 E Zygote  : v2
09-13 16:33:18.154  6845  6845 I libpersona: KNOX_SDCARD checking this for 10171
09-13 16:33:18.154  1018  4349 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6845 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 16:33:18.154  1018  4349 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-13 16:33:18.154  1018  4349 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 16:33:18.154  6845  6845 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:18.154  6845  6845 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:18.154  6845  6845 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:18.164  6845  6845 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-13 16:33:18.174  1018  4349 D InputDispatcher: Focused application set to: xxxx
09-13 16:33:18.174  1018  4349 D InputDispatcher: Focus left window: 1482
09-13 16:33:18.174  6825  6825 D AndroidRuntime: Shutting down VM
09-13 16:33:18.174  1018  1347 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=20, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
09-13 16:33:18.174  1018  1347 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
09-13 16:33:18.184  6286  6286 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
09-13 16:33:18.194  1018  1479 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 16:33:18.194  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-13 16:33:18.194  6286  6286 I AASAservice-TokenRule: parseToken()
09-13 16:33:18.194  6286  6286 W System.err: java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
09-13 16:33:18.194  6286  6286 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-13 16:33:18.194  6286  6286 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 16:33:18.194  6286  6286 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-13 16:33:18.194  6286  6286 W System.err: 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:86)
09-13 16:33:18.194  6286  6286 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:55)
09-13 16:33:18.194  6286  6286 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-13 16:33:18.194  6286  6286 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-13 16:33:18.194  6286  6286 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-13 16:33:18.194  6286  6286 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:33:18.194  6286  6286 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-13 16:33:18.194  6286  6286 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 16:33:18.194  6286  6286 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:33:18.194  6286  6286 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 16:33:18.194  6286  6286 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 16:33:18.194  6286  6286 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 16:33:18.194  6286  6286 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
09-13 16:33:18.194  6286  6286 W System.err: 	at libcore.io.Posix.open(Native Method)
09-13 16:33:18.194  6286  6286 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:33:18.194  6286  6286 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 16:33:18.194  6286  6286 W System.err: 	... 14 more
09-13 16:33:18.194  6286  6286 E AASAservice-TokenRule: parseToken() : TokenFile is null
09-13 16:33:18.194  6286  6286 E AASAservice-UpdateReceiver: AASARuleUpdateResult() : Rule file is not exist.
09-13 16:33:18.204  6286  6286 I art     : System.exit called, status: 0
09-13 16:33:18.204  6286  6286 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 16:33:18.204  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 16:33:18.204  6845  6845 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:18.204  6845  6845 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:18.214  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 16:33:18.214  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 16:33:18.214  6798  6798 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-13 16:33:18.214  1018  1306 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-13 16:33:18.214  1018  1018 V ActivityManager: Display changed displayId=0
09-13 16:33:18.224  1455  2029 D TP/MmsSmsProvider: query,matched:400, calling pid = 6798
09-13 16:33:18.224  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 16:33:18.234  1455  1862 D TP/MmsSmsProvider: update, matched:300, calling pid = 6798
09-13 16:33:18.234  1455  1862 V TP/MmsSmsProvider: syncDBData start
09-13 16:33:18.234  1455  1862 V TP/MmsSmsProvider: syncDBData sms end
09-13 16:33:18.234  1455  1862 V TP/MmsSmsProvider: syncDBData mms end
09-13 16:33:18.234  1455  1862 V TP/MmsSmsProvider: syncDBData end
09-13 16:33:18.244  1018  1306 D PersonaManager: isKioskContainerExistOnDevice
09-13 16:33:18.254  1018  1481 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-13 16:33:18.254  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.254  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.254  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.254  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.264  6861  6861 E Zygote  : MountEmulatedStorage()
09-13 16:33:18.264  6861  6861 E Zygote  : v2
09-13 16:33:18.264  6861  6861 I libpersona: KNOX_SDCARD checking this for 10068
09-13 16:33:18.264  6861  6861 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:18.274  6861  6861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:18.274  1018  1481 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6861 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-13 16:33:18.274  6861  6861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:18.274  6861  6861 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 16:33:18.274  1018  1556 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-13 16:33:18.284  1018  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.284  1018  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.284  1018  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.284  1018  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.294  6798  6843 D Mms/Synchronizer: [end]    doSync consume time = 192.086719
09-13 16:33:18.304  6861  6861 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:18.314  6861  6861 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:18.314   259   453 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-13 16:33:18.314  2764  2764 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected
09-13 16:33:18.314   259   456 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-13 16:33:18.314  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{1e4e70a8 token=android.os.BinderProxy@2880f30f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 16:33:18.314  1482  1482 D Launcher: onTrimMemory. Level: 20
09-13 16:33:18.324  6876  6876 E Zygote  : MountEmulatedStorage()
09-13 16:33:18.324  6876  6876 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:18.324  6876  6876 E Zygote  : v2
09-13 16:33:18.324  6876  6876 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:18.324  6876  6876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:18.324  6876  6876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:18.324  6876  6876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:33:18.324  1018  1556 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:33:18.334  1018  1478 I ActivityManager: Process com.samsung.aasaservice (pid 6286)(adj 0) has died(118,711)
09-13 16:33:18.334  1018  1478 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
09-13 16:33:18.344  1018  1479 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-13 16:33:18.344  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-13 16:33:18.344  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:18.344  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:18.344  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-13 16:33:18.344  6798  6842 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 70.69026
09-13 16:33:18.354  1018  6724 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
09-13 16:33:18.354  6798  6888 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-13 16:33:18.354  6798  6888 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
09-13 16:33:18.354  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.354  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.354  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.354  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.374  6893  6893 E Zygote  : MountEmulatedStorage()
09-13 16:33:18.374  6893  6893 E Zygote  : v2
09-13 16:33:18.374  6893  6893 I libpersona: KNOX_SDCARD checking this for 10042
09-13 16:33:18.374  6893  6893 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:18.374  6893  6893 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:18.374  1018  6724 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6893 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-13 16:33:18.374  6893  6893 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:18.384  6893  6893 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-13 16:33:18.384  6861  6861 D BadgeProvider: onCreate
09-13 16:33:18.384  6861  6861 D BadgeProvider: DatabaseHelper
09-13 16:33:18.384  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
09-13 16:33:18.384  6825  6825 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-13 16:33:18.394  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.394  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.394  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.394  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.404  6876  6876 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:18.404  6876  6876 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:18.404  6893  6893 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:18.404  6893  6893 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:18.414  6908  6908 E Zygote  : MountEmulatedStorage(),
09-13 16:33:18.414  6908  6908 E Zygote  : v2,
,09-13 16:33:18.414  6908  6908 I libpersona: KNOX_SDCARD checking this for 10014
09-13 16:33:18.414  6908  6908 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:18.414  6908  6908 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:18.414  1018  1044 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6908 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,09-13 16:33:18.424  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66,
,09-13 16:33:18.424  6908  6908 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:18.424  6908  6908 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:33:18.434  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-13 16:33:18.434  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.434  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.434  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.434  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.444  6908  6908 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:18.444  6908  6908 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:18.454  6923  6923 E Zygote  : MountEmulatedStorage()
09-13 16:33:18.454  6923  6923 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:18.454  6923  6923 E Zygote  : v2
09-13 16:33:18.454  6923  6923 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:18.454  6923  6923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:18.454  5939  5939 I Finsky  : [1] com.google.android.finsky.selfupdate.f.a(166): Skipping DFE self-update. Local Version [80691500] >= Server Version [-1]
09-13 16:33:18.454  6923  6923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:18.454  1018  1030 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6923 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:33:18.464  6923  6923 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:18.464  6893  6893 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:18.464  6893  6893 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 16:33:18.464  6893  6893 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 16:33:18.464  1018  1478 I ActivityManager: Killing 6199:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-13 16:33:18.484  6798  6832 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-13 16:33:18.484   308   308 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 623us total 32.324ms
,09-13 16:33:18.494  6923  6923 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:18.494  6923  6923 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:18.504  1455  1650 D TP/SmsProvider: query,matched:26, calling pid = 6798
,09-13 16:33:18.504  1455  1650 D TP/SmsProvider: match 26:Elapsed time : 0.904 ms
,09-13 16:33:18.504   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.847ms
,09-13 16:33:18.504  6893  6893 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-13 16:33:18.514  1455  1471 D TP/MmsSmsProvider: query,matched:6, calling pid = 6798
,09-13 16:33:18.524  1455  1471 D TP/MmsSmsProvider: match 6:Elapsed time : 1.608 ms
,09-13 16:33:18.524   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 17.035ms
09-13 16:33:18.524  6876  6876 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,09-13 16:33:18.534   285   285 E installd: system dir 0 : /system/app/
09-13 16:33:18.534   285   285 E installd: system dir 1 : /system/priv-app/
09-13 16:33:18.534   285   285 E installd: system dir 2 : /vendor/app/
09-13 16:33:18.534   285   285 E installd: system dir 3 : /oem/app/
,09-13 16:33:18.544  1018  1479 I ActivityManager: Killing 6337:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-13 16:33:18.544  6845  6845 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-13 16:33:18.554  1018  1347 I TactileAssist: enable value -1
,09-13 16:33:18.554  1018  1347 I TactileAssist: internal enable value -1
09-13 16:33:18.554  1018  1347 I TactileAssist: intensity value -1
09-13 16:33:18.554  1018  1347 I TactileAssist: saveAppList value true
,09-13 16:33:18.554  1018  1347 I TactileAssist: List of disabled apps :
,09-13 16:33:18.554  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,09-13 16:33:18.554  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.554  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.554  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.554  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.564  1018  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-13 16:33:18.574  6939  6939 E Zygote  : MountEmulatedStorage(),
09-13 16:33:18.574  6876  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.PackageEventReceiver.onReceive:182 android.app.ActivityThread.handleReceiver:3125 
09-13 16:33:18.574  6939  6939 E Zygote  : v2
,09-13 16:33:18.574  6939  6939 I libpersona: KNOX_SDCARD checking this for 10023
09-13 16:33:18.574  6939  6939 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:18.574  6939  6939 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:18.574  6939  6939 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 16:33:18.574  1018  1030 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6939 uid=10023 gids={50023, 9997} abi=armeabi-v7a
09-13 16:33:18.574  6939  6939 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:18.584  1018  1347 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
09-13 16:33:18.584  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,09-13 16:33:18.584  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:18.584  1018  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:18.584  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,09-13 16:33:18.584  1018  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:18.594  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:18.594  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:18.594  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 16:33:18.594  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.594  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.594  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.594  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.604  6955  6955 E Zygote  : MountEmulatedStorage()
,09-13 16:33:18.604  6955  6955 E Zygote  : v2
09-13 16:33:18.604  6955  6955 I libpersona: KNOX_SDCARD checking this for 10011
09-13 16:33:18.604  6955  6955 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:18.614  6939  6939 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:18.614  6939  6939 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:18.624  6955  6955 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 16:33:18.624  6955  6955 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:18.624  6955  6955 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:33:18.624  1018  1478 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6955 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-13 16:33:18.624  1018  6724 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-13 16:33:18.634  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.634  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.634  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.634  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.634  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,09-13 16:33:18.654  6968  6968 E Zygote  : MountEmulatedStorage()
09-13 16:33:18.654  6968  6968 E Zygote  : v2
,09-13 16:33:18.654  6968  6968 I libpersona: KNOX_SDCARD checking this for 10048
09-13 16:33:18.654  6968  6968 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:18.654  1018  6724 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6968 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a,
,09-13 16:33:18.654  1018  1472 I ActivityManager: Killing 6537:com.sec.android.app.themechooser/u0a145 (adj 15): empty #21
,09-13 16:33:18.654  6968  6968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:18.664  6968  6968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:18.664  1018  1479 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 16:33:18.664  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 16:33:18.664  6968  6968 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 16:33:18.664  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 16:33:18.664  1018  1136 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-13 16:33:18.664  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:18.664  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
09-13 16:33:18.664  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:18.664  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,09-13 16:33:18.674  1018  1306 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-13 16:33:18.674  1018  1306 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-13 16:33:18.674  1018  1306 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:18.674  1018  1306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:18.674  1018  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-13 16:33:18.674  6955  6955 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:18.674  6955  6955 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:18.684  6665  6665 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-13 16:33:18.684  6665  6665 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-13 16:33:18.684  6665  6665 I TapandpayWidget:Utils: Clear T&P info.
09-13 16:33:18.684  6665  6665 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-13 16:33:18.704  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-13 16:33:18.704  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.704  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.704  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.704  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.714  6968  6968 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:18.714  6845  6845 I cr.library_loader: Time to load native libraries: 54 ms (timestamps 4046-4100)
09-13 16:33:18.714  6845  6845 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-13 16:33:18.714  6968  6968 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:18.724  6990  6990 E Zygote  : MountEmulatedStorage()
09-13 16:33:18.724  6990  6990 E Zygote  : v2
09-13 16:33:18.724  6990  6990 I libpersona: KNOX_SDCARD checking this for 10087
09-13 16:33:18.724  6990  6990 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:18.724  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:18.724  1018  1136 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6990 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
09-13 16:33:18.724  1018  1478 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-13 16:33:18.734  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:18.734  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
09-13 16:33:18.734  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 16:33:18.734  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:18.734  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:18.734  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
09-13 16:33:18.734  6955  6955 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 16:33:18.734  6955  6955 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 16:33:18.734  6939  6939 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-13 16:33:18.744  1018  1044 W ActivityManager: Activity pause timeout for ActivityRecord{3d71ef9 u0 com.test.thalitest/.MainActivity t2}
,09-13 16:33:18.754  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-13 16:33:18.754  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.754  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.754  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:18.754  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.764  6845  6845 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e5c818a}
09-13 16:33:18.764  6845  6845 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 16:33:18.784  6798  6832 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-13 16:33:18.784  1018  1136 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7007 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-13 16:33:18.784  7007  7007 E Zygote  : MountEmulatedStorage()
09-13 16:33:18.784  7007  7007 I libpersona: KNOX_SDCARD checking this for 10009
09-13 16:33:18.784  7007  7007 E Zygote  : v2
09-13 16:33:18.784  7007  7007 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:18.784  6845  6845 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 16:33:18.784  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:18.784  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:18.784  1018  1136 I ActivityManager: Killing 6550:com.sec.pcw.device/1000 (adj 15): empty #21
,09-13 16:33:18.784  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-13 16:33:18.794  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:18.794  6990  6990 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:18.794  1018  1472 I ActivityManager: Killing 6374:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-13 16:33:18.804  6968  6968 D Compatibility: onReceive() it will make start service
,09-13 16:33:18.804  1018  6724 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-13 16:33:18.804  1018  6724 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-13 16:33:18.804  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:18.804  1018  6724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 16:33:18.804  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-13 16:33:18.814  1018  1306 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-13 16:33:18.814  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.814  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.814  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.814  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:18.824   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-13 16:33:18.824  6968  7016 D Compatibility: onHandleIntent(),
,09-13 16:33:18.824  6968  7016 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,09-13 16:33:18.834  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-13 16:33:18.834  7007  7007 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:18.834  6845  6845 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-13 16:33:18.834  6968  7016 D Compatibility: found: 2
,09-13 16:33:18.834  6845  6845 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-13 16:33:18.844  7024  7024 E Zygote  : MountEmulatedStorage(),
09-13 16:33:18.844  7024  7024 E Zygote  : v2
09-13 16:33:18.844  7024  7024 I libpersona: KNOX_SDCARD checking this for 10052,
09-13 16:33:18.844  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
09-13 16:33:18.844  7024  7024 I libpersona: KNOX_SDCARD not a persona,
09-13 16:33:18.844  7024  7024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:18.844  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,09-13 16:33:18.844  7024  7024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 16:33:18.844  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,09-13 16:33:18.844  7024  7024 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:33:18.844  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-13 16:33:18.844  1018  1556 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-13 16:33:18.844  1018  1306 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7024 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-13 16:33:18.854  6968  7016 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 16:33:18.854  6968  7016 D Compatibility: skipping ResolveInfo{38e3cd00 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-13 16:33:18.854  6968  7016 D Compatibility: considering ResolveInfo{2f747939 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-13 16:33:18.854  6968  7016 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 16:33:18.854  6968  7016 D Compatibility: enabling receiver ResolveInfo{2c9d2b7e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-13 16:33:18.854  6845  6845 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 16:33:18.864  1018  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:18.864  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-13 16:33:18.864  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-13 16:33:18.864  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-13 16:33:18.864  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-13 16:33:18.864  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-13 16:33:18.874  6968  7016 D Compatibility: enabling receiver ResolveInfo{3a018df com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 16:33:18.874  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:18.874  7024  7024 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:18.874  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:18.874  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:18.874  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 16:33:18.884  1018  1479 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-13 16:33:18.884  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-13 16:33:18.884  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
09-13 16:33:18.884  1018  1030 I ActivityManager: Killing 6395:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-13 16:33:18.884  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-13 16:33:18.884  6955  6955 I MultiDex: VM with version 2.1.0 has multidex support
09-13 16:33:18.884  6955  6955 I MultiDex: install
09-13 16:33:18.884  6955  6955 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-13 16:33:18.884  6968  7016 D Compatibility: enabling receiver ResolveInfo{2e38b92c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 16:33:18.894  6968  7016 D Compatibility: enabling receiver ResolveInfo{1a9a6ff5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 16:33:18.894  6968  7016 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
09-13 16:33:18.894  6939  6939 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-13 16:33:18.924  1018  1480 I ActivityManager: Killing 6570:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-13 16:33:18.934  2764  2764 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,09-13 16:33:18.954  6845  6845 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 16:33:18.954  6845  6845 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 16:33:18.954  6845  6845 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 16:33:18.954  6845  6845 I Adreno-EGL: Local Branch: 
09-13 16:33:18.954  6845  6845 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 16:33:18.954  6845  6845 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 16:33:18.954  6845  6845 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 16:33:18.964  1018  1499 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-13 16:33:18.964  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 16:33:18.974  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:18.974  6756  6756 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-13 16:33:18.994  6955  6955 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 16:33:19.004  1018  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:19.004  1018  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.014  1018  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.014  1018  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:19.014  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.024  4744  6717 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 16:33:19.024  4744  6715 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,09-13 16:33:19.024  4744  4744 D AsyncTaskServiceImpl: Submit a task: nzm
,09-13 16:33:19.034  1018  6724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:19.034  4744  6717 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 16:33:19.034  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.034  1018  6724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:19.044  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.044  1018  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:19.044  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.044  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.044  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.044  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.044  1018  1556 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:19.054  1018  1556 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.054  1018  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:19.054  1018  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.064  4744  5002 D nzm     : Processing package: com.test.thalitest
,09-13 16:33:19.074  4744  5002 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-13 16:33:19.074  4744  5002 D nzm     : Found info for package com.test.thalitest in db.
,09-13 16:33:19.074  1018  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:19.074  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.074  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.074  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:19.074  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.084  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:19.084  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.084  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.084  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.084  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.084  1018  1347 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:19.084  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.094  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.094  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.094  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.094  1018  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:19.094  4744  6717 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 16:33:19.094  4744  6717 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 16:33:19.104  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.104  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.104  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.104  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:19.104  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.104  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.104  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.104  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.114  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:19.114  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.114  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.114  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.114  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.114  6845  6845 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 16:33:19.124  1018  1479 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 16:33:19.124  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.124  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.124  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.124  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 16:33:19.144  1018  1347 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 16:33:19.144  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.144  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.144  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.144  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 16:33:19.154  6845  6845 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 16:33:19.154  5939  5939 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,09-13 16:33:19.154  6845  6845 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 16:33:19.164  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:19.164  6845  6845 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 16:33:19.164  6845  6845 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 16:33:19.174  6955  6955 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 16:33:19.174  6955  6955 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@329ad066: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-13 16:33:19.174  6955  6955 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 16:33:19.174  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.174  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.174  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.184  1018  4349 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.184  1018  4349 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.184  1018  4349 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.184  1018  4349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.184  1018  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:19.194  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.194  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.194  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.194  2006  2006 D WearableService: callingUid 10011, callindPid: 2006
,09-13 16:33:19.204  1018  1499 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-13 16:33:19.204  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.204  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.204  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:19.204  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-13 16:33:19.204  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,09-13 16:33:19.204  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.204  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.204  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.204  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 16:33:19.214  6773  6783 E SQLiteLog: (283) recovered 244 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,09-13 16:33:19.214  1018  1556 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:19.214  1018  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.214  1018  1556 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.214  1018  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.214  1018  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.214  1018  1347 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-13 16:33:19.214  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.214  5939  5939 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-13 16:33:19.224  5939  5939 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-13 16:33:19.224  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.224  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.224  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 16:33:19.234  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:19.244  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.244  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.244  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:19.244  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.264  6955  6955 D ChimeraCfgMgr: Reading stored module config
,09-13 16:33:19.304  1018  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:19.314  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.324  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:19.324  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.344  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:19.344  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:19.344  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:19.344  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:19.364  7070  7070 E Zygote  : MountEmulatedStorage(),
09-13 16:33:19.364  7070  7070 E Zygote  : v2
09-13 16:33:19.364  7070  7070 I libpersona: KNOX_SDCARD checking this for 1000,
09-13 16:33:19.364  7070  7070 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:19.364  7070  7070 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 16:33:19.364  1018  1044 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=7070 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:33:19.374  7070  7070 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 16:33:19.374  7070  7070 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:19.394  4744  7065 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-13 16:33:19.394  6845  6845 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:33:19.414  1018  1499 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-13 16:33:19.424  6845  6845 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 16:33:19.434  7070  7070 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:19.434  7070  7070 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:19.434  6845  6845 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-13 16:33:19.444  6845  6845 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-13 16:33:19.444  6845  6845 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-13 16:33:19.454  6845  6845 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 16:33:19.454  6845  6845 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:33:19.464  7070  7070 D AASAservice: onCreate()
,09-13 16:33:19.474  7070  7070 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,09-13 16:33:19.474  2764  2764 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
,09-13 16:33:19.484  2006  2164 I art     : Explicit concurrent mark sweep GC freed 51594(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 10MB/17MB, paused 1.262ms total 81.622ms
,09-13 16:33:19.494  1018  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:19.494  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.494  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.494  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.504  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:19.504  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.504  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:19.504  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.504  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.524  6845  7095 D OpenGLRenderer: Render dirty regions requested: true
,09-13 16:33:19.524  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 16:33:19.524  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 16:33:19.524  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-13 16:33:19.524  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-13 16:33:19.524  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 16:33:19.534  6845  6845 V ActivityThread: updateVisibility : ActivityRecord{1c30cd5 token=android.os.BinderProxy@6db72bf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-13 16:33:19.534  6845  7052 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-13 16:33:19.544  6845  6845 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-13 16:33:19.544  6845  6845 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-13 16:33:19.584  6955  7067 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-13 16:33:19.734  1018  6724 I art     : Explicit concurrent mark sweep GC freed 23302(1272KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/37MB, paused 2.666ms total 180.837ms
,09-13 16:33:19.734  1018  7092 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:19.734  1018  7092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:19.734  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:19.734  1018  7092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:19.734  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:19.744  1018  1556 D LocationManagerService: getProviders()=[passive]
,09-13 16:33:19.754   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-13 16:33:19.774  1018  7092 D InputDispatcher: Focus entered window: 6845
,09-13 16:33:19.774  6955  6955 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 16:33:19.774  6955  6955 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 16:33:19.774  6845  6845 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-13 16:33:19.774  6845  7095 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 16:33:19.774  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 16:33:19.774  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 16:33:19.784  6845  7095 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-13 16:33:19.784  6845  7095 D OpenGLRenderer: Enabling debug mode 0
,09-13 16:33:19.804  1018  1306 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 16:33:19.814  1018  7111 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:19.814  1178  1178 I StatusBar: Icon Only
,09-13 16:33:19.814  1178  1178 D PanelView: There is/are notification(s) 
,09-13 16:33:19.824  1018  1049 I ActivityManager: Displayed Component not be shown by security: +1s579ms (total +1s692ms)
,09-13 16:33:19.824  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d71ef9 u0 com.test.thalitest/.MainActivity t2} time:85216
09-13 16:33:19.824  1018  1049 W ActivityManager: mDVFSHelper.release()
,09-13 16:33:19.834   259   456 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-13 16:33:19.834   259  1040 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-13 16:33:19.834  6955  6955 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,09-13 16:33:19.834  6955  6955 D CAR.SERVICE: onBind
09-13 16:33:19.834  6955  6955 D CAR.SERVICE: CSB onClientsConnected
,09-13 16:33:19.834  6990  7040 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-13 16:33:19.834  6990  7040 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 16:33:19.834  6990  7040 I GAv4    :   adb logcat -s GAv4
,09-13 16:33:19.844  6845  6845 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-13 16:33:19.844  6845  6845 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6db72bf time:85235
,09-13 16:33:19.864  1876  1876 I SamsungIME: getCurrentCandidateView
,09-13 16:33:19.874  6798  6798 I Mms/MmsApp:  start initViewCache mms
,09-13 16:33:19.874  6798  6798 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1525.464531
09-13 16:33:19.874  6798  6798 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-13 16:33:19.884  6955  6955 D CAR.TEL.Service: Binding to InCallService
,09-13 16:33:19.894  6990  7040 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:19.894  7024  7063 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 16:33:19.894  1018  1499 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,09-13 16:33:19.904  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_action
,09-13 16:33:19.904  6955  6955 E CAR.TEL.Service: Failed to bind to InCallService
,09-13 16:33:19.904  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallService2; callingUser = 0; userId(target) = 0
09-13 16:33:19.904  1018  1030 W ActivityManager: Unable to start service Intent { act=local_action cmp=com.google.android.gms/.car.InCallService2 } U=0: not found
,09-13 16:33:19.914  1018  1480 I ActivityManager: Killing 6413:com.samsung.helphub/1000 (adj 15): empty #21
,09-13 16:33:19.934  6845  6845 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6845
,09-13 16:33:19.934  6990  7040 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:19.984  6990  7040 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,09-13 16:33:20.024  6990  7004 W art     : Suspending all threads took: 16.667ms
,09-13 16:33:20.024  6955  6963 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
09-13 16:33:20.024  6955  6963 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,09-13 16:33:20.034  6955  6963 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,09-13 16:33:20.034  6955  6963 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000006@DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000006/DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk': Failed to open oat filename for reading: No such file or directory
,09-13 16:33:20.034  6955  6963 D ChimeraFileApk: Classloading successful. Optimized code found.
,09-13 16:33:20.034  6955  6963 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,09-13 16:33:20.044  6990  7119 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:20.124  6955  6963 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,09-13 16:33:20.124  6955  6963 D CAR.SERVICE: Package validated; name: com.android.vending
,09-13 16:33:20.134  6955  6963 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.
,09-13 16:33:20.154  1876  1876 D SamsungIME: Dismiss ExpandCandiate
,09-13 16:33:20.214  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:20.214  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:20.214  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:20.214  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,09-13 16:33:20.224  6798  6798 D AbsListView: Get MotionRecognitionManager
,09-13 16:33:20.224  1018  1478 D MotionRecognitionService:  ssp status : false
,09-13 16:33:20.224  6798  6798 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 354.352291
,09-13 16:33:20.274  1018  1556 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:20.274  1018  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:20.274  6845  6845 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 16:33:20.284  1018  1556 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:20.284  1018  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:20.284  1018  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:20.304  7024  7063 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 413 ms] updated apps [took 413 ms] 
,09-13 16:33:20.304  1018  1306 I ActivityManager: Killing 6585:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #21
,09-13 16:33:20.374  1018  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,09-13 16:33:20.374  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:20.374  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.384  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.384  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.384  6845  7114 D jxcore_app_log: JniHelper::setJavaVM(0xb84bf2b0), pthread_self() = -1197165312
09-13 16:33:20.394  7136  7136 E Zygote  : MountEmulatedStorage()
09-13 16:33:20.394  7136  7136 E Zygote  : v2
09-13 16:33:20.394  7136  7136 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:20.394  7136  7136 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:20.394  7136  7136 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:20.394  1018  1481 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7136 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:33:20.394  1018  1481 I ActivityManager: Killing 6631:com.android.keychain/1000 (adj 15): empty #21
09-13 16:33:20.394  7136  7136 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:20.404  7136  7136 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:33:20.404  6845  7114 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:33:20.404  6845  7114 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:33:20.404  6845  7114 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:33:20.404  6845  7114 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:33:20.404  6845  7114 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 16:33:20.404  6845  7114 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3546cc90 added. We now have 1 listener(s)
09-13 16:33:20.414  6845  7114 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
09-13 16:33:20.414  6845  7114 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-13 16:33:20.414  6845  7114 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:33:20.414  6845  7114 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:33:20.414  7136  7136 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:33:20.424  6845  7114 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@329c89af added. We now have 1 listener(s)
09-13 16:33:20.424  7136  7136 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:20.424  6845  7114 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:33:20.444  6845  7114 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:33:20.444  6845  7114 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 16:33:20.444  6845  7114 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:33:20.444  6845  7114 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:33:20.444  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 16:33:20.444  6845  7114 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 16:33:20.444  1018  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 16:33:20.444  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 16:33:20.454  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:20.454  6798  6798 D Mms/BubbleViewCache: fillCache bubble = 1
,09-13 16:33:20.464  6845  7114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:20.464  6845  7114 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-13 16:33:20.474  6845  7114 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 16:33:20.474  6845  7114 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:20.474  6845  7114 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:20.474  6845  7114 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:20.474  6845  7114 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:20.474  6845  7114 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:20.474  6845  7114 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:20.474  6845  7114 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:20.474  6845  7114 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:20.474  6845  7114 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 16:33:20.474  6845  7114 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:33:20.474  6845  7114 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:33:20.474  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:20.484  7136  7136 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-13 16:33:20.484  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:20.484  7136  7136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-13 16:33:20.484  1018  1499 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,09-13 16:33:20.484  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-13 16:33:20.484  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:20.484  1018  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:20.484  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-13 16:33:20.494  1018  7092 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,09-13 16:33:20.494  1018  7092 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.494  1018  7092 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.494  1018  7092 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.494  1018  7092 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:20.504  7154  7154 E Zygote  : MountEmulatedStorage()
,09-13 16:33:20.504  7154  7154 I libpersona: KNOX_SDCARD checking this for 10098
09-13 16:33:20.504  7154  7154 E Zygote  : v2
09-13 16:33:20.504  7154  7154 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:20.504  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:20.514  1018  7092 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7154 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-13 16:33:20.514  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:20.514  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:20.534  6845  6845 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 16:33:20.544  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 16:33:20.544  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:20.544  7154  7154 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:20.544  7136  7136 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-13 16:33:20.564  7136  7153 E FilterInstaller: installFilters
,09-13 16:33:20.584  1876  1876 I SamsungIME: KeybaordView init() : load resources
,09-13 16:33:20.594  7136  7153 E FilterInstaller: There is no requred permission
,09-13 16:33:20.594  1018  1479 I ActivityManager: Killing 6444:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-13 16:33:20.634  1018  1306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:33:20.634  1018  1306 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4307, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 16:33:20.634  1018  1306 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 16:33:20.634  1018  1306 D BatteryService: stay LED for fully charged
,09-13 16:33:20.634  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:20.644  1018  1018 I MotionRecognitionService: Plugged
,09-13 16:33:20.644  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 16:33:20.644  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:20.644  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:33:20.644  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 16:33:20.644  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:33:20.654  1876  1876 I SamsungIME: getCurrentKeyboard
09-13 16:33:20.654  1876  1876 I SamsungIME: getTextKeyboard
,09-13 16:33:20.664  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:20.664  3165  3165 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:33:20.664  3165  3286 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:33:20.674  7154  7154 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
09-13 16:33:20.674  7154  7154 D PackageIntentReceiver: Not GearManger package! 
,09-13 16:33:20.674  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,09-13 16:33:20.674  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.674  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.674  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.674  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:20.674  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 16:33:20.674  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:20.684  1018  1480 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7169 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:33:20.694  1018  1480 I ActivityManager: Killing 6737:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #21
,09-13 16:33:20.694  7169  7169 E Zygote  : MountEmulatedStorage()
09-13 16:33:20.694  7169  7169 E Zygote  : v2
09-13 16:33:20.694  7169  7169 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:20.694  7169  7169 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:20.694  7169  7169 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:20.694  7169  7169 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:20.704  1876  1876 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-13 16:33:20.714  7169  7169 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:20.744  7169  7169 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:20.744  7169  7169 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:20.754  6990  7104 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 16:33:20.754  6990  7104 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 16:33:20.764  4744  5116 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-13 16:33:20.794   289   289 E SMD     : DCD OFF
,09-13 16:33:20.834  1018  1030 I ActivityManager: Killing 6598:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-13 16:33:20.844  1018  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-13 16:33:20.844  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:20.844  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.844  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:20.844  1018  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:20.864  7186  7186 E Zygote  : MountEmulatedStorage()
09-13 16:33:20.864  7186  7186 E Zygote  : v2
09-13 16:33:20.864  6682  7185 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
09-13 16:33:20.864  7186  7186 I libpersona: KNOX_SDCARD checking this for 10117
09-13 16:33:20.864  7186  7186 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:20.864  6682  7185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-13 16:33:20.864  7186  7186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 16:33:20.864  7186  7186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 16:33:20.874  1018  1480 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7186 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-13 16:33:20.874  7186  7186 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:33:20.894   308   308 I art     : Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 27.770ms
,09-13 16:33:20.894  1018  7092 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-13 16:33:20.894  1018  7092 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-13 16:33:20.894  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:20.894  1018  7092 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:20.894  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-13 16:33:20.904  7186  7186 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:20.904  7186  7186 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:20.904  6682  6682 D AcmsService: onStartCommand
09-13 16:33:20.904  6682  6682 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-13 16:33:20.904  6682  6682 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 2
09-13 16:33:20.904  6682  6682 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-13 16:33:20.904  6682  6682 D AcmsService: Incremented Counter Value : onStartCommand
09-13 16:33:20.904  6682  6682 D AcmsService: Inside handle Intent
09-13 16:33:20.904  6682  6682 D AcmsService: App added - package name: com.test.thalitest
09-13 16:33:20.904  6682  6682 D AcmsCore: Post to AcmsCoreHandler
09-13 16:33:20.904  6682  6682 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:33:20.904  6682  6682 D AcmsServiceMonitor: Incrementing - Counter value: 4
09-13 16:33:20.904  6682  6682 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-13 16:33:20.904  6682  6682 D AcmsService: Decremented Counter Value : handleStartIntent
09-13 16:33:20.904  6682  6682 D AcmsServiceMonitor: Decrementing - Counter value: 3
,09-13 16:33:20.924   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 31.209ms
,09-13 16:33:20.944   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 18.741ms,
,09-13 16:33:20.944  7186  7186 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 16:33:20.964  4744  5116 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-13 16:33:21.044  6990  7104 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 16:33:21.094  6990  7004 W art     : Suspending all threads took: 6.217ms
,09-13 16:33:21.144  6990  7104 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 16:33:21.144  6990  7104 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19e9884e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-13 16:33:21.144  6990  7104 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 16:33:21.304  6845  7152 W jxcore-log: Initializing JXcore engine
09-13 16:33:21.304  6845  7152 W jxcore-log: JXcore engine is ready
,09-13 16:33:21.314  4744  5116 I Icing   : Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,09-13 16:33:21.374  2004  2004 E audit   : type=1400 msg=audit(1473777201.374:205): avc:  denied  { ioctl } for  pid=7152 comm="Thread-1270" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-13 16:33:21.374  2004  2004 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:21.374  2004  2004 E audit   : type=1300 msg=audit(1473777201.374:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f5928f8 items=0 ppid=308 ppcomm=main pid=7152 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1270" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-13 16:33:21.374  2004  2004 E audit   : type=1320 msg=audit(1473777201.374:205): 
,09-13 16:33:21.384  6845  7152 W jxcore-log: Starting JXcore engine
,09-13 16:33:21.424  1018  1479 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 16:33:21.424  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.424  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:21.424  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.424  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-13 16:33:21.444  1018  7092 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,09-13 16:33:21.444  1018  7092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.444  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:21.444  1018  7092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.444  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-13 16:33:21.514  6845  7152 W jxcore-log: Platform android
09-13 16:33:21.514  6845  7152 W jxcore-log: 
09-13 16:33:21.514  6845  7152 W jxcore-log: Process ARCH arm
09-13 16:33:21.514  6845  7152 W jxcore-log: 
,09-13 16:33:21.534  1018  1136 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-13 16:33:21.544  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-13 16:33:21.544  4744  5116 I Icing   : Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
,09-13 16:33:21.544  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:21.544  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:21.544  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:21.544  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:21.554  7208  7208 E Zygote  : MountEmulatedStorage()
,09-13 16:33:21.554  7208  7208 E Zygote  : v2
09-13 16:33:21.554  7208  7208 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:21.554  7208  7208 I libpersona: KNOX_SDCARD not a persona,
,09-13 16:33:21.554  7208  7208 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 16:33:21.564  7208  7208 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:21.564  7208  7208 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:21.564  1018  1044 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7208 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:33:21.574  1018  1481 I ActivityManager: Killing 6861:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-13 16:33:21.574  1018  1478 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 16:33:21.574  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.574  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:21.604  7208  7208 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:21.604  7208  7208 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:21.624  1018  6724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:21.624  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:21.624  1018  6724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.624  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 16:33:21.634  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.634  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:21.634  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.634  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:21.644  1018  1556 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-13 16:33:21.644  1018  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.644  7208  7208 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-13 16:33:21.644  7208  7208 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-13 16:33:21.644  7208  7208 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-13 16:33:21.644  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:21.664  7208  7208 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-13 16:33:21.664  7208  7208 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-13 16:33:21.664  7208  7208 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 16:33:21.664  7208  7208 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REPLACED
09-13 16:33:21.664  7208  7208 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_PACKAGE_REPLACED_START
,09-13 16:33:21.664  1018  1481 I splitIntent: Split this intent : android.intent.action.PACKAGE_REPLACED, mSplitNum[0]=5, mSplitNum[1]=9, mSplitNum[2]=13, mBgSplitQueueNum=3 divideNum= 4 r.nextReceiver= 1 receivers.size=17
,09-13 16:33:21.664  1018  1481 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REPLACED !! Enqueue -> schedule it!!
,09-13 16:33:21.674  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-13 16:33:21.674  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:21.674  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:21.674  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:21.674  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:21.674  6968  6968 D Compatibility: onReceive() it will make start service
,09-13 16:33:21.684  7223  7223 E Zygote  : MountEmulatedStorage(),
09-13 16:33:21.684  7223  7223 E Zygote  : v2
09-13 16:33:21.684  7223  7223 I libpersona: KNOX_SDCARD checking this for 10110
09-13 16:33:21.684  7223  7223 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:21.684  7223  7223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:21.694  7223  7223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 16:33:21.694  7223  7223 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:33:21.694  1018  1044 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=7223 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 16:33:21.704  6616  6698 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-13 16:33:21.704  6616  6698 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:33:21.704  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:21.704  6616  6698 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 16:33:21.704  6616  6698 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-13 16:33:21.704  1018  6724 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,09-13 16:33:21.704  1018  6724 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-13 16:33:21.704  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:21.704  1018  6724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:21.704  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-13 16:33:21.714  6616  6698 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-13 16:33:21.714  6616  6698 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 16:33:21.714  6616  6698 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 16:33:21.714  6616  6698 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:33:21.714  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:21.714  6616  6698 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 16:33:21.744  7223  7223 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:21.744  7223  7223 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:21.754  6616  6698 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 16:33:21.754  6616  6698 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:33:21.754  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:21.764  6845  7152 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:33:21.764  6845  7152 I jxcore-log: 
,09-13 16:33:21.764  6845  7152 W jxcore-log: JXcore engine is started
,09-13 16:33:21.764  6616  6698 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 16:33:21.764  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:21.764  6616  6698 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-13 16:33:21.774  1018  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:21.774  1018  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.774  1018  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:21.774  1018  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.774  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:21.774  6845  7114 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 16:33:21.774  4744  6717 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-13 16:33:21.774  6845  6845 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 16:33:21.784  6968  7238 D Compatibility: onHandleIntent()
,09-13 16:33:21.784  6968  7238 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REPLACED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,09-13 16:33:21.794  1018  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:21.794  1018  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.794  1018  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:21.794  1018  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:21.794  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:21.824  4744  4744 D AsyncTaskServiceImpl: Submit a task: nzm
,09-13 16:33:21.824  1018  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:21.824  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:21.824  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.824  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:21.834  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:21.834  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.834  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:21.834  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.834  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:21.834  1018  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:21.834  1018  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:33:21.834  1018  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:21.844  1018  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.844  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 16:33:21.844  6968  7238 D Compatibility: found: 2
09-13 16:33:21.844  6968  7238 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-13 16:33:21.844  6968  7238 D Compatibility: skipping ResolveInfo{b0e3c18 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-13 16:33:21.844  6968  7238 D Compatibility: considering ResolveInfo{1def1671 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-13 16:33:21.844  6968  7238 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 16:33:21.854  6968  7238 D Compatibility: enabling receiver ResolveInfo{24092c56 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000},
,09-13 16:33:21.864  4744  6717 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest,
09-13 16:33:21.864  2006  2006 E NetworkScheduler.SR: Invalid parameter app
09-13 16:33:21.864  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:21.864  2006  2006 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?,
,09-13 16:33:21.864  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 16:33:21.864  6968  7238 D Compatibility: enabling receiver ResolveInfo{3ee44d7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000},
09-13 16:33:21.864  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:21.864  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.864  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,09-13 16:33:21.864  6616  6698 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
09-13 16:33:21.864  6616  6698 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:33:21.864  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:21.864  6616  6698 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-13 16:33:21.864  6616  6698 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 16:33:21.874  6616  6698 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
09-13 16:33:21.874  6616  6698 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 16:33:21.874  4744  5116 D nzm     : Processing package: com.test.thalitest,
09-13 16:33:21.874  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
09-13 16:33:21.874  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
09-13 16:33:21.884  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:21.884  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.884  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:21.884  6968  7238 D Compatibility: enabling receiver ResolveInfo{1ab701c4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 16:33:21.884  1018  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:21.884  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:21.884  6616  6698 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 16:33:21.884  6616  6698 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 16:33:21.894  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:21.894  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:21.894  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 16:33:21.904  6968  7238 D Compatibility: enabling receiver ResolveInfo{40da8ad com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 16:33:21.914  6616  6698 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
09-13 16:33:21.914  6616  6698 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 16:33:21.914  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:21.914  6616  6698 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 16:33:21.914  6923  6923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:168 android.app.ActivityThread.handleReceiver:3125 ,
,09-13 16:33:21.934  1018  1347 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu,
,09-13 16:33:21.934  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
09-13 16:33:21.934  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:21.934  1018  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:21.934  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-13 16:33:21.944  6616  6698 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-13 16:33:21.944  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:21.944  6616  6698 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 16:33:21.944  6616  6698 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 16:33:21.954  6968  7238 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-13 16:33:22.014  6616  6698 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-13 16:33:22.014  6616  6698 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:33:22.014  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:22.024  6616  6698 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 16:33:22.034  6682  6720 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-13 16:33:22.034  6616  6698 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,09-13 16:33:22.044  1018  1478 I ActivityManager: Killing 6798:com.android.mms/u0a41 (adj 15): empty #21
,09-13 16:33:22.084  6616  6698 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 16:33:22.084  6616  6698 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-13 16:33:22.084  6616  6698 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 16:33:22.084  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:22.084  6616  6698 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 16:33:22.094  4744  5116 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-13 16:33:22.094  4744  5116 D nzm     : Found info for package com.test.thalitest in db.
,09-13 16:33:22.094  6682  6720 I AcmsKeyStoreHelper: Key Store exist
,09-13 16:33:22.094  6682  6720 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-13 16:33:22.104  1018  1347 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:22.104  6616  6698 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-13 16:33:22.104  6616  6698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:22.104  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:22.104  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:22.104  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:22.104  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:22.114  1018  6724 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-13 16:33:22.124  1018  6724 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-13 16:33:22.124  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:22.124  1018  6724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:22.124  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-13 16:33:22.124  1018  1478 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 16:33:22.124  1018  1306 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:22.124  1018  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:22.124  1018  1306 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:22.124  1018  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:22.124  1018  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:22.144  1018  4349 D CountryDetector: No listener is left
,09-13 16:33:22.244  6682  6720 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-13 16:33:22.244  6682  6720 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-13 16:33:22.244  6682  6720 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-13 16:33:22.244  6682  6720 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:33:22.244  6682  6720 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-13 16:33:22.244  6682  6720 D AcmsCertificateMngr: handleAppRemoved() Enter com.test.thalitest
,09-13 16:33:22.244  1018  1481 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-13 16:33:22.244  6682  6720 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.provider: com.samsung.android.mirrorlink.acms.provider.AcmsDbProvider
,09-13 16:33:22.254  6682  6720 D AcmsAppEntryInterface: App not found in DB Hence ignore
09-13 16:33:22.254  6682  6720 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>5
09-13 16:33:22.254  6682  6720 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:33:22.254  6682  6720 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-13 16:33:22.254  6682  6720 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-13 16:33:22.264  6682  6720 D AcmsCore: This is NOT a valid MirrorLink app
09-13 16:33:22.264  6682  6720 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-13 16:33:22.264  6682  6720 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 16:33:22.264  6682  6720 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-13 16:33:22.264  6682  6720 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-13 16:33:22.264  6682  6682 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 16:33:22.264  6682  6682 D AcmsService: Enter onDestroy
09-13 16:33:22.264  6682  6682 I AcmsService: cleanUp(): inside service clean up
09-13 16:33:22.264  6682  6682 D AcmsCore: AcmsCore: inside DeInit
09-13 16:33:22.264  6682  6682 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-13 16:33:22.264  6682  6682 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-13 16:33:22.264  6682  6682 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-13 16:33:22.264  6682  6682 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-13 16:33:22.264  6682  6682 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-13 16:33:22.264  6682  6682 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 16:33:22.264  6682  6682 D AcmsService: killing acms process
09-13 16:33:22.264  6682  6682 I Process : Sending signal. PID: 6682 SIG: 9
,09-13 16:33:22.304   258   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 16:33:22.304   258   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 16:33:22.304  7223  7246 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 16:33:22.314   258   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 16:33:22.314   258   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 16:33:22.314  7223  7246 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 16:33:22.324  7223  7223 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 16:33:22.324  7223  7223 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 16:33:22.324  7223  7223 I GAv4    :   adb logcat -s GAv4
,09-13 16:33:22.324   258   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 16:33:22.324   258   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 16:33:22.334  7223  7247 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 16:33:22.334   258   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 16:33:22.334   258   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 16:33:22.344  7223  7247 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 16:33:22.344  7223  7223 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:22.354  1018  1481 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 16:33:22.364  1018  4349 I ActivityManager: Process ACMS.Process (pid 6682)(adj 0) has died(30,756)
,09-13 16:33:22.374  1018  3384 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:22.374  7223  7223 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:22.384  7223  7249 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:33:22.394  5939  5939 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-13 16:33:22.394  5939  5939 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 16:33:22.444  5939  5939 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 16:33:22.544  1018  7092 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-13 16:33:22.544  1018  7092 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-13 16:33:22.544  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:22.544  1018  7092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:22.544  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 16:33:22.544  5939  5939 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(743): Logging device features
,09-13 16:33:22.554  1018  6724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:22.564  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 16:33:22.564  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:22.564  1018  6724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:22.564  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 16:33:22.574  5939  5939 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(59): Cancelling accelerated self-Update check
,09-13 16:33:22.584  5939  5939 W InstanceID/Rpc: Found 10011
,09-13 16:33:22.614  2006  2018 D DeviceConnectionService: client connected with version: 9080000
,09-13 16:33:22.624  1018  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:22.624  1018  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:22.624  1018  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:22.624  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:22.634  5939  5939 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-13 16:33:22.634  5939  5939 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=hygiene due to Gms not connected
,09-13 16:33:22.634  1018  1556 I ActivityManager: Killing 6893:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-13 16:33:22.684  1018  6724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:22.694  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:22.694  1018  6724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:22.694  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-13 16:33:22.714  7223  7223 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-13 16:33:22.734  7223  7223 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 8124-8126)
09-13 16:33:22.734  7223  7223 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 16:33:22.744  7223  7223 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {acf03bb}
,09-13 16:33:22.744  7223  7223 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 16:33:22.744  7223  7223 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 16:33:22.764  7223  7223 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 16:33:22.764  7223  7223 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:33:22.774  7223  7223 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 16:33:22.784  7223  7223 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 16:33:22.784  7223  7223 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 16:33:22.784  7223  7223 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 16:33:22.784  7223  7223 I Adreno-EGL: Local Branch: 
09-13 16:33:22.784  7223  7223 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 16:33:22.784  7223  7223 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 16:33:22.784  7223  7223 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 16:33:22.854  7223  7277 W cr.media: Requires BLUETOOTH permission
,09-13 16:33:22.854  7223  7223 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 16:33:22.864  7223  7223 I NSApplication: Starting up...
,09-13 16:33:22.864  1018  1481 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 16:33:22.874  1018  1478 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 16:33:22.874  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-13 16:33:22.874  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:22.874  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:22.874  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:22.874  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:22.894  7282  7282 E Zygote  : MountEmulatedStorage()
,09-13 16:33:22.894  7282  7282 E Zygote  : v2
09-13 16:33:22.894  7282  7282 I libpersona: KNOX_SDCARD checking this for 10121
09-13 16:33:22.894  7282  7282 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:22.894  7282  7282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:22.894  1018  1136 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7282 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-13 16:33:22.894  1018  1136 I ActivityManager: Killing 6939:com.wsomacp/u0a23 (adj 15): empty #21
09-13 16:33:22.894  1018  1136 I ActivityManager: Killing 6876:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #22,
,09-13 16:33:22.894  7282  7282 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:22.894  7282  7282 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 16:33:22.924  7282  7282 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:22.924  7282  7282 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:22.934  7282  7282 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 16:33:22.934  7282  7282 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 16:33:22.934  7282  7282 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 16:33:22.954  7282  7282 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.PACKAGE_REPLACED
,09-13 16:33:22.954  6665  6665 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-13 16:33:22.964  6665  6665 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REPLACED / mCurIndex :-10
,09-13 16:33:22.964  6665  6665 I TapandpayWidget:Utils: Clear T&P info.
,09-13 16:33:22.964  6665  6665 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-13 16:33:22.964  1018  1136 I ActivityManager: Killing 6908:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-13 16:33:22.984  2475  2475 D daemonapp: [MSC_Daemon]>>> AWDCDS:28 [0:0] AWD CD Act : androidintentactionPACKAGE_REPLACED
,09-13 16:33:22.984  1018  1030 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REPLACED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.,
,09-13 16:33:22.994  1018  1018 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,09-13 16:33:22.994  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,09-13 16:33:23.004  1018  1388 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:33:23.004  1018  1388 D AlarmManagerService: Setting time of day to sec=1473777203
,09-13 16:33:23.004  1018  1388 D AlarmManagerService: Trying to open a file
,09-13 16:33:23.004  1018  1388 D AlarmManagerService: File Open Success
,09-13 16:33:23.014  1018  1388 D AlarmManagerService: File Close Success
09-13 16:33:23.014  1018  1388 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,09-13 16:33:23.820  1018  1097 V AlarmManager: waitForAlarm result :65536
09-13 16:33:23.820  1018  1388 W AlarmManagerService: Unable to set rtc to 1473777203: Invalid argument
,09-13 16:33:23.820  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:23.820  1018  1018 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:23.820  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:23.820  1018  1018 I BackgroundCompactionService: onStart. jobID=801
,09-13 16:33:23.820  1018  1097 V AlarmManager: No more alarm at this time.nowELAPSED=88407 batch.start=93309
09-13 16:33:23.820  1018  1044 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 16:33:23.820  1018  1018 I BackgroundCompactionService: onStart done. jobID=801
09-13 16:33:23.820  1018  1044 W ActivityManager: Failed to update preferences for: com.google.android.partnersetup
,09-13 16:33:23.820  1018  7297 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,09-13 16:33:23.820  1018  1018 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1473777203838
,09-13 16:33:23.829  1018  7297 I BackgroundCompactionService: compact_memory command done
,09-13 16:33:23.829  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
09-13 16:33:23.829  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 16:33:23.829  1018  1018 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,09-13 16:33:23.839  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 16:33:23.839  1018  1018 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,09-13 16:33:23.839  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 16:33:23.859  1018  1018 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 16:33:23.869  1018  1472 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-13 16:33:23.869  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:33:23.869  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
09-13 16:33:23.869  1018  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,09-13 16:33:23.869  1018  1472 W ActivityManager: userId = 0, bbcId = -10000,
09-13 16:33:23.869  1018  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:23.869  1018  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 16:33:23.879  1018  1018 I DrmEventService:  no response from SecureClock 
,09-13 16:33:23.879  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:23.879  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:23.879  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 16:33:23.889  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:33:23.889  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:33:23.889  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 16:33:23.889  5939  7299 I Finsky  : [1065] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,09-13 16:33:23.899  1018  1018 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
09-13 16:33:23.899  1018  1018 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,09-13 16:33:23.899  5939  6041 I PlayCommon: [1047] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 16:33:23.899  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,09-13 16:33:23.899  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:23.899  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:23.899  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:23.899  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:23.909  5939  7300 I PlayCommon: [1066] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-13 16:33:23.909  5939  7300 I PlayCommon: [1066] com.google.android.play.a.l.e(789): No file ready to send
,09-13 16:33:23.919  7301  7301 E Zygote  : MountEmulatedStorage()
,09-13 16:33:23.919  7301  7301 E Zygote  : v2,
,09-13 16:33:23.919  7301  7301 I libpersona: KNOX_SDCARD checking this for 10058
09-13 16:33:23.919  7301  7301 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:23.919  7301  7301 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:23.919  7301  7301 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 16:33:23.919  7301  7301 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:33:23.919  1018  1044 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7301 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 16:33:23.919  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-13 16:33:23.919  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:23.919  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:23.919  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:23.919  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:23.929  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,09-13 16:33:23.929  1018  1480 D SettingsProvider: name = lockscreen_zoom_panning_effect
,09-13 16:33:23.929  1018  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 16:33:23.929  1018  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 16:33:23.929  1018  1480 D SettingsProvider: selectionArgs: false
09-13 16:33:23.929  1018  1480 D SettingsProvider: selectionArgs: 10049
09-13 16:33:23.929  1018  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 16:33:23.929  1018  1480 D SettingsProvider: ret = -1
,09-13 16:33:23.929  1178  1178 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,09-13 16:33:23.939  4744  5002 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-13 16:33:23.939  7311  7311 E Zygote  : MountEmulatedStorage()
09-13 16:33:23.939  7311  7311 E Zygote  : v2
09-13 16:33:23.939  7311  7311 I libpersona: KNOX_SDCARD checking this for 10008
09-13 16:33:23.939  7311  7311 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:23.939  7311  7311 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:23.939  1178  1178 D KeyguardEffectViewController: isPreloadedWallpaper=true
09-13 16:33:23.939  1178  1178 I GeometricMosaic_Keyguard: update
,09-13 16:33:23.949  7311  7311 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:23.949  1178  1178 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null,
09-13 16:33:23.949  7311  7311 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 16:33:23.949  1018  1018 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7311 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 16:33:23.949  1018  7092 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 16:33:23.949  1018  7092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 16:33:23.959  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,09-13 16:33:23.959  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:23.959  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:23.959  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:23.959  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:23.969  7327  7327 E Zygote  : MountEmulatedStorage()
,09-13 16:33:23.969  7327  7327 I libpersona: KNOX_SDCARD checking this for 10131
09-13 16:33:23.969  7327  7327 E Zygote  : v2
09-13 16:33:23.969  7327  7327 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:23.969  7327  7327 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:23.979  7327  7327 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:23.979  7327  7327 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:23.979  1018  1044 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7327 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-13 16:33:23.989  7311  7311 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:23.989  7311  7311 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:23.989  7301  7301 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:33:23.989  7301  7301 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:23.999  2475  2475 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
09-13 16:33:23.999  2475  2475 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-13 16:33:23.999  2475  2475 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
09-13 16:33:23.999  2475  2475 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 16:33:24.029  2475  2475 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,09-13 16:33:24.029  7327  7327 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:24.029  7327  7327 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:24.049  2475  2475 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true,
,09-13 16:33:24.049  2475  2475 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================,
09-13 16:33:24.049  2475  2475 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
09-13 16:33:24.049  2475  2475 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 16:33:24.049  2475  2475 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================,
09-13 16:33:24.049  2475  2475 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,09-13 16:33:24.079  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:24.099  5939  6041 I PlayCommon: [1047] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,09-13 16:33:24.109  7327  7327 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 16:33:24.109  7327  7327 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:33:24.109  7327  7327 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:24.119  1178  1178 I KeyguardEffectViewUtil: set current wallpaper info
,09-13 16:33:24.119  1018  1556 D SettingsProvider: name = keyguard_current_wallpaper_type
,09-13 16:33:24.119  1018  1556 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-13 16:33:24.119  1018  1556 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-13 16:33:24.119  1018  1556 D SettingsProvider: selectionArgs: false
09-13 16:33:24.119  1018  1556 D SettingsProvider: selectionArgs: 10049
,09-13 16:33:24.119  1018  1556 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-13 16:33:24.119  1018  1556 D SettingsProvider: ret = -1
,09-13 16:33:24.119  5939  6041 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-13 16:33:24.119  5939  6041 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 16:33:24.119  5939  6041 I System.out: (HTTPLog)-Static: isShipBuild true
09-13 16:33:24.119  5939  6041 I System.out: (HTTPLog)-Thread-1047-525982554: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-13 16:33:24.119  5939  6041 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:33:24.119   279   921 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 16:33:24.119   279   921 D Netd    : getNetworkForDns: using netid 502 for uid 10026
,09-13 16:33:24.129  1018  1472 D SettingsProvider: name = keyguard_current_wallpaper_file_path
09-13 16:33:24.129  1018  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 16:33:24.129  1018  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 16:33:24.129  1018  1472 D SettingsProvider: selectionArgs: false
09-13 16:33:24.129  1018  1472 D SettingsProvider: selectionArgs: 10049
09-13 16:33:24.129  1018  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 16:33:24.129  1018  1472 D SettingsProvider: ret = -1
,09-13 16:33:24.129  1018  1480 D SettingsProvider: name = keyguard_current_wallpaper_res_id
09-13 16:33:24.129  1018  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 16:33:24.129  1018  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 16:33:24.129  1018  1480 D SettingsProvider: selectionArgs: false
09-13 16:33:24.129  1018  1480 D SettingsProvider: selectionArgs: 10049
09-13 16:33:24.129  1018  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 16:33:24.129  1018  1480 D SettingsProvider: ret = -1
,09-13 16:33:24.169  2475  2489 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 16:33:24.179  1018  1347 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-13 16:33:24.179  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-13 16:33:24.179  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:24.179  1018  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:24.179  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 16:33:24.189  2475  2475 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-13 16:33:24.189  7301  7301 I ExternalOEMControlProvider: onCreate
,09-13 16:33:24.199  2475  2475 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,09-13 16:33:24.209  2475  2475 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,09-13 16:33:24.209  1178  1705 D TEST    : run!!!
,09-13 16:33:24.209  2475  2475 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-13 16:33:24.209  2475  2475 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,09-13 16:33:24.219  2475  2475 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-13 16:33:24.219  2475  2475 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,09-13 16:33:24.229  1178  1705 I GeometricMosaic_Renderer: setBackgroundBitmap
,09-13 16:33:24.239  1018  1136 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-13 16:33:24.239  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-13 16:33:24.239  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:24.239  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 16:33:24.239  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 16:33:24.239  1018  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-13 16:33:24.239  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.239  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.239  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.239  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.249  5939  6041 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 16:33:24.259  7354  7354 E Zygote  : MountEmulatedStorage(),
09-13 16:33:24.259  7354  7354 E Zygote  : v2
09-13 16:33:24.259  7354  7354 I libpersona: KNOX_SDCARD checking this for 1000,
09-13 16:33:24.259  7354  7354 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:24.259  7354  7354 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:24.259  1018  1481 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7354 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:33:24.259  7354  7354 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 16:33:24.259  7354  7354 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:24.259  1018  1556 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,09-13 16:33:24.269  2475  2475 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET,
09-13 16:33:24.269  1018  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.269  2475  2475 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0,
09-13 16:33:24.269  1018  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.269  1018  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.269  1018  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.279  1018  1556 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7362 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-13 16:33:24.289  7362  7362 E Zygote  : MountEmulatedStorage(),
09-13 16:33:24.289  7362  7362 E Zygote  : v2
09-13 16:33:24.289  7362  7362 I libpersona: KNOX_SDCARD checking this for 10037,
09-13 16:33:24.289  7362  7362 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:24.289  7362  7362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-13 16:33:24.299  7362  7362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:24.299  7362  7362 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 16:33:24.329  1791  1791 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,09-13 16:33:24.329  4744  5002 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-13 16:33:24.349  7354  7354 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:24.349  1791  1791 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-13 16:33:24.349  1018  6724 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,09-13 16:33:24.349  7354  7354 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:24.359  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.359  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.359  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.359  1018  6724 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.359  7362  7362 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:24.369  7362  7362 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:24.379  7385  7385 E Zygote  : MountEmulatedStorage()
09-13 16:33:24.379  7385  7385 E Zygote  : v2
09-13 16:33:24.379  7385  7385 I libpersona: KNOX_SDCARD checking this for 10081
09-13 16:33:24.379  7385  7385 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:24.379  7385  7385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:24.379  1018  6724 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7385 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 16:33:24.379  7385  7385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:24.379  7385  7385 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:24.389  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:24.389  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:24.399  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:24.399  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:24.419  7311  7311 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-13 16:33:24.419  7385  7385 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:24.419  7385  7385 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:24.449  1018  1478 I art     : Explicit concurrent mark sweep GC freed 28613(1572KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/37MB, paused 3.142ms total 223.178ms
,09-13 16:33:24.449  7362  7362 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,09-13 16:33:24.469  1018  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:24.469  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,09-13 16:33:24.469  7301  7353 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,09-13 16:33:24.469  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:24.469  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:24.469  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:24.469  7385  7385 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-13 16:33:24.469  7311  7311 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
09-13 16:33:24.469  7385  7385 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 16:33:24.469  7385  7385 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:33:24.469  7385  7385 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:24.469  7385  7385 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-13 16:33:24.489  2900  2900 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Sep 13 16:33:24 GMT+02:00 2016
,09-13 16:33:24.489  1018  1481 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-13 16:33:24.489  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-13 16:33:24.489  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:24.489  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:24.489  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-13 16:33:24.499  2900  2900 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-13 16:33:24.499  1018  1472 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-13 16:33:24.499  1018  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.499  1018  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.499  1018  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.499  1018  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.499  7362  7362 I CalendarProvider2: CalendarProvider2.onCreate() called
,09-13 16:33:24.499  2900  2900 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-13 16:33:24.509  2900  2900 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 16:33:24.509  7403  7403 E Zygote  : MountEmulatedStorage(),
09-13 16:33:24.509  7403  7403 E Zygote  : v2
09-13 16:33:24.509  7403  7403 I libpersona: KNOX_SDCARD checking this for 10036,
09-13 16:33:24.509  7403  7403 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:24.509  7403  7403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:24.519  1018  1472 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=7403 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-13 16:33:24.519  7403  7403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 16:33:24.519  7403  7403 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-13 16:33:24.529  5939  6041 I PlayCommon: [1047] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,09-13 16:33:24.529  2900  2900 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 16:33:24.539  7403  7403 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:24.539  5939  6041 I PlayCommon: [1047] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-13 16:33:24.539  5939  6041 I PlayCommon: [1047] com.google.android.play.a.l.e(789): No file ready to send
,09-13 16:33:24.539  7403  7403 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:24.549  7354  7354 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 16:33:24.549  7354  7354 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-13 16:33:24.549  7354  7354 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 16:33:24.549  1018  1478 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,09-13 16:33:24.559  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.559  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.559  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.559  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.569  1018  1478 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7419 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,09-13 16:33:24.569  2900  7401 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
09-13 16:33:24.569  1018  1478 I ActivityManager: Killing 6990:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-13 16:33:24.579  2900  7401 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
09-13 16:33:24.579  7419  7419 I libpersona: KNOX_SDCARD checking this for 10153
09-13 16:33:24.579  7419  7419 E Zygote  : MountEmulatedStorage()
09-13 16:33:24.579  7419  7419 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:24.579  7419  7419 E Zygote  : v2
,09-13 16:33:24.579  7419  7419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:24.579  2900  7401 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Sep 13 16:33:24 GMT+02:00 2016
,09-13 16:33:24.579  7419  7419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:24.579  7419  7419 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:24.589   289   289 E SMD     : DCD OFF,
,09-13 16:33:24.599  2900  7401 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,09-13 16:33:24.599  7419  7419 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:24.599  7419  7419 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:24.599  2900  2900 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-13 16:33:24.619   308   308 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 44.067ms
,09-13 16:33:24.619  7403  7403 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@179b5e32
,09-13 16:33:24.629  1018  1479 I ActivityManager: Killing 7136:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-13 16:33:24.629  1018  1479 I ActivityManager: Killing 6756:com.sec.android.gallery3d/u0a39 (adj 15): empty #22
,09-13 16:33:24.629   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.714ms
,09-13 16:33:24.639  7419  7419 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:24.649   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 18.532ms,
,09-13 16:33:24.669  7403  7403 I SA      : [SSP] onCreated
,09-13 16:33:24.679  1018  1306 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,09-13 16:33:24.679  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.679  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.679  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.679  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.689  7435  7435 E Zygote  : MountEmulatedStorage()
,09-13 16:33:24.689  7435  7435 E Zygote  : v2
09-13 16:33:24.689  7435  7435 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:33:24.689  7435  7435 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:24.699  7435  7435 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:24.699  1018  1306 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:33:24.699  1018  1306 I ActivityManager: Killing 7154:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
09-13 16:33:24.699  7435  7435 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:24.699  7435  7435 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:24.719  1018  4349 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
09-13 16:33:24.719  1018  4349 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-13 16:33:24.719  1018  4349 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:24.719  1018  4349 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:24.719  1018  4349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-13 16:33:24.719  7435  7435 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:24.729  7435  7435 D ActivityThread: Added TimaKeyStore provider
09-13 16:33:24.729  7403  7403 I SA      : [TPM] There is no property file
,09-13 16:33:24.729  7403  7403 I SA      : [SCU] isHaveSA() - false
,09-13 16:33:24.739  7403  7403 I SA      : [TPM] getModelProperty : null
09-13 16:33:24.739  7403  7403 I SA      : [TPM] getCSCProperty : null
,09-13 16:33:24.739  7403  7403 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-13 16:33:24.739  7403  7403 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-13 16:33:24.739  7403  7403 I SA      : [DM] TFT FEATURE: false
,09-13 16:33:24.759  1018  1478 D SettingsProvider: name = next_alarm_formatted
09-13 16:33:24.759  1018  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 16:33:24.759  1018  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 16:33:24.759  1018  1478 D SettingsProvider: selectionArgs: false
09-13 16:33:24.759  1018  1478 D SettingsProvider: selectionArgs: 10081
09-13 16:33:24.759  1018  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 16:33:24.759  1018  1478 D SettingsProvider: ret = -1
,09-13 16:33:24.769  7403  7403 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,09-13 16:33:24.769  7403  7403 I SA      : [DM] init START
,09-13 16:33:24.779  7403  7403 I SA      : [DM] This device is not a Vodafone
,09-13 16:33:24.779  7435  7435 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473777204792
09-13 16:33:24.779  7435  7435 D         : TimeServiceNative: User Time to be set is 1473777204792
09-13 16:33:24.779  7435  7435 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-13 16:33:24.779  7435  7435 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-13 16:33:24.779  7435  7435 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473777204792
,09-13 16:33:24.779   329   571 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-13 16:33:24.779  7435  7435 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-13 16:33:24.779   329  7455 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473777204792
09-13 16:33:24.779   329  7455 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473777204792, operation = 0
,09-13 16:33:24.779   329  7455 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/11/71 18:8:41
09-13 16:33:24.779   329  7455 D QC-time-services: Daemon:Value read from RTC seconds = 37562921000
09-13 16:33:24.779   329  7455 D QC-time-services: Daemon:new time 1473777204792 
09-13 16:33:24.779   329  7455 D QC-time-services: Daemon: delta 1436214283792 genoff 1436214283792 
09-13 16:33:24.779   329  7455 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214283792 to memory
09-13 16:33:24.779   329  7455 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-13 16:33:24.779   329  7455 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-13 16:33:24.779  7403  7403 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-13 16:33:24.779  7403  7403 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
09-13 16:33:24.779  7403  7403 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-13 16:33:24.779  7403  7403 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-13 16:33:24.789  7403  7403 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-13 16:33:24.799  7403  7403 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-13 16:33:24.799  7403  7403 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-13 16:33:24.799  7403  7403 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-13 16:33:24.799  7403  7403 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-13 16:33:24.799  7403  7403 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-13 16:33:24.799  7403  7403 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-13 16:33:24.809  7403  7403 I SA      : [SCU] isHaveSA() - false
09-13 16:33:24.809   329  7455 D QC-time-services: Updating the TOD offset
09-13 16:33:24.809   329  7455 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214283792 to memory
09-13 16:33:24.809   329  7455 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-13 16:33:24.809   329  7455 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-13 16:33:24.809  7403  7403 I SA      : support phone number id : false
,09-13 16:33:24.809  7403  7403 I SA      : [DM] Supports Ref Jpn : true
09-13 16:33:24.809  7403  7403 I SA      : [DM] init END
,09-13 16:33:24.809   329  7455 E QC-time-services: Daemon:Update to modem bit set
09-13 16:33:24.809   329  7455 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-13 16:33:24.809   329  7455 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249483792
,09-13 16:33:24.809  7435  7435 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,09-13 16:33:24.809  1018  1347 I ActivityManager: Killing 7169:com.samsung.helphub/1000 (adj 15): empty #21
09-13 16:33:24.809   329   569 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,09-13 16:33:24.809   329   571 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-13 16:33:24.819  1018  1472 I ActivityManager: Killing 7186:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-13 16:33:24.859  1018  1479 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,09-13 16:33:24.859  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.859  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:24.859  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.859  1018  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:24.869  7457  7457 E Zygote  : MountEmulatedStorage(),
09-13 16:33:24.869  7457  7457 I libpersona: KNOX_SDCARD checking this for 10041
09-13 16:33:24.869  7457  7457 E Zygote  : v2
09-13 16:33:24.869  7457  7457 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:24.869  7457  7457 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:24.869  1018  1479 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=7457 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
09-13 16:33:24.869  1018  1479 I ActivityManager: Killing 7208:com.sec.pcw.device/1000 (adj 15): empty #21
,09-13 16:33:24.879  7457  7457 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:24.879  7457  7457 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 16:33:24.899  7457  7457 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:24.899  7457  7457 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:24.919  7457  7457 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-13 16:33:24.919  7457  7457 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 16:33:24.919  7457  7457 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:24.919  7385  7385 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 139.958ms
,09-13 16:33:24.919  7457  7457 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 16:33:24.919  7457  7457 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-13 16:33:24.949  7457  7457 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,09-13 16:33:25.019  1018  4349 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-13 16:33:25.029  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-13 16:33:25.029  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:25.029  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-13 16:33:25.029  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:25.039  1018  4349 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7473 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-13 16:33:25.039  1018  4349 I ActivityManager: Killing 6616:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,09-13 16:33:25.039  7473  7473 E Zygote  : MountEmulatedStorage()
09-13 16:33:25.039  7473  7473 E Zygote  : v2
09-13 16:33:25.039  7473  7473 I libpersona: KNOX_SDCARD checking this for 10090
09-13 16:33:25.039  7473  7473 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:25.039  7473  7473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:25.049  7473  7473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:25.049  7473  7473 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:25.069  7473  7473 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:25.069  7473  7473 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:25.089  7473  7473 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,09-13 16:33:25.089  7473  7473 D elm:15121: ELMEngine.ELMEngine( context ).
,09-13 16:33:25.089  7473  7473 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-13 16:33:25.099  1018  1479 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-13 16:33:25.099  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-13 16:33:25.099  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:25.099  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:25.099  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-13 16:33:25.099  7473  7473 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,09-13 16:33:25.099  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,09-13 16:33:25.099  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:25.109  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:25.109  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:25.109  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:25.109  7473  7473 D elm:15121: ElmAgentService : onCreate()
,09-13 16:33:25.109  7473  7488 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,09-13 16:33:25.109  7457  7457 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 123.111ms
,09-13 16:33:25.119  7490  7490 E Zygote  : MountEmulatedStorage()
09-13 16:33:25.119  7490  7490 E Zygote  : v2
,09-13 16:33:25.119  7490  7490 I libpersona: KNOX_SDCARD checking this for 10130
09-13 16:33:25.119  7490  7490 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:25.119  7490  7490 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:25.119  1018  1031 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7490 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,09-13 16:33:25.119  7490  7490 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 16:33:25.119  7473  7488 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
09-13 16:33:25.119  7490  7490 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-13 16:33:25.129  7473  7473 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,09-13 16:33:25.129  7473  7473 D elm:15121: ModuleBase.ModifySetAlarm()
09-13 16:33:25.129  7473  7473 D elm:15121: MDMBridge.getInstance()
09-13 16:33:25.129  7473  7473 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-13 16:33:25.129  7473  7473 D elm:15121: ElmAgentService : onDestroy().
,09-13 16:33:25.129  1018  1499 I ActivityManager: Killing 7007:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-13 16:33:25.159  7490  7490 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:25.159  7490  7490 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:25.169  7490  7490 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:25.169  7490  7490 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-13 16:33:25.189  1018  7092 I ActivityManager: Killing 6968:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-13 16:33:25.199  7457  7505 D Mms/ArtClassLoader: init before art
,09-13 16:33:25.209  7457  7457 D Mms/TelephonyPermission: start operation mode monitor
,09-13 16:33:25.209  7457  7457 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 16:33:25.219  7457  7457 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 16:33:25.219  7457  7457 D Mms/TelephonyPermission: isDefault true
,09-13 16:33:25.219  7457  7457 D Mms/MmsApp: onCreate() com.android.mms
,09-13 16:33:25.259  7457  7457 D Mms/MmsApp: [start]    initCountryIso consume time = 314.477448
,09-13 16:33:25.259  1018  6724 D CountryDetector: The first listener is added
,09-13 16:33:25.269  7457  7457 D Mms/MmsApp: [end]    initCountryIso consume time = 7.246979
,09-13 16:33:25.269  7457  7457 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.326302
,09-13 16:33:25.269  7457  7457 D Mms/MmsConfig: before partial update
,09-13 16:33:25.289  7457  7457 D Mms/MmsConfig: Load Resize quality : 80
,09-13 16:33:25.289  7457  7457 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,09-13 16:33:25.289  7457  7457 D EasySignUpManager_1.0.1: isAuth is false
,09-13 16:33:25.289  7457  7457 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,09-13 16:33:25.299  1455  1470 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7457
,09-13 16:33:25.299  1455  1470 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.846 ms
,09-13 16:33:25.309  7457  7457 D EasySignUpManager_1.0.1: isAuth is false
,09-13 16:33:25.309  7457  7457 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,09-13 16:33:25.309  7457  7457 E CscParser: mps_code.dat does not exist
,09-13 16:33:25.309  7457  7457 E CscParser: customer_path =/system/csc/customer.xml
09-13 16:33:25.309  7457  7457 E CscParser: fileName + /system/csc/customer.xml
,09-13 16:33:25.319  7457  7457 E CscParser: mps_code.dat does not exist
,09-13 16:33:25.319  7457  7457 E CscParser: customer_path =/system/csc/customer.xml
09-13 16:33:25.319  7457  7457 E CscParser: fileName + /system/csc/customer.xml
,09-13 16:33:25.329  7457  7457 D CscParser: getInstance fileName =/system/csc/customer.xml
,09-13 16:33:25.329  7457  7457 D Mms/MmsConfig:  enable multiwindow = false
,09-13 16:33:25.339  7457  7457 E Mms/MessageUtils: setCountryDetector : update country detector info 
,09-13 16:33:25.339  7457  7457 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-13 16:33:25.349  7457  7457 D Mms/MmsConfig: [end]    init() consume time = 77.963177
,09-13 16:33:25.349  7457  7457 D Mms/Contact: [start]    init() consume time = 1.25
,09-13 16:33:25.359  7457  7457 D Mms/Contact: [end]    init consume time = 10.98724
,09-13 16:33:25.359  1455  2029 D TP/MmsSmsProvider: query,matched:13, calling pid = 7457
,09-13 16:33:25.369  1455  2029 D TP/MmsSmsProvider: match 13:Elapsed time : 1.417 ms
,09-13 16:33:25.369  7457  7511 D Mms/DraftCache: [start]    rebuildCache consume time = 11.550573
,09-13 16:33:25.369  7457  7457 D Mms/MethodReflector: getSubId is called
09-13 16:33:25.369  7457  7457 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-13 16:33:25.369  1455  1471 D TP/MmsSmsProvider: query,matched:12, calling pid = 7457
,09-13 16:33:25.379  7457  7457 D Mms/MethodReflector: getTelephonyProperty is called
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: auto download without roaming -> true
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-13 16:33:25.379  7457  7457 D Mms/MethodReflector: getSubId is called
,09-13 16:33:25.379  1455  1471 D TP/MmsSmsProvider: match 12:Elapsed time : 4.458 ms
09-13 16:33:25.379  7457  7457 D Mms/MethodReflector: getDefaultSmsSubId is called
,09-13 16:33:25.379  7457  7457 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-13 16:33:25.379  7457  7457 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-13 16:33:25.379  7457  7457 D Mms/MethodReflector: getTelephonyProperty is called
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: roaming -> false (slotId = 1)
,09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: auto download without roaming -> true
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: auto download during roaming secondary -> false
09-13 16:33:25.379  7457  7457 D Mms/DownloadManager: mAutoDownload ------> true
,09-13 16:33:25.389  7457  7511 D Mms/DraftCache: [end]    rebuildCache consume time = 17.438594
,09-13 16:33:25.419  7457  7457 D ComposerPerformance: 1473777205437 ms / [DONE] Composer constructor
,09-13 16:33:25.429  7457  7457 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,09-13 16:33:25.429  7457  7513 D Mms/Conversation: [start]    init() consume time = 39.755573
,09-13 16:33:25.429  7457  7457 I Mms/ReservationManager: ReservationManager()
,09-13 16:33:25.429  7457  7457 I Mms/ReservationManager: resetAfterConnected()
,09-13 16:33:25.429  1455  2029 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,09-13 16:33:25.429  1455  2029 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 16:33:25.429  1455  2029 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-13 16:33:25.439  1455  2029 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,09-13 16:33:25.439  1455  1862 D TP/MmsSmsProvider: query,matched:7, calling pid = 7457
,09-13 16:33:25.449  1455  1862 D TP/MmsSmsProvider: match 7:Elapsed time : 3.946 ms
,09-13 16:33:25.449  7457  7457 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-13 16:33:25.449  7457  7457 D Mms/MmsApp: [end]    onCreate() consume time = 25.169375
,09-13 16:33:25.449  1455  2029 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,09-13 16:33:25.449  1455  2029 D TP/MmsSmsProvider: need read changed broadcast:false
,09-13 16:33:25.459  7457  7513 D Mms/Conversation: [end]    init consume time = 3.397812
,09-13 16:33:25.459  7457  7513 D Mms/MessagingNotification: [start]    init() consume time = 1.393542
,09-13 16:33:25.459  7457  7457 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,09-13 16:33:25.459  7457  7457 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,09-13 16:33:25.459  1018  7092 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,09-13 16:33:25.459  7457  7457 D Mms/MethodReflector: getSubId is called
09-13 16:33:25.459  7457  7457 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-13 16:33:25.459  1018  7092 I ActivityManager: Killing 6702:com.sec.spp.push/u0a32 (adj 15): empty #21
09-13 16:33:25.469  7457  7457 D Mms/MethodReflector: getTelephonyProperty is called
09-13 16:33:25.469  7457  7457 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 16:33:25.469  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,09-13 16:33:25.469  7457  7457 D Mms/DownloadManager: auto download without roaming -> true
09-13 16:33:25.469  7457  7457 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-13 16:33:25.469  7457  7457 D Mms/DownloadManager: mAutoDownload ------> true
,09-13 16:33:25.479  7457  7513 D Mms/MessagingNotification: [end]    init consume time = 19.91776
,09-13 16:33:25.489  1455  1862 D TP/MmsSmsProvider: query,matched:0, calling pid = 7457
,09-13 16:33:25.489  1455  1862 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-13 16:33:25.489  1455  1862 D TP/MmsSmsProvider: match 0:Elapsed time : 2.338 ms
,09-13 16:33:25.489  7457  7514 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 9.729583
,09-13 16:33:25.489  7457  7515 D Mms/Synchronizer: [start]    doSync consume time = 7.511563
,09-13 16:33:25.499  1455  1471 D TP/MmsSmsProvider: query,matched:400, calling pid = 7457
,09-13 16:33:25.499  1455  1650 D TP/MmsSmsProvider: update, matched:300, calling pid = 7457
09-13 16:33:25.499  1455  1650 V TP/MmsSmsProvider: syncDBData start
,09-13 16:33:25.499  1455  1650 V TP/MmsSmsProvider: syncDBData sms end
09-13 16:33:25.499  1018  1478 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,09-13 16:33:25.499  1455  1650 V TP/MmsSmsProvider: syncDBData mms end
,09-13 16:33:25.499  1455  1650 V TP/MmsSmsProvider: syncDBData end
,09-13 16:33:25.499  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:25.499  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:25.499  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:25.499  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:25.509  7516  7516 E Zygote  : MountEmulatedStorage()
,09-13 16:33:25.509  7516  7516 I libpersona: KNOX_SDCARD checking this for 10068
09-13 16:33:25.509  7516  7516 E Zygote  : v2
09-13 16:33:25.509  7516  7516 I libpersona: KNOX_SDCARD not a persona
09-13 16:33:25.509  7516  7516 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:25.519  1018  1478 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7516 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-13 16:33:25.519  7457  7514 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 23.717708
,09-13 16:33:25.519  7516  7516 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:25.519  7516  7516 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 16:33:25.519  7457  7515 D Mms/Synchronizer: [end]    doSync consume time = 4.739584
,09-13 16:33:25.539  7516  7516 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:25.539  7516  7516 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:25.539  1018  1136 I ActivityManager: Killing 7223:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,09-13 16:33:25.559  7516  7516 D BadgeProvider: onCreate
,09-13 16:33:25.559  7516  7516 D BadgeProvider: DatabaseHelper
,09-13 16:33:25.579  7457  7513 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-13 16:33:25.579  7457  7505 D Mms/ArtClassLoader: init [DONE] art
,09-13 16:33:25.579  1455  1470 D TP/SmsProvider: query,matched:26, calling pid = 7457
,09-13 16:33:25.589  1455  1470 D TP/SmsProvider: match 26:Elapsed time : 1.587 ms
,09-13 16:33:25.589  1455  1471 D TP/MmsSmsProvider: query,matched:6, calling pid = 7457
,09-13 16:33:25.589  1455  1471 D TP/MmsSmsProvider: match 6:Elapsed time : 1.559 ms
,09-13 16:33:25.609  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,09-13 16:33:25.609  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:25.609  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:25.609  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:25.609  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:25.629  7532  7532 E Zygote  : MountEmulatedStorage(),
,09-13 16:33:25.629  7532  7532 E Zygote  : v2
,09-13 16:33:25.629  7532  7532 I libpersona: KNOX_SDCARD checking this for 10023
09-13 16:33:25.629  7532  7532 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:25.629  1018  1030 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7532 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,09-13 16:33:25.629  7532  7532 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 16:33:25.629  7532  7532 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 16:33:25.639  7532  7532 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:25.649  7532  7532 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:25.649  7532  7532 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:25.659  1018  1481 I ActivityManager: Killing 7024:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-13 16:33:25.699  7532  7532 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-13 16:33:25.719  7457  7513 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-13 16:33:25.719  7362  7362 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-13 16:33:25.729  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:25.729  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:25.729  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,09-13 16:33:25.729  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-13 16:33:25.729  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:25.729  1018  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:25.729  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-13 16:33:25.729  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:25.729  1018  7092 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:25.729  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-13 16:33:25.739  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,09-13 16:33:25.739  1018  1347 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-13 16:33:25.739  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-13 16:33:25.739  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,09-13 16:33:25.739  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:25.739  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
09-13 16:33:25.739  1018  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 16:33:25.739  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 16:33:25.739  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-13 16:33:25.749  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-13 16:33:25.749  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-13 16:33:25.749  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-13 16:33:25.749  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-13 16:33:25.749  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-13 16:33:25.749  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-13 16:33:25.749  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:25.749  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-13 16:33:25.749  1018  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:33:25.749  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-13 16:33:25.759  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-13 16:33:25.759  7532  7532 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-13 16:33:25.759  1018  1479 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-13 16:33:25.759  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-13 16:33:25.759  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:25.759  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 16:33:25.759  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 16:33:25.769  1018  1347 I ActivityManager: Killing 6923:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,09-13 16:33:25.979  6955  6955 D CAR.SERVICE: onUnbind
,09-13 16:33:25.979  6955  6955 D CAR.SERVICE: CSB onClientsDisconnected
09-13 16:33:25.979  6955  6955 D CAR.SERVICE: tearDown
09-13 16:33:25.979  6955  6955 D CAR.SERVICE: tearDownCarState
09-13 16:33:25.979  6955  6955 D CAR.SERVICE: Skip, car not connected.
09-13 16:33:25.979  6955  6955 D CAR.SERVICE: tearDownClientState
,09-13 16:33:25.979  6955  6955 D CAR.SERVICE: requestStop
,09-13 16:33:25.979  6955  6955 D CAR.SERVICE: onDestroy
,09-13 16:33:25.979  6955  6955 D CAR.SERVICE: tearDown
,09-13 16:33:25.979  6955  6955 D CAR.SERVICE: tearDownCarState
09-13 16:33:25.979  6955  6955 D CAR.SERVICE: Skip, car not connected.
09-13 16:33:25.979  6955  6955 D CAR.SERVICE: tearDownClientState
09-13 16:33:25.979  6955  6955 D CAR.SERVICE: requestStop
,09-13 16:33:25.989  6955  6955 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@246e1f16 that was originally bound here
09-13 16:33:25.989  6955  6955 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@246e1f16 that was originally bound here
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 16:33:25.989  6955  6955 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 16:33:25.999  1018  6724 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@1b7dc1b7
,09-13 16:33:27.449  7457  7457 I Mms/MmsApp:  start initViewCache mms,
09-13 16:33:27.449  7457  7457 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1931.241457
,09-13 16:33:27.449  7457  7457 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-13 16:33:27.549  7457  7457 D AbsListView: Get MotionRecognitionManager
,09-13 16:33:27.549  1018  4349 D MotionRecognitionService:  ssp status : false
,09-13 16:33:27.559  7457  7457 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 101.111719
,09-13 16:33:27.599   289   289 E SMD     : DCD OFF
,09-13 16:33:27.639  7457  7457 D Mms/BubbleViewCache: fillCache bubble = 1
,09-13 16:33:28.169  1018  3384 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:28.699  1018  1051 I PowerManagerService: [PWL] Off : 30s ago
,09-13 16:33:28.699  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-13 16:33:28.699  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-13 16:33:28.709  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.auth.account.be.accountstate.LoginAccountsChangedIntentService' (uid=10011, pid=4744, ws=null) (elapsedTime=44543)
,09-13 16:33:28.709  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 16:33:28.839  1018  3349 D SSRM:n  : SIOP:: AP = 440
,09-13 16:33:28.979  1018  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-13 16:33:29.359  1018  1058 D PackageManager: [MSG] MCS_UNBIND
,09-13 16:33:29.369  1018  1480 I ActivityManager: Killing 7282:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-13 16:33:30.599   289   289 E SMD     : DCD OFF,
,09-13 16:33:31.479  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:33:31.479  1018  1031 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 16:33:31.479  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 16:33:31.479  1018  1031 D BatteryService: stay LED for fully charged
09-13 16:33:31.479  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:31.489  1018  1018 I MotionRecognitionService: Plugged
,09-13 16:33:31.489  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:31.489  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 16:33:31.489  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 16:33:31.489  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 16:33:31.489  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:33:31.509  3165  3165 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:33:31.509  3165  3286 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:33:31.519  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:31.519  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:31.519  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:33.169  1018  3384 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:33.599   289   289 E SMD     : DCD OFF
,09-13 16:33:35.169  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 16:33:35.169  1018  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-13 16:33:35.179  5939  6044 I Finsky  : [1050] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,09-13 16:33:35.409  5939  6044 I Finsky  : [1050] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,09-13 16:33:35.409  5939  5939 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,09-13 16:33:35.409  1018  1306 I ActivityManager: Killing 6665:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-13 16:33:36.089  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:33:36.089  6845  7152 I jxcore-log: 
,09-13 16:33:36.089  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:33:36.089  6845  7152 I jxcore-log: 
,09-13 16:33:36.099  6845  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:36.099  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:36.099  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:36.099  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:36.099  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:36.099  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:36.099  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:36.099  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:36.099  6845  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:33:36.099  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:33:36.099  6845  7152 I jxcore-log: 
,09-13 16:33:36.109  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:33:36.109  6845  7152 I jxcore-log: 
,09-13 16:33:36.599   289   289 E SMD     : DCD OFF
,09-13 16:33:36.769  6845  7152 I jxcore-log: Unit Test app is loaded
09-13 16:33:36.769  6845  7152 I jxcore-log: 
,09-13 16:33:36.769  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:33:36.769  6845  7152 I jxcore-log: 
,09-13 16:33:36.779  6845  6845 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 16:33:36.779  6845  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:33:36.779  6845  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25318465 added. We now have 2 listener(s)
,09-13 16:33:36.779  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-13 16:33:36.779  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:33:36.779  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:33:36.779  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:33:36.779  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@378a553a added. We now have 2 listener(s)
09-13 16:33:36.779  6845  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:33:36.779  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:33:36.789  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:36.789  6845  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:36.789  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:36.789  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:36.789  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:36.789  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:36.789  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:36.789  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:36.789  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:36.789  6845  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:33:36.789  6845  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:33:36.789  6845  7152 D ExecuteNativeTests: Running unit tests
,09-13 16:33:36.799  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:36.799  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:36.799  6845  7152 D BluetoothAdapter: enable()
,09-13 16:33:36.799  6845  7152 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 16:33:36.809  1018  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 16:33:36.809  1018  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 16:33:36.809  1018  1031 D SecContentProvider2: mCursor = null
,09-13 16:33:36.809  1018  1031 D WifiService: setWifiEnabled: true pid=6845, uid=10171
,09-13 16:33:36.809  1018  1031 W ActivityManager: Permission Denial: getCurrentUser() from pid=6845, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-13 16:33:36.819  1018  1031 W WifiService: Failed getting userId using ActivityManagerNative,
,09-13 16:33:36.819  1018  1031 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6845, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-13 16:33:36.819  1018  1031 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 16:33:36.819  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-13 16:33:36.819  1018  1031 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-13 16:33:36.819  1018  1031 W WifiService: ,	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-13 16:33:36.819  1018  1031 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-13 16:33:36.819  1018  1031 D SettingsProvider: name = wifi_on
,09-13 16:33:36.819  6845  7152 I System.out: Running UT
,09-13 16:33:38.169  1018  3384 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 16:33:38.869  1018  3349 D SSRM:n  : SIOP:: AP = 410,
09-13 16:33:38.869  1018  3349 D U       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,09-13 16:33:38.879  1230  1230 D ContentApp:  LEVEL : -1
09-13 16:33:38.879  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.videoplayer, hostingType: broadcast
,09-13 16:33:38.879  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-13 16:33:38.879  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-13 16:33:38.879  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:38.879  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:38.899  7557  7557 E Zygote  : MountEmulatedStorage()
09-13 16:33:38.899  7557  7557 E Zygote  : v2
09-13 16:33:38.899  7557  7557 I libpersona: KNOX_SDCARD checking this for 10045
09-13 16:33:38.899  7557  7557 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:38.899  7557  7557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:38.899  1018  1044 I ActivityManager: Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7557 uid=10045 gids={50045, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,09-13 16:33:38.909  7557  7557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:38.909  7557  7557 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:33:38.949  7557  7557 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:38.949  7557  7557 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:38.969  7557  7557 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-13 16:33:38.969  7557  7557 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 16:33:38.969  7557  7557 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:33:38.969  7557  7557 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 16:33:39.009  7557  7557 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,09-13 16:33:39.019  7557  7557 D videowall-Global: core_num = 4
,09-13 16:33:39.019  7557  7557 W linker  : libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,09-13 16:33:39.019  7557  7557 W linker  : libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,09-13 16:33:39.019  7557  7557 D videowall-Global: density : 1.5 width : 540 height : 960 Raw width : 540 Raw height : 960
,09-13 16:33:39.019  7557  7557 D videowall-Global: dsp : 540, swkey : false, Cores : 4, Clock : 0
,09-13 16:33:39.029  1018  1481 I ActivityManager: Killing 6955:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-13 16:33:39.609   289   289 E SMD     : DCD OFF
,09-13 16:33:40.499  4744  4763 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+metrics_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-13 16:33:40.499  4744  4763 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+help_responses_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-13 16:33:40.499  4744  4763 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+auto_complete_suggestions_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-13 16:33:41.539  1018  1499 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:33:41.539  1018  1499 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 16:33:41.549  1018  1499 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 16:33:41.549  1018  1499 D BatteryService: stay LED for fully charged
09-13 16:33:41.549  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:41.549  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:41.549  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:33:41.559  1018  1018 I MotionRecognitionService: Plugged
,09-13 16:33:41.559  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
09-13 16:33:41.559  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 16:33:41.559  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:33:41.569  3165  3165 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-13 16:33:41.569  3165  3286 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:33:41.589  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:41.589  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:41.589  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:42.609   289   289 E SMD     : DCD OFF,
,09-13 16:33:43.609  1018  1307 E Watchdog: !@Sync 3
,09-13 16:33:44.629   327   327 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-13 16:33:44.629   327   327 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 16:33:45.609   289   289 E SMD     : DCD OFF
,09-13 16:33:46.919  6845  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:33:46.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb added. We now have 3 listener(s)
,09-13 16:33:46.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-13 16:33:46.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:33:46.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:33:46.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:33:46.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 added. We now have 3 listener(s)
09-13 16:33:46.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:33:46.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:33:46.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:46.929  6845  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:46.929  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:46.929  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:46.929  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:46.929  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:46.929  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:46.929  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:46.929  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:46.939  6845  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:33:46.939  6845  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:33:46.939  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:46.939  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:46.939  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:33:46.949  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:46.949  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:46.949  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:33:46.949  6845  7152 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 16:33:46.949  6845  7152 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:33:46.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:33:46.949  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:46.949  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:46.949  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:33:46.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:46.949  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:46.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:46.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:33:46.949  6845  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb removed from the list
09-13 16:33:46.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:46.949  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 removed from the list
09-13 16:33:46.949  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:46.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:46.949  6845  7152 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 16:33:46.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:46.949  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:46.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:46.949  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:46.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:46.949  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:46.949  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:46.949  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:46.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:33:46.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:33:46.969  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 16:33:46.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:46.969  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 16:33:46.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:46.969  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
,09-13 16:33:46.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:46.969  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:46.969  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:46.969  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:33:46.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:46.969  6845  7152 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:33:46.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:46.969  6845  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:46.969  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-13 16:33:46.969  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:46.969  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:46.969  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:46.969  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:46.969  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:46.969  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:46.969  6845  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-13 16:33:46.969  6845  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:33:46.969  6845  7152 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 16:33:46.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 16:33:46.969  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
09-13 16:33:46.969  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:46.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:46.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:46.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:33:46.979  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:46.979  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:33:46.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:46.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:46.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:46.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:46.979  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:46.979  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:46.979  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:46.979  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:33:46.989  6845  7577 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:33:46.989  6845  7577 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:33:46.989  6845  7577 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-13 16:33:46.989  6845  7577 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:33:46.989  6845  7577 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:33:46.989  6845  7577 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12360624
09-13 16:33:46.989  6845  7577 D BluetoothSocket: channel: 6
09-13 16:33:46.989  6845  7577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:33:46.999  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:46.999  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:46.999  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:33:46.999  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-13 16:33:46.999  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 08 EC A9 50 76 27
,09-13 16:33:46.999  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:33:46.999  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:46.999  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:47.009  3165  3175 D BtGatt.GattService: registerClient() - UUID=4aac1586-5be0-46a1-8ce8-bebb961e5269
,09-13 16:33:47.059  3165  3271 D BtGatt.GattService: onClientRegistered() - UUID=4aac1586-5be0-46a1-8ce8-bebb961e5269, clientIf=6
,09-13 16:33:47.059  6845  6854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:47.059  3165  3280 D BtGatt.AdvertiseManager: message : 0
,09-13 16:33:47.069  3165  3280 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:33:47.069  3165  3280 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:47.069  3165  3280 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:47.069  3165  3280 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:33:47.079  3165  3271 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:47.079  3165  3280 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:47.089  3165  3271 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:33:47.089  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:33:47.089  3165  3280 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:33:47.089  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:33:47.089  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:47.089  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:47.089  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:33:47.099  6845  7152 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:33:47.099  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:33:47.099  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:33:47.099  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:33:47.099  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:33:47.099  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:47.099  6845  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:47.099  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:47.609  6845  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 16:33:47.609  6845  7152 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 16:33:47.609  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 16:33:47.609  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 16:33:47.609  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:33:47.609  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:47.609  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:33:47.609  6845  7152 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@367e4342, channel: 6, state: LISTENING
,09-13 16:33:47.609  6845  7152 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@367e4342, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12360624, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@334cef53mSocket: android.net.LocalSocket@35df6090 impl:android.net.LocalSocketImpl@3ee82d89 fd:FileDescriptor[105]
,09-13 16:33:47.609  6845  7152 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35df6090 impl:android.net.LocalSocketImpl@3ee82d89 fd:FileDescriptor[105]
,09-13 16:33:47.609  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:33:47.609  6845  7577 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@367e4342, channel: 6, state: CLOSED
09-13 16:33:47.609  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:47.609  6845  7577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:33:47.609  6845  7577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:47.609  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 16:33:47.609  6845  7577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true,
,09-13 16:33:47.609  6845  6845 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true,
,09-13 16:33:47.609  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-13 16:33:47.609  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:47.609  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:47.609  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
09-13 16:33:47.619  6845  7152 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:33:47.619  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:47.619  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:33:47.619  3165  3280 D BtGatt.AdvertiseManager: message : 1
,09-13 16:33:47.619  3165  3280 D BtGatt.AdvertiseManager: stop advertise for client 6
09-13 16:33:47.619  3165  3280 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6,
09-13 16:33:47.619  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:33:47.619  3165  3271 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:33:47.619  3165  3271 D BtGatt.GattService: Client app is not null!
09-13 16:33:47.619  3165  3274 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:33:47.629  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:47.629  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:47.629  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
09-13 16:33:47.629  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:33:47.629  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:33:47.629  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:47.629  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:47.629  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:33:47.629  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:47.629  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:33:47.629  6845  6845 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:33:47.629  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:47.629  6845  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:33:47.629  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-13 16:33:47.629  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:47.629  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:47.629  6845  7152 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:33:47.629  6845  7152 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:33:47.629  6845  7152 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 16:33:47.629  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-13 16:33:47.639  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:47.639  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:47.639  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:47.639  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:47.639  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:33:47.639  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:47.639  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:47.639  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
09-13 16:33:47.639  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:33:47.639  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:47.639  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:47.639  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:47.639  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:47.649  6845  7581 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:33:47.649  6845  7581 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:33:47.649  6845  7581 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-13 16:33:47.649  6845  7581 D BluetoothSocket: bindListen(), new LocalSocket 
,09-13 16:33:47.649  6845  7581 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:33:47.649  6845  7581 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e81f5bc
,09-13 16:33:47.649  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:33:47.649  6845  7581 D BluetoothSocket: channel: 6
09-13 16:33:47.649  6845  7581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:33:47.649  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-13 16:33:47.659  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:33:47.659  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-13 16:33:47.659  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 08 EC A9 50 76 27
09-13 16:33:47.659  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:33:47.659  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:47.659  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:47.659  3165  3176 D BtGatt.GattService: registerClient() - UUID=3d8efd93-ab31-45c0-a2a8-6382549ae7e2
,09-13 16:33:47.699  3165  3271 D BtGatt.GattService: onClientRegistered() - UUID=3d8efd93-ab31-45c0-a2a8-6382549ae7e2, clientIf=6
,09-13 16:33:47.699  6845  6853 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:47.699  3165  3280 D BtGatt.AdvertiseManager: message : 0
,09-13 16:33:47.699  3165  3280 D BtGatt.AdvertiseManager: number of adv instance running0
09-13 16:33:47.699  3165  3280 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:47.709  3165  3280 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:47.709  3165  3280 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:33:47.719  3165  3271 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:47.719  3165  3280 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:47.719  3165  3271 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:33:47.719  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:33:47.719  3165  3280 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:33:47.719  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:33:47.719  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:47.729  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:47.729  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:33:47.729  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:33:47.729  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:33:47.729  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:33:47.729  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:33:47.729  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:47.729  6845  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:47.739  6845  7152 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:33:47.739  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:47.739  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.739  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:47.739  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:47.739  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:47.739  6845  7152 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3df4f89a, channel: 6, state: LISTENING
09-13 16:33:47.739  6845  7152 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3df4f89a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e81f5bc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2628f5cbmSocket: android.net.LocalSocket@2056b1a8 impl:android.net.LocalSocketImpl@3efb04c1 fd:FileDescriptor[105]
09-13 16:33:47.739  6845  7152 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2056b1a8 impl:android.net.LocalSocketImpl@3efb04c1 fd:FileDescriptor[105]
09-13 16:33:47.739  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:33:47.739  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:47.739  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.739  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.739  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:47.739  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:47.739  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:47.739  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:33:47.739  6845  7581 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3df4f89a, channel: 6, state: CLOSED
09-13 16:33:47.739  6845  7581 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:33:47.739  6845  7581 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:47.739  6845  7581 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:33:47.739  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:33:47.739  6845  7152 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:33:47.739  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:33:47.739  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:33:47.739  3165  3280 D BtGatt.AdvertiseManager: message : 1
,09-13 16:33:47.739  3165  3280 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-13 16:33:47.749  3165  3280 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-13 16:33:47.749  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:33:47.749  3165  3271 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:33:47.749  3165  3271 D BtGatt.GattService: Client app is not null!
,09-13 16:33:47.749  3165  3274 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:33:47.759  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:47.759  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:47.759  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:33:47.759  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:33:47.759  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:33:47.759  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:33:47.759  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:33:47.759  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:33:47.759  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:33:47.759  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:33:47.759  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:33:47.759  6845  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:47.759  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:47.759  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.759  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.769  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:47.769  6845  7152 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:33:47.769  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:47.779  6845  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:47.779  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:47.779  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:47.779  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:47.779  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:47.779  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:47.779  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:47.779  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:47.779  6845  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:33:47.779  6845  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:33:47.779  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:47.789  6845  7152 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-13 16:33:47.789  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-13 16:33:47.789  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:47.789  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:47.789  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:47.789  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:47.789  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:47.789  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:33:47.789  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:47.789  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:47.789  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:47.789  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:47.789  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:33:47.789  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:47.789  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:47.789  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:47.799  6845  7584 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 16:33:47.799  6845  7584 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:33:47.799  6845  7584 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-13 16:33:47.799  6845  7584 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:33:47.799  6845  7584 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:33:47.799  6845  7584 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16f22bfd
09-13 16:33:47.799  6845  7584 D BluetoothSocket: channel: 6
09-13 16:33:47.799  6845  7584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:33:47.799  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:47.799  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:47.799  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:33:47.799  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-13 16:33:47.809  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 08 EC A9 50 76 27
09-13 16:33:47.809  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-13 16:33:47.809  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:47.809  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:47.809  3165  3176 D BtGatt.GattService: registerClient() - UUID=f7a4f206-9cde-46d2-9e48-d748728e2a5b
,09-13 16:33:47.849  3165  3271 D BtGatt.GattService: onClientRegistered() - UUID=f7a4f206-9cde-46d2-9e48-d748728e2a5b, clientIf=6
,09-13 16:33:47.849  6845  6854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:47.849  3165  3280 D BtGatt.AdvertiseManager: message : 0
,09-13 16:33:47.859  3165  3280 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:33:47.859  3165  3280 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:47.859  3165  3280 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:47.859  3165  3280 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:33:47.869  3165  3271 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:47.869  3165  3280 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:47.869  3165  3271 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:33:47.869  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:33:47.869  3165  3280 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:33:47.869  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:33:47.879  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:47.879  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:47.879  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:33:47.879  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:33:47.879  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:33:47.879  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:33:47.879  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:33:47.879  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:47.889  6845  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:47.889  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:47.889  6845  7152 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:33:47.889  6845  7152 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 16:33:47.889  6845  7152 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 16:33:47.889  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 16:33:47.889  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:33:47.889  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:33:47.889  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:47.889  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:33:47.889  6845  7152 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3bc05343, channel: 6, state: LISTENING
,09-13 16:33:47.899  6845  7152 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3bc05343, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16f22bfd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33140dc0mSocket: android.net.LocalSocket@3e3a8af9 impl:android.net.LocalSocketImpl@adb3a3e fd:FileDescriptor[105]
,09-13 16:33:47.899  6845  7152 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e3a8af9 impl:android.net.LocalSocketImpl@adb3a3e fd:FileDescriptor[105]
,09-13 16:33:47.899  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left,
09-13 16:33:47.899  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:33:47.899  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:47.899  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:33:47.899  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:47.899  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:47.899  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:47.899  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:33:47.899  6845  7584 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3bc05343, channel: 6, state: CLOSED
09-13 16:33:47.899  6845  7584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:33:47.899  6845  7584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:47.899  6845  7584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:33:47.899  6845  7152 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:33:47.899  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:33:47.899  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:33:47.899  3165  3280 D BtGatt.AdvertiseManager: message : 1
,09-13 16:33:47.909  3165  3280 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-13 16:33:47.909  3165  3280 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-13 16:33:47.909  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:33:47.909  3165  3271 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:33:47.909  3165  3271 D BtGatt.GattService: Client app is not null!
,09-13 16:33:47.909  3165  3274 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:33:47.919  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:33:47.919  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:33:47.919  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:33:47.919  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:33:47.919  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:33:47.919  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:47.919  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:33:47.919  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:33:47.919  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:47.919  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:33:47.919  6845  6845 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:33:47.919  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:47.919  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:47.919  6845  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:47.919  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.929  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.929  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.929  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.929  6845  7152 D io.j,xcore.node.ConnectivityMonitor: stop
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.929  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:33:47.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:47.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:33:47.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:47.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:33:47.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:47.929  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.929  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.929  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.929  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.939  6845  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.939  6845  7152 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:33:47.939  6845  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.939  6845  7152 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:33:47.939  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:33:47.939  6845  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 16:33:47.939  6845  7152 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:33:47.939  6845  7152 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 16:33:47.939  6845  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.939  6845  7152 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:33:47.939  6845  7152 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 16:33:47.939  6845  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.939  6845  7152 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:33:47.939  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 16:33:47.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 16:33:47.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 16:33:47.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 16:33:47.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 16:33:47.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 16:33:47.949  6845  7152 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 16:33:47.949  6845  7152 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:33:47.949  6845  7152 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 16:33:47.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.949  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 16:33:47.949  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.949  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.949  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.949  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.949  6845  7590 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1371
09-13 16:33:47.949  6845  7589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1371)
09-13 16:33:47.949  6845  7589 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1371)
09-13 16:33:47.949  6845  7152 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 16:33:47.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.949  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.949  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.949  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.949  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.949  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.949  6845  7152 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 16:33:47.959  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.959  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.959  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.959  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.959  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.959  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.959  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.959  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.959  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.959  6845  7152 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 16:33:47.959  6845  7152 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:33:47.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:33:47.959  6845  7152 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:33:47.959  6845  7152 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:33:47.959  6845  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:33:47.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:33:47.959  6845  7152 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:33:47.959  6845  7152 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:33:47.959  6845  7152 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:33:47.959  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:33:47.959  6845  7152 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:33:47.959  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:47.959  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.959  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.959  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:47.959  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:47.959  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:47.959  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:47.959  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:47.959  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:47.959  6845  7152 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:33:47.959  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:47.959  6845  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:47.959  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:47.959  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:47.959  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:47.959  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:47.959  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:47.959  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:47.959  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:33:47.969  6845  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:47.969  6845  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:33:47.969  6845  7152 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 16:33:47.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 16:33:47.969  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:47.969  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:47.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:47.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:47.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:33:47.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:47.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:47.969  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:47.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:47.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:47.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:47.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:47.969  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:33:47.979  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:33:47.979  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:33:47.979  6845  7591 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:33:47.979  6845  7591 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:33:47.979  6845  7591 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
09-13 16:33:47.979  6845  7591 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:33:47.979  6845  7591 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:33:47.979  6845  7591 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@124cbc4a
09-13 16:33:47.979  6845  7591 D BluetoothSocket: channel: 6
09-13 16:33:47.979  6845  7591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:33:47.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:33:47.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:33:47.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:33:47.979  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-13 16:33:47.979  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 08 EC A9 50 76 27
09-13 16:33:47.989  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:47.989  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:47.989  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:33:47.989  3165  3175 D BtGatt.GattService: registerClient() - UUID=7188e9ee-cc8f-4ca8-a8c7-fceff914817e
,09-13 16:33:48.039  3165  3271 D BtGatt.GattService: onClientRegistered() - UUID=7188e9ee-cc8f-4ca8-a8c7-fceff914817e, clientIf=6
,09-13 16:33:48.039  6845  6854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:48.039  3165  3280 D BtGatt.AdvertiseManager: message : 0
,09-13 16:33:48.039  3165  3280 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:33:48.039  3165  3280 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:48.039  3165  3280 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:48.039  3165  3280 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:33:48.049  3165  3271 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:48.049  3165  3280 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:48.049  3165  3271 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:33:48.049  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:33:48.049  3165  3280 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:33:48.049  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:33:48.049  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:48.059  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:48.059  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:33:48.059  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:33:48.059  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:33:48.059  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:33:48.059  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:33:48.059  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:48.069  6845  7152 I io.jxcore.node.ConnectionHelper: start: OK,
09-13 16:33:48.069  6845  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:33:48.069  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:48.069  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.069  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:48.069  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:48.069  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:48.069  6845  7152 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@396dd4d8, channel: 6, state: LISTENING
09-13 16:33:48.069  6845  7152 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@396dd4d8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@124cbc4a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21ada031mSocket: android.net.LocalSocket@14a25316 impl:android.net.LocalSocketImpl@17724497 fd:FileDescriptor[105]
09-13 16:33:48.069  6845  7152 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@14a25316 impl:android.net.LocalSocketImpl@17724497 fd:FileDescriptor[105]
,09-13 16:33:48.069  6845  7591 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@396dd4d8, channel: 6, state: CLOSED
09-13 16:33:48.069  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:33:48.069  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:33:48.069  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:48.069  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:48.069  6845  7591 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:33:48.069  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.069  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:48.069  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:48.069  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:48.069  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:33:48.069  6845  7591 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:48.069  6845  7591 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:33:48.069  6845  7152 D BluetoothLeScanner: could not find callback wrapper
09-13 16:33:48.069  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:48.069  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:33:48.069  3165  3280 D BtGatt.AdvertiseManager: message : 1
,09-13 16:33:48.079  3165  3280 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-13 16:33:48.079  3165  3280 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-13 16:33:48.079  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:33:48.099  3165  3271 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-13 16:33:48.099  3165  3271 D BtGatt.GattService: Client app is not null!
,09-13 16:33:48.099  3165  3274 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:33:48.099  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:33:48.099  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:33:48.099  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:33:48.099  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:33:48.099  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:33:48.099  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:33:48.099  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:33:48.099  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:33:48.099  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:33:48.099  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:33:48.099  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:33:48.099  6845  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:33:48.099  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:33:48.099  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
,09-13 16:33:48.099  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.099  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.109  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:33:48.109  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:33:48.109  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.109  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
,09-13 16:33:48.109  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.109  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list,
09-13 16:33:48.109  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.109  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:33:48.109  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.109  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:33:48.109  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:48.119  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:48.119  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.119  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:33:48.119  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:48.119  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:48.119  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:33:48.119  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.119  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:48.119  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:33:48.119  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:48.119  6845  7152 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 16:33:48.119  6845  7152 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 16:33:48.119  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:48.119  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.119  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-13 16:33:48.119  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:48.119  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.119  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:48.119  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.119  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.119  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.129  6845  7595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:33:48.129  6845  7595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:33:48.129  6845  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:33:48.129  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.129  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.129  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.129  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:48.129  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:33:48.129  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:48.129  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.129  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.129  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.129  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:33:48.129  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.129  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:48.129  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f145fdb not in the list
09-13 16:33:48.129  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:48.129  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f43ba78 not in the list
09-13 16:33:48.129  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:48.129  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:48.129  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:48.129  6845  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
09-13 16:33:48.129  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:33:48.129  6845  7152 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing,
09-13 16:33:48.129  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 16:33:48.129  6845  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-13 16:33:48.129  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 16:33:48.139  6845  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:33:48.139  6845  7152 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-13 16:33:48.139  6845  7152 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing,
09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 16:33:48.139  6845  7152 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 16:33:48.149  6845  7596 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775,
09-13 16:33:48.149  6845  7596 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:33:48.609   289   289 E SMD     : DCD OFF
,09-13 16:33:48.629  6845  6845 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:33:48.649   279   921 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-13 16:33:48.649   279   921 D Netd    : getNetworkForDns: using netid 502 for uid 10171
,09-13 16:33:48.649  6845  7598 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 16:33:48.649  6845  7598 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:33:48.659  6845  7598 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:48.659  6845  7598 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:33:48.659  6845  7598 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 16:33:48.659  6845  7596 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775,
,09-13 16:33:48.659  6845  7596 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:33:48.659  6845  7596 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:48.659  6845  7601 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1424, name: IncomingSocketThread/Sender)
09-13 16:33:48.659  6845  7596 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:48.659  6845  7596 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 16:33:48.659  6845  7604 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1427, name: OutgoingSocketThread/Receiver)
09-13 16:33:48.659  6845  7602 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1425, name: IncomingSocketThread/Receiver)
09-13 16:33:48.659  6845  7602 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1425, thread name: IncomingSocketThread/Receiver)
09-13 16:33:48.659  6845  7602 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:33:48.659  6845  7604 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1427, thread name: OutgoingSocketThread/Receiver)
09-13 16:33:48.659  6845  7604 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:33:48.659  6845  7602 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1425, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:33:48.659  6845  7604 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1427, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 16:33:48.669  6845  7603 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1426, name: OutgoingSocketThread/Sender)
,09-13 16:33:48.719  1018  1051 I PowerManagerService: [PWL] Off : 50s ago
,09-13 16:33:48.719  1018  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-13 16:33:48.719  1018  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-13 16:33:48.719  1018  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=3165, ws=null) (elapsedTime=628)
,09-13 16:33:48.929  1018  3349 D SSRM:n  : SIOP:: AP = 360,
,09-13 16:33:49.159  6845  7152 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 16:33:49.159  6845  7152 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 16:33:49.159  6845  7152 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@60541eb Bundle[{}]
,09-13 16:33:49.159  6845  7152 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:33:49.159  6845  7152 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 16:33:49.159  6845  7152 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 16:33:49.159  6845  7152 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 16:33:49.159  6845  7152 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 16:33:49.159  6845  7152 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:33:49.169  6845  7605 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 16:33:49.169  6845  7605 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:33:49.629   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 16:33:49.679  6845  7607 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 16:33:49.679  6845  7607 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:33:49.679  6845  7607 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:33:49.679  6845  7607 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:33:49.679  6845  7607 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:33:49.679  6845  7605 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 16:33:49.679  6845  7605 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 16:33:49.679  6845  7605 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:33:49.679  6845  7605 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:33:49.679  6845  7605 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:33:49.679  6845  7610 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1439, name: IncomingSocketThread/Receiver)
,09-13 16:33:49.679  6845  7609 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1438, name: IncomingSocketThread/Sender)
,09-13 16:33:49.679  6845  7610 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1439, thread name: IncomingSocketThread/Receiver)
,09-13 16:33:49.679  6845  7610 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-13 16:33:49.679  6845  7610 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1439, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:33:49.689  6845  7612 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1441, name: OutgoingSocketThread/Receiver)
09-13 16:33:49.689  6845  7612 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1441, thread name: OutgoingSocketThread/Receiver)
,09-13 16:33:49.689  6845  7612 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done,
09-13 16:33:49.689  6845  7612 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1441, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 16:33:49.689  6845  7611 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1440, name: OutgoingSocketThread/Sender)
,09-13 16:33:50.179  6845  7152 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1450)
,09-13 16:33:50.179  6845  7152 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 16:33:50.179  6845  7152 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1451)
,09-13 16:33:50.179  6845  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 16:33:50.179  6845  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48b0e6d added. We now have 3 listener(s)
,09-13 16:33:50.189  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-13 16:33:50.189  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 16:33:50.189  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:33:50.189  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:33:50.189  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e88aa2 added. We now have 3 listener(s)
,09-13 16:33:50.189  6845  7152 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:33:50.189  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:33:50.189  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-13 16:33:50.199  6845  7152 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:33:50.199  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:33:50.199  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:33:50.199  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:33:50.199  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:33:50.199  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:33:50.199  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:33:50.199  6845  7152 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:33:50.199  6845  7152 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:33:50.199  6845  7152 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:33:50.199  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:50.209  6845  6845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:33:50.209  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:33:50.209  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:33:50.209  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:33:50.209  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:33:50.209  6845  7152 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48b0e6d removed from the list
,09-13 16:33:50.209  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:33:50.209  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e88aa2 removed from the list
,09-13 16:33:50.209  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:50.209  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:50.209  6845  7152 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-13 16:33:50.209  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 16:33:50.219  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:33:50.219  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:33:50.219  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections,
09-13 16:33:50.219  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-13 16:33:50.219  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
09-13 16:33:50.219  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:50.219  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:50.219  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:33:50.219  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:33:50.219  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:50.219  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-13 16:33:50.219  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:50.229  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
09-13 16:33:50.229  6845  7613 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:33:50.229  6845  7613 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:33:50.229  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:50.229  6845  7613 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-13 16:33:50.229  6845  7613 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:33:50.229  6845  7613 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:33:50.229  6845  7613 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c572469
09-13 16:33:50.229  6845  7613 D BluetoothSocket: channel: 6
09-13 16:33:50.229  6845  7613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:33:50.229  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:50.239  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:33:50.239  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-13 16:33:50.239  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 08 EC A9 50 76 27
,09-13 16:33:50.239  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:50.239  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:50.239  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:50.239  3165  3176 D BtGatt.GattService: registerClient() - UUID=284a86c1-23ae-4953-8d34-eaae87b8978a,
,09-13 16:33:50.279  3165  3271 D BtGatt.GattService: onClientRegistered() - UUID=284a86c1-23ae-4953-8d34-eaae87b8978a, clientIf=6
,09-13 16:33:50.279  6845  6853 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:50.279  3165  3280 D BtGatt.AdvertiseManager: message : 0
,09-13 16:33:50.279  3165  3280 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:33:50.279  3165  3280 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:50.289  3165  3280 D BtGatt.AdvertiseManager: starting advertising
09-13 16:33:50.289  3165  3280 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:33:50.309  3165  3271 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:50.309  3165  3280 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:50.309  3165  3271 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:33:50.309  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:33:50.309  3165  3280 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:33:50.309  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 16:33:50.309  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:50.309  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:50.309  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:33:50.309  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:33:50.309  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:33:50.309  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-13 16:33:50.309  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:33:50.309  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:50.319  6845  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:50.319  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:50.629   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:33:50.829  6845  6845 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:33:50.829  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:33:50.829  6845  6845 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:33:51.609   289   289 E SMD     : DCD OFF
09-13 16:33:51.609  1018  1478 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 16:33:51.609  1018  1478 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 16:33:51.609  1018  1478 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 16:33:51.609  1018  1478 D BatteryService: stay LED for fully charged
09-13 16:33:51.609  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:33:51.609  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:33:51.609  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:33:51.609  1018  1018 I MotionRecognitionService: Plugged
,09-13 16:33:51.619  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
09-13 16:33:51.619  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 16:33:51.619  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:33:51.619   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 16:33:51.629  3165  3165 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-13 16:33:51.629  3165  3286 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:33:51.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:51.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:51.649  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:33:52.629   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 16:33:53.619   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:33:53.829  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:33:53.829  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:33:53.829  6845  7152 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2bf32f8f, channel: 6, state: LISTENING,
09-13 16:33:53.829  6845  7152 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2bf32f8f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c572469, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@26a3021cmSocket: android.net.LocalSocket@1bb49e25 impl:android.net.LocalSocketImpl@9b4cbfa fd:FileDescriptor[109]
09-13 16:33:53.829  6845  7152 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1bb49e25 impl:android.net.LocalSocketImpl@9b4cbfa fd:FileDescriptor[109]
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:33:53.829  6845  7613 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2bf32f8f, channel: 6, state: CLOSED
09-13 16:33:53.829  6845  7613 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:33:53.829  6845  7613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:33:53.829  6845  7613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:33:53.829  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:33:53.829  6845  7152 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:33:53.829  3165  3280 D BtGatt.AdvertiseManager: message : 1
09-13 16:33:53.829  3165  3280 D BtGatt.AdvertiseManager: stop advertise for client 6
09-13 16:33:53.829  3165  3280 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-13 16:33:53.829  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-13 16:33:53.829  3165  3271 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:33:53.829  3165  3271 D BtGatt.GattService: Client app is not null!
09-13 16:33:53.829  3165  3175 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:53.829  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:53.829  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:33:53.839  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:53.839  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:33:53.839  6845  6845 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:33:53.839  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:53.839  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:53.839  6845  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:33:53.839  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:53.839  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:33:53.839  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:53.839  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:33:53.839  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48b0e6d not in the list,
09-13 16:33:53.839  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:33:53.839  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e88aa2 not in the list
09-13 16:33:53.839  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:33:53.839  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:53.839  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:53.849  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:33:53.849  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:33:53.849  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-13 16:33:53.849  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:33:53.849  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:53.849  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:53.849  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:53.859  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-13 16:33:53.859  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:53.859  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 16:33:53.869  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-13 16:33:53.869  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 16:33:53.869  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 16:33:53.869  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 16:33:53.879  3165  3176 D BtGatt.GattService: registerClient() - UUID=38079948-32e7-4a30-a0d4-6a07e6ddbd84
,09-13 16:33:53.919  3165  3271 D BtGatt.GattService: onClientRegistered() - UUID=38079948-32e7-4a30-a0d4-6a07e6ddbd84, clientIf=6
,09-13 16:33:53.919  6845  6854 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:53.919  3165  5167 D BtGatt.GattService: start scan with filters
,09-13 16:33:53.919  3165  3282 D BtGatt.ScanManager: handling starting scan
,09-13 16:33:53.919  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 16:33:53.919  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 16:33:53.919  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 16:33:53.919  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 16:33:53.929  3165  3282 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a9a6ff5
,09-13 16:33:53.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 16:33:53.929  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 16:33:53.929  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 16:33:53.929  3165  3271 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 16:33:53.929  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:53.929  3165  3282 D BtGatt.ScanManager: allow scan with filters
09-13 16:33:53.929  3165  3282 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 16:33:53.929  3165  3282 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-13 16:33:53.929  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:53.929  3165  3271 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
,09-13 16:33:53.929  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:53.929  3165  3282 D BtGatt.ScanManager: Starting BLE batch scan
09-13 16:33:53.929  3165  3282 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 16:33:53.939  3165  3271 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-13 16:33:53.939  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:53.949  3165  3271 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-13 16:33:53.949  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:54.169  5682  5682 D FactoryTest: Not factory mode
,09-13 16:33:54.169  5682  5682 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-13 16:33:54.169  5682  5682 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-13 16:33:54.169  5682  5682 D MTPRx   : still no open session command from host, so toast
,09-13 16:33:54.179  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-13 16:33:54.179  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-13 16:33:54.179  5682  5682 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118776,
09-13 16:33:54.179  1018  1479 E PersonaManagerService: inState():  stateMachine is null !!
,09-13 16:33:54.179  1018  1479 I PersonaManagerService: PersonaId don't exist
09-13 16:33:54.179  1018  1479 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-13 16:33:54.189  1018  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-13 16:33:54.189  1018  1479 W ActivityManager: userId = 0, bbcId = -10000,
09-13 16:33:54.189  1018  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 16:33:54.189  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-13 16:33:54.199  1018  1479 W ActivityManager: mDVFSHelper.acquire()
,09-13 16:33:54.209  1018  1479 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:33:54.209  1018  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 16:33:54.209  1018  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-13 16:33:54.209  1018  1479 D InputDispatcher: Focused application set to: xxxx
,09-13 16:33:54.209  1018  1479 D InputDispatcher: Focus left window: 6845
,09-13 16:33:54.219  5682  5682 E MTPRx   : started activity for popup
,09-13 16:33:54.219  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 16:33:54.219  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 16:33:54.239  5682  5682 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-13 16:33:54.239  5682  5682 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 16:33:54.239  5682  5682 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 16:33:54.239  5682  5682 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:33:54.239  5682  5682 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:33:54.239  5682  5682 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 16:33:54.269  5682  5682 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-13 16:33:54.279  1018  1306 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-13 16:33:54.279  1018  1306 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 16:33:54.279  1018  1306 D InputDispatcher: Focused application set to: xxxx
,09-13 16:33:54.279  1018  1306 D InputDispatcher: Focus entered window: 6845
,09-13 16:33:54.279  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-13 16:33:54.279  1018  1347 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 16:33:54.279  1018  1347 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@803cc6 attribute=null, token = android.os.BinderProxy@1557923f
,09-13 16:33:54.279  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 16:33:54.319  5682  5682 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-13 16:33:54.329  5682  5682 D PhoneWindow: *FMB* installDecor mIsFloating : true
,09-13 16:33:54.329  5682  5682 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-13 16:33:54.349  6845  6845 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 16:33:54.349  6845  6845 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-13 16:33:54.349  6845  6845 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 16:33:54.349  6845  6845 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-13 16:33:54.349  1018  1306 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 16:33:54.349  1018  1306 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 16:33:54.349  1018  1306 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-13 16:33:54.349  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-13 16:33:54.349  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 16:33:54.369  6845  6845 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:33:54.369  6845  6845 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 16:33:54.369  6845  6845 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@60541eb Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2073adc6, 16908290=android.view.AbsSavedState$1@2073adc6}, android:focusedViewId=100}]}]
09-13 16:33:54.369  6845  6845 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 16:33:54.369  6845  6845 V ActivityThread: updateVisibility : ActivityRecord{1c30cd5 token=android.os.BinderProxy@6db72bf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-13 16:33:54.369  6845  6845 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 16:33:54.369  6845  6845 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 16:33:54.379  6845  6845 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6db72bf time:118971
,09-13 16:33:54.379  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:33:54.429  6845  6845 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 16:33:54.429  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 16:33:54.429  6845  6845 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:33:54.449  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 16:33:54.449  3165  3165 D BtGatt.ScanManager: awakened up at time 119044
,09-13 16:33:54.449  3165  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:33:54.449  3165  3271 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 16:33:54.449  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:54.619   289   289 E SMD     : DCD OFF
,09-13 16:33:54.629   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-13 16:33:54.949  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 16:33:54.959  3165  3165 D BtGatt.ScanManager: awakened up at time 119551
,09-13 16:33:54.959  3165  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:33:54.959  3165  3271 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 16:33:54.959  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:55.459  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 16:33:55.469  1018  1097 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.479  3165  3165 D BtGatt.ScanManager: awakened up at time 120076
,09-13 16:33:55.479  3165  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:33:55.489  3165  3271 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
,09-13 16:33:55.489  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:55.489  3165  3271 D BtGatt.GattService: current time is 120081524431
09-13 16:33:55.489  3165  3271 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, -111, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,09-13 16:33:55.489  3165  3271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-13 16:33:55.489  3165  3271 D ScanRecord: parseFromBytes
09-13 16:33:55.489  3165  3271 D ScanRecord: first manudata for manu ID
09-13 16:33:55.489  3165  3271 D BtGatt.GattService: result: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-81, mTimestampNanos=112831836046}
09-13 16:33:55.489  3165  3271 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 16:33:55.489  6845  6853 D ScanRecord: parseFromBytes
,09-13 16:33:55.489  6845  6853 D ScanRecord: first manudata for manu ID
,09-13 16:33:55.509  2006  2006 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-13 16:33:55.549  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:55.549  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.549  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.549  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:55.549  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.589  4744  4744 D ConnectivityManager: CallingUid : 10011, CallingPid : 4744
,09-13 16:33:55.599  1018  7092 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 16:33:55.599  1018  1130 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-13 16:33:55.599  1018  1130 D ConnectivityService: apparently satisfied.  currentScore=60
,09-13 16:33:55.599  1018  1130 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
09-13 16:33:55.599  4744  7624 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 16:33:55.639  4744  7625 W DriveInitializer: Background init thread started
,09-13 16:33:55.679   258   533 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-13 16:33:55.679   258   533 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 16:33:55.679  4744  7625 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-13 16:33:55.739  1018  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:55.739  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IcingGcmTaskService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.739  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.739  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:55.739  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.749  4744  7625 W DriveInitializer: Background init thread ended
,09-13 16:33:55.749  1018  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:55.749  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.749  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.759  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:55.759  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.769  1018  1306 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:55.769  1018  1306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.769  1018  1306 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.769  1018  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:55.769  1018  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.779  1018  1499 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:55.779  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.789  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.789  1018  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:55.789  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.799  4744  5116 I Icing   : Performing maintenance.
,09-13 16:33:55.799  1018  4349 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:55.799  1018  4349 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.799  1018  4349 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:55.799  1018  4349 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:55.799  1018  4349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.799  1018  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:55.809  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.809  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:55.809  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.809  1018  1499 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 16:33:55.809  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.819  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 16:33:55.819  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:33:55.819  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.819  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:55.819  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.829  1018  1480 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-13 16:33:55.829  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-13 16:33:55.829  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.829  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:55.829  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.889  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:55.899  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:55.899  2006  2006 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 16:33:55.929  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.929  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:55.929  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.929  1018  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:55.929  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:55.929  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:55.929  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:55.989  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 16:33:55.989  3165  3165 D BtGatt.ScanManager: awakened up at time 120584,
09-13 16:33:55.989  3165  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:33:55.999  1018  6724 I art     : Explicit concurrent mark sweep GC freed 33085(1922KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/37MB, paused 3.017ms total 157.451ms
,09-13 16:33:55.999  3165  3271 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-13 16:33:55.999  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:56.029  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:56.029  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-13 16:33:56.029  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:56.029  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:56.029  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.039  4744  7636 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-13 16:33:56.049  4744  7641 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-13 16:33:56.059  4744  7641 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-13 16:33:56.069  1018  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:56.069  1018  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-13 16:33:56.069  1018  1480 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:56.069  1018  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:56.069  1018  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.139  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:56.139  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:56.149  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:56.149  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.209  1018  1556 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:56.209  1018  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-13 16:33:56.209  1018  1556 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:56.209  1018  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.209  1018  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.229  1018  1556 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-13 16:33:56.229  1018  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-13 16:33:56.229  1018  1556 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:56.229  1018  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.229  1018  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.249  1018  7092 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:56.249  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:56.249  1018  7092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.249  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.319  1018  7092 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:56.319  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:56.319  1018  7092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.319  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.319  1018  7092 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:56.319  1018  7092 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:56.319  1018  7092 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:56.319  1018  7092 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:56.339  7646  7646 E Zygote  : MountEmulatedStorage()
,09-13 16:33:56.339  7646  7646 E Zygote  : v2
09-13 16:33:56.339  7646  7646 I libpersona: KNOX_SDCARD checking this for 10011
09-13 16:33:56.339  7646  7646 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:56.339  7646  7646 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:56.339  1018  7092 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7646 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-13 16:33:56.339  7646  7646 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:33:56.339  2006  2164 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-13 16:33:56.339  2006  2164 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
09-13 16:33:56.339  2006  2164 I System.out: (HTTPLog)-Static: isShipBuild true
09-13 16:33:56.339  2006  2164 I System.out: (HTTPLog)-Thread-189-545518932: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-13 16:33:56.339  2006  2164 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 16:33:56.339  7646  7646 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:33:56.349   279   921 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 16:33:56.349   279   921 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 16:33:56.349  2006  2164 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 16:33:56.349  2006  2164 I qtaguid : Tagging socket 58 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2006, getuid(): 10011
,09-13 16:33:56.369  7646  7646 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:56.369  7646  7646 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:56.389  7646  7646 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-13 16:33:56.389  7646  7646 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 16:33:56.429  7646  7646 I MultiDex: VM with version 2.1.0 has multidex support
09-13 16:33:56.429  7646  7646 I MultiDex: install
09-13 16:33:56.429  7646  7646 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 16:33:56.459  7646  7646 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 16:33:56.489  2006  2164 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2006, getuid(): 10011
,09-13 16:33:56.509  1018  1097 V AlarmManager: waitForAlarm result :4
,09-13 16:33:56.509  3165  3165 D BtGatt.ScanManager: awakened up at time 121105
,09-13 16:33:56.509  3165  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:33:56.509  3165  3271 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 16:33:56.509  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:56.519  7646  7646 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 16:33:56.519  7646  7646 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@329ad066: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-13 16:33:56.519  7646  7646 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 16:33:56.539  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-13 16:33:56.539  7646  7646 D ChimeraCfgMgr: Reading stored module config
,09-13 16:33:56.559  1018  7092 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:56.559  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:56.559  1018  7092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.559  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.559  1018  6724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,09-13 16:33:56.559  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:56.559  1018  6724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.559  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.599  2006  2006 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=b95c3eb8-e1b7-4b57-89f2-cbd9abe0e111
,09-13 16:33:56.609  7646  7660 I art     : Background sticky concurrent mark sweep GC freed 26001(1233KB) AllocSpace objects, 2(32KB) LOS objects, 2% free, 7MB/7MB, paused 12.169ms total 52.194ms
,09-13 16:33:56.649  7646  7666 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-13 16:33:56.649  7646  7646 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 16:33:56.649  7646  7646 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 16:33:56.729  6773  7064 I art     : Explicit concurrent mark sweep GC freed 1386(59KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 1.841ms total 24.164ms
,09-13 16:33:56.739   284   284 D WVCdm   : Instantiating CDM.
,09-13 16:33:56.739   284   807 I WVCdm   : CdmEngine::OpenSession
,09-13 16:33:56.739   284   807 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-13 16:33:56.769   284   807 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-13 16:33:56.789   284   807 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-13 16:33:56.829  7646  7662 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-13 16:33:56.829  7646  7662 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 16:33:56.829  7646  7662 I System.out: (HTTPLog)-Static: isShipBuild true
,09-13 16:33:56.829  7646  7662 I System.out: (HTTPLog)-Thread-1420-181339067: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-13 16:33:56.829  7646  7662 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:33:56.829   279   921 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 16:33:56.829   279   921 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 16:33:56.849   284   807 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-13 16:33:56.849   284   284 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-13 16:33:56.849   284   284 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-13 16:33:56.849   284   284 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-13 16:33:56.849   284   284 D WVCdm   : PrepareKeyRequest: nonce=620523788
,09-13 16:33:56.859  2006  2157 W GCoreFlp: No location to return for getLastLocation()
,09-13 16:33:56.939  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:33:56.939  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:33:56.939  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:33:56.939  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48b0e6d not in the list
09-13 16:33:56.939  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:33:56.939  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:33:56.939  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:33:56.939  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:33:56.939  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:33:56.939  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 16:33:56.939  3165  3176 D BtGatt.GattService: stopScan() - queue size =1
,09-13 16:33:56.939  3165  3282 D BtGatt.ScanManager: filter size is 1
,09-13 16:33:56.939  3165  3282 D BtGatt.ScanManager: delete FilterIndex - 3
,09-13 16:33:56.949  3165  3271 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 16:33:56.949  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:56.949  3165  3274 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 16:33:56.949  3165  3282 D BtGatt.ScanManager: stopping BLe Batch
,09-13 16:33:56.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:33:56.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 16:33:56.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 16:33:56.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 16:33:56.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 16:33:56.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:33:56.949  3165  3271 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 16:33:56.949  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 16:33:56.949  3165  3282 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 16:33:56.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:33:56.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:33:56.949  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:33:56.949  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:56.959  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:33:56.959  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:33:56.959  7646  7662 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 16:33:56.959  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:33:56.959  7646  7662 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 7646, getuid(): 10011
,09-13 16:33:56.959  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e88aa2 not in the list
,09-13 16:33:56.959  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:33:56.959  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:33:56.959  3165  3271 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=4
09-13 16:33:56.959  3165  3271 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 16:33:56.959  3165  3271 D BtGatt.GattService: current time is 121558060993
09-13 16:33:56.959  3165  3271 D BtGatt.GattService: Batch record : [77, -3, -4, 78, -104, 86, 1, -128, -61, -43, 5, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 71, -122, -77, 84, 69, -12, 1, -128, -66, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 103, 82, 8, 75, 14, 106, 1, -128, -90, -95, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -69, 45, -84, 104, -41, 48, 1, 58, -36, -27, -120, 80, -122, 0, 81, 34, 97, 112, -14, -5, 1, -128, -71, 6, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 16:33:56.959  3165  3271 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
09-13 16:33:56.959  3165  3271 D ScanRecord: parseFromBytes
09-13 16:33:56.959  3165  3271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 16:33:56.959  3165  3271 D ScanRecord: parseFromBytes
09-13 16:33:56.959  3165  3271 D ScanRecord: first manudata for manu ID
09-13 16:33:56.959  3165  3271 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -69, 45, -84, 104, -41, 48, 1, 58, -36, -27, -120, 80, -122],
09-13 16:33:56.959  3165  3271 D ScanRecord: parseFromBytes
09-13 16:33:56.959  3165  3271 D ScanRecord: first manudata for manu ID
09-13 16:33:56.959  3165  3271 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 16:33:56.959  3165  3271 D ScanRecord: parseFromBytes
09-13 16:33:56.959  3165  3271 D ScanRecord: first manudata for manu ID
,09-13 16:33:56.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:33:56.969  6845  7152 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-13 16:33:56.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-13 16:33:56.969  2006  2157 I art     : Explicit concurrent mark sweep GC freed 69204(3MB) AllocSpace objects, 10(208KB) LOS objects, 40% free, 11MB/18MB, paused 1.638ms total 84.500ms
,09-13 16:33:56.969  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:56.969  6845  7152 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:33:56.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:33:56.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:33:56.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:33:56.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:33:56.969  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:33:56.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:33:56.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:33:56.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:33:56.969  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:33:56.969  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-13 16:33:56.979  6845  7152 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:33:56.979  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:56.979  6845  7676 D BluetoothSocket: bindListen(): myUserId = 0
09-13 16:33:56.979  6845  7676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:33:56.979  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:56.979  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.979  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.989  6845  7676 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-13 16:33:56.989  6845  7676 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 16:33:56.989  6845  7676 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 16:33:56.989  6845  7676 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26196cdd
09-13 16:33:56.989  6845  7676 D BluetoothSocket: channel: 6
,09-13 16:33:56.989  6845  7676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:33:56.989  1018  1306 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:56.989  1018  1306 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:56.989  1018  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.989  1018  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.989  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:33:56.989  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:33:56.989  1018  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:56.999  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:56.999  1018  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:56.999  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:56.999  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:33:56.999  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-13 16:33:56.999  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 08 EC A9 50 76 27
09-13 16:33:56.999  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:56.999  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 8, -20, -87, 80, 118, 39]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:33:56.999  6845  7152 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-13 16:33:57.009  3165  3176 D BtGatt.GattService: registerClient() - UUID=9add4f93-1b83-452b-9e30-60aa624df083
,09-13 16:33:57.009  4744  7644 D UdcContextInitService: registered all accounts: true
,09-13 16:33:57.019  2006  2160 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 16:33:57.029  2006  2165 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-13 16:33:57.049  3165  3271 D BtGatt.GattService: onClientRegistered() - UUID=9add4f93-1b83-452b-9e30-60aa624df083, clientIf=6
,09-13 16:33:57.049  6845  6854 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-13 16:33:57.049  3165  3280 D BtGatt.AdvertiseManager: message : 0
,09-13 16:33:57.049  3165  3280 D BtGatt.AdvertiseManager: number of adv instance running0
,09-13 16:33:57.049  3165  3280 D BtGatt.AdvertiseManager: size of list is =0
,09-13 16:33:57.049  3165  3280 D BtGatt.AdvertiseManager: starting advertising
,09-13 16:33:57.049  3165  3280 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-13 16:33:57.059  3165  3271 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-13 16:33:57.059  3165  3280 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:33:57.059  3165  3271 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-13 16:33:57.069  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-13 16:33:57.069  3165  3280 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-13 16:33:57.069  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:33:57.069  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:33:57.069  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:33:57.069  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:33:57.069  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:33:57.069  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:33:57.069  6845  6845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:33:57.069  6845  6845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:33:57.069  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:33:57.079  6845  6845 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:57.079  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:33:57.139  4744  5116 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-13 16:33:57.139  4744  5116 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 16:33:57.139  4744  5116 I System.out: (HTTPLog)-Static: isShipBuild true
09-13 16:33:57.139  4744  5116 I System.out: (HTTPLog)-Thread-870-667872329: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-13 16:33:57.139  4744  5116 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:33:57.139   279   921 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 16:33:57.139   279   921 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 16:33:57.179  4744  5116 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 16:33:57.179  4744  5116 I qtaguid : Tagging socket 107 with tag 1000320000000000{268448256,0} for uid -1, pid: 4744, getuid(): 10011
,09-13 16:33:57.199  1018  1044 W ActivityManager: mDVFSHelper.release()
,09-13 16:33:57.199  1018  1556 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-13 16:33:57.199  1018  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-13 16:33:57.199  1018  1556 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:57.209  1018  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:57.209  1018  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:57.219  7646  7662 I qtaguid : Untagging socket 30
,09-13 16:33:57.389  4744  5116 I qtaguid : Untagging socket 107
,09-13 16:33:57.409  4744  5116 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:33:57.409  4744  5116 I qtaguid : Tagging socket 107 with tag 1000320000000000{268448256,0} for uid -1, pid: 4744, getuid(): 10011
,09-13 16:33:57.409  4744  5116 I qtaguid : Tagging socket 111 with tag 1000320000000000{268448256,0} for uid -1, pid: 4744, getuid(): 10011
,09-13 16:33:57.459  4744  5116 I qtaguid : Untagging socket 107
,09-13 16:33:57.459  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:57.469  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:57.469  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:57.469  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:57.469  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:57.469  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:57.469  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.googlequicksearchbox
09-13 16:33:57.469  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-13 16:33:57.469  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:57.469  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:57.469  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:57.479  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:57.489  1018  1044 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.UdcSettingBroadcastReceiver: pid=7682 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-13 16:33:57.489  1018  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:57.489  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:57.489  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:57.489  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:57.489  7682  7682 E Zygote  : MountEmulatedStorage()
09-13 16:33:57.489  7682  7682 I libpersona: KNOX_SDCARD checking this for 10052
09-13 16:33:57.489  7682  7682 E Zygote  : v2
,09-13 16:33:57.489  7682  7682 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:57.499  7682  7682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:33:57.499  7682  7682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:57.499  7682  7682 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:33:57.539  7682  7682 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:57.539  7682  7682 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:57.549  7690  7690 I dex2oat : ----------------------------------------------------
09-13 16:33:57.549  7690  7690 I dex2oat : <SS>: S T A R T I N G . . .
09-13 16:33:57.549  7690  7690 I dex2oat : <SS>: Zip is absent. Canceled.
,09-13 16:33:57.549  7690  7690 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 16:33:57.579  6845  6845 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:33:57.579  6845  6845 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:33:57.579  6845  6845 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:33:57.609  7690  7690 I dex2oat : dex2oat took 56.618ms (threads: 4)
,09-13 16:33:57.609   289   289 E SMD     : DCD OFF
,09-13 16:33:57.619  7646  7662 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 16:33:57.619  7646  7662 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 16:33:57.619  7646  7662 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 16:33:57.619  7646  7662 I Adreno-EGL: Local Branch: 
09-13 16:33:57.619  7646  7662 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 16:33:57.619  7646  7662 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 16:33:57.619  7646  7662 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 16:33:57.669  4744  5116 I Icing   : updateResources: need to parse ozd{com.google.android.gms},
,09-13 16:33:57.699  7646  7662 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 16:33:57.699  7646  7662 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 16:33:57.699  7646  7662 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 16:33:57.699  7646  7662 I Adreno-EGL: Local Branch: 
09-13 16:33:57.699  7646  7662 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 16:33:57.699  7646  7662 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 16:33:57.699  7646  7662 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 16:33:57.749  7646  7662 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 16:33:57.749  7646  7662 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 16:33:57.749  7646  7662 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 16:33:57.749  7646  7662 I Adreno-EGL: Local Branch: 
09-13 16:33:57.749  7646  7662 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 16:33:57.749  7646  7662 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 16:33:57.749  7646  7662 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 16:33:57.829  4744  5116 I Icing   : Performing maintenance usage 1823448 budget 4967754092 free 99.963% index free 99.974% purge? false target 3477427864
,09-13 16:33:57.839  1018  1472 D LocationManagerService: getProviders()=[passive]
,09-13 16:33:57.849  1018  1306 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,09-13 16:33:57.849  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:57.849  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:57.849  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:33:57.849  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:33:57.869  7709  7709 E Zygote  : MountEmulatedStorage(),
09-13 16:33:57.869  7709  7709 E Zygote  : v2
09-13 16:33:57.869  7709  7709 I libpersona: KNOX_SDCARD checking this for 10014
09-13 16:33:57.869  7709  7709 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:33:57.869  7709  7709 I libpersona: KNOX_SDCARD not a persona
,09-13 16:33:57.869  7709  7709 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:33:57.869  1018  1306 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7709 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,09-13 16:33:57.869  7709  7709 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:33:57.879  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:57.879  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:57.879  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 16:33:57.889  7709  7709 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:33:57.889  7709  7709 D ActivityThread: Added TimaKeyStore provider
,09-13 16:33:57.899  1018  4349 I ActivityManager: Killing 7301:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-13 16:33:57.979  1018  7092 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:57.989  1018  7092 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:57.989  1018  7092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:57.989  1018  7092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:57.989  4744  5016 I Icing   : Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,09-13 16:33:58.009  1018  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:58.009  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:58.009  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:58.009  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:58.019  1018  1499 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:58.019  1018  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:58.019  1018  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:58.019  1018  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:58.019  1018  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:58.039  1018  1556 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:58.039  1018  1556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:58.039  1018  1556 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:58.039  1018  1556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:58.039  1018  1556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:58.059  1018  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 16:33:58.059  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:58.059  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 16:33:58.059  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:58.159  2006  7643 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:33:58.169  2006  7643 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 16:33:58.169  2006  7643 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2006, getuid(): 10011
,09-13 16:33:58.169  1018  3384 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:33:58.199  2006  7643 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2006, getuid(): 10011,
,09-13 16:33:58.449   284   808 I WVCdm   : CdmEngine::CloseSession
,09-13 16:33:58.459   284   808 I WVCdm   : L3 Terminate.
,09-13 16:33:58.959  1018  3349 D SSRM:n  : SIOP:: AP = 360
,09-13 16:33:59.009  2006  2165 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 16:33:59.019  2006  2165 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-13 16:33:59.029  2006  2165 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-13 16:33:57.148+0200, stopTime=2016-09-13 16:33:59.044+0200, duration=1896ms
,09-13 16:33:59.039  2006  7732 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:33:59.039   279   921 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 16:33:59.039   279   921 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 16:33:59.049  2006  7732 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-13 16:33:59.049  2006  7732 I qtaguid : Tagging socket 69 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2006, getuid(): 10011
,09-13 16:33:59.089  2006  7732 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2006, getuid(): 10011
,09-13 16:33:59.099  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-13 16:33:59.339  2006  7732 I qtaguid : Untagging socket 69
,09-13 16:33:59.369  1018  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 16:33:59.369  1018  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-13 16:33:59.379  1018  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:59.379  1018  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:59.379  1018  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:59.409  2006  2165 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-13 16:33:59.479  1018  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:59.479  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:59.479  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:59.479  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:59.519  1018  1306 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:59.519  1018  1306 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:59.519  1018  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:59.519  1018  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:59.559  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:59.559  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:59.559  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:59.559  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:59.559  2006  7739 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 16:33:59.559  2006  7737 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 16:33:59.559  1018  6724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:59.559  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:59.559  1018  6724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:59.559  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:59.589  1018  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:59.589  1018  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:59.589  1018  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:59.589  1018  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:59.589  2006  7739 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 16:33:59.589  2006  7737 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 16:33:59.589  1018  1306 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 16:33:59.589  1018  1306 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:33:59.589  1018  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:59.589  1018  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:59.619  1018  4349 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 16:33:59.619  1018  4349 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:33:59.619  1018  4349 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:33:59.619  1018  4349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 16:33:59.619  2006  7739 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 16:33:59.619  2006  7737 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 16:33:59.619   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:33:59.629  2006  7737 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-13 16:33:59.629  2006  7737 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 16:33:59.669  1018  4349 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 16:33:59.829  1018  6724 I art     : Explicit concurrent mark sweep GC freed 25049(1330KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/37MB, paused 2.302ms total 150.816ms
,09-13 16:33:59.869  2006  7737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:33:59.869   279   921 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 16:33:59.869   279   921 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 16:33:59.869  2006  7737 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 16:33:59.869  2006  7737 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2006, getuid(): 10011
,09-13 16:33:59.909  2006  7737 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2006, getuid(): 10011
,09-13 16:33:59.989  1018  1097 V AlarmManager: waitForAlarm result :8,
,09-13 16:34:00.169  1018  1347 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 16:34:00.179  2006  7737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:34:00.179  2006  7737 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2006, getuid(): 10011
,09-13 16:34:00.319  1018  1031 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 16:34:00.329  2006  7737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:34:00.329  2006  7737 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2006, getuid(): 10011
,09-13 16:34:00.469  1018  1472 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 16:34:00.529  2006  7737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:34:00.529  2006  7737 I qtaguid : Tagging socket 58 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2006, getuid(): 10011
,09-13 16:34:00.579  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:34:00.579  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:34:00.579  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:34:00.579  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:34:00.579  6845  7152 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1da0af23, channel: 6, state: LISTENING
09-13 16:34:00.579  6845  7152 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1da0af23, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26196cdd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ad96c20mSocket: android.net.LocalSocket@3e44f9d9 impl:android.net.LocalSocketImpl@1e54af9e fd:FileDescriptor[109]
09-13 16:34:00.579  6845  7152 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e44f9d9 impl:android.net.LocalSocketImpl@1e54af9e fd:FileDescriptor[109]
09-13 16:34:00.579  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:34:00.579  6845  7152 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:34:00.579  6845  7676 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1da0af23, channel: 6, state: CLOSED
09-13 16:34:00.579  6845  7676 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:34:00.579  6845  7676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:34:00.579  6845  7676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:34:00.579  6845  6845 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:34:00.579  6845  6845 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:34:00.579  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48b0e6d not in the list
09-13 16:34:00.579  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:00.579  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:34:00.579  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:34:00.579  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:34:00.579  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:34:00.579  6845  7152 D BluetoothLeScanner: could not find callback wrapper
09-13 16:34:00.579  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:34:00.579  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:34:00.579  3165  3280 D BtGatt.AdvertiseManager: message : 1
09-13 16:34:00.579  3165  3280 D BtGatt.AdvertiseManager: stop advertise for client 6
09-13 16:34:00.579  3165  3280 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-13 16:34:00.579  3165  3280 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
09-13 16:34:00.589  3165  3271 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
09-13 16:34:00.589  3165  3271 D BtGatt.GattService: Client app is not null!
09-13 16:34:00.589  3165  3176 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 16:34:00.589  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:34:00.589  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:34:00.589  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:34:00.589  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:34:00.599  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:34:00.599  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:00.599  6845  7152 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:34:00.599  6845  7152 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:34:00.599  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:00.599  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:00.599  6845  6845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:34:00.599  6845  6845 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:34:00.599  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e88aa2 not in the list
09-13 16:34:00.599  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:00.599  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:00.599  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:00.609  6845  7152 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:34:00.609  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:00.609  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:00.609  6845  7152 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48b0e6d not in the list
09-13 16:34:00.609  6845  7152 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:34:00.609  6845  7152 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e88aa2 not in the list
09-13 16:34:00.609  6845  7152 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:34:00.609  6845  7152 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:34:00.609  6845  7152 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:34:00.609  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
09-13 16:34:00.609   289   289 E SMD     : DCD OFF
09-13 16:34:00.609  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:34:00.609  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 16:34:00.609  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:34:00.609  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:34:00.609  6845  7152 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 16:34:00.619  6845  7743 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1472, name: My test thread name)
09-13 16:34:00.619   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:34:00.659  2006  7737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:34:00.659  2006  7737 I qtaguid : Tagging socket 81 with tag fffffca200000000{4294966434,0} for uid -1, pid: 2006, getuid(): 10011
,09-13 16:34:00.819  1018  1480 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 16:34:00.829  2006  7737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:34:00.829  2006  7737 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 2006, getuid(): 10011
,09-13 16:34:01.099  6845  6845 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:34:01.169  2006  7731 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 16:34:01.169  2006  7731 I qtaguid : Tagging socket 69 with tag 1000310200000000{268448002,0} for uid 10011, pid: 2006, getuid(): 10011
,09-13 16:34:01.359  2006  7731 I qtaguid : Untagging socket 69
,09-13 16:34:01.359  2006  2165 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-13 16:34:01.389  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-13 16:34:01.619   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 16:34:01.669  1018  1136 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 16:34:01.679  1018  1136 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 16:34:01.679  1018  1136 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 16:34:01.679  1018  1136 D BatteryService: stay LED for fully charged
,09-13 16:34:01.679  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 16:34:01.679  1018  1018 I MotionRecognitionService: Plugged
,09-13 16:34:01.679  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 16:34:01.689  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 16:34:01.689  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 16:34:01.689  1409  1409 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 16:34:01.689  1409  1409 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 16:34:01.709  3165  3165 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 16:34:01.709  3165  3286 D HeadsetStateMachine: Disconnected process message: 10
,09-13 16:34:01.719  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:34:01.719  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:34:01.719  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 16:34:02.629  6845  7152 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1472,
09-13 16:34:02.629  6845  7152 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1472, name: My test thread name)
09-13 16:34:02.629  6845  7745 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1473, name: My test thread name)
09-13 16:34:02.629  6845  7745 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1473, thread name: My test thread name),
09-13 16:34:02.629  6845  7745 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1473, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 16:34:02.629   327   327 I ServiceManager: Waiting for service AtCmdFwd...
09-13 16:34:02.629  6845  7152 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:34:02.629  6845  7746 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1477, name: My test thread name)
,09-13 16:34:02.629  6845  7746 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1477, thread name: My test thread name): Test exception.
,09-13 16:34:02.629  6845  7746 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1477, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 16:34:02.629  6845  7152 I jxcore-log: Total number of executed tests:  76
09-13 16:34:02.629  6845  7152 I jxcore-log: 
,09-13 16:34:02.639  6845  7152 I jxcore-log: Number of passed tests:  76,
09-13 16:34:02.639  6845  7152 I jxcore-log: 
09-13 16:34:02.639  6845  7152 I jxcore-log: Number of failed tests:  0
09-13 16:34:02.639  6845  7152 I jxcore-log: 
,09-13 16:34:02.639  6845  7152 I jxcore-log: Number of ignored tests:  0
09-13 16:34:02.639  6845  7152 I jxcore-log: 
,09-13 16:34:02.639  6845  7152 I jxcore-log: Total duration:  15712
09-13 16:34:02.639  6845  7152 I jxcore-log: 
,09-13 16:34:02.639  6845  7152 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:34:02.639  6845  7152 I jxcore-log: 
,09-13 16:34:02.639  6845  7152 I jxcore-log: My device name is: samsung-SM-A300FU
09-13 16:34:02.639  6845  7152 I jxcore-log: 
09-13 16:34:02.649  6845  7152 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 16:34:02.649  6845  7152 I jxcore-log: 
09-13 16:34:02.659  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:02.659  6845  7152 I jxcore-log: 
09-13 16:34:02.659  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:02.659  6845  7152 I jxcore-log: 
09-13 16:34:02.659  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:02.659  6845  7152 I jxcore-log: 
,09-13 16:34:02.659  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:02.659  6845  7152 I jxcore-log: 
,09-13 16:34:02.669  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:02.669  6845  7152 I jxcore-log: 
,09-13 16:34:02.679  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:02.679  6845  7152 I jxcore-log: 
,09-13 16:34:02.679  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:02.679  6845  7152 I jxcore-log: 
,09-13 16:34:02.679  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:34:02.679  6845  7152 I jxcore-log: 
,09-13 16:34:02.679  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:02.679  6845  7152 I jxcore-log: 
,09-13 16:34:02.679  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 16:34:02.679  6845  7152 I jxcore-log: 
,09-13 16:34:02.679  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:34:02.679  6845  7152 I jxcore-log: 
,09-13 16:34:02.689  6845  7152 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:34:02.689  6845  7152 I jxcore-log: 
,09-13 16:34:02.709  6845  7743 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1472, name: My test thread name), during the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187,
,09-13 16:34:02.949  7747  7747 D AndroidRuntime: 
09-13 16:34:02.949  7747  7747 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 16:34:02.949  7747  7747 D AndroidRuntime: CheckJNI is OFF,
09-13 16:34:02.959  7747  7747 D AndroidRuntime: readGMSProperty: start
09-13 16:34:02.959  7747  7747 D AndroidRuntime: readGMSProperty: already setted!!
09-13 16:34:02.959  7747  7747 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 16:34:02.959  7747  7747 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 16:34:02.959  7747  7747 D AndroidRuntime: readGMSProperty: end
09-13 16:34:02.959  7747  7747 D AndroidRuntime: addProductProperty: start
,09-13 16:34:03.079  7747  7747 E AffinityControl: AffinityControl: registerfunction enter,
,09-13 16:34:03.109  7747  7747 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 16:34:03.119  1018  1306 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-13 16:34:03.119  1018  1306 D PackageManager: START PACKAGE DELETE: observer{200296226}
09-13 16:34:03.119  1018  1306 D PackageManager: pkg{<packageName>}
09-13 16:34:03.119  1018  1306 D PackageManager: user{0}
09-13 16:34:03.119  1018  1306 D PackageManager: caller{2000}
09-13 16:34:03.119  1018  1306 D PackageManager: flags{2}
09-13 16:34:03.119  1018  1306 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 16:34:03.119  1018  1306 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-13 16:34:03.119  1018  1306 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 16:34:03.119  1018  1306 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-13 16:34:03.119  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-13 16:34:03.119  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-13 16:34:03.119  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 16:34:03.119  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 16:34:03.119  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 16:34:03.119  1018  1058 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-13 16:34:03.129  1018  1044 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-13 16:34:03.129  1018  1044 I ActivityManager: Killing 6845:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-13 16:34:03.129  1018  1044 I ActivityManager:   Force finishing activity ActivityRecord{3d71ef9 u0 com.test.thalitest/.MainActivity t2}
09-13 16:34:03.129  1018  1044 D InputDispatcher: Focus left window: 6845
,09-13 16:34:03.139   259  1040 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,09-13 16:34:03.139   259   456 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-13 16:34:03.149  1018  1044 D InputDispatcher: Focused application released
,09-13 16:34:03.149  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 16:34:03.149  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 16:34:03.149  1018  1044 D FocusedStackFrame: Set to : 0
,09-13 16:34:03.149  1018  1044 W ActivityManager: mDVFSHelper.acquire()
,09-13 16:34:03.209  1018  1058 W PackageSettings: Skipping PackageSetting{33baf75a com.example.hello/10168} due to missing metadata
,09-13 16:34:03.229  1018  1044 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-13 16:34:03.239  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-13 16:34:03.249  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-13 16:34:03.269  2643  2643 I art     : Explicit concurrent mark sweep GC freed 2497(121KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 759us total 20.965ms
,09-13 16:34:03.299  1482  1482 D Launcher: onRestart, Launcher: 502208113
,09-13 16:34:03.309  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 16:34:03.319  4744  4744 I art     : Explicit concurrent mark sweep GC freed 38321(2MB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 12MB/21MB, paused 1.343ms total 73.907ms
,09-13 16:34:03.319  1018  1018 D RCPManagerService: PackageReceiver onReceive()
09-13 16:34:03.319  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-13 16:34:03.319  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-13 16:34:03.319  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 16:34:03.319  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-13 16:34:03.319  1876  1876 E SamsungIME: mOCRHelper is null
,09-13 16:34:03.329  2006  2160 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.,
,09-13 16:34:03.339  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,09-13 16:34:03.339  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-13 16:34:03.349  1018  1125 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-13 16:34:03.349  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 16:34:03.349  1018  1125 V NetworkStats: performPollLocked(flags=0x3)
,09-13 16:34:03.349  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-13 16:34:03.349  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 16:34:03.369  1018  7092 I ActivityManager: Killing 6644:com.samsung.android.sm/1000 (adj 15): empty #21
,09-13 16:34:03.369  1482  1482 D Launcher: onStart, Launcher: 502208113
,09-13 16:34:03.369  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 16:34:03.369  1018  1125 V NetworkStats: performPollLocked() took 21ms
,09-13 16:34:03.369  1482  1482 D Launcher.HomeView: onStart
,09-13 16:34:03.369  1482  1482 D Launcher: onResume, Launcher: 502208113
,09-13 16:34:03.379  1018  1556 D SettingsProvider: name = kids_home_mode
09-13 16:34:03.379  1018  1556 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 16:34:03.379  1018  1556 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 16:34:03.379  1018  1556 D SettingsProvider: selectionArgs: false
09-13 16:34:03.379  1018  1556 D SettingsProvider: selectionArgs: 10006
09-13 16:34:03.379  1018  1556 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 16:34:03.379  1018  1556 D SettingsProvider: ret = -1
,09-13 16:34:03.379  1482  1482 D Launcher.HomeView: onResume
,09-13 16:34:03.379  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:34:03.389  2900  2900 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 13 16:34:03 GMT+02:00 2016
,09-13 16:34:03.389  1438  1438 D RegisteredServicesCache: empty dynamic service
,09-13 16:34:03.389  1018  6724 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-13 16:34:03.389  1018  6724 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-13 16:34:03.389  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
,09-13 16:34:03.399  1018  6724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:03.399  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-13 16:34:03.399  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-13 16:34:03.399  2900  2900 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-13 16:34:03.409  1018  7092 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
09-13 16:34:03.409  1018  7092 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-13 16:34:03.409  7473  7473 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-13 16:34:03.419  1018  1031 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-13 16:34:03.419  1482  1482 D MenuAppsGridFragment: onResume
,09-13 16:34:03.419  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-13 16:34:03.419  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:03.419  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:03.419  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-13 16:34:03.429  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-13 16:34:03.429  7473  7473 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-13 16:34:03.429  1482  1482 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-13 16:34:03.429  7473  7473 D elm:15121: ElmAgentService : onCreate()
,09-13 16:34:03.429  7473  7761 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-13 16:34:03.429  7473  7761 D elm:15121: MainReceiver.listeningToPackageRemoved()
,09-13 16:34:03.429  7473  7761 D elm:15121: MDMBridge.getInstance()
09-13 16:34:03.429  7473  7761 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-13 16:34:03.449  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:34:03.449  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 16:34:03.449  1018  1478 D ActivityManager: handle home activity for 0
,09-13 16:34:03.449  1018  1478 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-13 16:34:03.449  1018  1478 D KnoxTimeoutHandler: post home show event for user 0
09-13 16:34:03.449  1018  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
09-13 16:34:03.449  1018  1478 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 16:34:03.449  1018  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-13 16:34:03.449  1018  1043 W TextServicesManagerService: no available spell checker services found
,09-13 16:34:03.449  1018  1478 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 16:34:03.449  1018  1478 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-13 16:34:03.449  7473  7761 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-13 16:34:03.449  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
09-13 16:34:03.459  1482  1482 D Launcher.HomeView: onPause
,09-13 16:34:03.459  1482  1482 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-13 16:34:03.459  2900  2900 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-13 16:34:03.469  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-13 16:34:03.479  1018  7092 I TactileAssist: enable value -1
,09-13 16:34:03.479  1018  7092 I TactileAssist: internal enable value -1
09-13 16:34:03.479  1018  7092 I TactileAssist: intensity value -1
09-13 16:34:03.479  1018  7092 I TactileAssist: saveAppList value true
,09-13 16:34:03.479  1018  6724 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-13 16:34:03.489  1018  6724 D SecContentProvider2: mCursor = null
,09-13 16:34:03.489  1018  7092 I TactileAssist: List of disabled apps :
,09-13 16:34:03.489  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.489  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.489  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.489  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:03.489  2900  2900 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 16:34:03.489  2900  2900 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 16:34:03.499  7762  7762 E Zygote  : MountEmulatedStorage()
,09-13 16:34:03.499  7762  7762 E Zygote  : v2
09-13 16:34:03.499  7762  7762 I libpersona: KNOX_SDCARD checking this for 1000
,09-13 16:34:03.499  7762  7762 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:03.499  7762  7762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 16:34:03.499  1018  1058 I art     : Explicit concurrent mark sweep GC freed 30964(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/37MB, paused 6.684ms total 246.949ms
09-13 16:34:03.509  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:03.509  1018  1044 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7762 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 16:34:03.509  7762  7762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:34:03.509  7762  7762 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:34:03.509  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
09-13 16:34:03.509  7473  7473 D elm:15121: ElmAgentService : onDestroy().
09-13 16:34:03.509  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.509  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.509  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.509  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.509  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:34:03.519  2900  7760 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-13 16:34:03.519  2900  7760 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-13 16:34:03.529   308   308 I art     : Explicit concurrent mark sweep GC freed 8675(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 19.671ms
,09-13 16:34:03.529  2900  7760 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-13 16:34:03.539  2900  7760 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-13 16:34:03.539   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.509ms
,09-13 16:34:03.549  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:03.559  1018  1058 D PackageManager: delete codoeFile: 
,09-13 16:34:03.569  7762  7762 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-13 16:34:03.569  7762  7762 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:03.569   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 25.373ms
,09-13 16:34:03.569  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-13 16:34:03.579  7777  7777 E Zygote  : MountEmulatedStorage()
09-13 16:34:03.579  7777  7777 E Zygote  : v2
09-13 16:34:03.579  7777  7777 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:03.579  7777  7777 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:03.579  7777  7777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 16:34:03.579  1018  1058 I AASA_removePackage: UID=10171 Target=com.test.thalitest,
,09-13 16:34:03.579  7777  7777 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:03.579  1018  1044 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7777 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:34:03.579  7777  7777 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:03.589  1018  1058 D PackageManager: result of delete: 1{200296226}
,09-13 16:34:03.589  7747  7747 D AndroidRuntime: Shutting down VM
,09-13 16:34:03.599  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:03.609   289   289 E SMD     : DCD OFF
,09-13 16:34:03.609  7777  7777 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:03.619  7777  7777 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:03.619   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
09-13 16:34:03.619  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-13 16:34:03.619  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-13 16:34:03.619  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 16:34:03.619  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.619  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.619  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.619  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-13 16:34:03.619  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicy: uID is 10171
09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-13 16:34:03.619  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-13 16:34:03.619  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,09-13 16:34:03.619  1018  1018 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-13 16:34:03.629  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-13 16:34:03.629   327   327 I ServiceManager: Waiting for service AtCmdFwd...
09-13 16:34:03.629  1018  1472 D InputDispatcher: Focus entered window: 1482
,09-13 16:34:03.629  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 16:34:03.629  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 16:34:03.629  1482  1482 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 16:34:03.639  7793  7793 E Zygote  : MountEmulatedStorage()
,09-13 16:34:03.639  7793  7793 I libpersona: KNOX_SDCARD checking this for 10048
09-13 16:34:03.639  7793  7793 E Zygote  : v2
09-13 16:34:03.639  7793  7793 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:03.649  1018  1031 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7793 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
09-13 16:34:03.649  7793  7793 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:03.649  7793  7793 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:03.649  7793  7793 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 16:34:03.649  1018  1044 W ActivityManager: mDVFSHelper.release()
,09-13 16:34:03.659  1482  1482 D Launcher.HomeView: onStop
09-13 16:34:03.659  1482  1482 V ActivityThread: updateVisibility : ActivityRecord{1e4e70a8 token=android.os.BinderProxy@2880f30f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,09-13 16:34:03.659  2900  7760 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
09-13 16:34:03.659  1018  1499 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 16:34:03.659  1018  1499 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6845 uid 10171
,09-13 16:34:03.669  1018  7802 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 16:34:03.679  7762  7762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-13 16:34:03.679  1876  1876 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-13 16:34:03.679  1018  1306 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-13 16:34:03.679  1018  1306 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-13 16:34:03.679  1018  1306 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:03.679  1018  1306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:03.679  1018  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-13 16:34:03.689  7793  7793 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:03.689  7793  7793 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:03.689  1018  1136 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-13 16:34:03.689  2900  7760 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-13 16:34:03.699  2900  7760 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-13 16:34:03.699  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.699  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.699  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.699  1018  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:03.699  7777  7777 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,09-13 16:34:03.709  7811  7811 E Zygote  : MountEmulatedStorage(),
09-13 16:34:03.709  7811  7811 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:03.709  7811  7811 E Zygote  : v2
09-13 16:34:03.709  7811  7811 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:03.719  7811  7811 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 16:34:03.719  7811  7811 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:03.719  7811  7811 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:03.719  1018  1136 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7811 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:34:03.729  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 16:34:03.729  1018  3349 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-13 16:34:03.729  1018  1472 D SecContentProvider2: uri = -1 selection = getSealedState
09-13 16:34:03.729  1018  1472 D SecContentProvider2: mCursor = null
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicy: uID is 10171
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-13 16:34:03.729  7777  7777 I PopupuiReceiver_KNOX: getSealedState : true
09-13 16:34:03.729  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-13 16:34:03.729  1018  1481 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
09-13 16:34:03.729  1018  1481 D SecContentProvider2: mCursor = null
09-13 16:34:03.729  7777  7777 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
09-13 16:34:03.729  1018  7092 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-13 16:34:03.729  1018  7092 D SecContentProvider2: mCursor = null
09-13 16:34:03.729  1018  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-13 16:34:03.729  7777  7777 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-13 16:34:03.729  7777  7777 D PopupuiReceiver: Action package removed
09-13 16:34:03.729  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-13 16:34:03.739  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:03.739  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:03.739  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-13 16:34:03.739  7811  7811 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:34:03.739  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.739  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.739  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.739  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:03.739  7811  7811 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:03.749  2900  2900 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-13 16:34:03.749  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:03.759  1018  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 16:34:03.759  1018  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:34:03.759  1018  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 16:34:03.759  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:03.759  7826  7826 E Zygote  : MountEmulatedStorage()
09-13 16:34:03.759  7826  7826 I libpersona: KNOX_SDCARD checking this for 1000
09-13 16:34:03.759  7826  7826 E Zygote  : v2
09-13 16:34:03.759  7826  7826 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:03.759  7826  7826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:03.769  1018  1018 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7826 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 16:34:03.769  7826  7826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:34:03.769  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-13 16:34:03.769  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-13 16:34:03.769  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
09-13 16:34:03.769  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-13 16:34:03.769  7826  7826 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:34:03.769  1018  4349 I ActivityManager: Killing 7354:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
09-13 16:34:03.769  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:03.769  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 16:34:03.779  7793  7793 D Compatibility: onReceive() it will make start service
,09-13 16:34:03.779  1018  4349 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast,
09-13 16:34:03.779  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.779  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.779  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.779  1018  4349 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.779  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:03.779  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 16:34:03.789  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:03.789  1178  1178 I StatusBar: Icon Only
,09-13 16:34:03.789  1178  1178 D PanelView: There is/are notification(s) 
,09-13 16:34:03.789  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-13 16:34:03.789  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 16:34:03.789  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:03.799  7837  7837 I libpersona: KNOX_SDCARD checking this for 10145
09-13 16:34:03.789  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-13 16:34:03.799  7837  7837 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:03.789  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 16:34:03.799  1018  4349 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7837 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 16:34:03.799  7747  7747 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-13 16:34:03.799  7837  7837 E Zygote  : MountEmulatedStorage()
09-13 16:34:03.799  7837  7837 E Zygote  : v2
09-13 16:34:03.799  7837  7837 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:03.799  7837  7837 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:03.799  1018  4349 I ActivityManager: Killing 7311:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-13 16:34:03.809  7837  7837 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 16:34:03.809  1018  1031 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-13 16:34:03.809  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
09-13 16:34:03.809  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:03.809  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 16:34:03.809  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-13 16:34:03.819  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
,09-13 16:34:03.819  1018  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-13 16:34:03.819  1018  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-13 16:34:03.819  1018  1162 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,09-13 16:34:03.829  7826  7826 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:34:03.829  7826  7826 D ActivityThread: Added TimaKeyStore provider
09-13 16:34:03.829  7793  7848 D Compatibility: onHandleIntent()
,09-13 16:34:03.829  7793  7848 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-13 16:34:03.829  7837  7837 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:03.839  7793  7848 D Compatibility: found: 2
09-13 16:34:03.839  7837  7837 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:03.839  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{21669b86 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:128432
,09-13 16:34:03.839  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 16:34:03.839  1018  1058 D PackageManager: userId{-1}
09-13 16:34:03.839  1018  1058 D PackageManager: andCode{true}
,09-13 16:34:03.849  7793  7848 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 16:34:03.849  1018  1136 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-13 16:34:03.849  1018  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-13 16:34:03.849  1018  1136 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:03.849  1018  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:03.849  1018  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-13 16:34:03.849  7793  7848 D Compatibility: skipping ResolveInfo{38e3cd00 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-13 16:34:03.849  7793  7848 D Compatibility: considering ResolveInfo{2f747939 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-13 16:34:03.849  7793  7848 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 16:34:03.849  7793  7848 D Compatibility: enabling receiver ResolveInfo{2c9d2b7e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 16:34:03.849  7811  7811 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 16:34:03.849  7793  7848 D Compatibility: enabling receiver ResolveInfo{3a018df com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 16:34:03.849  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-13 16:34:03.859  1018  6724 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-13 16:34:03.859  1018  6724 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 16:34:03.859  1018  6724 W ActivityManager: userId = 0, bbcId = -10000
09-13 16:34:03.859  1018  6724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 16:34:03.859  1018  6724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 16:34:03.869  7793  7848 D Compatibility: enabling receiver ResolveInfo{2e38b92c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 16:34:03.869  7793  7848 D Compatibility: enabling receiver ResolveInfo{1a9a6ff5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 16:34:03.879  7793  7848 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-13 16:34:03.889  1018  1306 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-13 16:34:03.889  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.889  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.889  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.889  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.889  7826  7826 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-13 16:34:03.889  7826  7826 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-13 16:34:03.889  7826  7826 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-13 16:34:03.889  7811  7811 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-13 16:34:03.899  1018  1030 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0,
09-13 16:34:03.899  1018  1030 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-13 16:34:03.899  7862  7862 E Zygote  : MountEmulatedStorage()
09-13 16:34:03.899  7862  7862 E Zygote  : v2
09-13 16:34:03.899  7862  7862 I libpersona: KNOX_SDCARD checking this for 10055
09-13 16:34:03.899  7862  7862 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:03.899  7862  7862 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:03.909  7862  7862 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 16:34:03.909  1018  1306 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7862 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
09-13 16:34:03.909  7862  7862 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:03.909  7837  7837 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-13 16:34:03.909  7837  7837 D ThemeInfoUtil: isCurrentFestival = false
,09-13 16:34:03.909  1018  1306 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-13 16:34:03.919  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:03.919  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.919  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.919  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.919  7826  7826 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-13 16:34:03.919  7826  7826 I PCWCLIENTTRACE_PushUtil: sales region : global
09-13 16:34:03.919  7826  7826 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 16:34:03.919  7826  7826 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-13 16:34:03.929  1018  1306 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7877 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,09-13 16:34:03.939  7877  7877 E Zygote  : MountEmulatedStorage()
,09-13 16:34:03.939  7877  7877 E Zygote  : v2
09-13 16:34:03.939  7877  7877 I libpersona: KNOX_SDCARD checking this for 10087
09-13 16:34:03.939  7877  7877 I libpersona: KNOX_SDCARD not a persona
09-13 16:34:03.939  1018  1306 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-13 16:34:03.939  7862  7862 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 16:34:03.939  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.939  7877  7877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-13 16:34:03.939  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.939  7862  7862 D ActivityThread: Added TimaKeyStore provider
09-13 16:34:03.939  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-13 16:34:03.939  7877  7877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:34:03.939  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.939  7877  7877 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 16:34:03.959  7890  7890 E Zygote  : MountEmulatedStorage()
09-13 16:34:03.959  7890  7890 E Zygote  : v2
09-13 16:34:03.959  7890  7890 I libpersona: KNOX_SDCARD checking this for 10148
09-13 16:34:03.959  7890  7890 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:03.959  7890  7890 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:03.969  7890  7890 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 16:34:03.969  1018  1306 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7890 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-13 16:34:03.969  1018  1306 I ActivityManager: Killing 7385:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-13 16:34:03.969  7890  7890 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 16:34:03.969  7877  7877 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:03.979  1018  1306 I ActivityManager: Killing 7403:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-13 16:34:03.979  7877  7877 D ActivityThread: Added TimaKeyStore provider
09-13 16:34:03.979  7682  7860 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 16:34:03.979  1018  1306 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-13 16:34:03.979  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.979  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.979  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 16:34:03.979  1018  1306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 16:34:03.999  7906  7906 E Zygote  : MountEmulatedStorage()
09-13 16:34:03.999  7906  7906 E Zygote  : v2
09-13 16:34:03.999  7906  7906 I libpersona: KNOX_SDCARD checking this for 10029
09-13 16:34:03.999  7906  7906 I libpersona: KNOX_SDCARD not a persona
,09-13 16:34:03.999  7906  7906 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 16:34:04.009  1018  1306 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7906 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-13 16:34:04.009  1018  1306 I ActivityManager: Killing 7419:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-13 16:34:04.009  7906  7906 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 16:34:04.009  7906  7906 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 16:34:04.009  7890  7890 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 16:34:04.009  7890  7890 D ActivityThread: Added TimaKeyStore provider
,09-13 16:34:04.019  7682  7860 E SQLiteLog: (28) failed to open "/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db" with flag (131138) and mode_t (0) due to error (30)
,09-13 16:34:04.029  7682  7860 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.e.Jx(UpdateIcingCorporaService.java:408)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.g.bdp(UpdateIcingCorporaService.java:347)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-13 16:34:04.029  7682  7860 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 16:34:04.039  7862  7862 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-13 16:34:04.039  7906  7906 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-13 16:34:04.039  7906  7906 D ActivityThread: Added TimaKeyStore provider

```
