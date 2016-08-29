#### Test 814185776bb1ff3_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-29 09:53:32.174  6573  6573 D CscParser: getInstance fileName =/system/csc/customer.xml
08-29 09:53:32.184  3780  6616 W BaseAppContext: Using Auth Proxy for data requests.
08-29 09:53:32.194  6573  6573 D Mms/MmsConfig:  enable multiwindow = false
08-29 09:53:32.194  3780  6616 W BaseAppContext: Using Auth Proxy for data requests.
08-29 09:53:32.204  6695  6695 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 09:53:32.204  6695  6695 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 09:53:32.204  6695  6695 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 09:53:32.204  6695  6695 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
08-29 09:53:32.204  6573  6573 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-29 09:53:32.204  6573  6573 E Mms/MessageUtils: updateCountryIso : update country iso info 
08-29 09:53:32.204  3780  6616 W BaseAppContext: Using Auth Proxy for data requests.
08-29 09:53:32.214  6573  6573 D Mms/MmsConfig: [end]    init() consume time = 229.054427
08-29 09:53:32.214  6573  6573 D Mms/Contact: [start]    init() consume time = 5.423906
--------- beginning of system
08-29 09:53:32.224  1016  3766 I ActivityManager: Killing 6332:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
08-29 09:53:32.244  1463  3333 D TP/MmsSmsProvider: query,matched:13, calling pid = 6573
08-29 09:53:32.244  1463  3333 D TP/MmsSmsProvider: match 13:Elapsed time : 1.412 ms
08-29 09:53:32.254  3780  6602 I qtaguid : Tagging socket 100 with tag 1000040b00000000{268436491,0} for uid -1, pid: 3780, getuid(): 10011
08-29 09:53:32.264  3780  6616 W BaseAppContext: Using Auth Proxy for data requests.
08-29 09:53:32.264  6573  6573 D Mms/Contact: [end]    init consume time = 45.555573
,08-29 09:53:32.314  6573  6736 D Mms/DraftCache: [start]    rebuildCache consume time = 48.921927
08-29 09:53:32.314  1463  1656 D TP/MmsSmsProvider: query,matched:12, calling pid = 6573
08-29 09:53:32.314  1463  1656 D TP/MmsSmsProvider: match 12:Elapsed time : 1.640 ms
08-29 09:53:32.314  6573  6736 D Mms/DraftCache: [end]    rebuildCache consume time = 8.409167
08-29 09:53:32.324  1016  1335 I ActivityManager: Killing 6067:com.google.android.talk/u0a102 (adj 15): empty #21
08-29 09:53:32.324  6573  6573 D Mms/MethodReflector: getSubId is called
08-29 09:53:32.324  6573  6573 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-29 09:53:32.334  6573  6573 D Mms/MethodReflector: getTelephonyProperty is called
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: auto download without roaming -> true
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-29 09:53:32.334  6573  6573 D Mms/MethodReflector: getSubId is called
08-29 09:53:32.334  6573  6573 D Mms/MethodReflector: getDefaultSmsSubId is called
08-29 09:53:32.334  6573  6573 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-29 09:53:32.334  6573  6573 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-29 09:53:32.334  6573  6573 D Mms/MethodReflector: getTelephonyProperty is called
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: auto download without roaming -> true
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: auto download during roaming secondary -> false
08-29 09:53:32.334  6573  6573 D Mms/DownloadManager: mAutoDownload ------> true
08-29 09:53:32.394  6573  6641 D Mms/ArtClassLoader: init [DONE] art
08-29 09:53:32.404  6573  6573 D ComposerPerformance: 1472457212419 ms / [DONE] Composer constructor
08-29 09:53:32.404  6573  6573 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-29 09:53:32.404  6573  6573 I Mms/ReservationManager: ReservationManager()
08-29 09:53:32.404  6573  6573 I Mms/ReservationManager: resetAfterConnected()
08-29 09:53:32.414  1463  2141 D TP/MmsSmsProvider: query,matched:7, calling pid = 6573
08-29 09:53:32.414  1463  2141 D TP/MmsSmsProvider: match 7:Elapsed time : 1.626 ms
08-29 09:53:32.424  6573  6739 D Mms/Conversation: [start]    init() consume time = 102.939323
08-29 09:53:32.424  6573  6573 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-29 09:53:32.424  1463  1656 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-29 09:53:32.424  1463  1656 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-29 09:53:32.424  1463  1656 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-29 09:53:32.424  1463  1656 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-29 09:53:32.434  1463  1656 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-29 09:53:32.434  1463  1656 D TP/MmsSmsProvider: need read changed broadcast:false
08-29 09:53:32.434  6573  6739 D Mms/Conversation: [end]    init consume time = 12.747812
08-29 09:53:32.434  6573  6573 D Mms/MmsApp: [end]    onCreate() consume time = 0.001458
08-29 09:53:32.444  6573  6739 D Mms/MessagingNotification: [start]    init() consume time = 6.902344
08-29 09:53:32.444  6573  6739 D Mms/MessagingNotification: [end]    init consume time = 4.630313
08-29 09:53:32.444  6573  6573 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-29 09:53:32.444  6573  6573 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-29 09:53:32.454  1463  1477 D TP/MmsSmsProvider: query,matched:0, calling pid = 6573
08-29 09:53:32.454  1463  1477 V TP/MmsSmsProvider: getSimpleConversations entered.
08-29 09:53:32.454  1463  1477 D TP/MmsSmsProvider: match 0:Elapsed time : 1.691 ms
08-29 09:53:32.454  6573  6573 D Mms/MethodReflector: getSubId is called
08-29 09:53:32.454  6573  6573 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-29 09:53:32.454  6573  6573 D Mms/MethodReflector: getTelephonyProperty is called
08-29 09:53:32.454  6573  6573 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-29 09:53:32.454  6573  6573 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-29 09:53:32.454  1016  3755 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-29 09:53:32.454  1016  3755 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.454  1016  3755 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.454  1016  3755 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.454  1016  3755 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.464  6573  6573 D Mms/DownloadManager: auto download without roaming -> true
08-29 09:53:32.464  6573  6573 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-29 09:53:32.464  6573  6573 D Mms/DownloadManager: mAutoDownload ------> true
08-29 09:53:32.474  6742  6742 E Zygote  : MountEmulatedStorage()
08-29 09:53:32.474  6742  6742 I libpersona: KNOX_SDCARD checking this for 10068
08-29 09:53:32.474  6742  6742 E Zygote  : v2
08-29 09:53:32.474  6742  6742 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:32.474  6742  6742 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:32.474  1016  3755 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6742 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-29 09:53:32.474  6742  6742 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:32.474  6742  6742 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 09:53:32.474  6573  6573 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-29 09:53:32.484  6573  6740 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 34.398437
08-29 09:53:32.484  1016  1343 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-29 09:53:32.484  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-29 09:53:32.484  6573  6741 D Mms/Synchronizer: [start]    doSync consume time = 3.436302
08-29 09:53:32.484  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:32.484  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:32.484  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-29 09:53:32.484  1463  3334 D TP/MmsSmsProvider: query,matched:400, calling pid = 6573
08-29 09:53:32.494  1463  1482 D TP/MmsSmsProvider: update, matched:300, calling pid = 6573
08-29 09:53:32.494  1463  1482 V TP/MmsSmsProvider: syncDBData start
08-29 09:53:32.494  1463  1482 V TP/MmsSmsProvider: syncDBData sms end
08-29 09:53:32.494  1463  1482 V TP/MmsSmsProvider: syncDBData mms end
08-29 09:53:32.494  1463  1482 V TP/MmsSmsProvider: syncDBData end
08-29 09:53:32.494  1016  3766 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-29 09:53:32.494  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.494  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.494  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.494  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.514  6757  6757 E Zygote  : MountEmulatedStorage()
08-29 09:53:32.514  6757  6757 E Zygote  : v2
08-29 09:53:32.514  6757  6757 I libpersona: KNOX_SDCARD checking this for 10042
08-29 09:53:32.514  6757  6757 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:32.514  6757  6757 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:32.524  6742  6742 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:32.524  6742  6742 D ActivityThread: Added TimaKeyStore provider
08-29 09:53:32.524  6757  6757 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:32.534  6573  6741 D Mms/Synchronizer: [end]    doSync consume time = 49.454844
08-29 09:53:32.534  1016  3766 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6757 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-29 09:53:32.544  6573  6740 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 6.834948
08-29 09:53:32.544  6757  6757 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-29 09:53:32.544  1016  1474 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 09:53:32.554  6573  6762 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-29 09:53:32.554  6573  6762 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-29 09:53:32.554  6737  6737 D AndroidRuntime: 
08-29 09:53:32.554  6737  6737 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 09:53:32.564  6737  6737 D AndroidRuntime: CheckJNI is OFF
08-29 09:53:32.564  6737  6737 D AndroidRuntime: readGMSProperty: start
08-29 09:53:32.564  6737  6737 D AndroidRuntime: readGMSProperty: already setted!!
08-29 09:53:32.564  6737  6737 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 09:53:32.564  6737  6737 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 09:53:32.564  6737  6737 D AndroidRuntime: readGMSProperty: end
08-29 09:53:32.564  6737  6737 D AndroidRuntime: addProductProperty: start
08-29 09:53:32.564  1016  1489 I ActivityManager: Killing 6401:com.android.defcontainer/u0a3 (adj 15): empty #21
08-29 09:53:32.564  1016  1489 I ActivityManager: Killing 6296:com.android.calendar/u0a131 (adj 15): empty #22
08-29 09:53:32.594  6757  6757 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:32.594  6757  6757 D ActivityThread: Added TimaKeyStore provider
08-29 09:53:32.614  6742  6742 D BadgeProvider: onCreate
08-29 09:53:32.614  6742  6742 D BadgeProvider: DatabaseHelper
08-29 09:53:32.644  6573  6739 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-29 09:53:32.654  1463  3333 D TP/SmsProvider: query,matched:26, calling pid = 6573
08-29 09:53:32.654  6757  6757 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 09:53:32.654  6757  6757 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 09:53:32.654  6757  6757 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-29 09:53:32.654  1463  3333 D TP/SmsProvider: match 26:Elapsed time : 3.916 ms
08-29 09:53:32.704  6737  6737 E AffinityControl: AffinityControl: registerfunction enter
08-29 09:53:32.714   295   295 E SMD     : DCD OFF
08-29 09:53:32.724  6757  6757 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-29 09:53:32.734  1016  3766 I ActivityManager: Killing 6193:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-29 09:53:32.734  6737  6737 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 09:53:32.744  1016  1056 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-29 09:53:32.744  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-29 09:53:32.744  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.744  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.744  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.744  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.744  1016  1136 E PersonaManagerService: inState():  stateMachine is null !!
08-29 09:53:32.754  1016  1136 I PersonaManagerService: PersonaId don't exist
08-29 09:53:32.754  1016  1136 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-29 09:53:32.764  6783  6783 E Zygote  : MountEmulatedStorage()
08-29 09:53:32.764  6783  6783 E Zygote  : v2
08-29 09:53:32.764  6783  6783 I libpersona: KNOX_SDCARD checking this for 10003
08-29 09:53:32.764  6783  6783 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:32.764  6783  6783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:32.774  1016  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6783 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-29 09:53:32.774  6783  6783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:32.774  6783  6783 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 09:53:32.784  1016  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 09:53:32.794  1016  1136 W ActivityManager: mDVFSHelper.acquire()
08-29 09:53:32.804  3780  6616 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 164.253ms
08-29 09:53:32.804  1016  1136 D FocusedStackFrame: Set to : 0
08-29 09:53:32.804  6783  6783 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:32.804  6783  6783 D ActivityThread: Added TimaKeyStore provider
08-29 09:53:32.814  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 09:53:32.814  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-29 09:53:32.824  1016  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.824  1016  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.824  1016  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.824  1016  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:32.844  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 09:53:32.844  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 09:53:32.844  6799  6799 E Zygote  : MountEmulatedStorage()
08-29 09:53:32.844  6799  6799 I libpersona: KNOX_SDCARD checking this for 10170
08-29 09:53:32.844  6799  6799 E Zygote  : v2
08-29 09:53:32.844  6799  6799 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:32.844   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-29 09:53:32.844  6799  6799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:32.844  6799  6799 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:32.844  1016  1136 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6799 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 09:53:32.844  6799  6799 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 09:53:32.844  1016  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-29 09:53:32.844  1016  1136 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 09:53:32.864  1016  1136 D InputDispatcher: Focused application set to: xxxx
08-29 09:53:32.864  1016  1136 D InputDispatcher: Focus left window: 1490
08-29 09:53:32.864  6737  6737 D AndroidRuntime: Shutting down VM
08-29 09:53:32.864  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 09:53:32.864  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 09:53:32.884  1016  1474 I art     : Explicit concurrent mark sweep GC freed 141954(7MB) AllocSpace objects, 4(1863KB) LOS objects, 33% free, 23MB/34MB, paused 14.410ms total 216.517ms
08-29 09:53:32.884  1463  3333 D TP/MmsSmsProvider: query,matched:6, calling pid = 6573
08-29 09:53:32.884  6799  6799 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:32.884  6799  6799 D ActivityThread: Added TimaKeyStore provider
08-29 09:53:32.894  1463  3333 D TP/MmsSmsProvider: match 6:Elapsed time : 4.761 ms
08-29 09:53:32.904  1016  1562 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-29 09:53:32.904  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-29 09:53:32.914  1016  1016 V ActivityManager: Display changed displayId=0
08-29 09:53:32.914  3780  4415 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-29 09:53:32.934  1016  1562 D PersonaManager: isKioskContainerExistOnDevice
08-29 09:53:32.954  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-29 09:53:32.964   291   291 E installd: system dir 0 : /system/app/
08-29 09:53:32.964   291   291 E installd: system dir 1 : /system/priv-app/
08-29 09:53:32.964   291   291 E installd: system dir 2 : /vendor/app/
08-29 09:53:32.964   291   291 E installd: system dir 3 : /oem/app/
08-29 09:53:32.964   257  1098 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-29 09:53:32.964   257   435 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-29 09:53:32.974  6561  6625 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-29 09:53:32.974  6561  6625 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 09:53:32.974  6561  6625 I GAv4    :   adb logcat -s GAv4
08-29 09:53:32.994  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{23029bff token=android.os.BinderProxy@7f6eb98 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-29 09:53:32.994  1490  1490 D Launcher: onTrimMemory. Level: 20
08-29 09:53:32.994  1663  4428 I art     : Explicit concurrent mark sweep GC freed 13301(637KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 1.020ms total 50.620ms
08-29 09:53:33.024  6561  6625 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-29 09:53:33.024  1016  1474 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 09:53:33.034  1016  1028 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-29 09:53:33.034  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.034  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.034  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.034  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.044  1016  1056 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-29 09:53:33.064  6818  6818 E Zygote  : MountEmulatedStorage()
08-29 09:53:33.064  6818  6818 E Zygote  : v2
08-29 09:53:33.064  6818  6818 I libpersona: KNOX_SDCARD checking this for 10023
08-29 09:53:33.064  6818  6818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:33.064  6818  6818 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:33.064  6818  6818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:33.064  6818  6818 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 09:53:33.074  1016  1028 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6818 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-29 09:53:33.074  6737  6737 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 09:53:33.084  6799  6799 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-29 09:53:33.094  6818  6818 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:33.094  6818  6818 D ActivityThread: Added TimaKeyStore provider
08-29 09:53:33.094  1016  1561 I ActivityManager: Killing 6449:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-29 09:53:33.104  6799  6799 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5474-5476)
08-29 09:53:33.104  6799  6799 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 09:53:33.124  6561  6625 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-29 09:53:33.124  3780  6602 I qtaguid : Untagging socket 97
08-29 09:53:33.134  6799  6799 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c70b0d4}
08-29 09:53:33.134  6799  6799 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 09:53:33.134  6799  6799 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 09:53:33.164  3780  3780 I ConfigFetchService: fetch service done; releasing wakelock
08-29 09:53:33.164  3780  3780 I ConfigFetchService: stopping self
08-29 09:53:33.174  6561  6625 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-29 09:53:33.184  6818  6818 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-29 09:53:33.204  6799  6799 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-29 09:53:33.204  6799  6799 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 09:53:33.224  6573  6739 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-29 09:53:33.224  6799  6799 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 09:53:33.234  6561  6583 W art     : Suspending all threads took: 7.177ms
08-29 09:53:33.244  6799  6799 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 09:53:33.244  6799  6799 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 09:53:33.244  6799  6799 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 09:53:33.244  6799  6799 I Adreno-EGL: Local Branch: 
08-29 09:53:33.244  6799  6799 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 09:53:33.244  6799  6799 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 09:53:33.244  6799  6799 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-29 09:53:33.254  6561  6837 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-29 09:53:33.254  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-29 09:53:33.264  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-29 09:53:33.264  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-29 09:53:33.264  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-29 09:53:33.264  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-29 09:53:33.264  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-29 09:53:33.264  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-29 09:53:33.274  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-29 09:53:33.274  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-29 09:53:33.274  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-29 09:53:33.274  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-29 09:53:33.274  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-29 09:53:33.284  3780  4415 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-29 09:53:33.284  6818  6818 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-29 09:53:33.344  6799  6799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 09:53:33.354  6799  6799 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-29 09:53:33.354  6799  6799 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-29 09:53:33.364  6799  6799 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-29 09:53:33.364  6799  6799 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-29 09:53:33.394  3780  4415 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-29 09:53:33.404  1016  3766 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-29 09:53:33.404  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.404  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.404  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.404  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.414  1016  3766 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6859 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 09:53:33.424  6859  6859 E Zygote  : MountEmulatedStorage()
08-29 09:53:33.424  6859  6859 E Zygote  : v2
08-29 09:53:33.424  6859  6859 I libpersona: KNOX_SDCARD checking this for 1000
08-29 09:53:33.424  6859  6859 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:33.424  6859  6859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:33.424  1016  3766 I ActivityManager: Killing 6464:com.sec.spp.push/u0a32 (adj 15): empty #21
08-29 09:53:33.424  6859  6859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:33.424  6859  6859 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 09:53:33.434  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-29 09:53:33.434  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:33.434  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:33.434  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 09:53:33.434  1016  1041 W ActivityManager: Activity pause timeout for ActivityRecord{197c786b u0 com.test.thalitest/.MainActivity t163}
08-29 09:53:33.454  6859  6859 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:33.454  6859  6859 D ActivityThread: Added TimaKeyStore provider
08-29 09:53:33.454  6537  6600 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-29 09:53:33.484  6859  6859 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-29 09:53:33.494  6859  6859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-29 09:53:33.494  1016  1136 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-29 09:53:33.494  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-29 09:53:33.494  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:33.494  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:33.494  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-29 09:53:33.494  1016  1328 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-29 09:53:33.494  6859  6859 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-29 09:53:33.504  6537  6600 I AcmsKeyStoreHelper: Key Store exist
08-29 09:53:33.504  6537  6600 I AcmsKeyStoreHelper: Hence loading the keystore file
08-29 09:53:33.524  6561  6856 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 09:53:33.524  6561  6856 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-29 09:53:33.534  6859  6877 E FilterInstaller: installFilters
08-29 09:53:33.534  1016  3702 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-29 09:53:33.534  1016  3702 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 09:53:33.534  1016  3702 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 09:53:33.534  1016  3702 D BatteryService: stay LED for charging
08-29 09:53:33.534  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 09:53:33.534  6859  6877 E FilterInstaller: There is no requred permission
08-29 09:53:33.534  1016  1562 I ActivityManager: Killing 5089:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-29 09:53:33.554  6799  6799 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 09:53:33.564  1016  1016 I MotionRecognitionService: Plugged
08-29 09:53:33.564  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-29 09:53:33.564  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 09:53:33.564  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
08-29 09:53:33.564  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 09:53:33.564  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-29 09:53:33.564  6537  6600 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-29 09:53:33.564  6537  6600 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-29 09:53:33.564  6537  6600 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-29 09:53:33.564  6537  6600 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-29 09:53:33.564  6537  6600 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-29 09:53:33.564  6537  6600 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-29 09:53:33.564  6537  6600 D AcmsCore: This is NOT a valid MirrorLink app
08-29 09:53:33.564  6537  6600 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-29 09:53:33.564  6537  6600 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-29 09:53:33.564  6537  6600 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-29 09:53:33.564  6537  6600 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-29 09:53:33.574  6561  6856 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-29 09:53:33.584  3210  3210 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 09:53:33.584  3210  3337 D HeadsetStateMachine: Disconnected process message: 10
08-29 09:53:33.584  1016  1016 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-29 09:53:33.584  1016  1016 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-29 09:53:33.584  1016  1016 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-29 09:53:33.584  1016  1016 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
08-29 09:53:33.584  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-29 09:53:33.594  6537  6537 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-29 09:53:33.594  6537  6537 D AcmsService: Enter onDestroy
08-29 09:53:33.594  6537  6537 I AcmsService: cleanUp(): inside service clean up
08-29 09:53:33.594  6537  6537 D AcmsCore: AcmsCore: inside DeInit
08-29 09:53:33.594  6537  6537 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-29 09:53:33.594  6537  6537 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-29 09:53:33.594  6537  6537 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-29 09:53:33.594  6537  6537 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-29 09:53:33.594  6537  6537 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-29 09:53:33.594  6537  6537 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-29 09:53:33.594  6537  6537 D AcmsService: killing acms process
08-29 09:53:33.594  6537  6537 I Process : Sending signal. PID: 6537 SIG: 9
08-29 09:53:33.594  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 09:53:33.594  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 09:53:33.594  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 09:53:33.594  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.594  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.594  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.594  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.604  6799  6799 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 09:53:33.614  6879  6879 E Zygote  : MountEmulatedStorage()
08-29 09:53:33.614  6879  6879 I libpersona: KNOX_SDCARD checking this for 10008
08-29 09:53:33.614  6879  6879 E Zygote  : v2
08-29 09:53:33.614  6879  6879 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:33.614  1016  1016 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6879 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 09:53:33.614  6879  6879 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:33.624  6799  6799 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 09:53:33.624  6799  6799 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-29 09:53:33.624  6879  6879 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:33.624  6879  6879 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 09:53:33.624  6799  6799 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-29 09:53:33.634  6799  6799 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 09:53:33.634  6799  6799 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 09:53:33.644  6879  6879 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:33.644  6879  6879 D ActivityThread: Added TimaKeyStore provider
08-29 09:53:33.644  6561  6856 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-29 09:53:33.644  6561  6856 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d4982ea: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-29 09:53:33.644  6561  6856 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-29 09:53:33.664  1016  1470 I ActivityManager: Process ACMS.Process (pid 6537)(adj 0) has died(46,765)
08-29 09:53:33.674  6799  6897 D OpenGLRenderer: Render dirty regions requested: true
08-29 09:53:33.684  1016  1136 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 09:53:33.684  1016  1136 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 09:53:33.684  1016  1136 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-29 09:53:33.684  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 09:53:33.684  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-29 09:53:33.684  6799  6848 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-29 09:53:33.694  6799  6799 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 09:53:33.694  6799  6799 V ActivityThread: updateVisibility : ActivityRecord{8dd2934 token=android.os.BinderProxy@f6fb621 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-29 09:53:33.694  6799  6799 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 09:53:33.704   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-29 09:53:33.714  6879  6879 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
08-29 09:53:33.724  1016  1136 D InputDispatcher: Focus entered window: 6799
08-29 09:53:33.724  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 09:53:33.724  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 09:53:33.724  6799  6799 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-29 09:53:33.724  6799  6897 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 09:53:33.734  6799  6897 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-29 09:53:33.734  6799  6897 D OpenGLRenderer: Enabling debug mode 0
08-29 09:53:33.744  1016  1562 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-29 09:53:33.754  1175  1175 D PanelView: There is/are notification(s) 
08-29 09:53:33.754  1016  6903 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-29 09:53:33.784  1016  1046 I ActivityManager: Displayed Component not be shown by security: +842ms (total +966ms)
08-29 09:53:33.784  1016  1046 W ActivityManager: mDVFSHelper.release()
08-29 09:53:33.784  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{197c786b u0 com.test.thalitest/.MainActivity t163} time:96150
08-29 09:53:33.784  6799  6799 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-29 09:53:33.784  6799  6799 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f6fb621 time:96152
08-29 09:53:33.784   257  1097 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-29 09:53:33.784   257   435 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-29 09:53:33.794  6879  6879 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
08-29 09:53:33.794  1016  1328 I ActivityManager: Killing 6497:com.samsung.helphub/1000 (adj 15): empty #21
,08-29 09:53:33.844  1016  3766 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 09:53:33.844  1016  3766 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,08-29 09:53:33.844  1016  3766 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:33.844  1016  3766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:33.844  1016  3766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:33.884  1887  1887 I SamsungIME: getCurrentCandidateView
,08-29 09:53:33.884  1016  1561 I ActivityManager: Killing 6472:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-29 09:53:33.894  1016  3766 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-29 09:53:33.894  1016  3766 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-29 09:53:33.894  1016  3766 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:33.894  1016  3766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:33.894  1016  3766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:33.914  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Aug 29 09:53:33 GMT+02:00 2016
,08-29 09:53:33.914  1016  1489 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 09:53:33.914  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 09:53:33.914  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:33.914  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:33.914  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 09:53:33.914  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 09:53:33.924  1016  1562 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 09:53:33.924  1016  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.924  1016  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.924  1016  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:33.924  1016  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:33.924  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 09:53:33.924  2814  2814 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 09:53:33.934  2814  2814 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 09:53:33.934  2814  6910 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-29 09:53:33.934  6911  6911 E Zygote  : MountEmulatedStorage(),
08-29 09:53:33.934  6911  6911 E Zygote  : v2
08-29 09:53:33.934  6911  6911 I libpersona: KNOX_SDCARD checking this for 10036
08-29 09:53:33.934  6911  6911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:33.934  6911  6911 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:33.934  6911  6911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:33.944  6911  6911 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,08-29 09:53:33.944  1016  1562 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6911 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-29 09:53:33.944  2814  6910 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-29 09:53:33.944  2814  6910 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Mon Aug 29 09:53:33 GMT+02:00 2016
,08-29 09:53:33.964  6799  6799 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6799
,08-29 09:53:33.974  6911  6911 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:33.974  6911  6911 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:33.984  2814  6910 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-29 09:53:33.984  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 09:53:34.004  1887  1887 D SamsungIME: Dismiss ExpandCandiate
,08-29 09:53:34.014  6911  6911 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@62dd63c
,08-29 09:53:34.024  6911  6911 I SA      : [SSP] onCreated
,08-29 09:53:34.034  6911  6911 I SA      : [TPM] There is no property file
,08-29 09:53:34.034  6911  6911 I SA      : [SCU] isHaveSA() - false
,08-29 09:53:34.034  6911  6911 I SA      : [TPM] getModelProperty : null
08-29 09:53:34.034  6911  6911 I SA      : [TPM] getCSCProperty : null
,08-29 09:53:34.044  6911  6911 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-29 09:53:34.044  6911  6911 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 09:53:34.044  6911  6911 I SA      : [DM] TFT FEATURE: false
,08-29 09:53:34.054  6911  6911 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-29 09:53:34.054  6911  6911 I SA      : [DM] init START
,08-29 09:53:34.064  6911  6911 I SA      : [DM] This device is not a Vodafone
,08-29 09:53:34.064  6911  6911 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-29 09:53:34.064  6911  6911 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 09:53:34.064  6911  6911 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-29 09:53:34.064  6911  6911 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-29 09:53:34.064  6911  6911 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-29 09:53:34.064  6911  6911 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-29 09:53:34.074  6911  6911 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-29 09:53:34.084  6911  6911 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-29 09:53:34.084  6911  6911 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-29 09:53:34.084  6911  6911 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-29 09:53:34.084  6911  6911 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-29 09:53:34.084  6911  6911 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 09:53:34.084  6911  6911 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-29 09:53:34.084  6911  6911 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-29 09:53:34.084  6911  6911 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-29 09:53:34.094  6911  6911 I SA      : [SCU] isHaveSA() - false
08-29 09:53:34.094  6911  6911 I SA      : support phone number id : false
08-29 09:53:34.094  6911  6911 I SA      : [DM] Supports Ref Jpn : true
,08-29 09:53:34.094  6911  6911 I SA      : [DM] init END
,08-29 09:53:34.144  1016  1335 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-29 09:53:34.144  1016  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.144  1016  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.144  1016  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.144  1016  1335 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.154  6933  6933 E Zygote  : MountEmulatedStorage()
08-29 09:53:34.154  6933  6933 E Zygote  : v2
08-29 09:53:34.154  6933  6933 I libpersona: KNOX_SDCARD checking this for 10058
08-29 09:53:34.154  6933  6933 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:34.164  1016  1335 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6933 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-29 09:53:34.164  1016  1335 I ActivityManager: Killing 6028:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-29 09:53:34.164  6933  6933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:34.164  6933  6933 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:34.164  6933  6933 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:34.194  1887  1887 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 09:53:34.204  6933  6933 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:34.204  6933  6933 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:34.224  6799  6799 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 09:53:34.244  1887  1887 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 09:53:34.254  1887  1887 I SamsungIME: KeybaordView init() : load resources
,08-29 09:53:34.274  6933  6933 I ExternalOEMControlProvider: onCreate
,08-29 09:53:34.284  1887  1887 I SamsungIME: getCurrentKeyboard
08-29 09:53:34.284  1887  1887 I SamsungIME: getTextKeyboard
,08-29 09:53:34.294  1016  1328 I ActivityManager: Killing 5510:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-29 09:53:34.294  1766  1766 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-29 09:53:34.294  6933  6948 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-29 09:53:34.294  1766  1766 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 09:53:34.294  1016  1562 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-29 09:53:34.304  1016  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.304  1016  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.304  1016  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.304  1016  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.314  1887  1887 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-29 09:53:34.314  6949  6949 E Zygote  : MountEmulatedStorage()
08-29 09:53:34.314  6949  6949 E Zygote  : v2
08-29 09:53:34.314  6949  6949 I libpersona: KNOX_SDCARD checking this for 10081
08-29 09:53:34.314  6949  6949 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:34.314  6949  6949 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:34.314  6949  6949 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:34.314  6949  6949 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 09:53:34.324  1016  1562 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6949 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 09:53:34.324  6799  6906 D jxcore_app_log: JniHelper::setJavaVM(0xb7b2d2b0), pthread_self() = -1207191792
,08-29 09:53:34.334  6799  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 09:53:34.334  6799  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 09:53:34.334  6799  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 09:53:34.334  6799  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 09:53:34.334  6799  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 09:53:34.334  6799  6906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22069c2a added. We now have 1 listener(s)
08-29 09:53:34.334  6949  6949 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:34.334  6949  6949 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:34.334  6799  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-29 09:53:34.334  6799  6906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 09:53:34.344   321   321 I art     : Explicit concurrent mark sweep GC freed 8666(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 24.277ms
08-29 09:53:34.344  6799  6906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:53:34.344  6799  6906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 09:53:34.344  6799  6906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10e16991 added. We now have 1 listener(s)
,08-29 09:53:34.344  6799  6906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:53:34.354   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.239ms total 17.461ms
08-29 09:53:34.364  6799  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:53:34.364  6799  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 09:53:34.364  6799  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 09:53:34.364  6799  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 09:53:34.364  6799  6906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 09:53:34.364  6799  6906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:34.364  6799  6906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
08-29 09:53:34.374  6799  6906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 09:53:34.374  6799  6906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:34.374  6799  6906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:34.374  6799  6906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:34.374  6799  6906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:34.374  6799  6906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:34.374  6799  6906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:34.374  6799  6906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:34.374  6799  6906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:53:34.374  6799  6906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 09:53:34.374  6799  6906 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:53:34.374   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.726ms
08-29 09:53:34.374  6799  6906 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 09:53:34.374  6949  6949 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 09:53:34.384  6949  6949 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 09:53:34.384  6949  6949 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:53:34.384  6949  6949 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 09:53:34.384  6949  6949 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
08-29 09:53:34.384  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:34.394  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:34.404  6799  6799 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 09:53:34.424  6573  6573 I Mms/MmsApp:  start initViewCache mms
,08-29 09:53:34.434  6573  6573 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1889.335624
08-29 09:53:34.434  6573  6573 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-29 09:53:34.444  1016  1489 D SettingsProvider: name = next_alarm_formatted
,08-29 09:53:34.444  1016  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 09:53:34.444  1016  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 09:53:34.444  1016  1489 D SettingsProvider: selectionArgs: false
08-29 09:53:34.444  1016  1489 D SettingsProvider: selectionArgs: 10081
08-29 09:53:34.444  1016  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 09:53:34.444  1016  1489 D SettingsProvider: ret = -1
,08-29 09:53:34.564  6573  6573 D AbsListView: Get MotionRecognitionManager
,08-29 09:53:34.564  1016  1489 D MotionRecognitionService:  ssp status : false
,08-29 09:53:34.564  6573  6573 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 138.843854
,08-29 09:53:34.574  6949  6949 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 126.275ms
,08-29 09:53:34.654  6573  6573 D Mms/BubbleViewCache: fillCache bubble = 1
,08-29 09:53:34.684  1016  3766 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-29 09:53:34.684  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.684  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.684  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.684  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.694  6967  6967 E Zygote  : MountEmulatedStorage(),
08-29 09:53:34.694  6967  6967 E Zygote  : v2
08-29 09:53:34.694  6967  6967 I libpersona: KNOX_SDCARD checking this for 10090
08-29 09:53:34.694  6967  6967 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:34.694  6967  6967 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:34.704  6967  6967 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:34.704  1016  3766 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6967 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-29 09:53:34.704  6967  6967 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:34.704  1016  3766 I ActivityManager: Killing 6524:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21,
,08-29 09:53:34.724  6967  6967 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:34.724  6967  6967 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:34.744  6967  6967 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-29 09:53:34.744  6967  6967 D elm:15121: ELMEngine.ELMEngine( context ).
,08-29 09:53:34.744  6967  6967 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-29 09:53:34.744  1016  1561 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-29 09:53:34.754  1016  1561 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-29 09:53:34.754  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:34.754  1016  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:34.754  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-29 09:53:34.754  6967  6967 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-29 09:53:34.754  1016  1496 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-29 09:53:34.754  6967  6967 D elm:15121: ElmAgentService : onCreate()
,08-29 09:53:34.754  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.754  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.754  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.754  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.764  6967  6982 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-29 09:53:34.764  6984  6984 E Zygote  : MountEmulatedStorage()
08-29 09:53:34.764  6984  6984 E Zygote  : v2
08-29 09:53:34.764  6984  6984 I libpersona: KNOX_SDCARD checking this for 10130
08-29 09:53:34.764  6984  6984 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:34.764  6984  6984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:34.774  6967  6982 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).,
08-29 09:53:34.774  1016  1496 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6984 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-29 09:53:34.774  6967  6967 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
08-29 09:53:34.774  6984  6984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:34.774  6967  6967 D elm:15121: ModuleBase.ModifySetAlarm()
,08-29 09:53:34.774  6967  6967 D elm:15121: MDMBridge.getInstance()
08-29 09:53:34.774  6967  6967 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-29 09:53:34.774  6984  6984 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,08-29 09:53:34.784  6967  6967 D elm:15121: ElmAgentService : onDestroy().
,08-29 09:53:34.784  1016  1328 I ActivityManager: Killing 6561:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-29 09:53:34.804  6984  6984 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:34.814  6984  6984 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:34.824  6984  6984 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 09:53:34.824  6984  6984 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-29 09:53:34.844  1016  1561 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-29 09:53:34.844  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.844  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.844  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.844  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.854  7000  7000 E Zygote  : MountEmulatedStorage()
08-29 09:53:34.854  7000  7000 E Zygote  : v2
08-29 09:53:34.854  7000  7000 I libpersona: KNOX_SDCARD checking this for 10131
08-29 09:53:34.854  7000  7000 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:34.854  7000  7000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:34.854  7000  7000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:34.864  7000  7000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 09:53:34.864  1016  1561 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7000 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-29 09:53:34.864  1016  1561 I ActivityManager: Killing 6131:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-29 09:53:34.884  7000  7000 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:34.884  7000  7000 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:34.904  7000  7000 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 09:53:34.904  7000  7000 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 09:53:34.904  7000  7000 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 09:53:34.944  2668  2683 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-29 09:53:34.944  1016  3755 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-29 09:53:34.944  1016  3755 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-29 09:53:34.944  1016  3755 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:34.944  1016  3755 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:34.944  1016  3755 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-29 09:53:34.964  1016  1328 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-29 09:53:34.964  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-29 09:53:34.974  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:34.974  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:34.974  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-29 09:53:34.974  1016  1028 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-29 09:53:34.974  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.974  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.974  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.974  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.984  7020  7020 E Zygote  : MountEmulatedStorage()
,08-29 09:53:34.994  7020  7020 E Zygote  : v2
08-29 09:53:34.994  7020  7020 I libpersona: KNOX_SDCARD checking this for 10037
08-29 09:53:34.994  7020  7020 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:34.994  7020  7020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:34.994  1016  1028 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7020 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:53:34.994  1016  1343 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-29 09:53:34.994  7020  7020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:34.994  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.994  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.994  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:34.994  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:34.994  7020  7020 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 09:53:35.014  7035  7035 E Zygote  : MountEmulatedStorage()
08-29 09:53:35.014  7035  7035 E Zygote  : v2
08-29 09:53:35.014  7035  7035 I libpersona: KNOX_SDCARD checking this for 1000
08-29 09:53:35.014  7035  7035 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:35.024  1016  1343 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 09:53:35.024  7035  7035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 09:53:35.024  7035  7035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 09:53:35.024  7020  7020 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:35.024  7020  7020 D ActivityThread: Added TimaKeyStore provider
08-29 09:53:35.024  7035  7035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:35.044  7035  7035 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:35.044  7035  7035 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:35.054  7020  7020 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-29 09:53:35.084  7020  7020 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-29 09:53:35.084  6799  6965 W jxcore-log: Initializing JXcore engine
08-29 09:53:35.084  6799  6965 W jxcore-log: JXcore engine is ready
,08-29 09:53:35.094  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 09:53:35.094  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 09:53:35.094  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 09:53:35.094  1016  3766 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-29 09:53:35.104  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:35.104  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:35.104  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:35.104  1016  3766 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:35.114  7053  7053 E Zygote  : MountEmulatedStorage()
,08-29 09:53:35.114  7053  7053 E Zygote  : v2
08-29 09:53:35.114  7053  7053 I libpersona: KNOX_SDCARD checking this for 10153
08-29 09:53:35.114  7053  7053 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:35.114  7053  7053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:35.114  1016  3766 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7053 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-29 09:53:35.124  1016  3766 I ActivityManager: Killing 6609:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-29 09:53:35.124  7053  7053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 09:53:35.124  7053  7053 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:35.144  7053  7053 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:35.144  7053  7053 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:35.144  2015  2015 E audit   : type=1400 msg=audit(1472457215.144:205): avc:  denied  { ioctl } for  pid=6965 comm="Thread-1265" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 09:53:35.144  2015  2015 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:35.144  2015  2015 E audit   : type=1300 msg=audit(1472457215.144:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f9908f8 items=0 ppid=321 ppcomm=main pid=6965 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1265" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-29 09:53:35.144  2015  2015 E audit   : type=1320 msg=audit(1472457215.144:205): 
,08-29 09:53:35.164  7053  7053 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 09:53:35.164  6799  6965 W jxcore-log: Starting JXcore engine
,08-29 09:53:35.174  1016  1496 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-29 09:53:35.184  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:35.184  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:35.184  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:35.184  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:35.194  7071  7071 E Zygote  : MountEmulatedStorage()
,08-29 09:53:35.194  7071  7071 E Zygote  : v2
08-29 09:53:35.194  7071  7071 I libpersona: KNOX_SDCARD checking this for 1000
08-29 09:53:35.194  7071  7071 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:35.194  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:35.204  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:35.204  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 09:53:35.204  1016  1496 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 09:53:35.204  1016  1496 I ActivityManager: Killing 6626:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-29 09:53:35.214  1016  1562 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,08-29 09:53:35.214  1016  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-29 09:53:35.214  1016  1562 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:35.214  1016  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:35.214  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-29 09:53:35.224  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:35.224  7071  7071 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:35.254  7071  7071 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472457215268
08-29 09:53:35.254  7071  7071 D         : TimeServiceNative: User Time to be set is 1472457215268
08-29 09:53:35.254  7071  7071 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-29 09:53:35.254  7071  7071 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-29 09:53:35.254  7071  7071 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472457215268
,08-29 09:53:35.254   334   408 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-29 09:53:35.254  7071  7071 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-29 09:53:35.254   334  7088 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472457215268
08-29 09:53:35.254   334  7088 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472457215268, operation = 0
,08-29 09:53:35.264   334  7088 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/24/71 1:36:24
08-29 09:53:35.264   334  7088 D QC-time-services: Daemon:Value read from RTC seconds = 36207384000
08-29 09:53:35.264   334  7088 D QC-time-services: Daemon:new time 1472457215268 
08-29 09:53:35.264   334  7088 D QC-time-services: Daemon: delta 1436249831268 genoff 1436249831268 
08-29 09:53:35.264   334  7088 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249831268 to memory
08-29 09:53:35.264   334  7088 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-29 09:53:35.264   334  7088 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-29 09:53:35.274  1016  3766 I ActivityManager: Killing 6659:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-29 09:53:35.284   334  7088 D QC-time-services: Updating the TOD offset
08-29 09:53:35.284   334  7088 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249831268 to memory
08-29 09:53:35.284   334  7088 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-29 09:53:35.284   334  7088 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-29 09:53:35.284   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb81e17c8
08-29 09:53:35.284   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-29 09:53:35.284   272   272 I rmt_storage: wakelock acquired: 1, error no: 42,
08-29 09:53:35.284   272   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1205987192)
,08-29 09:53:35.284   334  7088 E QC-time-services: Daemon:Update to modem bit set
,08-29 09:53:35.284   334  7088 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-29 09:53:35.284   334  7088 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285031268
08-29 09:53:35.294  7071  7071 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-29 09:53:35.294   334   399 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-29 09:53:35.294   334   408 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-29 09:53:35.294  1016  1496 I ActivityManager: Killing 6642:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-29 09:53:35.304  6799  6965 W jxcore-log: Platform android
08-29 09:53:35.304  6799  6965 W jxcore-log: 
,08-29 09:53:35.304  6799  6965 W jxcore-log: Process ARCH arm
08-29 09:53:35.304  6799  6965 W jxcore-log: 
,08-29 09:53:35.304  2668  2668 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-29 09:53:35.304  2668  2668 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-29 09:53:35.304  2668  2668 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-29 09:53:35.304  2668  2668 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-29 09:53:35.314  2668  2668 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-29 09:53:35.314  2668  2668 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-29 09:53:35.314  2668  2668 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-29 09:53:35.324  2668  2668 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,08-29 09:53:35.324  2668  2668 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-29 09:53:35.324  2668  2668 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-29 09:53:35.324  2668  2668 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-29 09:53:35.324  2668  2668 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-29 09:53:35.324  2668  2668 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-29 09:53:35.334  2668  2668 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-29 09:53:35.334  2668  2668 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-29 09:53:35.334  2668  2668 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-29 09:53:35.334  2668  2668 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-29 09:53:35.334  2668  2668 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-29 09:53:35.344  2668  2668 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-29 09:53:35.344  2668  2668 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-29 09:53:35.344   272   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-29 09:53:35.344   272   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-29 09:53:35.344   272   312 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1205987192) wakelock released: 1, error no: 0
08-29 09:53:35.344   272   312 I rmt_storage: 
,08-29 09:53:35.344   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb81e17c8
,08-29 09:53:35.514  6799  6965 I jxcore-log: JXcore Cordova bridge is ready!
08-29 09:53:35.514  6799  6965 I jxcore-log: 
,08-29 09:53:35.514  6799  6965 W jxcore-log: JXcore engine is started
,08-29 09:53:35.524  6799  6906 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 09:53:35.524  6799  6799 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 09:53:35.714   295   295 E SMD     : DCD OFF,
,08-29 09:53:36.164  1016  3376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 09:53:36.224  7020  7020 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-29 09:53:36.224  1016  1041 W ActivityManager: userId = 0, bbcId = -10000,
08-29 09:53:36.224  1016  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:36.224  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
08-29 09:53:36.224  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
08-29 09:53:36.224  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:36.224  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:36.234  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-29 09:53:36.234  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:36.234  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:36.234  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
08-29 09:53:36.234  1016  1496 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-29 09:53:36.234  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
08-29 09:53:36.244  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:36.244  1016  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:36.244  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-29 09:53:36.244  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:36.244  1016  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:36.244  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
08-29 09:53:36.254  1016  1562 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-29 09:53:36.254  1016  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
08-29 09:53:36.254  1016  1562 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:36.254  1016  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:36.254  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-29 09:53:36.264  1016  1343 I ActivityManager: Killing 6695:com.sec.pcw.device/1000 (adj 15): empty #21
,08-29 09:53:38.174  1663  1663 I ConfigService: onDestroy
,08-29 09:53:38.724   295   295 E SMD     : DCD OFF,
,08-29 09:53:40.484  1016  3363 D SSRM:n  : SIOP:: AP = 400
,08-29 09:53:41.164  1016  3376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 09:53:41.724   295   295 E SMD     : DCD OFF
,08-29 09:53:42.864  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-29 09:53:43.044  1016  1056 D PackageManager: [MSG] MCS_UNBIND
,08-29 09:53:43.054  1016  1489 I ActivityManager: Killing 6713:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-29 09:53:43.574  1016  1335 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 09:53:43.574  1016  1335 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4276, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 09:53:43.574  1016  1335 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 09:53:43.574  1016  1335 D BatteryService: stay LED for charging
08-29 09:53:43.574  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 09:53:43.584  1016  1016 I MotionRecognitionService: Plugged
,08-29 09:53:43.584  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 09:53:43.584  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 09:53:43.584  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 09:53:43.584  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 09:53:43.584  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 09:53:43.604  3210  3210 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 09:53:43.604  3210  3337 D HeadsetStateMachine: Disconnected process message: 10
,08-29 09:53:43.614  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 09:53:43.614  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 09:53:43.614  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 09:53:44.724   295   295 E SMD     : DCD OFF
,08-29 09:53:45.914  1016  1316 E Watchdog: !@Sync 3
,08-29 09:53:47.204  1016  1095 V AlarmManager: waitForAlarm result :4
,08-29 09:53:47.214  1016  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,08-29 09:53:47.284   332   332 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 09:53:47.284   332   332 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 09:53:47.354  1016  3766 I art     : Explicit concurrent mark sweep GC freed 20941(1221KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/34MB, paused 2.406ms total 133.831ms
,08-29 09:53:47.584  6078  6189 D Finsky  : [1104] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-29 09:53:47.584  6078  6078 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-29 09:53:47.724   295   295 E SMD     : DCD OFF
,08-29 09:53:47.974  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 09:53:47.974  6799  6965 I jxcore-log: 
,08-29 09:53:47.974  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-29 09:53:47.974  6799  6965 I jxcore-log: 
,08-29 09:53:47.974  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:47.974  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:47.974  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:47.974  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:47.974  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:47.974  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:47.974  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:47.974  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:53:47.984  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:53:47.984  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 09:53:47.984  6799  6965 I jxcore-log: 
,08-29 09:53:47.984  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 09:53:47.984  6799  6965 I jxcore-log: 
,08-29 09:53:48.654  6799  6965 D executeNativeTests: Running unit tests
,08-29 09:53:48.734  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:53:48.734  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a added. We now have 2 listener(s)
,08-29 09:53:48.744  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 09:53:48.744  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:53:48.744  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:53:48.744  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:53:48.744  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b added. We now have 2 listener(s)
08-29 09:53:48.744  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:53:48.744  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:53:48.744  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:53:48.744  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:48.744  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:48.744  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:48.744  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:48.744  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:48.744  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:48.744  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:48.744  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:53:48.754  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:53:48.754  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:53:48.754  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:48.754  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 09:53:48.754  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:53:48.754  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 09:53:48.754  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:48.754  6799  6965 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 09:53:48.754  6799  6965 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:53:48.754  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:53:48.754  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:53:48.754  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 09:53:48.754  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:53:48.754  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:48.764  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:48.764  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.764  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:53:48.764  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a removed from the list
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:48.764  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b removed from the list
08-29 09:53:48.764  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:48.764  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:48.764  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.764  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:48.764  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:48.764  6799  6965 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 09:53:48.764  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:53:48.764  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:48.764  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:48.764  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.764  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:48.764  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:48.764  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:48.764  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:48.764  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.764  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:48.764  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.764  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 09:53:48.764  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:48.764  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:53:48.774  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:48.774  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:48.774  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:53:48.774  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:48.774  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.774  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:48.774  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:48.774  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:48.774  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:48.774  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:48.774  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.774  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:48.774  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.774  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:48.774  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:48.774  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:48.774  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:48.774  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:48.774  6799  6965 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:53:48.774  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:53:48.784  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:48.784  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:48.784  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:48.784  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:48.784  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:48.784  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:48.784  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:48.784  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:53:48.784  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:53:48.784  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:53:48.784  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:53:48.784  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:53:48.784  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:53:48.784  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:48.784  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 09:53:48.784  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:48.784  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:53:48.784  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:48.794  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:53:48.794  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:53:48.804  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 09:53:48.804  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 09:53:48.804  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:53:48.804  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 09:53:48.804  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 09:53:48.814  3210  3219 D BtGatt.GattService: registerClient() - UUID=23f2a9f9-e258-42ca-a643-dd08754a2211
,08-29 09:53:48.864  3210  3286 D BtGatt.GattService: onClientRegistered() - UUID=23f2a9f9-e258-42ca-a643-dd08754a2211, clientIf=6
,08-29 09:53:48.864  6799  6811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 09:53:48.864  3210  3221 D BtGatt.GattService: start scan with filters,
,08-29 09:53:48.864  3210  3335 D BtGatt.ScanManager: handling starting scan,
,08-29 09:53:48.864  3210  3335 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:48.864  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:53:48.864  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:53:48.864  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 09:53:48.864  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:53:48.874  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:53:48.874  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:53:48.874  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 09:53:48.874  3210  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 09:53:48.874  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:48.874  3210  3335 D BtGatt.ScanManager: allow scan with filters
08-29 09:53:48.874  3210  3335 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 09:53:48.874  3210  3335 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 09:53:48.884  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:53:48.884  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 09:53:48.884  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:48.884  3210  3335 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 09:53:48.884  3210  3335 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 09:53:48.884  6799  6965 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 09:53:48.894  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:48.894  6799  6965 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:53:48.894  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:48.894  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:53:48.894  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.894  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:53:48.894  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:53:48.894  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:53:48.894  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:53:48.894  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 09:53:48.894  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:53:48.894  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:53:48.894  3210  3326 D BtGatt.GattService: stopScan() - queue size =1
,08-29 09:53:48.894  3210  3219 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 09:53:48.894  3210  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 09:53:48.894  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:48.894  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 09:53:48.894  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:53:48.894  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:53:48.894  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 09:53:48.894  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 09:53:48.894  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:53:48.904  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 09:53:48.904  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 09:53:48.904  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:53:48.904  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 09:53:48.904  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:48.904  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:53:48.904  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:48.904  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:48.904  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:48.904  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:48.904  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:48.904  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:48.904  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:48.904  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:48.904  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:48.904  6799  6965 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 09:53:48.904  3210  3335 D BtGatt.ScanManager: filter size is 1
08-29 09:53:48.904  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:48.904  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:53:48.904  3210  3335 D BtGatt.ScanManager: delete FilterIndex - 3
,08-29 09:53:48.904  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:53:48.914  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:48.914  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:48.914  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:48.914  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:48.914  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:48.914  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:48.914  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:48.914  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:53:48.914  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 09:53:48.914  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:48.914  3210  3335 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:53:48.914  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:53:48.914  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:53:48.914  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:48.914  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 09:53:48.914  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:53:48.914  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:53:48.914  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:53:48.914  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:48.914  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 09:53:48.924  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:48.924  3210  3335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 09:53:48.924  3210  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 09:53:48.924  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:48.924  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:53:48.924  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:48.924  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:53:48.924  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:53:48.934  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:53:48.934  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 09:53:48.934  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 09:53:48.934  3210  3219 D BtGatt.GattService: registerClient() - UUID=06165025-6bf5-4986-bbdc-787e3fd4cdc9
,08-29 09:53:48.984  3210  3286 D BtGatt.GattService: onClientRegistered() - UUID=06165025-6bf5-4986-bbdc-787e3fd4cdc9, clientIf=6
,08-29 09:53:48.984  6799  6807 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 09:53:48.984  3210  3221 D BtGatt.GattService: start scan with filters
,08-29 09:53:48.984  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:53:48.984  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:53:48.984  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:53:48.984  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:53:48.984  3210  3335 D BtGatt.ScanManager: handling starting scan
,08-29 09:53:48.984  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:53:48.984  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:53:48.984  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 09:53:48.984  3210  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 09:53:48.984  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:48.994  3210  3335 D BtGatt.ScanManager: allow scan with filters
08-29 09:53:48.994  3210  3335 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 09:53:48.994  3210  3335 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 09:53:48.994  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:53:48.994  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-29 09:53:48.994  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:48.994  3210  3335 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 09:53:48.994  3210  3335 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-29 09:53:48.994  6799  6965 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 09:53:49.004  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:53:49.004  6799  6965 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 09:53:49.004  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:53:49.004  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 09:53:49.004  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.004  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 09:53:49.004  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 09:53:49.004  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 09:53:49.004  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:53:49.004  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 09:53:49.004  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 09:53:49.004  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:53:49.004  3210  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 09:53:49.004  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:49.014  3210  3326 D BtGatt.GattService: stopScan() - queue size =1
,08-29 09:53:49.014  3210  3219 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 09:53:49.014  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 09:53:49.014  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 09:53:49.014  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 09:53:49.014  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:53:49.014  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:53:49.014  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:53:49.014  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 09:53:49.014  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:49.014  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:53:49.014  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:53:49.014  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 09:53:49.024  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:53:49.024  3210  3335 D BtGatt.ScanManager: filter size is 1
08-29 09:53:49.024  3210  3335 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 09:53:49.024  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:49.024  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:49.024  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:53:49.024  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.024  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:53:49.024  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:49.024  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
,08-29 09:53:49.024  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.024  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.024  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.024  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.024  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:53:49.034  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 09:53:49.034  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:49.034  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.034  3210  3335 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:53:49.034  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:53:49.034  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.034  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:53:49.034  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.034  6799  6965 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 09:53:49.034  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-29 09:53:49.034  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:49.034  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:53:49.034  3210  3335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 09:53:49.044  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:49.044  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:49.044  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:49.044  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:49.044  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:49.044  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:49.044  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:49.044  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:53:49.044  3210  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 09:53:49.044  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:49.044  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:53:49.044  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:53:49.044  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:53:49.044  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:53:49.044  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:53:49.044  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:53:49.044  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 09:53:49.054  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:53:49.054  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:49.054  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:49.054  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:53:49.064  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:53:49.064  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:53:49.064  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 09:53:49.064  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 09:53:49.064  3210  3326 D BtGatt.GattService: registerClient() - UUID=5bd26eee-56ac-40f6-a6cb-d325a045fa73
,08-29 09:53:49.104  3210  3286 D BtGatt.GattService: onClientRegistered() - UUID=5bd26eee-56ac-40f6-a6cb-d325a045fa73, clientIf=6
,08-29 09:53:49.104  6799  6807 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 09:53:49.114  3210  3327 D BtGatt.GattService: start scan with filters
,08-29 09:53:49.114  3210  3335 D BtGatt.ScanManager: handling starting scan
,08-29 09:53:49.114  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 09:53:49.114  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 09:53:49.114  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 09:53:49.114  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:53:49.114  3210  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 09:53:49.114  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:49.114  3210  3335 D BtGatt.ScanManager: allow scan with filters
,08-29 09:53:49.124  3210  3335 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 09:53:49.124  3210  3335 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-29 09:53:49.124  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:53:49.124  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:53:49.124  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:53:49.124  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:53:49.124  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 09:53:49.124  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:49.124  3210  3335 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 09:53:49.124  3210  3335 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 09:53:49.124  6799  6965 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 09:53:49.134  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.134  6799  6965 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:53:49.134  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.134  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:53:49.134  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.134  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:53:49.134  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:53:49.134  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:53:49.134  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:53:49.134  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:53:49.134  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:53:49.134  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:53:49.134  3210  3326 D BtGatt.GattService: stopScan() - queue size =1
,08-29 09:53:49.134  3210  3327 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 09:53:49.134  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 09:53:49.134  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 09:53:49.134  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:53:49.134  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 09:53:49.134  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 09:53:49.134  3210  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 09:53:49.134  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:53:49.144  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:53:49.144  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 09:53:49.144  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 09:53:49.144  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 09:53:49.144  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:53:49.144  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-29 09:53:49.144  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:49.144  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:49.144  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:49.144  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:53:49.144  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.144  6799  6965 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:53:49.144  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.144  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.144  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:53:49.144  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.144  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:53:49.144  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
,08-29 09:53:49.144  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.144  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.144  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:53:49.144  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.144  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.144  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.154  6799  6965 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 09:53:49.154  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.154  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.154  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.154  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.154  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 09:53:49.154  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.154  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.154  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.154  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.154  6799  6965 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 09:53:49.154  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.154  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.154  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.154  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.154  6799  6965 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 09:53:49.154  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.154  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:53:49.154  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
,08-29 09:53:49.154  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.154  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.154  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.154  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.154  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.164  3210  3335 D BtGatt.ScanManager: filter size is 1
08-29 09:53:49.164  3210  3335 D BtGatt.ScanManager: delete FilterIndex - 5
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.164  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:53:49.164  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:53:49.164  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:53:49.164  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:53:49.164  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.164  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:53:49.164  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.164  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.164  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.164  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:53:49.164  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.164  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.164  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.164  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.164  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.164  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.164  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.164  6799  6965 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 09:53:49.164  6799  6965 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-29 09:53:49.164  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 09:53:49.164  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:49.164  3210  3335 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:53:49.164  6799  6965 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:53:49.164  6799  6965 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710],
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 09:53:49.164  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:53:49.174  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:53:49.174  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:53:49.174  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 09:53:49.174  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 09:53:49.174  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:53:49.174  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:53:49.174  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:53:49.174  6799  6965 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 09:53:49.174  6799  6965 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-29 09:53:49.174  6799  6965 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 09:53:49.174  6799  6965 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:53:49.174  6799  6965 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:53:49.174  6799  6965 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 09:53:49.174  6799  6965 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 09:53:49.174  6799  6965 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:53:49.174  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 09:53:49.174  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 09:53:49.174  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:49.174  3210  3335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 09:53:49.174  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 09:53:49.174  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 09:53:49.174  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 09:53:49.174  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 09:53:49.174  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 09:53:49.174  6799  6965 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 09:53:49.174  6799  6965 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:53:49.174  6799  6965 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-29 09:53:49.174  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.174  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.174  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.174  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.174  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.174  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.174  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 09:53:49.174  3210  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 09:53:49.174  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:53:49.174  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.174  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.174  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.174  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.174  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:53:49.174  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.174  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.174  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.174  6799  7098 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1329)
,08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.184  6799  6965 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-29 09:53:49.184  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.184  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.184  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.184  6799  7099 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1329
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.184  6799  6965 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 09:53:49.184  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.184  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.184  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.184  6799  7098 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 09:53:49.184  6799  6965 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:53:49.184  6799  6965 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-29 09:53:49.184  6799  6965 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:53:49.184  6799  6965 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:53:49.184  6799  6965 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 09:53:49.184  6799  6965 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 09:53:49.184  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.184  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.184  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.184  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.184  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.184  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.184  6799  7098 D BluetoothSocket: connect(): myUserId = 0
08-29 09:53:49.184  6799  7098 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.184  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.184  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.194  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.194  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.194  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.194  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.194  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.194  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.194  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:53:49.194  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.194  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.194  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.194  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.194  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.194  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.194  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.194  3210  3219 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:53:49.194  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.194  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.194  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.194  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.194  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.194  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:53:49.194  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.194  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.194  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.194  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.194  6799  7098 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,08-29 09:53:49.194  6799  6965 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:53:49.194  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:53:49.204  6799  6799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 09:53:49.204  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
,08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.204  6799  6799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:53:49.204  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.204  6799  7100 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:53:49.204  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.204  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.204  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.204  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.204  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.204  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.204  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.204  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.204  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:53:49.204  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.204  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.204  6799  7100 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.204  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 09:53:49.204  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.204  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:53:49.204  6799  6799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 09:53:49.204  6799  6965 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-29 09:53:49.204  6799  6965 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:53:49.204  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 09:53:49.204  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.204  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.204  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.204  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.204  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.204  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.204  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.204  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.204  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.204  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.204  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.204  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.214  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.214  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:53:49.214  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.214  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.214  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.214  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.214  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:53:49.214  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.214  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.214  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.214  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.214  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.214  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:53:49.214  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:53:49.214  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:53:49.214  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.214  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.214  6799  6965 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@121b147a not in the list
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.214  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:53:49.214  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:53:49.214  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.214  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:53:49.214  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:53:49.214  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:53:49.214  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621142b not in the list
,08-29 09:53:49.214  6799  6965 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:53:49.214  6799  6965 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:53:49.214  6799  6965 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-29 09:53:49.214  6799  6965 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:53:49.214  6799  6965 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:53:49.214  6799  6965 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 09:53:49.214  6799  6965 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 09:53:49.224  6799  6965 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-29 09:53:49.224  6799  6965 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 09:53:49.224  6799  6965 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 09:53:49.224  6799  6965 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 09:53:49.224  6799  6965 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 09:53:49.224  6799  6965 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-29 09:53:49.224  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 09:53:49.224  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ce61515 added. We now have 2 listener(s)
08-29 09:53:49.224  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:53:49.224  6799  6965 D BluetoothAdapter: enable(),
,08-29 09:53:49.224  6799  6965 D BluetoothAdapter: enable(): BT is already enabled..!,
,08-29 09:53:49.224  1016  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-29 09:53:49.224  1016  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 09:53:49.224  1016  1029 D SecContentProvider2: mCursor = null
,08-29 09:53:49.234  1016  1029 D WifiService: setWifiEnabled: true pid=6799, uid=10170
,08-29 09:53:49.234  1016  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 09:53:49.234  1016  1029 W WifiService: Failed getting userId using ActivityManagerNative
08-29 09:53:49.234  1016  1029 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 09:53:49.234  1016  1029 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 09:53:49.234  1016  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 09:53:49.234  1016  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 09:53:49.234  1016  1029 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 09:53:49.234  1016  1029 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 09:53:49.234  1016  1029 D SettingsProvider: name = wifi_on
,08-29 09:53:49.234  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 09:53:49.234  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba1902a added. We now have 3 listener(s)
08-29 09:53:49.234  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:53:49.244  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 09:53:49.244  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18335e1b added. We now have 4 listener(s)
,08-29 09:53:49.244  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:53:49.244  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:53:49.244  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@186d7bb8 added. We now have 5 listener(s)
,08-29 09:53:49.244  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:53:49.244  1016  1136 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 09:53:49.244  1016  1136 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 09:53:49.244  1016  1136 D SecContentProvider2: mCursor = null
,08-29 09:53:49.254  1016  1136 D WifiService: setWifiEnabled: false pid=6799, uid=10170
,08-29 09:53:49.254  1016  1136 D SettingsProvider: name = wifi_on
,08-29 09:53:49.264  1016  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 09:53:49.264  6799  6965 D BluetoothAdapter: disable()
08-29 09:53:49.264  1016  1335 D SettingsProvider: name = bluetooth_on
,08-29 09:53:49.264  1394  1394 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 09:53:49.264  1394  1394 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-29 09:53:49.264  1394  1394 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-29 09:53:49.264  1394  1394 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 09:53:49.274  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-29 09:53:49.274  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:53:49.284  3210  3283 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-29 09:53:49.284  3210  3283 D BluetoothAdapterProperties: Setting state to 13
08-29 09:53:49.284  3210  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 09:53:49.284  3210  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 09:53:49.284  3210  3283 D BluetoothAdapterService: updateAdapterState state is 13
08-29 09:53:49.284  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:53:49.284  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 09:53:49.284  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:49.284  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:49.284  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:49.284  3210  3283 D BluetoothAdapterService: Autoconnection is available 
,08-29 09:53:49.284  3210  3283 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 09:53:49.284  3210  3283 D BluetoothAdapterService: terminating service from this receiver
,08-29 09:53:49.284  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0,
,08-29 09:53:49.284  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:49.284  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.284  3210  3210 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-29 09:53:49.284  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 09:53:49.284  3210  3210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@122fb1e7, channel: 19, state: LISTENING
08-29 09:53:49.284  3210  3210 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@122fb1e7, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@191b33ef, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@62d5194mSocket: android.net.LocalSocket@1c9f043d impl:android.net.LocalSocketImpl@272d9432 fd:FileDescriptor[80]
08-29 09:53:49.284  3210  3210 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c9f043d impl:android.net.LocalSocketImpl@272d9432 fd:FileDescriptor[80],
,08-29 09:53:49.284  3210  3283 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 09:53:49.294  3210  3283 D BluetoothAdapterProperties: mDiscovering is false
,08-29 09:53:49.294  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:49.294  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:53:49.294  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:49.294  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:49.294  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:49.294  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:49.294  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:49.294  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:49.294  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:53:49.294  1016  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 09:53:49.294  1394  1394 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-29 09:53:49.294  1394  1394 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-29 09:53:49.294  1394  1394 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
08-29 09:53:49.294  4753  4753 D BluetoothPbap: Proxy object disconnected
08-29 09:53:49.294  4753  4753 D PbapServerProfile: Bluetooth service disconnected
,08-29 09:53:49.294  1016  1128 E WifiNative-wlan0: do suspend true
08-29 09:53:49.294  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:53:49.294  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:49.294  3210  3283 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
08-29 09:53:49.294  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:53:49.294  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:49.304  3210  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 09:53:49.304  3210  3286 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:53:49.304  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 09:53:49.304  3210  3283 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-29 09:53:49.304  3210  3283 E bt-btif : cmd socket is not created
08-29 09:53:49.304  3210  5295 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:53:49.304  3210  3287 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-29 09:53:49.304  6799  7098 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fa084f6, channel: -1, state: INIT
08-29 09:53:49.304  6799  7098 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2fa084f6, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c1fc0f7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c5a9b64mSocket: android.net.LocalSocket@2144d1cd impl:android.net.LocalSocketImpl@33c7fa82 fd:FileDescriptor[106]
08-29 09:53:49.304  6799  7098 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2144d1cd impl:android.net.LocalSocketImpl@33c7fa82 fd:FileDescriptor[106]
08-29 09:53:49.304  6799  7098 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1329)
08-29 09:53:49.304  3210  3283 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 09:53:49.304  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:49.314  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:53:49.314  3210  3287 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40,
08-29 09:53:49.314  3210  3287 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-29 09:53:49.314  3210  3287 W bt-btif : invalid rfc slot id: 4
,08-29 09:53:49.314  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:49.314  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-29 09:53:49.314  3210  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-29 09:53:49.314  3210  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:53:49.314  3210  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
08-29 09:53:49.314  3210  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:53:49.314  3210  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:53:49.314  3210  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:53:49.314  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:49.324  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:53:49.324  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-29 09:53:49.334  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-29 09:53:49.334  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 09:53:49.334  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-29 09:53:49.344  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 09:53:49.344  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:53:49.344  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:53:49.344  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:53:49.344  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-29 09:53:49.344  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 09:53:49.344  1016  1474 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:53:49.354  1016  1343 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 09:53:49.354  1887  1887 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 09:53:49.354  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 09:53:49.354  3210  3210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c57f300, channel: 5, state: LISTENING
08-29 09:53:49.354  3210  3210 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c57f300, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14421efc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f7ca739mSocket: android.net.LocalSocket@21cc17e impl:android.net.LocalSocketImpl@ea6f6df fd:FileDescriptor[82]
08-29 09:53:49.354  3210  3210 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21cc17e impl:android.net.LocalSocketImpl@ea6f6df fd:FileDescriptor[82]
,08-29 09:53:49.354  4753  4753 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:53:49.354  3210  3210 I BtOppRfcommListener: stopping Accept Thread
08-29 09:53:49.354  3210  3210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2bc93f2c, channel: 12, state: LISTENING
08-29 09:53:49.354  3210  3210 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2bc93f2c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@386e3a6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3df77df5mSocket: android.net.LocalSocket@2b3f778a impl:android.net.LocalSocketImpl@3f2e21fb fd:FileDescriptor[86]
08-29 09:53:49.354  3210  3210 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2b3f778a impl:android.net.LocalSocketImpl@3f2e21fb fd:FileDescriptor[86]
,08-29 09:53:49.354  3210  5295 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 09:53:49.364   282  1002 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:53:49.364  1663  2529 V NativeCrypto: Read error: ssl=0xb80a3200: I/O error during system call, Connection timed out
,08-29 09:53:49.364  1016  1130 E ConnectivityService: updateNetworkInfo()
,08-29 09:53:49.364  1016  1130 E ConnectivityService: updateNetworkInfo(),
08-29 09:53:49.364  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-29 09:53:49.364  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-29 09:53:49.374  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:49.374  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:49.374  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 09:53:49.374  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 09:53:49.374  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:49.374  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.374  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:49.374  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 09:53:49.374  4753  4753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:53:49.374  1663  2529 V NativeCrypto: SSL shutdown failed: ssl=0xb80a3200: I/O error during system call, Broken pipe
,08-29 09:53:49.384  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:49.384  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:49.384  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:49.384  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:49.384  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:49.384  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:49.384  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:49.384  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:49.384  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:53:49.384  1016  1562 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-29 09:53:49.384  1016  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:49.384  1016  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:53:49.384  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:49.384  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:53:49.384  1016  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-29 09:53:49.384  1016  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:53:49.394  1016  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-29 09:53:49.394  1016  1735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 09:53:49.394  1016  1735 I qtaguid : Tagging socket 330 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
08-29 09:53:49.394  3210  3210 V BluetoothOppManager: cleanUp...
08-29 09:53:49.394  1016  1335 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 09:53:49.394  1016  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 09:53:49.394  1016  1127 D WifiP2pService: InactiveState{ what=131204 }
08-29 09:53:49.394  1016  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 09:53:49.394  1016  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 09:53:49.404  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:49.404  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-29 09:53:49.404  1016  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.404  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 09:53:49.404  1016  1735 I qtaguid : Untagging socket 330
08-29 09:53:49.404  1016  1735 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 09:53:49.414  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 09:53:49.414  1016  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:53:49.414  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:53:49.414  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:49.414  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:53:49.414  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.414  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:49.414  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-29 09:53:49.414  1016  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:49.414  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.414  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:49.424  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:53:49.424  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-29 09:53:49.424  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 09:53:49.424  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 09:53:49.424   282   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 09:53:49.424   282   998 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-29 09:53:49.424  1016  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 09:53:49.424  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:53:49.424  1016  1130 V NetworkStats: updateIfacesLocked()
08-29 09:53:49.424  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-29 09:53:49.424  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 09:53:49.424  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:53:49.434  1663  1663 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:53:49.434  1016  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-29 09:53:49.434  1016  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-29 09:53:49.434  4753  4753 D DockEventReceiver: finishStartingService: stopping service
08-29 09:53:49.434  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 09:53:49.434  1016  1127 D WifiP2pService: P2pDisablingState
08-29 09:53:49.434  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.434  1016  1130 V NetworkStats: performPollLocked() took 7ms
08-29 09:53:49.434  1016  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 09:53:49.434  1016  1127 D WifiP2pService: p2p socket connection lost
,08-29 09:53:49.434  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 09:53:49.434  1016  1127 D WifiP2pService: P2pDisabledState
08-29 09:53:49.434  1016  1128 E WifiNative-wlan0: do suspend true
08-29 09:53:49.434  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 09:53:49.434  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 09:53:49.434  1016  1046 D WifiDisplayController: disconnect
08-29 09:53:49.434  1016  1046 D WifiDisplayController: updateConnection
08-29 09:53:49.434  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 09:53:49.434  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 09:53:49.444  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-29 09:53:49.444  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 09:53:49.444  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 09:53:49.444  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 09:53:49.444  1016  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-29 09:53:49.444  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 09:53:49.444  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.444  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.444  1016  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 09:53:49.444  1016  1735 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:49.444  1175  1734 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 09:53:49.444  1016  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 09:53:49.444  4753  4753 D BluetoothNotiBroadcastReceiver: onReceive
08-29 09:53:49.444  1016  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-29 09:53:49.444  1016  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-29 09:53:49.444  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 09:53:49.454  1463  1463 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 09:53:49.454  1463  1463 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 09:53:49.454  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
08-29 09:53:49.454  1016  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 09:53:49.454  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:53:49.454  1016  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 09:53:49.454  1016  1125 V NetworkStats: updateIfacesLocked()
08-29 09:53:49.454  1016  1130 E ConnectivityService: updateNetworkInfo()
08-29 09:53:49.454  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
08-29 09:53:49.454  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 09:53:49.454  1016  3766 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 09:53:49.454  1016  1131 D Tethering: MasterInitialState.processMessage what=3
08-29 09:53:49.454  1016  1130 E ConnectivityService: updateNetworkInfo()
08-29 09:53:49.454  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.454  1016  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-29 09:53:49.454  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:53:49.454  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:53:49.454  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 09:53:49.464  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:49.464  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 09:53:49.464  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-29 09:53:49.464  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 09:53:49.464  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.464  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 09:53:49.464  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-29 09:53:49.464  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.464  1016  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-29 09:53:49.464  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.464  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.464  1016  1125 V NetworkStats: performPollLocked() took 7ms
08-29 09:53:49.464  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.464  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 09:53:49.464  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:49.464  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:49.464  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:49.464  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:49.464  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:53:49.464  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 09:53:49.464  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 09:53:49.464  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-29 09:53:49.474  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-29 09:53:49.474  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-29 09:53:49.474  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:53:49.474  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:49.474  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:53:49.474  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.474  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.474  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.474  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.474  1016  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
08-29 09:53:49.474  1016  1127 D WifiP2pService: DefaultState{ what=143375 }
08-29 09:53:49.474  7112  7112 E Zygote  : MountEmulatedStorage()
08-29 09:53:49.474  7112  7112 E Zygote  : v2
08-29 09:53:49.474  7112  7112 I libpersona: KNOX_SDCARD checking this for 10055
08-29 09:53:49.474  7112  7112 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:49.484  7112  7112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:49.484  7112  7112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:49.484  1016  1328 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7112 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 09:53:49.484  7112  7112 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:49.484  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.484  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 09:53:49.484   282  1002 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:53:49.494  1394  1394 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 09:53:49.494  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
,08-29 09:53:49.494  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:49.494  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:53:49.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.504  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.504  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:49.504  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 09:53:49.504  1016  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 09:53:49.514  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:53:49.514  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:49.514  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:49.514  7112  7112 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:49.514  7112  7112 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:53:49.514  4753  4753 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:49.514  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 09:53:49.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:49.524  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.524  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:49.524  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:49.524  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:49.524  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-29 09:53:49.524  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:49.524  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 09:53:49.524  1175  1175 D HotspotTile: onReceive : 0, 0
,08-29 09:53:49.524  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 09:53:49.524  3210  3283 D BtConfig.SecureMode: isSecureModeOn:false
08-29 09:53:49.524  3210  3283 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 09:53:49.524  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-29 09:53:49.524  3210  3283 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-29 09:53:49.524  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 09:53:49.524  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 09:53:49.524  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:49.524  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:49.524  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:49.524  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:49.524  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:49.524  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:49.534  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:49.534  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:49.534  1016  3702 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:49.534  1016  3702 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 09:53:49.534  1016  3702 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:49.534  1016  3702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.534  1016  3702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:49.544  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 09:53:49.544  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 09:53:49.544  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 09:53:49.544  3210  3210 D HeadsetService: Received stop request...Stopping profile...
,08-29 09:53:49.544  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-29 09:53:49.544  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:49.544  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-29 09:53:49.544  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.544  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 09:53:49.544  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-29 09:53:49.544  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 09:53:49.544  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627,
,08-29 09:53:49.544  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 09:53:49.554  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:53:49.554  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 09:53:49.554  3210  3210 D A2dpService: Received stop request...Stopping profile...
,08-29 09:53:49.554  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 09:53:49.554  3210  3339 D A2dpStateMachine: Exit Disconnected: -1
,08-29 09:53:49.554  4753  4753 D HeadsetProfile: Bluetooth service disconnected
,08-29 09:53:49.554  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:49.554  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.554  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:49.554  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-29 09:53:49.554  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 09:53:49.564  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 09:53:49.564  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:49.564  1016  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:49.564  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-29 09:53:49.564  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:49.564  1016  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.564  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 09:53:49.564  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 09:53:49.564  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 09:53:49.564  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 09:53:49.564  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:49.564  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 09:53:49.564  1016  1016 D BluetoothA2dp: Proxy object disconnected
08-29 09:53:49.564  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 09:53:49.574  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:49.574  4753  4753 D BluetoothA2dp: Proxy object disconnected
08-29 09:53:49.574  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.574  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 09:53:49.574  7112  7112 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 09:53:49.574  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService,
08-29 09:53:49.574  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:53:49.574  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 09:53:49.574  4753  4753 D A2dpProfile: Bluetooth service disconnected
08-29 09:53:49.574  1016  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:49.574  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 09:53:49.574  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:49.574  1016  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.574  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:49.574  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 09:53:49.574  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 09:53:49.574  3210  3283 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 09:53:49.574  1016  1328 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:49.574  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 09:53:49.584  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:49.584  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.584  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:49.584  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:53:49.584  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 09:53:49.584  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:53:49.584  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-29 09:53:49.584  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:53:49.584  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:53:49.584  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 09:53:49.584  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 09:53:49.584  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-29 09:53:49.584  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 09:53:49.584  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 09:53:49.584  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 09:53:49.584  3210  3283 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 09:53:49.584  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 09:53:49.584  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 09:53:49.584  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 09:53:49.584  3210  3210 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 09:53:49.584  3210  3210 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 09:53:49.584  3210  3210 D HidService: Received stop request...Stopping profile...
,08-29 09:53:49.594  3210  3210 D HidService: Stopping Bluetooth HidService
08-29 09:53:49.594  3210  3210 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 09:53:49.594  3210  3210 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 09:53:49.594  3210  3210 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 09:53:49.594  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:49.594  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-29 09:53:49.594  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 09:53:49.594  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 09:53:49.594  3210  3210 D HealthService: Received stop request...Stopping profile...
08-29 09:53:49.594  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:49.594  3210  3210 D BluetoothA2dp: Proxy object disconnected
08-29 09:53:49.594  3210  3210 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-29 09:53:49.594  3210  3340 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 09:53:49.594  3210  3210 I GKI_LINUX: GKI_exit_task 2 done
08-29 09:53:49.594  3210  3210 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 09:53:49.594  3210  3210 D PanService: Received stop request...Stopping profile...
,08-29 09:53:49.594  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:49.594  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:53:49.594  4753  4753 D BluetoothInputDevice: Proxy object disconnected
08-29 09:53:49.594  4753  4753 D HidProfile: Bluetooth service disconnected
08-29 09:53:49.594  4753  4753 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:53:49.594  4753  4753 D PanProfile: Bluetooth service disconnected
08-29 09:53:49.594  3210  3210 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 09:53:49.604  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:49.604  4753  4753 D BluetoothMap: Proxy object disconnected
08-29 09:53:49.604  4753  4753 D MapProfile: Bluetooth service disconnected
,08-29 09:53:49.604  3210  3210 D SapService: Received stop request...Stopping profile...
08-29 09:53:49.604  3210  3210 D SapService: Stopping Bluetooth SapService
08-29 09:53:49.604  7112  7112 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-29 09:53:49.604  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:49.604  7112  7112 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 09:53:49.604  7112  7112 D UserAnalysis: Create SecureDbHelper
,08-29 09:53:49.604  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 09:53:49.604  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:53:49.604  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:53:49.604  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 09:53:49.604  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 09:53:49.604  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:53:49.604  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:53:49.604  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 09:53:49.604  3210  3210 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:53:49.604  3210  3210 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:53:49.604  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 09:53:49.604  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:53:49.604  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:53:49.604  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 09:53:49.604  3210  3210 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:53:49.604  3210  3210 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 09:53:49.604  4753  4753 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 09:53:49.604  4753  4753 D SapProfile: Bluetooth service disconnected
,08-29 09:53:49.614  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-29 09:53:49.614  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:53:49.614  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 09:53:49.614  3210  3210 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-29 09:53:49.614  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-29 09:53:49.614  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:53:49.614  3210  3210 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 09:53:49.614  3210  3210 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 09:53:49.614  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 09:53:49.614  3210  3283 D BluetoothAdapterProperties: Setting state to 10
08-29 09:53:49.614  3210  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 09:53:49.614  3210  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 09:53:49.614  3210  3283 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 09:53:49.614  3210  3283 D BluetoothAdapterService: Autoconnection is available 
08-29 09:53:49.614  3210  3283 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 09:53:49.614  3210  3283 I BluetoothAdapterState: Entering OffState
,08-29 09:53:49.614  7112  7112 D IntelligenceServiceApplication: onCreate()
,08-29 09:53:49.614  4753  4763 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 09:53:49.624  1016  3755 I ActivityManager: Killing 6742:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-29 09:53:49.624  6799  6811 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.624  6799  6811 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.624  6799  6811 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 09:53:49.624  6799  6811 D BluetoothLeAdvertiser: Exit stop advertising
08-29 09:53:49.624  6799  6811 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 09:53:49.624  6799  6811 D BluetoothLeScanner: Exiting stopAllScan
,08-29 09:53:49.624  7112  7112 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 09:53:49.634  1394  1394 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 09:53:49.634  1016  3755 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 09:53:49.634  1016  3755 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:49.634  1016  3755 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:49.634  1016  3755 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:49.634  1016  3755 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:49.644  7128  7128 E Zygote  : MountEmulatedStorage()
,08-29 09:53:49.644  7128  7128 E Zygote  : v2
08-29 09:53:49.644  7128  7128 I libpersona: KNOX_SDCARD checking this for 10105
08-29 09:53:49.644  7128  7128 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:49.644  7128  7128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:49.654  1016  3755 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7128 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-29 09:53:49.654  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 09:53:49.654  7128  7128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 09:53:49.654  7128  7128 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 09:53:49.654  7112  7112 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 09:53:49.654  1437  1447 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.654  1437  1447 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.654  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 09:53:49.654  4753  7127 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:53:49.664  4753  4763 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:53:49.664  4753  4763 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.664  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 09:53:49.664  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.664  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:53:49.664  1611  1627 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.664  1611  1627 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.664  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 09:53:49.664  3210  3327 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:53:49.664  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 09:53:49.664  1663  1678 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.664  1663  1678 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.664  1463  2141 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.664  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 09:53:49.664  1463  2141 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.664  4753  4767 D Bluetoothsap: onBluetoothStateChange: up=false
08-29 09:53:49.664  4753  4767 D Bluetoothsap: Unbinding service...
,08-29 09:53:49.664  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.664  4753  7127 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 09:53:49.674  1450  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.674  1450  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:53:49.674  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 09:53:49.674  3210  3221 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.674  3210  3221 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.674  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.674  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.674  1175  1190 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 09:53:49.674  1175  1190 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:53:49.674  4753  4767 D BluetoothMap: onBluetoothStateChange: up=false
08-29 09:53:49.674  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.674  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:49.674  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
08-29 09:53:49.674  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 09:53:49.674  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 09:53:49.674  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 09:53:49.674  7112  7112 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 09:53:49.674  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 09:53:49.684  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.684  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 09:53:49.684  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:49.684  1175  1175 D BluetoothTile:  getBluetoothState : 10
,08-29 09:53:49.684  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 09:53:49.684  1887  1887 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 09:53:49.684  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 09:53:49.684  7128  7128 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:49.684  7128  7128 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:49.684  1016  3766 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:53:49.694  4753  4753 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:53:49.694  1394  1394 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 09:53:49.694  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 09:53:49.694  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 09:53:49.694  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 09:53:49.694  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:49.694  1016  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-29 09:53:49.694  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 09:53:49.694  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 09:53:49.694  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 09:53:49.694  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 09:53:49.694  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:49.694  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.694  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 09:53:49.704  6799  6799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:53:49.704  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.704  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 09:53:49.704  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 09:53:49.714  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 09:53:49.714  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.714  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-29 09:53:49.714  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.724  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 09:53:49.724  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 09:53:49.724  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-29 09:53:49.734  1394  1394 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-29 09:53:49.734  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:49.734  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:49.734  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 09:53:49.734  1394  1394 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-29 09:53:49.734  1394  1394 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 09:53:49.734  1394  1394 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 09:53:49.734  1394  1394 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 09:53:49.734  1016  1131 D Tethering: InitialState.processMessage what=4
,08-29 09:53:49.734  1016  1131 E Tethering: No numeric data
,08-29 09:53:49.734  1016  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 09:53:49.734  1016  1131 D Tethering: clearTetheredNotification()
,08-29 09:53:49.734  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:49.734  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:49.734  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:49.734  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.734  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
08-29 09:53:49.734  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:49.734  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:49.734  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:49.734  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:53:49.734  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:53:49.734  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 09:53:49.734  1175  1175 D HotspotTile: updateTetherState():false, false
,08-29 09:53:49.744  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.744  1016  1125 V NetworkStats: performPollLocked() took 3ms
,08-29 09:53:49.744  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:49.744  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:53:49.814   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 09:53:49.814   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 09:53:49.814  7128  7163 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 09:53:49.814   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 09:53:49.814   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 09:53:49.824  7128  7163 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 09:53:49.874  1394  1394 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 09:53:49.954  1394  1394 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
08-29 09:53:49.954  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:53:49.954  7128  7128 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.File.doAccess(File.java:283),
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:53:49.964  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:49.954  7128  7128 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332),
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 09:53:49.954  7128  7128 D StrictMode: ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:53:49.964  1016  1328 I ActivityManager: Killing 6757:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
08-29 09:53:49.954  7128  7128 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
,08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:53:49.954  7128  7128 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.andr,oid.apps.gmm.shared.f.a.a(PG:48)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:53:49.954  7128  7128 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:53:49.954  7128  7128 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:53:49.954  7128  7128 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:53:49.974  1016  1343 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:53:49.954  7128  7128 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:53:49.954  7128  7128 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:53:49.974  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 09:53:49.964  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:49.964  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 09:53:49.974  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:49.974  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:49.974  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 09:53:49.974  2213  2213 I Hs20UtilService: Starting #8
08-29 09:53:49.974  2213  2228 I Hs20UtilService: Message received 5007
08-29 09:53:49.974  1016  1016 I ApplicationPolicy: updateDataUsageMap
08-29 09:53:49.984  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:49.994  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:49.994  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 09:53:49.994  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 09:53:49.994  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 09:53:49.994  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:53:50.004  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 09:53:50.004  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 09:53:50.004  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 09:53:50.014  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 09:53:50.014  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 09:53:50.014  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 09:53:50.014  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:53:50.014  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 09:53:50.014  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 09:53:50.014  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 09:53:50.014  1016  1474 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-29 09:53:50.014  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.014  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.014  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.014  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.034  7175  7175 E Zygote  : MountEmulatedStorage()
08-29 09:53:50.034  7175  7175 E Zygote  : v2
08-29 09:53:50.034  7175  7175 I libpersona: KNOX_SDCARD checking this for 10064
08-29 09:53:50.034  7175  7175 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:50.034  7175  7175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:50.034  1016  1474 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7175 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 09:53:50.044  7175  7175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:50.044  7175  7175 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:50.044  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:53:50.064  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-29 09:53:50.064  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 09:53:50.064  7128  7173 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.,
,08-29 09:53:50.074  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:50.074  7175  7175 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:50.084  4753  4753 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:50.084  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:53:50.084  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 09:53:50.084  1611  2111 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:53:50.084  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 09:53:50.084  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:50.084  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:50.084  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:50.084  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:50.084  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:50.084  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:50.084  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-29 09:53:50.084  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 09:53:50.084  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:50.094  1175  1175 D HotspotTile: onReceive : 1, 0
,08-29 09:53:50.094  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:50.094  1016  3702 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 09:53:50.094  1016  3702 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:50.094  1016  3702 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:50.094  1016  3702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 09:53:50.104  7175  7175 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 09:53:50.114  7175  7175 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 09:53:50.114  7175  7175 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 09:53:50.144  7175  7175 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 09:53:50.144  1016  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 09:53:50.144  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.144  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.144  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.144  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.164  7192  7192 E Zygote  : MountEmulatedStorage(),
,08-29 09:53:50.164  7192  7192 E Zygote  : v2,
08-29 09:53:50.164  7192  7192 I libpersona: KNOX_SDCARD checking this for 10065
08-29 09:53:50.164  7192  7192 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:50.164  7192  7192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:50.164  1016  1496 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7192 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:53:50.164  7192  7192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:50.164  7192  7192 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 09:53:50.174  1016  1496 I ActivityManager: Killing 6818:com.wsomacp/u0a23 (adj 15): empty #21
,08-29 09:53:50.184  7192  7192 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:50.184  7192  7192 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:50.184   321   321 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 22.306ms
,08-29 09:53:50.204   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.653ms
,08-29 09:53:50.204  7192  7192 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 09:53:50.214  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:50.214  1016  1561 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-29 09:53:50.214  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:50.214  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-29 09:53:50.214  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.214  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.214  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.214  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.224   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 16.346ms,
,08-29 09:53:50.234  7207  7207 E Zygote  : MountEmulatedStorage(),
08-29 09:53:50.234  7207  7207 E Zygote  : v2
,08-29 09:53:50.234  7207  7207 I libpersona: KNOX_SDCARD checking this for 10102
08-29 09:53:50.234  7207  7207 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:50.234  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 09:53:50.234  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:50.234  1016  1561 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7207 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-29 09:53:50.234  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 09:53:50.234  1016  1561 I ActivityManager: Killing 6859:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-29 09:53:50.254  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:50.254  7207  7207 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:50.274  7207  7207 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 09:53:50.314  1016  1048 I PowerManagerService: [PWL] Off : 50s ago
,08-29 09:53:50.324  1016  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-29 09:53:50.324  1016  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 09:53:50.324  1016  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=866)
,08-29 09:53:50.484  7207  7227 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-29 09:53:50.484  7207  7227 I Babel_SMS: MmsConfig.loadMmsSettings
,08-29 09:53:50.484  7207  7227 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-29 09:53:50.484  7207  7227 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 09:53:50.494  1016  3363 D SSRM:n  : SIOP:: AP = 390
,08-29 09:53:50.514  7207  7227 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-29 09:53:50.514  7207  7227 I Babel_SMS: MmsConfig.loadFromResources
,08-29 09:53:50.524  7207  7227 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 09:53:50.524  7207  7227 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 09:53:50.544  1016  1561 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-29 09:53:50.544  1016  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-29 09:53:50.544  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.544  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:50.544  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 09:53:50.564  7207  7207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:53:50.564  7207  7207 I Babel_Crash: startup - clean
,08-29 09:53:50.584  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.584  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.594  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.594  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.594  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:50.594  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.594  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.604  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:50.604  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.604  7207  7207 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 09:53:50.604  7207  7207 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 09:53:50.604  7207  7207 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 09:53:50.614  7207  7207 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-29 09:53:50.614  7207  7207 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-29 09:53:50.614  1016  1335 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 09:53:50.614  1016  1335 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:53:50.614  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.614  1016  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:50.614  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:53:50.614  7207  7207 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 09:53:50.624  2213  2213 I Hs20UtilService: Starting #9
,08-29 09:53:50.624  2213  2228 I Hs20UtilService: Message received 5007
,08-29 09:53:50.624  7207  7207 W AudioCapabilities: Unsupported mime audio/x-ima
,08-29 09:53:50.624  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 09:53:50.624  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 09:53:50.624  7207  7207 W AudioCapabilities: Unsupported mime audio/qcelp,
08-29 09:53:50.624  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 09:53:50.624  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:53:50.624  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 09:53:50.624  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 09:53:50.624  7207  7207 W AudioCapabilities: Unsupported mime audio/evrc
08-29 09:53:50.624  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 09:53:50.634  1016  3766 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:53:50.634  1016  3766 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:53:50.634  1016  3766 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:50.634  1016  3766 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.634  1016  3766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:53:50.644  2213  2213 I Hs20UtilService: Starting #10
,08-29 09:53:50.644  2213  2228 I Hs20UtilService: Message received 5011
,08-29 09:53:50.644  7207  7207 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 09:53:50.644  1016  1043 D Tethering: interfaceRemoved wlan0
08-29 09:53:50.644  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 09:53:50.644  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 09:53:50.644  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 09:53:50.644  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 09:53:50.644  7207  7207 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 09:53:50.644  7035  7035 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 09:53:50.654  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.654  1016  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.654  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.654  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.664  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.664  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.664  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.664  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.664  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.664  7207  7207 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-29 09:53:50.664  7207  7207 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 09:53:50.664  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:50.664  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:50.664  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.664  7207  7207 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 09:53:50.674  7207  7207 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-29 09:53:50.674  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.674  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.674  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.674  7207  7207 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-29 09:53:50.674  7207  7207 W VideoCapabilities: Unsupported mime video/mp43
,08-29 09:53:50.674  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.674  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.674  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.674  7207  7207 W VideoCapabilities: Unsupported mime video/sorenson
,08-29 09:53:50.684  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.684  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.684  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.684  7207  7207 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 09:53:50.684  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.684  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.684  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.694  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.694  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.694  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.694  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:50.694  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.694  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.694  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:50.694  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.694  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.694  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:50.694  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:50.694  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 09:53:50.704  7207  7207 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 09:53:50.704  4753  4753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:53:50.704  1016  1496 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 09:53:50.704  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 09:53:50.704  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:50.704  1016  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:50.704  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 09:53:50.714  1663  1663 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:53:50.724  4753  4753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:53:50.724  4753  4753 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 09:53:50.724   295   295 E SMD     : DCD OFF
,08-29 09:53:50.724  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:50.724  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 09:53:50.744  1016  1561 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 09:53:50.744  7207  7207 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 09:53:50.744  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.744  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.744  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.744  1016  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.744  7207  7207 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 09:53:50.744  7207  7207 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 09:53:50.744  1016  1043 D Tethering: interfaceRemoved p2p0
08-29 09:53:50.744  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 09:53:50.754  7207  7207 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 09:53:50.754  7232  7232 E Zygote  : MountEmulatedStorage()
,08-29 09:53:50.754  7232  7232 E Zygote  : v2,
08-29 09:53:50.754  1016  1561 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7232 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 09:53:50.764  7232  7232 I libpersona: KNOX_SDCARD checking this for 1000
08-29 09:53:50.764  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:50.764  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:50.764  1016  1335 I ActivityManager: Killing 6879:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 09:53:50.764  7207  7207 I vclib   : onServiceConnected
,08-29 09:53:50.764  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:50.764  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:50.784  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:50.794  7232  7232 D ActivityThread: Added TimaKeyStore provider,
,08-29 09:53:50.814  7232  7232 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-29 09:53:50.814  7232  7232 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-29 09:53:50.814  7232  7232 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 09:53:50.824  7232  7232 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-29 09:53:50.824  7232  7232 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 09:53:50.824  7232  7232 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 09:53:50.824  7232  7232 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:53:50.824  1016  1496 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-29 09:53:50.824  1016  1496 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-29 09:53:50.824  1016  1496 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,08-29 09:53:50.834  1016  1496 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
08-29 09:53:50.834  7232  7247 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-29 09:53:50.834  1016  1496 I ActivityManager: Killing 3780:com.google.android.gms/u0a11 (adj 15): empty #21
,08-29 09:53:50.844  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 09:53:50.844  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.844  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.844  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.844  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.864  7249  7249 E Zygote  : MountEmulatedStorage(),
08-29 09:53:50.864  7249  7249 I libpersona: KNOX_SDCARD checking this for 10001
08-29 09:53:50.864  7249  7249 E Zygote  : v2
08-29 09:53:50.864  7249  7249 I libpersona: KNOX_SDCARD not a persona,
08-29 09:53:50.864  7249  7249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 09:53:50.864  7249  7249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:50.864  7249  7249 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:50.874  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7249 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:53:50.884  7249  7249 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:50.884  7249  7249 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:50.964  1016  3702 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-29 09:53:50.964  1016  3702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.964  1016  3702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:50.964  1016  3702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.964  1016  3702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:50.984  7267  7267 E Zygote  : MountEmulatedStorage(),
08-29 09:53:50.984  7267  7267 E Zygote  : v2
08-29 09:53:50.984  1016  3702 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7267 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 09:53:50.984  7267  7267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:50.984  7267  7267 I libpersona: KNOX_SDCARD checking this for 1000
08-29 09:53:50.984  7267  7267 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:50.984  1016  3702 I ActivityManager: Killing 6911:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-29 09:53:50.994  7267  7267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:50.994  7267  7267 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:51.014  7267  7267 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:51.014  7267  7267 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:51.044  7267  7267 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 09:53:51.164  7267  7267 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-29 09:53:51.174  7267  7267 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-29 09:53:51.174  7267  7267 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:53:51.184  7267  7267 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 09:53:51.184  7267  7267 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-29 09:53:51.184  7267  7267 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-29 09:53:51.184  1016  1470 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
,08-29 09:53:51.184  1016  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.184  1016  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.184  1016  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.184  1016  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:51.204  7282  7282 E Zygote  : MountEmulatedStorage(),
,08-29 09:53:51.204  1016  1470 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7282 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:53:51.204  1016  1470 I ActivityManager: Killing 6573:com.android.mms/u0a41 (adj 15): empty #21,
,08-29 09:53:51.214  7282  7282 E Zygote  : v2,
08-29 09:53:51.214  7282  7282 I libpersona: KNOX_SDCARD checking this for 10008
08-29 09:53:51.214  7282  7282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:51.214  7282  7282 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:51.214  7282  7282 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:51.214  7282  7282 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 09:53:51.234  7282  7282 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:51.234  7282  7282 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:51.304  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gms, hostingType: broadcast
,08-29 09:53:51.304  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:51.304  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.304  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.304  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:51.314  1016  1028 I ActivityManager: Start proc com.google.android.gms for broadcast com.google.android.gms/.gcm.gmsproc.GmsAutoStarter: pid=7297 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-29 09:53:51.314  7297  7297 E Zygote  : MountEmulatedStorage()
08-29 09:53:51.314  1016  1028 I ActivityManager: Killing 6933:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
08-29 09:53:51.314  7297  7297 E Zygote  : v2
08-29 09:53:51.314  7297  7297 I libpersona: KNOX_SDCARD checking this for 10011
08-29 09:53:51.314  7297  7297 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:51.314  7297  7297 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 09:53:51.324  7297  7297 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:51.324  7297  7297 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 09:53:51.324  1016  1470 D CountryDetector: No listener is left
,08-29 09:53:51.354  7297  7297 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:51.354  7297  7297 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:51.384  7297  7297 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-29 09:53:51.384  7297  7297 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 09:53:51.414  7297  7297 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-29 09:53:51.414  7297  7297 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-29 09:53:51.424  7297  7297 I MultiDex: VM with version 2.1.0 has multidex support
08-29 09:53:51.424  7297  7297 I MultiDex: install
08-29 09:53:51.424  7297  7297 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 09:53:51.474  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 09:53:51.524  7297  7297 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 09:53:51.574  7297  7297 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 09:53:51.574  7297  7297 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3cce1c30: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-29 09:53:51.574  7297  7297 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 09:53:51.584  1016  1335 I ActivityManager: Killing 6356:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 09:53:51.594  1016  1562 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-29 09:53:51.594  1016  1562 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 09:53:51.594  1016  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:51.594  1016  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:51.594  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 09:53:51.604  1016  1095 V AlarmManager: waitForAlarm result :4
,08-29 09:53:51.644  7297  7315 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-29 09:53:51.694  7297  7319 I iu.SyncManager: SYNC; picasa accounts
,08-29 09:53:51.704  7297  7297 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-29 09:53:51.724  1016  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 09:53:51.724  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-29 09:53:51.724  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:51.734  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:51.734  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:51.754  7297  7297 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:53:51.784  7297  7297 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-29 09:53:51.794  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 09:53:51 GMT+02:00 2016
,08-29 09:53:51.794  1016  1489 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-29 09:53:51.794  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 09:53:51.794  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:51.794  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:51.794  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 09:53:51.804  2814  2814 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 09:53:51.804  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 09:53:51.804  2814  2814 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 09:53:51.814  1016  1474 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 09:53:51.814  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:51.814  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.814  2814  2814 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-29 09:53:51.814  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:51.814  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:51.814  2814  7323 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 09:53:51.824  7324  7324 E Zygote  : MountEmulatedStorage(),
08-29 09:53:51.824  7324  7324 I libpersona: KNOX_SDCARD checking this for 10031
08-29 09:53:51.824  7324  7324 E Zygote  : v2
08-29 09:53:51.824  7324  7324 I libpersona: KNOX_SDCARD not a persona,
08-29 09:53:51.834  1016  1474 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7324 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-29 09:53:51.834  2814  7323 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION,
,08-29 09:53:51.834  7324  7324 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:51.834  7324  7324 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 09:53:51.834  7324  7324 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 09:53:51.844  2814  7323 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-29 09:53:51.844  2814  7323 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 09:53:51.844  2814  2814 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 09:53:51.854  7324  7324 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 09:53:51.854  7324  7324 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:51.894  7324  7324 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-29 09:53:51.894  1016  3702 I ActivityManager: Killing 6949:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-29 09:53:51.914  1016  1343 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 09:53:51.914  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.914  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.914  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:51.914  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:51.914  2750  7339 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-29 09:53:51.914  2750  7339 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-29 09:53:51.914  2750  7339 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-29 09:53:51.924  2750  7339 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-29 09:53:51.924  2750  7339 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 09:53:51.924  7340  7340 E Zygote  : MountEmulatedStorage(),
08-29 09:53:51.924  7340  7340 E Zygote  : v2
08-29 09:53:51.924  7340  7340 I libpersona: KNOX_SDCARD checking this for 10032
08-29 09:53:51.924  7340  7340 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:51.924  7340  7340 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:51.934  1016  1343 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7340 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-29 09:53:51.934  7340  7340 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:51.934  7340  7340 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 09:53:51.954  7340  7340 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:51.954  7340  7340 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:52.004  7340  7355 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-29 09:53:52.004  7340  7355 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 09:53:52.014  7340  7340 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-29 09:53:52.014  1016  1489 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 09:53:52.014  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:52.014  7340  7355 D SPPClientService: PushLog.txt file is not deleted.
08-29 09:53:52.014  7340  7355 D SPPClientService: PushLog.txt file is not deleted.
08-29 09:53:52.014  7340  7355 D SPPClientService: ============PushLog. stop!
,08-29 09:53:52.014  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:52.014  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:52.014  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:52.024  7357  7357 E Zygote  : MountEmulatedStorage(),
08-29 09:53:52.024  7357  7357 E Zygote  : v2
08-29 09:53:52.024  7357  7357 I libpersona: KNOX_SDCARD checking this for 10036
08-29 09:53:52.024  7357  7357 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:52.024  7357  7357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:52.034  1016  1489 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7357 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-29 09:53:52.034  1016  1489 I ActivityManager: Killing 6967:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-29 09:53:52.034  1016  1474 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-29 09:53:52.034  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-29 09:53:52.034  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:52.034  1016  1474 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 09:53:52.034  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-29 09:53:52.034  7357  7357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:52.034  7357  7357 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-29 09:53:52.054  7357  7357 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:52.054  7357  7357 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:52.064  7340  7365 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-29 09:53:52.084  7357  7357 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@62dd63c
,08-29 09:53:52.094  7357  7357 I SA      : [SSP] onCreated
,08-29 09:53:52.104  7357  7357 I SA      : [TPM] There is no property file
,08-29 09:53:52.104  7357  7357 I SA      : [SCU] isHaveSA() - false
,08-29 09:53:52.114  7357  7357 I SA      : [TPM] getModelProperty : null
,08-29 09:53:52.114  7357  7357 I SA      : [TPM] getCSCProperty : null
,08-29 09:53:52.114  7357  7357 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-29 09:53:52.114  7357  7357 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 09:53:52.114  7357  7357 I SA      : [DM] TFT FEATURE: false
,08-29 09:53:52.114  7357  7357 I SA      : [DM] init START
,08-29 09:53:52.114  7357  7357 I SA      : [DM] This device is not a Vodafone
,08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-29 09:53:52.124  7357  7357 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-29 09:53:52.124  7357  7357 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75),
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75),
08-29 09:53:52.134  7357  7357 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-29 09:53:52.134  7357  7357 I SA      : [SCU] isHaveSA() - false
08-29 09:53:52.134  7357  7357 I SA      : support phone number id : false
08-29 09:53:52.134  7357  7357 I SA      : [DM] Supports Ref Jpn : true
,08-29 09:53:52.134  7357  7357 I SA      : [DM] init END
,08-29 09:53:52.134  7357  7357 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 09:53:52.144  7357  7357 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-29 09:53:52.144  7357  7357 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 09:53:52.144  7357  7357 I SA      : [SLFUCHKMGR] constructor called
,08-29 09:53:52.154  7357  7357 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-29 09:53:52.154  7357  7357 I SA      : [OR] == isSIMCardReady false ==
,08-29 09:53:52.154  7357  7357 I SA      : [SCU] == networkStateCheck == false
08-29 09:53:52.154  7357  7357 I SA      : [OR] onReceive END
,08-29 09:53:52.154  1016  1561 I ActivityManager: Killing 7053:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-29 09:53:52.164  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:53:52.164  1766  1766 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 09:53:52.174  2668  2683 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,08-29 09:53:52.174  1766  1766 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 09:53:52.174  1766  1766 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-29 09:53:52.174  1766  1766 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 09:53:52.174  1766  1766 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 09:53:52.174  1766  1766 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 09:53:52.174  1766  1766 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 09:53:52.184  1016  1496 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-29 09:53:52.184  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:52.184  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:52.184  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:52.184  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:52.194  7379  7379 E Zygote  : MountEmulatedStorage(),
08-29 09:53:52.194  7379  7379 E Zygote  : v2
,08-29 09:53:52.194  7379  7379 I libpersona: KNOX_SDCARD checking this for 10077
08-29 09:53:52.194  7379  7379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:52.194  7379  7379 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:52.194  7379  7379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 09:53:52.194  1016  1496 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7379 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 09:53:52.194  7379  7379 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,08-29 09:53:52.214  7379  7379 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:52.214  7379  7379 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:52.284   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:53:52.294  1016  1328 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 09:53:52.294  1016  1328 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 09:53:52.294  1016  1328 D SecContentProvider2: mCursor = null
,08-29 09:53:52.294  1016  1328 D WifiService: setWifiEnabled: true pid=6799, uid=10170
,08-29 09:53:52.294  1016  1328 W ActivityManager: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 09:53:52.304  1016  1328 W WifiService: Failed getting userId using ActivityManagerNative
08-29 09:53:52.304  1016  1328 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 09:53:52.304  1016  1328 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 09:53:52.304  1016  1328 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 09:53:52.304  1016  1328 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 09:53:52.304  1016  1328 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 09:53:52.304  1016  1328 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 09:53:52.304  1016  1328 D SettingsProvider: name = wifi_on
,08-29 09:53:52.334  1016  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 09:53:52.444  1016  3702 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-29 09:53:52.444  1016  3702 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 09:53:52.444  1016  3702 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:52.444  1016  3702 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:52.444  1016  3702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 09:53:52.454  1016  1496 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-29 09:53:52.454  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:52.454  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:52.454  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:52.454  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:52.464  7398  7398 E Zygote  : MountEmulatedStorage(),
08-29 09:53:52.464  7398  7398 E Zygote  : v2
08-29 09:53:52.464  7398  7398 I libpersona: KNOX_SDCARD checking this for 10110
,08-29 09:53:52.464  7398  7398 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:52.464  7398  7398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 09:53:52.474  1016  1496 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7398 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:53:52.474  1016  1474 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
08-29 09:53:52.474  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 09:53:52.474  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:52.474  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:52.474  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 09:53:52.474  7398  7398 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:52.474  7207  7397 I Babel   : connection state changed from UNKNOWN to DISCONNECTED,
08-29 09:53:52.474  7398  7398 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 09:53:52.484  1016  1328 I ActivityManager: Killing 7020:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-29 09:53:52.494   321   321 I art     : Explicit concurrent mark sweep GC freed 8711(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 708us total 27.657ms
,08-29 09:53:52.504  7398  7398 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:53:52.504  7398  7398 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:52.514   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 17.766ms
,08-29 09:53:52.534   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 683us total 17.495ms
,08-29 09:53:52.644  1016  1489 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 09:53:52.754  1016  1043 D Tethering: interfaceAdded wlan0,
08-29 09:53:52.754  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:52.754  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:52.754  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:52.764  1016  1043 D Tethering: interfaceAdded p2p0
,08-29 09:53:52.764   282  1002 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-29 09:53:52.764   282  1002 D SoftapController: Softap fwReload - Ok
,08-29 09:53:52.764   282  1002 D CommandListener: Setting iface cfg,
08-29 09:53:52.764   282  1002 D CommandListener: Trying to bring down wlan0
,08-29 09:53:52.774   282  1002 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:53:52.774   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 09:53:52.774   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 09:53:52.774  7398  7422 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
08-29 09:53:52.774  1016  1128 E WifiHW  : supplicant_name : p2p_supplicant
08-29 09:53:52.774  1016  1131 E Tethering: No numeric data
08-29 09:53:52.774  1016  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 09:53:52.774  1016  1131 D Tethering: clearTetheredNotification()
08-29 09:53:52.774  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-29 09:53:52.774  1016  1131 D Tethering: InitialState.processMessage what=4
08-29 09:53:52.774  1016  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 09:53:52.774  1016  1128 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-29 09:53:52.774  1016  1131 E Tethering: No numeric data
,08-29 09:53:52.774  1016  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 09:53:52.774  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 09:53:52.774  1016  1131 D Tethering: clearTetheredNotification()
08-29 09:53:52.774  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 09:53:52.774  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 09:53:52.784  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:52.784  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-29 09:53:52.784  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:53:52.784  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:53:52.784  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 09:53:52.784  1175  1175 D HotspotTile: updateTetherState():false, false,
,08-29 09:53:52.784  1016  1125 V NetworkStats: performPollLocked() took 5ms
08-29 09:53:52.784   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 09:53:52.784   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 09:53:52.784  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:53:52.784  7398  7422 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 09:53:52.794  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:53:52.794  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:52.794  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:52.794  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 09:53:52.794  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 09:53:52.794  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:52.794  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:52.794  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:52.794  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:52.794  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:52.794  4753  4753 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:52.794  1175  1175 D HotspotTile: onReceive : 2, 0
08-29 09:53:52.794  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-29 09:53:52.804  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:53:52.804  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:52.804  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:52.804   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 09:53:52.804   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 09:53:52.804  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:52.804  7398  7425 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 09:53:52.804   256   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/,
08-29 09:53:52.804  7398  7425 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 09:53:52.804   256   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 09:53:52.824  7398  7398 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 09:53:52.824  7398  7398 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 09:53:52.824  7398  7398 I GAv4    :   adb logcat -s GAv4
,08-29 09:53:52.844  7398  7398 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 09:53:52.844  1016  1474 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 09:53:52.864  7398  7398 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,08-29 09:53:52.864  7398  7427 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 09:53:52.884  7424  7424 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-29 09:53:52.884  7424  7424 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 09:53:52.884  7424  7424 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 09:53:52.944  7424  7424 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-29 09:53:52.944   393   393 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7424
,08-29 09:53:52.944   393   393 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-29 09:53:52.944  7424  7424 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 09:53:52.944  7424  7424 I wpa_supplicant: ssSupport state is = 1
08-29 09:53:52.944  7424  7424 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 09:53:52.944  7424  7424 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-29 09:53:52.944   393   393 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7424
08-29 09:53:52.944   393   393 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-29 09:53:53.104  1016  1561 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 09:53:53.104  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:53.104  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:53.104  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-29 09:53:53.134  7398  7398 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-29 09:53:53.144   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-29 09:53:53.144  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-29 09:53:53.154  7398  7398 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5524-5526)
,08-29 09:53:53.154  7398  7398 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 09:53:53.164  7398  7398 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {122fb1e7}
,08-29 09:53:53.164  7398  7398 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 09:53:53.164  7398  7398 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 09:53:53.184  7398  7398 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 09:53:53.184  7398  7398 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 09:53:53.194  7398  7398 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 09:53:53.194  7424  7424 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 09:53:53.194  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 09:53:53.204  7398  7398 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-29 09:53:53.204  7398  7398 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 09:53:53.204  7398  7398 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 09:53:53.204  7398  7398 I Adreno-EGL: Local Branch: 
08-29 09:53:53.204  7398  7398 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 09:53:53.204  7398  7398 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405",
08-29 09:53:53.204  7398  7398 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 09:53:53.214  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 09:53:53.214   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7424
08-29 09:53:53.214   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-29 09:53:53.214  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 09:53:53.214  7424  7424 I wpa_supplicant: ssSupport state is = 1
08-29 09:53:53.214  7424  7424 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,08-29 09:53:53.214  7424  7424 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 09:53:53.214  7424  7424 E wpa_supplicant: SIM READ ERROR
08-29 09:53:53.214  7424  7424 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 09:53:53.214  7424  7424 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 09:53:53.214  7424  7424 E wpa_supplicant: SIM READ ERROR
08-29 09:53:53.214  7424  7424 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 09:53:53.214  7424  7424 I wpa_supplicant: wpa_default_ap_write_once,
08-29 09:53:53.214  7424  7424 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-29 09:53:53.224  7424  7424 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 09:53:53.224  7424  7424 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 09:53:53.224  7424  7424 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 09:53:53.224  7424  7424 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 09:53:53.224  7424  7424 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:53:53.224  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 09:53:53.234  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:53.234  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:53.264  7398  7457 W cr.media: Requires BLUETOOTH permission
,08-29 09:53:53.274  7398  7398 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 09:53:53.284  7398  7398 I NSApplication: Starting up...
,08-29 09:53:53.284  1016  1561 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 09:53:53.294  1016  1562 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 09:53:53.294   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:53:53.294  1016  1489 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-29 09:53:53.294  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:53.294  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:53.294  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:53.294  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:53.304  7462  7462 E Zygote  : MountEmulatedStorage(),
,08-29 09:53:53.314  7462  7462 E Zygote  : v2
08-29 09:53:53.314  7462  7462 I libpersona: KNOX_SDCARD checking this for 10117
08-29 09:53:53.314  7462  7462 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:53.314  7462  7462 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:53.314  1016  1489 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7462 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 09:53:53.314  7462  7462 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:53.314  1016  1489 I ActivityManager: Killing 7071:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-29 09:53:53.314  7462  7462 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 09:53:53.334  7424  7424 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 09:53:53.334  7462  7462 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:53.334  7462  7462 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:53.354  7462  7462 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 09:53:53.614  7424  7424 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 09:53:53.614  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 09:53:53.624  1016  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 09:53:53.624  1016  1496 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 09:53:53.624  1016  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 09:53:53.624  1016  1496 D BatteryService: stay LED for charging
,08-29 09:53:53.624  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
08-29 09:53:53.624  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-29 09:53:53.624   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7424
08-29 09:53:53.624   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 09:53:53.624  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-29 09:53:53.624  7424  7424 I wpa_supplicant: ssSupport state is = 1
,08-29 09:53:53.634  1016  1016 I MotionRecognitionService: Plugged
08-29 09:53:53.634  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 09:53:53.634  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 09:53:53.634  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 09:53:53.644  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 09:53:53.644  7424  7424 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 09:53:53.644  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
08-29 09:53:53.644  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 09:53:53.654  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 09:53:53.654   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7424
08-29 09:53:53.654   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 09:53:53.654  7424  7424 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 09:53:53.654  7424  7424 I wpa_supplicant: ssSupport state is = 1
08-29 09:53:53.654  7424  7424 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 09:53:53.654  7424  7424 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 09:53:53.654  7424  7424 E wpa_supplicant: SIM READ ERROR
08-29 09:53:53.654  7424  7424 I wpa_supplicant: wpa_default_ap_write_once
08-29 09:53:53.654  7424  7424 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-29 09:53:53.654  7424  7424 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-29 09:53:53.664  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 09:53:53.664  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 09:53:53.664  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 09:53:53.664  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 09:53:53.664  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 09:53:53.664  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 09:53:53.674  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
08-29 09:53:53.674  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 09:53:53.674  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 09:53:53.724  7424  7424 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 09:53:53.724  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 09:53:53.724   295   295 E SMD     : DCD OFF,
,08-29 09:53:53.734  1016  1136 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 09:53:53.734  1016  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:53.734  1016  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:53.734  1016  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:53.734  1016  1136 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:53.744  1016  1136 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7486 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 09:53:53.754  7486  7486 E Zygote  : MountEmulatedStorage()
,08-29 09:53:53.754  7486  7486 I libpersona: KNOX_SDCARD checking this for 10121
08-29 09:53:53.754  7486  7486 E Zygote  : v2
08-29 09:53:53.754  7486  7486 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:53.754  7486  7486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 09:53:53.754  1016  1136 I ActivityManager: Killing 6984:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-29 09:53:53.754  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 09:53:53.754  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 09:53:53.754  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 09:53:53.754  7486  7486 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:53.754  7486  7486 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:53.764  7424  7424 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-29 09:53:53.764  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 09:53:53.764  7424  7424 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 09:53:53.784  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-29 09:53:53.784  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-29 09:53:53.784  7424  7424 I wpa_supplicant: HOTSPOT20_ENABLE called
08-29 09:53:53.784  7424  7424 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 09:53:53.784  7424  7424 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 09:53:53.784  7424  7424 E wpa_supplicant: SIM READ ERROR
08-29 09:53:53.784  7424  7424 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 09:53:53.784  7486  7486 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 09:53:53.784  7486  7486 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:53.804  7486  7486 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:53:53.804  7486  7486 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 09:53:53.804  7486  7486 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 09:53:53.814  7486  7486 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:53:53.824  7486  7486 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service,
,08-29 09:53:53.824  7486  7486 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 09:53:53.834  1016  1343 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-29 09:53:53.834  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:53.834  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:53.834  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:53.834  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:53.844  7505  7505 E Zygote  : MountEmulatedStorage()
,08-29 09:53:53.844  7505  7505 I libpersona: KNOX_SDCARD checking this for 10141
08-29 09:53:53.844  7505  7505 E Zygote  : v2
08-29 09:53:53.844  7505  7505 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:53.844  7505  7505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:53.844  7505  7505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:53.854  7505  7505 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:53.854  1016  1343 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7505 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
08-29 09:53:53.854  1016  1343 I ActivityManager: Killing 7000:com.android.calendar/u0a131 (adj 15): empty #21
,08-29 09:53:53.854  7424  7424 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 09:53:53.874  7505  7505 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 09:53:53.874  7424  7424 I wpa_supplicant: Skip scan - bUseNetwork false
08-29 09:53:53.874  7505  7505 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:53.874  1016  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-29 09:53:53.884  4753  4753 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 09:53:53.884  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:53:53.884  1016  1128 E WifiConfigStore: Not a HS20
,08-29 09:53:53.884  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:53.884  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:53:53.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:53.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:53.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:53.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:53.884  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:53.884  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 09:53:53.884  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:53.884  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 09:53:53.884  1175  1175 D HotspotTile: onReceive : 3, 0
,08-29 09:53:53.884  1016  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 09:53:53.884  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:53.884  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:53.884  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:53.884  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:53.884  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:53.884  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:53.884  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:53.884  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:53.884  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:53.894  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 09:53:53.894  7424  7424 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 09:53:53.894  7424  7424 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 09:53:53.894  7424  7424 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 09:53:53.894  7424  7424 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 09:53:53.894  7424  7424 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 09:53:53.894  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 09:53:53.894  7424  7424 I wpa_supplicant: First Scan Start
08-29 09:53:53.894  7424  7424 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-29 09:53:53.894  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:53.894  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:53.894  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:53.894  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:53.894  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:53.894  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:53.894  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:53:53.894  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:53.894  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:53.894  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:53.894  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:53.894  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:53:53.894  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:53.894  1016  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-29 09:53:53.894  1016  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:53:53.894  1016  1128 I WifiNative-HAL: startHal
08-29 09:53:53.894  1016  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f1c288c
08-29 09:53:53.894  1016  1128 I WifiNative-HAL: Could not start hal,
08-29 09:53:53.894  7207  7207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:53:53.904  1016  1128 E WifiNative-wlan0: do suspend true
,08-29 09:53:53.904  1016  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 09:53:53.904  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-29 09:53:53.904  7505  7505 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-29 09:53:53.904  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 09:53:53.904  7505  7505 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:53:53.904   282  1002 D CommandListener: Setting iface cfg
08-29 09:53:53.904  7505  7505 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 09:53:53.904   282  1002 D CommandListener: Trying to bring up p2p0
08-29 09:53:53.904  7505  7505 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-29 09:53:53.904  1016  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:53.904  1016  1152 I WifiNative-HAL: startHal
08-29 09:53:53.904  1016  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e0849bc
,08-29 09:53:53.904  1016  1152 I WifiNative-HAL: Could not start hal
08-29 09:53:53.904  1016  1152 E WifiScanningService: could not start HAL
08-29 09:53:53.904  1016  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 09:53:53.904  1016  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 09:53:53.904  1016  1128 E WifiNative-wlan0: invaild command id : 215
08-29 09:53:53.904  1016  1016 D RttService: SCAN_AVAILABLE : 3
08-29 09:53:53.904  1016  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:53.914  1016  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 09:53:53.914  7424  7424 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 09:53:53.914  1016  1127 D WifiP2pService: P2pEnablingState
08-29 09:53:53.914  1016  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-29 09:53:53.914  1016  1127 D WifiP2pService: P2p socket connection successful
08-29 09:53:53.914  1016  1127 D WifiP2pService: P2pEnabledState
,08-29 09:53:53.914  7424  7424 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 09:53:53.914  1016  1128 E WifiStateMachine: Failed to set frequency band 0
08-29 09:53:53.914  7424  7424 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 09:53:53.914  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:53:53.914  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:53:53.914  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 09:53:53.914  1016  1130 E ConnectivityService: updateNetworkInfo()
08-29 09:53:53.914  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 09:53:53.914  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 09:53:53.914  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:53:53.914  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:53:53.914  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 09:53:53.914  1016  1046 D WifiDisplayController: disconnect
08-29 09:53:53.914  1016  1046 D WifiDisplayController: updateConnection
08-29 09:53:53.914  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 09:53:53.914  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 09:53:53.924  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:53:53.924  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 09:53:53.924  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 09:53:53.924  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 09:53:53.924  1016  1127 D WifiNative-p2p0: p2pGetDeviceAddress
,08-29 09:53:53.924  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 09:53:53.924  1016  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-29 09:53:53.924  1016  1136 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 09:53:53.924  1016  1127 D WifiP2pService: DeviceAddress: 0a:75:42
,08-29 09:53:53.924  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 09:53:53.924  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  secondary type: null
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  wps: 0
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  grpcapab: 0
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  devcapab: 0
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  status: 3
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  wfdInfo: null
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-29 09:53:53.924  1016  1046 D WifiDisplayController:  SConnectInfo : null
,08-29 09:53:53.954  1016  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 09:53:53.954  1016  1127 D WifiP2pService: InactiveState,
08-29 09:53:53.954  1016  1127 D WifiP2pService: InactiveState{ what=143376 },
,08-29 09:53:53.954  1016  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 09:53:53.954  7424  7424 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 09:53:53.954  1016  1127 D WifiP2pService: InactiveState{ what=143376 },
08-29 09:53:53.954  1016  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 09:53:53.964  1016  1489 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 09:53:53.974  1016  1343 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 09:53:54.004  1016  3755 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 09:53:54.014  1016  1561 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 09:53:54.064  1016  1496 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-29 09:53:54.064  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:54.064  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:54.064  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:54.064  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:54.074  1016  3702 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 09:53:54.074  7529  7529 I libpersona: KNOX_SDCARD checking this for 10068
08-29 09:53:54.074  7529  7529 E Zygote  : MountEmulatedStorage()
08-29 09:53:54.074  7529  7529 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:54.074  7529  7529 E Zygote  : v2
08-29 09:53:54.074  7529  7529 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:54.084  1016  1496 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7529 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-29 09:53:54.084  7529  7529 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:54.084  1016  1561 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 09:53:54.084  7529  7529 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 09:53:54.104  1016  1470 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 09:53:54.114  7529  7529 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:54.114  7529  7529 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:54.114  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-29 09:53:54.114  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:54.114  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:54.114  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:54.114  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:54.124  7545  7545 E Zygote  : MountEmulatedStorage(),
08-29 09:53:54.124  7545  7545 E Zygote  : v2
08-29 09:53:54.124  7545  7545 I libpersona: KNOX_SDCARD checking this for 10009
08-29 09:53:54.124  7545  7545 I libpersona: KNOX_SDCARD not a persona
08-29 09:53:54.134  1016  1328 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7545 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-29 09:53:54.134  7545  7545 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:53:54.134  1016  1328 I ActivityManager: Killing 6783:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-29 09:53:54.134  1016  1562 I ActivityManager: Killing 6078:com.android.vending/u0a26 (adj 15): empty #21
,08-29 09:53:54.134  7545  7545 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:53:54.144  7545  7545 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 09:53:54.174  7545  7545 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:54.174  7545  7545 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:54.294   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:53:54.314  1016  1343 I art     : Explicit concurrent mark sweep GC freed 62752(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 22MB/34MB, paused 2.439ms total 152.392ms
,08-29 09:53:54.334  7529  7529 D BadgeProvider: onCreate
,08-29 09:53:54.334  7529  7529 D BadgeProvider: DatabaseHelper
,08-29 09:53:54.344  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-29 09:53:54.344  1016  1470 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-29 09:53:54.344  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.354  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.354  7529  7538 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-29 09:53:54.374  7529  7538 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-29 09:53:54.374  7529  7538 D BadgeProvider: sendNotify, [notify] : null
08-29 09:53:54.374  7529  7538 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-29 09:53:54.374  7529  7538 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-29 09:53:54.374  7529  7538 D BadgeProvider: update, [UpdateCount] : 1
,08-29 09:53:54.374  1490  1490 D Launcher.Model: reloadBadges entered.
,08-29 09:53:54.404  1016  1343 I ActivityManager: Killing 7175:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-29 09:53:54.404  1016  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:53:54.404  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:53:54.404  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.404  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:54.404  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 09:53:54.404  2213  2213 I Hs20UtilService: Starting #11
08-29 09:53:54.404  2213  2228 I Hs20UtilService: Message received 5011
,08-29 09:53:54.414  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 09:53:54.414  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 09:53:54.414  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
08-29 09:53:54.414  7035  7035 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 09:53:54.414  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.414  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.414  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.424  1016  3766 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-29 09:53:54.424  1016  3766 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.424  1016  3766 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.424  1016  3766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.424  1016  3766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.424  1016  1335 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-29 09:53:54.424  1016  1335 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
,08-29 09:53:54.424  1663  5084 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-29 09:53:54.424  1016  1335 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-29 09:53:54.424  1016  1335 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-29 09:53:54.424  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.424  1016  1335 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:54.424  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.444  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.444  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:54.444  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.444  1663  1663 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 09:53:54.454  1016  3702 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.454  1016  3702 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:54.454  1016  3702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.454  1016  1474 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-29 09:53:54.454  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.454  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.454  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.454  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.464  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.464  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:54.464  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.474  1663  1663 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:53:54.474  1663  1663 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:53:54.474  1016  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.474  1016  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.474  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.474  7297  7297 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-29 09:53:54.484  1016  1343 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 09:53:54.484  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.484  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.484  1016  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.484  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.484  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.484  1016  1335 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.484  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.494  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.494  1016  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.494  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.504  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.504  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.504  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.504  1016  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 09:53:54.504  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.514  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.514  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.514  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:54.514  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:54.514  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:54.514  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:54.524  1016  1474 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7565 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-29 09:53:54.524  7565  7565 E Zygote  : MountEmulatedStorage()
08-29 09:53:54.524  7565  7565 I libpersona: KNOX_SDCARD checking this for 10011
08-29 09:53:54.524  7565  7565 E Zygote  : v2
,08-29 09:53:54.524  7565  7565 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:54.524  7565  7565 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:54.524  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.524  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.524  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.524  7565  7565 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 09:53:54.534  7565  7565 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-29 09:53:54.554  1016  3766 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.554  1016  3766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.554  1016  3766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.554  7565  7565 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:53:54.554  7565  7565 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:54.574  7565  7565 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 09:53:54.574  7565  7565 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-29 09:53:54.614  7565  7565 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
08-29 09:53:54.614  7565  7565 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,08-29 09:53:54.614  1463  3334 D TP/SmsProvider: query,matched:0, calling pid = 7297,
08-29 09:53:54.624  1463  3334 D TP/SmsProvider: match 0:Elapsed time : 2.152 ms
08-29 09:53:54.624  7565  7565 I MultiDex: VM with version 2.1.0 has multidex support
08-29 09:53:54.624  7565  7565 I MultiDex: install
08-29 09:53:54.624  7565  7565 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-29 09:53:54.624  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.624  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.624  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.634  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.634  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.634  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.634  1016  1562 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 09:53:54.644  1016  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.644  1016  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.644  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.644  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.644  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.644  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.644  1463  1477 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7297
,08-29 09:53:54.654  1016  1136 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 09:53:54.654  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-29 09:53:54.654  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.654  1016  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.654  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.654  7297  7584 D LocationInitializer: Restart initialization of location
,08-29 09:53:54.664  7565  7565 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-29 09:53:54.664   282   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 09:53:54.664   282   998 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-29 09:53:54.664  1016  1561 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 09:53:54.664  1016  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.664  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.664  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.664  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.664  1016  3755 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 09:53:54.674  1016  3755 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:53:54.674  1016  3755 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.674  1016  3755 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:54.674  1016  3755 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:53:54.674  2213  2213 I Hs20UtilService: Starting #12
,08-29 09:53:54.674  2213  2228 I Hs20UtilService: Message received 5011
,08-29 09:53:54.684  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 09:53:54.684  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 09:53:54.684  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
08-29 09:53:54.684  7035  7035 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 09:53:54.684  1016  1136 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 09:53:54.684  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.684  1016  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.684  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.694  1463  1656 D TP/SmsProvider: query,matched:0, calling pid = 7297
,08-29 09:53:54.704  1016  1470 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 09:53:54.704  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:53:54.704  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.704  1016  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:54.704  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:53:54.704  1463  1656 D TP/SmsProvider: match 0:Elapsed time : 6.493 ms
,08-29 09:53:54.704  2213  2213 I Hs20UtilService: Starting #13
08-29 09:53:54.704  2213  2228 I Hs20UtilService: Message received 5011
,08-29 09:53:54.704  1016  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 09:53:54.704  1016  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 09:53:54.704  1016  1128 E WifiNative-wlan0: invaild command id : 215
,08-29 09:53:54.714  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 09:53:54.714  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 09:53:54.714  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
08-29 09:53:54.714  7035  7035 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 09:53:54.724  1463  3334 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 7297
,08-29 09:53:54.734  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 09:53:54.734  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 09:53:54.734  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 09:53:54.734  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 09:53:54.734  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 09:53:54.734  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 09:53:54.734  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 09:53:54.734  1016  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-29 09:53:54.734  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:54.734  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:53:54.734  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:54.734  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:53:54.744  7565  7565 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-29 09:53:54.744  7565  7565 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e5375d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-29 09:53:54.744  7565  7565 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-29 09:53:54.754  7588  7588 E Zygote  : MountEmulatedStorage()
,08-29 09:53:54.754  7588  7588 I libpersona: KNOX_SDCARD checking this for 10064
08-29 09:53:54.754  7588  7588 E Zygote  : v2
08-29 09:53:54.754  7588  7588 I libpersona: KNOX_SDCARD not a persona
,08-29 09:53:54.764  7588  7588 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:53:54.764  7588  7588 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:53:54.764  1016  1489 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7588 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:53:54.764  7588  7588 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:53:54.794  7565  7565 D WearableService: callingUid 10011, callindPid: 7565
,08-29 09:53:54.804  7565  7599 D NativeLibraryUtils: Install completed successfully. count=0 extracted=0
,08-29 09:53:54.814  7588  7588 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-29 09:53:54.814  7588  7588 D ActivityThread: Added TimaKeyStore provider
,08-29 09:53:54.824  7588  7588 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
,08-29 09:53:54.834  1611  2697 E MDM     : [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-29 09:53:54.844  7588  7588 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 09:53:54.844  7588  7588 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 09:53:54.874  7588  7588 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 09:53:54.874  7192  7192 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 09:53:54.874  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.874  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.874  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-29 09:53:54.884  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.884  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.884  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.884  1016  3755 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-29 09:53:54.884  1016  3755 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.884  1016  3755 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.884  1016  3755 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.884  1016  3755 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.884  1663  2519 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-29 09:53:54.894  1016  1029 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
08-29 09:53:54.894  1016  1029 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
08-29 09:53:54.894  1016  1029 I splitIntent: other index=5, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
08-29 09:53:54.894  1016  1029 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,08-29 09:53:54.894  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.894  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.894  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.894  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.894  1016  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.894  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.894  1663  1663 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-29 09:53:54.904  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.904  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.904  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.904  1016  1335 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms,
08-29 09:53:54.904  1016  1335 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.904  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.904  1016  1335 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:54.904  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.904  1016  3766 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.914  1016  3766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:54.914  1016  3766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.914  1663  1663 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 09:53:54.914  1016  3755 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.914  1016  3755 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.914  1016  3755 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.914  7297  7297 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-29 09:53:54.914  1016  1561 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 09:53:54.924  1016  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.924  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.924  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.924  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.924  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.924  1016  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.924  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.924  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.924  1016  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.924  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.934  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.934  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.934  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.934  1016  3755 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.934  1016  3755 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.934  1016  3755 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.944  1611  5088 E MDM     : [157] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-29 09:53:54.944  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.944  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.944  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.954  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.954  1016  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:54.954  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.954  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.954  1016  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.954  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.964  1016  3766 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 09:53:54.964  1016  3766 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.964  1016  3766 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.964  1016  3766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.964  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.964  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.964  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.974  1016  1561 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 09:53:54.974  1016  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,08-29 09:53:54.974  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:54.974  1016  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:54.974  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:54.974  7297  7608 D LocationInitializer: Restart initialization of location
,08-29 09:53:54.974  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 09:53:54.974  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,08-29 09:53:54.984  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:54.984  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:54.984  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 09:53:55.104  7424  7424 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
08-29 09:53:55.104  7424  7424 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 09:53:55.104  7424  7424 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-29 09:53:55.104  7424  7424 I wpa_supplicant: Trying to associate with  'G700',
08-29 09:53:55.104  7424  7424 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 09:53:55.104  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-29 09:53:55.114  1016  7502 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 09:53:55.134  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 09:53:55.134  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:53:55.224  1016  1095 V AlarmManager: waitForAlarm result :4
,08-29 09:53:55.234  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:55.234  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 09:53:55.234  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-29 09:53:55.244  7424  7424 E wpa_supplicant: Cmd 35605 not handled
08-29 09:53:55.244  7424  7424 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 09:53:55.244  7424  7424 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-29 09:53:55.244  7424  7424 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 09:53:55.244  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 09:53:55.244  7424  7424 I wpa_supplicant: Associated with F4.99.3E
08-29 09:53:55.244  7424  7424 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 09:53:55.244  7424  7424 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 09:53:55.244  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-29 09:53:55.244  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:55.244  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:55.244  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:55.244  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 09:53:55.244  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 09:53:55.244  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:55.254  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 09:53:55.254  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 09:53:55.254  1016  1043 D Tethering: interfaceStatusChanged wlan0, false,
08-29 09:53:55.254  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 09:53:55.254  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 09:53:55.254  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-29 09:53:55.254  7424  7424 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-29 09:53:55.254  7424  7424 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 09:53:55.254  1016  1131 E Tethering: No numeric data,
,08-29 09:53:55.254  7424  7424 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
,08-29 09:53:55.254  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-29 09:53:55.264  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 09:53:55.254  7424  7424 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 09:53:55.264  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
08-29 09:53:55.254  1016  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
,08-29 09:53:55.264  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 09:53:55.254  7424  7424 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 09:53:55.264  1175  1175 D HotspotTile: updateTetherState():false, false
08-29 09:53:55.254  1016  1131 D Tethering: clearTetheredNotification()
,08-29 09:53:55.264  1016  1125 V NetworkStats: performPollLocked() took 5ms
08-29 09:53:55.254  7424  7424 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 09:53:55.264  7424  7424 I wpa_supplicant: Blacklist: Clear (temp) 
,08-29 09:53:55.264  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 09:53:55.264  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 09:53:55.264  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-29 09:53:55.264  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 09:53:55.264  1016  1128 D SecContentProvider2: mCursor = null
08-29 09:53:55.264  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.264  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:53:55.264  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 09:53:55.264  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.274  1016  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-29 09:53:55.274  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.274  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.274  1016  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 09:53:55.274  1016  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-29 09:53:55.274  1016  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 09:53:55.274  1016  1130 E ConnectivityService: updateNetworkInfo()
08-29 09:53:55.274  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 09:53:55.284  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:53:55.284  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:55.284  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-29 09:53:55.284  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:53:55.284  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 09:53:55.284  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.284  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.284  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 09:53:55.284  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.284  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:55.284  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-29 09:53:55.284  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 09:53:55.284  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:53:55.284  2213  2213 I Hs20UtilService: Starting #14
08-29 09:53:55.284  2213  2228 I Hs20UtilService: Message received 5007
,08-29 09:53:55.294  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 09:53:55.294  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 09:53:55.294  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 09:53:55.294  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:53:55.294  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 09:53:55.294   332   332 I ServiceManager: Waiting for service AtCmdFwd...
08-29 09:53:55.294  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 09:53:55.294  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 09:53:55.304  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:53:55.324   282  1002 D CommandListener: Setting iface cfg,
08-29 09:53:55.324  1016  1128 E WifiStateMachine: Start Dhcp Watchdog 2
08-29 09:53:55.324  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:53:55.324  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:53:55.334  1016  1335 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 09:53:55.334  1016  1335 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 09:53:55.334  1016  1335 D SecContentProvider2: mCursor = null
,08-29 09:53:55.334  1016  1335 D SettingsProvider: name = wifi_on,
08-29 09:53:55.334  1016  1335 D WifiService: setWifiEnabled: false pid=6799, uid=10170
,08-29 09:53:55.344  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:53:55.344  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:53:55.354  1016  1128 E WifiNative-wlan0: do suspend false
,08-29 09:53:55.354  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
08-29 09:53:55.354  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 09:53:55.354  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:53:55.354  1016  1128 D SecContentProvider2: mCursor = null
08-29 09:53:55.364  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-29 09:53:55.364  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:55.364  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:53:55.364  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.364  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.364  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.364  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.364  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:53:55.384  1016  1128 E WifiNative-wlan0: do suspend true
,08-29 09:53:55.404  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-29 09:53:55.404  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 09:53:55.414   282  1002 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:53:55.414  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:53:55.414  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:55.414  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:53:55.414  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.414  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.414  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.414  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.414  1016  1130 E ConnectivityService: updateNetworkInfo(),
08-29 09:53:55.414  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 09:53:55.414  1016  1130 E ConnectivityService: updateNetworkInfo()
,08-29 09:53:55.414  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-29 09:53:55.414   282  1002 E Netd    : no such netId 503
08-29 09:53:55.414  1016  1127 D WifiP2pService: InactiveState{ what=131204 }
08-29 09:53:55.414  1016  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 09:53:55.414  1016  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 09:53:55.414  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 09:53:55.414  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-29 09:53:55.414  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.414  1016  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-29 09:53:55.414  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:53:55.414  1016  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 09:53:55.414  1016  1130 V NetworkStats: updateIfacesLocked()
08-29 09:53:55.424  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 09:53:55.414  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-29 09:53:55.424  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1,
08-29 09:53:55.424  1016  1130 V NetworkStats: performPollLocked() took 5ms
08-29 09:53:55.424  1016  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:55.424  1016  1016 D RttService: SCAN_AVAILABLE : 1
08-29 09:53:55.424  1016  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:55.424  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:53:55.434  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:53:55.434  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 09:53:55.434  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 09:53:55.434  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-29 09:53:55.434  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 09:53:55.434  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.434  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 09:53:55.434  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.434  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 09:53:55.434  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.434  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 09:53:55.434  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.434  1016  1127 D WifiP2pService: P2pDisablingState
08-29 09:53:55.434  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.434  1016  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 09:53:55.434  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.434  1016  1127 D WifiP2pService: p2p socket connection lost
08-29 09:53:55.434  1016  1127 D WifiP2pService: P2pDisabledState
08-29 09:53:55.434  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 09:53:55.434  1016  1128 E WifiNative-wlan0: do suspend true
,08-29 09:53:55.434  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 09:53:55.434  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 09:53:55.434  1016  1046 D WifiDisplayController: disconnect
08-29 09:53:55.434  1016  1046 D WifiDisplayController: updateConnection
08-29 09:53:55.434  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 09:53:55.434  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 09:53:55.434  1016  7611 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:53:55.434  1016  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-29 09:53:55.434  1016  7611 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 09:53:55.434  1016  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 09:53:55.434  1016  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 09:53:55.434  1016  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 09:53:55.434  1016  1130 E ConnectivityService: updateNetworkInfo()
08-29 09:53:55.434  1016  1130 E ConnectivityService: updateNetworkInfo(),
08-29 09:53:55.434  1016  1343 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:53:55.434  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 09:53:55.434  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:55.434  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:55.434  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 09:53:55.434  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 09:53:55.444  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
08-29 09:53:55.444  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 09:53:55.444  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 09:53:55.444  2213  2213 I Hs20UtilService: Starting #15
,08-29 09:53:55.444  2213  2228 I Hs20UtilService: Message received 5007
,08-29 09:53:55.444  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 09:53:55.444  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 09:53:55.444  1016  1496 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 09:53:55.444  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 09:53:55.444  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 09:53:55.444  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 09:53:55.444  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:53:55.444  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 09:53:55.444  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 09:53:55.444  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 09:53:55.454  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 09:53:55.454  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 09:53:55.454  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 09:53:55.454  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:53:55.454  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 09:53:55.454  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 09:53:55.454  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 09:53:55.454  7588  7588 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 09:53:55.464  7588  7588 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 09:53:55.464  7588  7588 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 09:53:55.464   282  1002 D CommandListener: Clearing all IP addresses on wlan0,
08-29 09:53:55.464  1016  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-29 09:53:55.464  7192  7192 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 09:53:55.464  1016  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-29 09:53:55.474  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:53:55.474  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:55.474  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 09:53:55.474  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.474  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.474  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.474  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.474  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 09:53:55.474  7424  7424 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 09:53:55.484  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:53:55.484  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:55.484  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 09:53:55.484  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.484  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.484  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.484  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.494  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:53:55.494  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:55.494  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 09:53:55.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.494  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:53:55.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.494  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:53:55.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:53:55.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:55.494  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:55.494  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:55.494  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-29 09:53:55.494  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 09:53:55.494  1175  1175 D HotspotTile: onReceive : 0, 0
,08-29 09:53:55.494  4753  4753 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:55.494  1016  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 09:53:55.494  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:53:55.494  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:55.494  1016  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:55.494  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:53:55.494  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:53:55.494  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:55.494  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:55.494  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:55.494  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:53:55.494  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:55.494  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:55.494  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:55.494  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:55.504  2213  2213 I Hs20UtilService: Starting #16,
08-29 09:53:55.504  2213  2228 I Hs20UtilService: Message received 5007
08-29 09:53:55.504  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:55.504  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:55.504  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:53:55.504  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:55.504  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:55.504  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:55.504  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:53:55.504  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:53:55.504  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:55.504  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:55.504  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:55.504  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 09:53:55.504  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 09:53:55.504  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 09:53:55.504  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:53:55.504  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:55.504  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:53:55.504  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 09:53:55.504  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 09:53:55.514  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 09:53:55.514  1016  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 09:53:55.514  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:53:55.514  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:55.514  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:55.514  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:53:55.524  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 09:53:55.524  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 09:53:55.524  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
08-29 09:53:55.524  7035  7035 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 09:53:55.524  2213  2213 I Hs20UtilService: Starting #17
,08-29 09:53:55.524  2213  2228 I Hs20UtilService: Message received 5011
,08-29 09:53:55.564  7614  7614 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 09:53:55.574  7614  7614 I dhcpcd  : version 5.5.6 starting,
,08-29 09:53:55.574  7614  7614 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 09:53:55.634  7614  7614 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 09:53:55.634  7614  7614 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 09:53:55.634  7614  7614 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-29 09:53:55.634  7614  7614 I dhcpcd  : bssid match,
,08-29 09:53:55.634  7614  7614 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-29 09:53:55.704  7424  7424 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 09:53:55.754  7614  7614 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1,
,08-29 09:53:55.864  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 09:53:55.864  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 09:53:55.864  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 09:53:55.864  7424  7424 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 09:53:55.884  7424  7424 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-29 09:53:55.884  7424  7424 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 09:53:55.884  7424  7424 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-29 09:53:55.894  7424  7424 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-29 09:53:55.894  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:55.894  7424  7424 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 09:53:55.894  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:55.894  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:55.894  1016  1131 D Tethering: InitialState.processMessage what=4
08-29 09:53:55.894  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:55.894  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:55.894  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:55.894  1016  1131 E Tethering: No numeric data
,08-29 09:53:55.894  1016  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 09:53:55.904  1016  1131 D Tethering: clearTetheredNotification()
,08-29 09:53:55.904  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 09:53:55.904  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
08-29 09:53:55.904  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:53:55.904  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-29 09:53:55.904  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 09:53:55.904  1175  1175 D HotspotTile: updateTetherState():false, false
08-29 09:53:55.904  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.904  1016  1125 V NetworkStats: performPollLocked() took 6ms
08-29 09:53:55.914  7614  7614 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-29 09:53:55.914  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:53:55.914  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:53:55.914  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 09:53:55.914  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:53:55.914  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:53:56.124  7424  7424 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 09:53:56.224  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 09:53:56.224  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 09:53:56.224  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:56.224  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-29 09:53:56.224  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 09:53:56.224  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:53:56.234  7424  7424 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 09:53:56.284  5952  5952 D FactoryTest: Not factory mode,
08-29 09:53:56.284  5952  5952 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-29 09:53:56.294  5952  5952 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-29 09:53:56.294  5952  5952 D MTPRx   : still no open session command from host, so toast
,08-29 09:53:56.294   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 09:53:56.294  5952  5952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-29 09:53:56.294  5952  5952 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-29 09:53:56.304  5952  5952 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118671,
08-29 09:53:56.304  1016  3755 E PersonaManagerService: inState():  stateMachine is null !!
08-29 09:53:56.304  1016  3755 I PersonaManagerService: PersonaId don't exist,
08-29 09:53:56.304  1016  3755 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-29 09:53:56.304  1016  3755 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
08-29 09:53:56.304  1016  1095 V AlarmManager: waitForAlarm result :4
,08-29 09:53:56.304  1016  3755 W ActivityManager: userId = 0, bbcId = -10000,
08-29 09:53:56.304  1016  3755 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:56.304  1016  3755 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-29 09:53:56.314  1016  3755 W ActivityManager: mDVFSHelper.acquire()
,08-29 09:53:56.334  1016  3755 D PersonaManager: isKioskContainerExistOnDevice
,08-29 09:53:56.344  1016  3755 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 09:53:56.344  1016  3755 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 09:53:56.344  1016  3755 D InputDispatcher: Focused application set to: xxxx
,08-29 09:53:56.344  1016  3755 D InputDispatcher: Focus left window: 6799
,08-29 09:53:56.344  5952  5952 E MTPRx   : started activity for popup
,08-29 09:53:56.344  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 09:53:56.344  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 09:53:56.354  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-29 09:53:56.354  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 09:53:56.354  7207  7207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:53:56.364  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:53:56.364  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:53:56.364  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 09:53:56.364  1611  2111 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:53:56.364  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:56.364  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:56.364  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:56.364  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:53:56.364  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:53:56.364  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-29 09:53:56.364  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 09:53:56.364  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 09:53:56.364  1175  1175 D HotspotTile: onReceive : 1, 0
,08-29 09:53:56.374  4753  4753 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 09:53:56.374  1016  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:53:56.374  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:53:56.374  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:56.374  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:56.374  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:56.374  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:56.374  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 09:53:56.374  5952  5952 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 09:53:56.374  5952  5952 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 09:53:56.374  5952  5952 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 09:53:56.374  5952  5952 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 09:53:56.374  5952  5952 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 09:53:56.374  5952  5952 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-29 09:53:56.374  2213  2213 I Hs20UtilService: Starting #18
,08-29 09:53:56.374  2213  2228 I Hs20UtilService: Message received 5011
,08-29 09:53:56.384  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 09:53:56.384  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 09:53:56.384  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
08-29 09:53:56.384  7035  7035 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 09:53:56.394  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:56.394  1016  1136 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:56.394  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-29 09:53:56.404  5952  5952 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-29 09:53:56.404  1016  3702 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 09:53:56.404  1016  3702 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 09:53:56.404  1016  3702 D InputDispatcher: Focused application set to: xxxx
,08-29 09:53:56.404  1016  3702 D InputDispatcher: Focus entered window: 6799
,08-29 09:53:56.414  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 09:53:56.414  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 09:53:56.414  1016  1562 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-29 09:53:56.414  1016  1562 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@18119068 attribute=null, token = android.os.BinderProxy@17bf2a7d
,08-29 09:53:56.444  5952  5952 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-29 09:53:56.454  5952  5952 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-29 09:53:56.454  5952  5952 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-29 09:53:56.474  6799  6799 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 09:53:56.474  6799  6799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-29 09:53:56.474  6799  6799 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 09:53:56.474  6799  6799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-29 09:53:56.474  1016  1335 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 09:53:56.474  1016  1335 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 09:53:56.474  1016  1335 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 09:53:56.474  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-29 09:53:56.474  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 09:53:56.494  6799  6799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 09:53:56.494  6799  6799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 09:53:56.494  6799  6799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@38f394ed Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3d057593, 16908290=android.view.AbsSavedState$1@3d057593}, android:focusedViewId=100}]}]
08-29 09:53:56.494  6799  6799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 09:53:56.494  6799  6799 V ActivityThread: updateVisibility : ActivityRecord{8dd2934 token=android.os.BinderProxy@f6fb621 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-29 09:53:56.494  6799  6799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 09:53:56.494  6799  6799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 09:53:56.504  6799  6799 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f6fb621 time:118870
,08-29 09:53:56.504  1016  3755 D PersonaManager: isKioskContainerExistOnDevice
,08-29 09:53:56.724   295   295 E SMD     : DCD OFF
,08-29 09:53:56.894   282   996 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-29 09:53:56.894  1016  1043 D Tethering: interfaceRemoved wlan0
,08-29 09:53:56.894  1016  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 09:53:57.094  1016  1043 D Tethering: interfaceRemoved p2p0
,08-29 09:53:57.094  1016  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 09:53:57.304   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 09:53:57.924  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 09:53:58.354  6799  6965 D BluetoothAdapter: enable()
,08-29 09:53:58.354  1016  1028 W ActivityManager: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 09:53:58.354  1016  1028 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 09:53:58.354  1016  1028 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 09:53:58.354  1016  1028 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 09:53:58.354  1016  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 09:53:58.354  1016  1028 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 09:53:58.354  1016  1028 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 09:53:58.354  1016  1028 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 09:53:58.354  1016  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 09:53:58.354  1016  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 09:53:58.354  1016  1028 D SettingsProvider: name = bluetooth_on
,08-29 09:53:58.354  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 09:53:58.354  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 09:53:58.364  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 09:53:58.364  3210  3283 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 09:53:58.364  3210  3283 D BluetoothAdapterProperties: Setting state to 11
08-29 09:53:58.364  3210  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 09:53:58.364  3210  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 09:53:58.364  3210  3283 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 09:53:58.364  3210  3283 D BluetoothAdapterService: Autoconnection is available 
08-29 09:53:58.364  3210  3283 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-29 09:53:58.364  3210  3283 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 09:53:58.364  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 09:53:58.364  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,08-29 09:53:58.364  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 09:53:58.364  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-29 09:53:58.364  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 09:53:58.364  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-29 09:53:58.364  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 09:53:58.364  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
,08-29 09:53:58.364  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 09:53:58.374  1016  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:53:58.374  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.374  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.374  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.374  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 09:53:58.374  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 09:53:58.374  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 09:53:58.374  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:58.374  3210  3210 D HeadsetService: Received start request. Starting profile...
08-29 09:53:58.374  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
08-29 09:53:58.374  3210  3210 D HeadsetService: start()
08-29 09:53:58.374  3210  3210 D HeadsetStateMachine: make
,08-29 09:53:58.384  3210  3210 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 09:53:58.394  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 09:53:58.394  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-29 09:53:58.394  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-29 09:53:58.404  1887  1887 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 09:53:58.404  4753  4753 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:53:58.404  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:53:58.404  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 09:53:58.404  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:58.404  1016  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:53:58.404  1016  1328 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 09:53:58.414  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:58.414  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 09:53:58.414  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:58.414  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.414  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.414  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.414  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.414  1016  1335 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-29 09:53:58.414  1016  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.414  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-29 09:53:58.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 09:53:58.414  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.414  1016  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.414  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-29 09:53:58.414  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 09:53:58.414  1016  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:53:58.414  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.414  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.424  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.424  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.424  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-29 09:53:58.424  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 09:53:58.424  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 09:53:58.424  1663  1663 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:53:58.424  1016  1343 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-29 09:53:58.424  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.424  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.424  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.434  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 09:53:58.434  1016  3702 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:53:58.434  1016  3702 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.434  1016  3702 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.434  1016  3702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.434  1016  3702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.434  3210  3210 I bluedroid: get_profile_interface handsfree
,08-29 09:53:58.434  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-29 09:53:58.434  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 09:53:58.434  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 09:53:58.434  4753  4753 D BluetoothNotiBroadcastReceiver: onReceive
08-29 09:53:58.434  1016  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:58.434  1016  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.434  1016  1562 W ActivityManager: userId = 0, bbcId = -10000,
08-29 09:53:58.444  1016  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:58.444  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.444  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 09:53:58.444  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:53:58.444  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 09:53:58.444  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:53:58.444  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 09:53:58.444  1016  3755 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:53:58.454  1016  3755 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.454  1016  3755 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.454  1016  3755 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:58.454  1016  3755 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.454  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 09:53:58.454  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 09:53:58.454  3210  3283 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-29 09:53:58.454  3210  3210 E DualScoManager: Dual Sco Manager already instantiated
08-29 09:53:58.454  3210  3210 I DualScoManager: Set HeadsetServiceHelper
08-29 09:53:58.454  3210  3210 D BluetoothAtMessage: createCMTIContentObservers
,08-29 09:53:58.454  1016  1561 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-29 09:53:58.454  1016  1561 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 09:53:58.454  1016  1561 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 09:53:58.454  1016  1561 D SettingsProvider: selectionArgs: false
08-29 09:53:58.454  1016  1561 D SettingsProvider: selectionArgs: 1002
08-29 09:53:58.454  1016  1561 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 09:53:58.454  1016  1561 D SettingsProvider: ret = -1
,08-29 09:53:58.454  3210  7646 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 09:53:58.454  1016  1335 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:58.454  1016  1335 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.454  1016  1335 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.454  1016  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.454  1016  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.464  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:53:58.464  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:53:58.464  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:53:58.464  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:53:58.464  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:53:58.464  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:53:58.464  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 09:53:58.464  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 09:53:58.464  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 09:53:58.464  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 09:53:58.464  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 09:53:58.464  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 09:53:58.464  3210  3283 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 09:53:58.464  3210  3210 D HeadsetService: mStartError = false
08-29 09:53:58.464  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
08-29 09:53:58.464  3210  3210 D HeadsetStateMachine: Try to query the phonestate on bind
08-29 09:53:58.464  1437  1447 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 09:53:58.464  1437  1437 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 09:53:58.464  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 09:53:58.464  1437  1447 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 09:53:58.464  3210  3210 D A2dpService: Received start request. Starting profile...
08-29 09:53:58.464  3210  3210 D A2dpService: start()
08-29 09:53:58.464  3210  3210 I bluedroid: get_profile_interface avrcp
,08-29 09:53:58.464  3210  7646 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-29 09:53:58.464  3210  7646 D HeadsetStateMachine: map size, before remove : 0
08-29 09:53:58.464  3210  7646 D HeadsetStateMachine: map size, after remove: 0
,08-29 09:53:58.474  3210  3210 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 09:53:58.474  3210  3210 D Avrcp   : Initialize Media Controller
08-29 09:53:58.474  3210  3210 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 09:53:58.474  3210  3210 E Avrcp   : getActiveSessions
,08-29 09:53:58.474  3210  3210 D Avrcp   : pick active media Controller
08-29 09:53:58.474  3210  3210 D Avrcp   : Get the active Media Controller 
,08-29 09:53:58.484  3210  3210 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 09:53:58.484  3210  3210 D A2dpStateMachine: make
,08-29 09:53:58.484  3210  7647 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 09:53:58.484  3210  3210 I bluedroid: get_profile_interface a2dp
,08-29 09:53:58.484  3210  7649 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 09:53:58.484  3210  3210 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 09:53:58.484  3210  3210 D A2dpService: mStartError = false
08-29 09:53:58.484  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
08-29 09:53:58.484  3210  3210 D HidService: Received start request. Starting profile...
08-29 09:53:58.484  3210  3210 D HidService: start()
08-29 09:53:58.484  3210  3210 I bluedroid: get_profile_interface hidhost
08-29 09:53:58.484  3210  3210 D HidService: setHidService(): set to: null
08-29 09:53:58.484  3210  3210 D HidService: mStartError = false
08-29 09:53:58.484  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:58.484  3210  3210 D HeadsetStateMachine: Proxy object connected
08-29 09:53:58.484  3210  3210 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-29 09:53:58.484  3210  7646 D HeadsetStateMachine: Disconnected process message: 11
08-29 09:53:58.484  3210  3210 D HealthService: Received start request. Starting profile...
08-29 09:53:58.484  3210  3210 D HealthService: start()
,08-29 09:53:58.494  3210  7648 D A2dpStateMachine: Enter Disconnected: -2
,08-29 09:53:58.494  3210  3210 I bluedroid: get_profile_interface health,
08-29 09:53:58.494  3210  3210 D HealthService: mStartError = false
08-29 09:53:58.494  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
08-29 09:53:58.494  3210  3210 D PanService: Received start request. Starting profile...
08-29 09:53:58.494  3210  3210 D PanService: start()
08-29 09:53:58.494  3210  3210 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 09:53:58.494  3210  3210 I bluedroid: get_profile_interface pan
08-29 09:53:58.494  3210  3210 D PanService: mStartError = false
08-29 09:53:58.494  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
08-29 09:53:58.494  3210  3210 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 09:53:58.494  3210  3210 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-29 09:53:58.494  3210  7646 D HeadsetStateMachine: Disconnected process message: 18
,08-29 09:53:58.494  3210  3210 D BluetoothMapService: Received start request. Starting profile...
08-29 09:53:58.494  3210  3210 D BluetoothMapService: start()
,08-29 09:53:58.494  3210  3210 D BluetoothMapService: mStartError = false
08-29 09:53:58.494  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:58.494  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-29 09:53:58.494  3210  3210 D SapService: Received start request. Starting profile...
08-29 09:53:58.494  3210  3210 D SapService: start()
08-29 09:53:58.494  3210  3210 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 09:53:58.494  3210  3210 I bluedroid: get_profile_interface sap
08-29 09:53:58.494  3210  3210 D SapService: mStartError = false
08-29 09:53:58.494  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
08-29 09:53:58.494  3210  3210 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 09:53:58.494  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 09:53:58.494  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-29 09:53:58.494  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 09:53:58.494  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 09:53:58.504  3210  7646 D HeadsetStateMachine: Disconnected process message: 10
,08-29 09:53:58.504  3210  7646 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 09:53:58.504  3210  7646 D HeadsetStateMachine: Disconnected process message: 11
,08-29 09:53:58.504  3210  7647 D BluetoothMediaBrowser: no now playing list
,08-29 09:53:58.504  3210  7647 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 09:53:58.514  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-29 09:53:58.514  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 09:53:58.514  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 09:53:58.514  3210  3283 I bluedroid: enable
,08-29 09:53:58.524  3210  3286 E bt-btif : Calling BTA_HhEnable
,08-29 09:53:58.524  3210  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-29 09:53:58.524  3210  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 09:53:58.524  3210  3286 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 09:53:58.524  3210  3286 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-29 09:53:58.534  3210  3286 E BluetoothServiceJni: populateRssiValuesNative
08-29 09:53:58.534  3210  3286 I bluedroid: getModelRssiValues
08-29 09:53:58.534  3210  3286 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 09:53:58.534  3210  3286 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 09:53:58.534  3210  3286 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-29 09:53:58.534  1016  1016 D SettingsProvider: name = bluetooth_name
,08-29 09:53:58.534  1016  1095 V AlarmManager: waitForAlarm result :4
,08-29 09:53:58.534  3210  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 09:53:58.534  3210  3286 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:53:58.534  3210  3286 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:53:58.534  3210  3286 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-29 09:53:58.534  3210  3286 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-29 09:53:58.534  3210  3286 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-29 09:53:58.534  3210  3286 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 09:53:58.534  3210  3286 E bt-btif : JVenable fails
,08-29 09:53:58.534  3210  3286 D bte_conf: Device ID record 1 : primary
,08-29 09:53:58.534  3210  3286 D bte_conf:   vendorId            = 0075
08-29 09:53:58.534  3210  3286 D bte_conf:   vendorIdSource      = 0001
08-29 09:53:58.534  3210  3286 D bte_conf:   product             = 0100
,08-29 09:53:58.534  3210  3286 D bte_conf:   version             = 0200
08-29 09:53:58.534  3210  3286 D bte_conf:   clientExecutableURL = 
08-29 09:53:58.534  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:53:58.534  3210  3286 D bte_conf:   serviceDescription  = 
,08-29 09:53:58.534  3210  3286 D bte_conf:   documentationURL    = 
08-29 09:53:58.534  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:58.544  3210  3286 D bte_conf: bte_load_did_conf no section named DID2.
08-29 09:53:58.544  3210  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 09:53:58.544  3210  3286 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 09:53:58.544  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 09:53:58.544  3210  3283 D BluetoothAdapterProperties: ScanMode =  20
,08-29 09:53:58.544  3210  3283 D BluetoothAdapterProperties: State =  11
,08-29 09:53:58.544  1016  1029 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 09:53:58.544   282   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 09:53:58.544   282   998 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-29 09:53:58.554  3210  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 09:53:58.554  3210  3286 D BluetoothAdapterProperties: Scan Mode:21
08-29 09:53:58.554  3210  3286 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 09:53:58.554  3210  3283 D BluetoothAdapterProperties: Setting state to 12
08-29 09:53:58.554  3210  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 09:53:58.554  1016  1489 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 09:53:58.554  1016  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 09:53:58.554  1016  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 09:53:58.554  1016  1489 D SettingsProvider: selectionArgs: false
08-29 09:53:58.554  1016  1489 D SettingsProvider: selectionArgs: 1002
08-29 09:53:58.554  1016  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 09:53:58.554  1016  1489 D SettingsProvider: ret = -1
08-29 09:53:58.554  3210  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 09:53:58.554  3210  3283 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 09:53:58.554  1016  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:58.554  1016  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.554  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.554  1016  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.554  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.554  3210  3283 D BluetoothAdapterService: Autoconnection is available 
08-29 09:53:58.554  3210  3283 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 09:53:58.554  3210  3283 D BluetoothAdapterService: starting service from this receiver
,08-29 09:53:58.554  1016  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:53:58.554  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-29 09:53:58.554  1437  3336 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:53:58.564  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.564  1016  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.564  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.564  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-29 09:53:58.564  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:58.564  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:58.564  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:53:58.564  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:58.564  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:58.564  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:58.564  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:58.564  3210  3210 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 09:53:58.564  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 09:53:58.564  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:53:58.564  3210  3283 I BluetoothAdapterState: Entering On State from state = 11
,08-29 09:53:58.564  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.564  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.564  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.564  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:58.574  1437  3336 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:53:58.574  4753  4763 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 09:53:58.574  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.574  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:53:58.574  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-29 09:53:58.574  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:53:58.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:53:58.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:53:58.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:53:58.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:53:58.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:53:58.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:53:58.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:53:58.574  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 09:53:58.574  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.574  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.574  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.574  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.584  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:53:58.584  6799  6811 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 09:53:58.584  6799  6811 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:53:58.584  3210  3210 I BluetoothPbapService: Handler(): got msg=1
,08-29 09:53:58.584  4753  4767 D BluetoothPan: Binding service...
,08-29 09:53:58.584  1016  1136 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 09:53:58.594  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 09:53:58.594  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.594  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.594  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.594  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.594  3210  7656 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 09:53:58.594  7128  7137 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:53:58.594  7128  7137 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:53:58.594  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 09:53:58.594  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 09:53:58.594  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 09:53:58.594  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:53:58.594  4753  4753 D BluetoothPbap: Proxy object connected
08-29 09:53:58.594  4753  4753 D PbapServerProfile: Bluetooth service connected
08-29 09:53:58.594  1437  1447 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 09:53:58.594  1437  1447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:53:58.594  4753  4767 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:53:58.594  4753  4753 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:53:58.594  3210  7656 D BluetoothSocket: bindListen(): myUserId = 0
08-29 09:53:58.594  3210  7656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:53:58.594  4753  4753 D PanProfile: Bluetooth service connected
,08-29 09:53:58.604  4753  4767 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 09:53:58.604  3210  7656 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-29 09:53:58.604  3210  7656 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 09:53:58.604  3210  7656 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 09:53:58.604  3210  7656 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2db7290
,08-29 09:53:58.604  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 09:53:58.604  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.604  3210  7656 D BluetoothSocket: channel: 19
08-29 09:53:58.604  3210  7656 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-29 09:53:58.604  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.604  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.604  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.604  4753  4763 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 09:53:58.604  4753  4763 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:53:58.604  4753  4753 D BluetoothA2dp: Proxy object connected
08-29 09:53:58.604  4753  4753 D A2dpProfile: Bluetooth service connected
,08-29 09:53:58.604  1437  3336 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:53:58.604  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 09:53:58.604  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:53:58.604  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.604  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.604  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.604  1437  3336 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:53:58.604  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:53:58.614  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 09:53:58.614  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 09:53:58.614  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-29 09:53:58.614  1016  1016 D BluetoothA2dp: Proxy object connected
,08-29 09:53:58.614  1611  1627 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:53:58.614  1611  1627 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:53:58.614  3210  3221 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:53:58.614  3210  3221 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:53:58.614  1016  1045 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 09:53:58.614  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.614  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.614  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.614  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.614  3210  3210 D BluetoothA2dp: Proxy object connected
08-29 09:53:58.614  3210  3210 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-29 09:53:58.614  1663  1741 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:53:58.614  1663  1741 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:53:58.614  1463  3333 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:53:58.614  1463  3333 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:53:58.614  4753  7127 D Bluetoothsap: onBluetoothStateChange: up=true
08-29 09:53:58.614  4753  7127 D Bluetoothsap: Binding service...
,08-29 09:53:58.624  4753  7127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 09:53:58.624  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-29 09:53:58.624  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.624  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.624  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.624  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.624  4753  7127 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 09:53:58.624  4753  4753 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-29 09:53:58.624  4753  4753 D SapProfile: Bluetooth service connected
08-29 09:53:58.624  4753  4753 D Bluetoothsap: getConnectedDevices()
08-29 09:53:58.624  1463  1482 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:53:58.634  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 09:53:58.634  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:53:58.634  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.634  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.634  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.634  1463  1482 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:53:58.634  1016  1045 D BluetoothPan: Binding service...
,08-29 09:53:58.634  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 09:53:58.634  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.634  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:53:58.634  4753  4763 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 09:53:58.634  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-29 09:53:58.634  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.634  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.634  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.634  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.644  4753  4753 D BluetoothInputDevice: Proxy object connected
,08-29 09:53:58.644  4753  4753 D HidProfile: Bluetooth service connected
,08-29 09:53:58.644  1437  1447 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:53:58.644  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 09:53:58.644  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:53:58.644  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.644  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.644  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.644  1437  1447 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:53:58.644  1450  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 09:53:58.644  1450  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:53:58.644  4753  7127 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:53:58.644  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 09:53:58.644  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:53:58.644  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.644  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.644  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.654  4753  7127 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 09:53:58.654  3210  3326 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:53:58.654  3210  3326 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:53:58.654  4753  4753 D HeadsetProfile: Bluetooth service connected
,08-29 09:53:58.654  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:53:58.654  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:53:58.654  1175  1607 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:53:58.654  1175  1607 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:53:58.654  4753  4763 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 09:53:58.654  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 09:53:58.654  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 09:53:58.654  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:53:58.654  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.654  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.654  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 09:53:58.654  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 09:53:58.654  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:53:58.654  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-29 09:53:58.654  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 09:53:58.664  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-29 09:53:58.664  1437  1437 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@22069c2a, true
,08-29 09:53:58.664  1437  1437 D BluetoothHeadset: registerMessageListener
,08-29 09:53:58.664  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 09:53:58.664  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:58.664  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-29 09:53:58.664  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:53:58.664  1887  1887 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 09:53:58.664  4753  4753 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:53:58.664  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:53:58.674  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:58.674  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:53:58.674  1016  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:53:58.674  1016  1136 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 09:53:58.674  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:53:58.684  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:53:58.684  3210  3221 D HeadsetService: registerMessageListener
,08-29 09:53:58.684  3210  7658 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 09:53:58.684  3210  3221 D HeadsetService: registerMessageListener
,08-29 09:53:58.684  1437  1437 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-29 09:53:58.684  3210  7646 D HeadsetStateMachine: Disconnected process message: 70
08-29 09:53:58.684  3210  7646 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3fb7d789
,08-29 09:53:58.684  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 09:53:58.684  4753  4753 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-29 09:53:58.684  4753  4753 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 09:53:58.684  4753  4753 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 09:53:58.684  4753  4753 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 09:53:58.694  3210  7658 D BluetoothSocket: bindListen(): myUserId = 0
08-29 09:53:58.694  3210  7658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:53:58.694  3210  7658 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-29 09:53:58.694  3210  7658 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 09:53:58.694  3210  7658 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 09:53:58.694  3210  7658 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21e8b38e
08-29 09:53:58.694  3210  7658 D BluetoothSocket: channel: 5
,08-29 09:53:58.694  1437  1437 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 09:53:58.694  1437  1437 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-29 09:53:58.694  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 09:53:58.694  3210  7646 D HeadsetStateMachine: Disconnected process message: 9
,08-29 09:53:58.694  3210  7646 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 09:53:58.704  4753  4753 D BluetoothMap: Proxy object connected
08-29 09:53:58.704  4753  4753 D MapProfile: Bluetooth service connected
08-29 09:53:58.704  4753  4753 D BluetoothMap: getConnectedDevices()
,08-29 09:53:58.704   290   715 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 09:53:58.704   290   715 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 09:53:58.704   290   715 V voice   : voice_set_parameters: exit with code(-2)
08-29 09:53:58.704   290   715 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 09:53:58.704   290   715 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 09:53:58.704   290   715 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 09:53:58.704   290   715 V audio_hw_primary: adev_set_parameters: exit
08-29 09:53:58.704  3210  7646 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 09:53:58.704  4753  4753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:53:58.704  1016  1489 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 09:53:58.704  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.714  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.714  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:53:58.714  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 09:53:58.714  1663  1663 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:53:58.724  4753  4753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:53:58.724  4753  4753 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 09:53:58.734  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:53:58.734  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 09:53:58.734  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:53:58.734  3210  3210 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 09:53:58.734  1016  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:53:58.734  1016  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 09:53:58.744  1016  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:53:58.744  1016  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:53:58.744  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:53:58.744  1016  1328 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 09:53:58.754  3210  7663 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 09:53:58.754  3210  7663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:53:58.764  3210  7663 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-29 09:53:58.764  3210  7663 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 09:53:58.764  3210  7663 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 09:53:58.764  3210  7663 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1407a9a
,08-29 09:53:58.764  3210  7663 D BluetoothSocket: channel: 12
08-29 09:53:58.764  3210  7663 I BtOppRfcommListener: Accept thread started.
,08-29 09:53:59.324  1016  1041 W ActivityManager: mDVFSHelper.release()
,08-29 09:53:59.734   295   295 E SMD     : DCD OFF,
,08-29 09:53:59.954  1016  1335 I ActivityManager: Killing 7232:com.sec.pcw.device/1000 (adj 15): empty #21
,08-29 09:53:59.994  1016  1095 V AlarmManager: waitForAlarm result :8
,08-29 09:54:00.004  1016  1136 I ActivityManager: Killing 7249:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-29 09:54:00.524  1016  3363 D SSRM:n  : SIOP:: AP = 370
,08-29 09:54:01.174  1016  3376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 09:54:01.364  6799  6965 D BluetoothAdapter: disable()
,08-29 09:54:01.364  1016  3702 D SettingsProvider: name = bluetooth_on
,08-29 09:54:01.374  3210  3283 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
,08-29 09:54:01.374  3210  3283 D BluetoothAdapterProperties: Setting state to 13
08-29 09:54:01.374  3210  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 09:54:01.374  3210  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 09:54:01.374  3210  3283 D BluetoothAdapterService: updateAdapterState state is 13
,08-29 09:54:01.374  1016  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:01.374  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.374  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:01.374  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:01.374  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:01.374  3210  3283 D BluetoothAdapterService: Autoconnection is available 
08-29 09:54:01.374  3210  3283 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 09:54:01.374  3210  3283 D BluetoothAdapterService: terminating service from this receiver
,08-29 09:54:01.384  3210  3210 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-29 09:54:01.384  3210  3210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1aeb4fcb, channel: 19, state: LISTENING
,08-29 09:54:01.384  3210  3210 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1aeb4fcb, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2db7290, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a8303a8mSocket: android.net.LocalSocket@d5eec1 impl:android.net.LocalSocketImpl@341ba666 fd:FileDescriptor[80]
08-29 09:54:01.384  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-29 09:54:01.384  3210  3210 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d5eec1 impl:android.net.LocalSocketImpl@341ba666 fd:FileDescriptor[80]
,08-29 09:54:01.384  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:01.384  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:01.384  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:01.384  3210  3283 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 09:54:01.384  3210  3283 D BluetoothAdapterProperties: mDiscovering is false
,08-29 09:54:01.384  1016  1343 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 09:54:01.394  3210  3283 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 09:54:01.394  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:01.394  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,08-29 09:54:01.394  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-29 09:54:01.404  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 09:54:01.404  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:01.404  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-29 09:54:01.404  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:54:01.404  1887  1887 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 09:54:01.404  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:54:01.404  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 09:54:01.414  1016  1136 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:54:01.414  1016  1470 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 09:54:01.414  4753  4753 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:01.414  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 09:54:01.424  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:01.424  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:01.424  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:01.424  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:01.424  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:01.424  6799  6799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:54:01.424  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:01.434  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:01.434  3210  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-29 09:54:01.434  3210  3286 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:54:01.434  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:01.434  4753  4753 D BluetoothPbap: Proxy object disconnected
08-29 09:54:01.434  4753  4753 D PbapServerProfile: Bluetooth service disconnected
,08-29 09:54:01.434  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-29 09:54:01.444  3210  3283 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 09:54:01.444  3210  3283 E bt-btif : BTA got event 0x1a1c
,08-29 09:54:01.444  3210  3283 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 09:54:01.444  3210  3287 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-29 09:54:01.444  3210  7663 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 09:54:01.444  4753  4753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:01.444  3210  3210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@355d1da7, channel: 5, state: LISTENING
,08-29 09:54:01.444  3210  3210 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@355d1da7, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21e8b38e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2dd8b254mSocket: android.net.LocalSocket@c91b5fd impl:android.net.LocalSocketImpl@3e2bc2f2 fd:FileDescriptor[82]
,08-29 09:54:01.444  3210  3210 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@c91b5fd impl:android.net.LocalSocketImpl@3e2bc2f2 fd:FileDescriptor[82]
,08-29 09:54:01.444  1016  1496 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 09:54:01.444  3210  3210 I BtOppRfcommListener: stopping Accept Thread
08-29 09:54:01.444  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.444  3210  3210 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@733ed43, channel: 12, state: LISTENING
08-29 09:54:01.454  3210  3210 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@733ed43, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1407a9a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28389fc0mSocket: android.net.LocalSocket@2f48b4f9 impl:android.net.LocalSocketImpl@3aaf1c3e fd:FileDescriptor[86]
,08-29 09:54:01.454  3210  3210 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f48b4f9 impl:android.net.LocalSocketImpl@3aaf1c3e fd:FileDescriptor[86]
08-29 09:54:01.454  3210  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:54:01.454  3210  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:01.454  3210  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 09:54:01.454  3210  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:54:01.454  3210  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:54:01.454  3210  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 09:54:01.454  3210  7663 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 09:54:01.454  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:01.454  1016  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:01.454  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 09:54:01.454  3210  3210 V BluetoothOppManager: cleanUp...
,08-29 09:54:01.464  1663  1663 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:01.474  4753  4753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:01.474  4753  4753 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 09:54:01.474  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:01.474  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 09:54:01.644  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 09:54:01.644  3210  3283 D BtConfig.SecureMode: isSecureModeOn:false
08-29 09:54:01.644  3210  3283 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 09:54:01.644  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-29 09:54:01.644  3210  3283 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-29 09:54:01.644  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 09:54:01.644  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 09:54:01.644  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:01.644  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 09:54:01.644  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.644  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:01.644  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:01.644  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:01.644  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService,
08-29 09:54:01.644  1016  1343 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:01.644  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
08-29 09:54:01.644  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.644  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-29 09:54:01.644  3210  3210 D HeadsetService: Received stop request...Stopping profile...
08-29 09:54:01.644  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:01.644  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:01.644  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 09:54:01.654  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-29 09:54:01.654  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 09:54:01.654  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 09:54:01.654  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
08-29 09:54:01.654  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 09:54:01.654  4753  4753 D HeadsetProfile: Bluetooth service disconnected
08-29 09:54:01.654  1016  1136 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:01.654  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.654  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:01.654  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:01.654  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:01.654  3210  3210 D A2dpService: Received stop request...Stopping profile...
08-29 09:54:01.654  3210  7648 D A2dpStateMachine: Exit Disconnected: -1
,08-29 09:54:01.654  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-29 09:54:01.654  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 09:54:01.654  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 09:54:01.654  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
08-29 09:54:01.654  1016  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:01.654  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.664  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:01.664  1016  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:01.664  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:01.664  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 09:54:01.664  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 09:54:01.664  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 09:54:01.664  1016  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:01.664  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.664  1016  1016 D BluetoothA2dp: Proxy object disconnected
,08-29 09:54:01.664  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:01.664  1016  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:01.664  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:01.664  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 09:54:01.664  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 09:54:01.664  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 09:54:01.664  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 09:54:01.674  1016  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:01.674  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.674  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:01.674  1016  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:01.674  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:01.674  4753  4753 D BluetoothA2dp: Proxy object disconnected
08-29 09:54:01.674  4753  4753 D A2dpProfile: Bluetooth service disconnected
,08-29 09:54:01.674  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-29 09:54:01.674  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 09:54:01.674  3210  3283 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 09:54:01.674  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:01.674  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.674  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:01.674  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:01.674  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:01.684  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 09:54:01.684  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 09:54:01.684  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 09:54:01.684  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:54:01.684  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:54:01.684  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:54:01.684  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 09:54:01.684  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 09:54:01.684  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 09:54:01.684  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 09:54:01.684  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 09:54:01.684  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 09:54:01.684  3210  3283 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 09:54:01.684  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 09:54:01.684  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 09:54:01.684  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 09:54:01.684  3210  3210 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 09:54:01.684  3210  3210 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 09:54:01.684  3210  3210 D HidService: Received stop request...Stopping profile...
,08-29 09:54:01.684  3210  3210 D HidService: Stopping Bluetooth HidService
,08-29 09:54:01.684  3210  3210 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 09:54:01.684  3210  3210 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-29 09:54:01.684  3210  3210 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 09:54:01.684  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:01.694  4753  4753 D BluetoothInputDevice: Proxy object disconnected
,08-29 09:54:01.694  4753  4753 D HidProfile: Bluetooth service disconnected
08-29 09:54:01.694  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-29 09:54:01.694  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 09:54:01.694  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService,
,08-29 09:54:01.694  3210  3210 D BluetoothA2dp: Proxy object disconnected
,08-29 09:54:01.694  3210  3210 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-29 09:54:01.694  3210  3210 D HealthService: Received stop request...Stopping profile...,
08-29 09:54:01.694  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:01.694  3210  7649 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-29 09:54:01.694  3210  3210 I GKI_LINUX: GKI_exit_task 2 done
08-29 09:54:01.694  3210  3210 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-29 09:54:01.694  3210  3210 D PanService: Received stop request...Stopping profile...
,08-29 09:54:01.704  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:01.704  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 09:54:01.704  3210  3210 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 09:54:01.704  4753  4753 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 09:54:01.704  4753  4753 D PanProfile: Bluetooth service disconnected
,08-29 09:54:01.704  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:01.704  3210  3210 D SapService: Received stop request...Stopping profile...
08-29 09:54:01.704  3210  3210 D SapService: Stopping Bluetooth SapService
08-29 09:54:01.704  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:01.704  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 09:54:01.704  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:54:01.704  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:54:01.704  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 09:54:01.714  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 09:54:01.714  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:54:01.714  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:54:01.714  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 09:54:01.714  3210  3210 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:54:01.714  4753  4753 D BluetoothMap: Proxy object disconnected
08-29 09:54:01.714  4753  4753 D MapProfile: Bluetooth service disconnected
08-29 09:54:01.714  3210  3210 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:54:01.714  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 09:54:01.714  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:54:01.714  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:54:01.714  3210  3210 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 09:54:01.714  4753  4753 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 09:54:01.714  4753  4753 D SapProfile: Bluetooth service disconnected
08-29 09:54:01.714  3210  3210 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:54:01.714  3210  3210 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 09:54:01.714  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true,
08-29 09:54:01.714  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:54:01.714  3210  3210 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 09:54:01.714  3210  3210 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-29 09:54:01.714  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-29 09:54:01.714  3210  3210 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 09:54:01.714  3210  3210 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 09:54:01.714  3210  3210 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 09:54:01.714  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-29 09:54:01.714  3210  3283 D BluetoothAdapterProperties: Setting state to 10
08-29 09:54:01.714  3210  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 09:54:01.714  3210  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 09:54:01.714  3210  3283 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 09:54:01.714  3210  3283 D BluetoothAdapterService: Autoconnection is available 
08-29 09:54:01.714  3210  3283 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 09:54:01.714  3210  3283 I BluetoothAdapterState: Entering OffState
,08-29 09:54:01.714  4753  4763 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 09:54:01.714  6799  6811 D BluetoothAdapter: onBluetoothStateChange: up=false,
08-29 09:54:01.714  6799  6811 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 09:54:01.714  6799  6811 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 09:54:01.714  6799  6811 D BluetoothLeAdvertiser: Exit stop advertising
08-29 09:54:01.714  6799  6811 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-29 09:54:01.714  6799  6811 D BluetoothLeScanner: Exiting stopAllScan
,08-29 09:54:01.724  7128  7137 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.724  7128  7137 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.724  1437  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.724  1437  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.724  4753  7127 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:54:01.724  4753  4763 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.724  4753  4763 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.724  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:54:01.724  1611  1857 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.724  1611  1857 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.724  3210  3326 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 09:54:01.734  1663  4427 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.734  1663  4427 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.734  1463  3334 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.734  1463  3334 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.734  4753  4767 D Bluetoothsap: onBluetoothStateChange: up=false
,08-29 09:54:01.734  4753  4767 D Bluetoothsap: Unbinding service...
,08-29 09:54:01.734  4753  7127 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 09:54:01.734  1450  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.734  1450  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.734  3210  3221 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.734  3210  3221 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.744  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.744  1016  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.744  1175  3358 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 09:54:01.744  1175  3358 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 09:54:01.744  4753  4767 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 09:54:01.744  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:01.744  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
,08-29 09:54:01.744  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 09:54:01.754  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 09:54:01.754  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:01.754  1175  1175 D BluetoothTile:  getBluetoothState : 10
,08-29 09:54:01.764  1016  1328 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:54:01.764  1016  1470 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 09:54:01.764  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 09:54:01.764  1887  1887 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 09:54:01.764  4753  4753 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:01.774  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:01.774  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:01.774  4753  4753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:01.774  1016  1470 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 09:54:01.774  1016  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 09:54:01.774  1016  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:01.774  1016  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:01.774  1016  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 09:54:01.784  1663  1663 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:01.784  4753  4753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:01.784  4753  4753 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 09:54:01.794  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:01.794  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 09:54:02.304   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 09:54:02.744   295   295 E SMD     : DCD OFF
,08-29 09:54:02.904  1016  1095 V AlarmManager: waitForAlarm result :4
,08-29 09:54:02.904  1016  1016 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-29 09:54:02.904   282   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-29 09:54:02.904   282   998 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-29 09:54:02.904  1016  1016 V AlarmManagerEXT: <AppSync3 Whitelist>
08-29 09:54:02.904  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-29 09:54:02.904  1016  1016 V AlarmManagerEXT: (AppSync) ### 0 added ###
08-29 09:54:02.904  1175  1175 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 09:54:02.914  1175  1175 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-29 09:54:02.924  1175  1175 D SecKeyguardClockView: HomeTimezone(): 1
,08-29 09:54:02.924  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:02.924  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:54:02.924  1175  1175 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 09:54:02.924  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-29 09:54:02.924  1175  1175 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-29 09:54:02.924  1175  1175 I KeyguardEffectViewController: *** don't update sliding image ***
,08-29 09:54:02.964  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 09:54:02.964  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 09:54:02.964  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 09:54:02.984  1175  1175 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 09:54:03.304   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:54:03.684  1016  1335 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 09:54:03.684  1016  1335 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4300, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 09:54:03.684  1016  1335 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 09:54:03.684  1016  1335 D BatteryService: stay LED for charging
,08-29 09:54:03.684  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 09:54:03.694  1016  1016 I MotionRecognitionService: Plugged
,08-29 09:54:03.694  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 09:54:03.694  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 09:54:03.694  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 09:54:03.694  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 09:54:03.694  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 09:54:03.724  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 09:54:03.724  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 09:54:03.724  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 09:54:04.304   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:54:04.384  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:54:04.384  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:05.304   332   332 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:54:05.744   295   295 E SMD     : DCD OFF,
,08-29 09:54:06.304   332   332 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 09:54:07.304   332   332 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-29 09:54:07.384  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 09:54:07.384  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27d809d0 added. We now have 6 listener(s)
08-29 09:54:07.384  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-29 09:54:07.384  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:07.384  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30d9bdc9 added. We now have 7 listener(s)
,08-29 09:54:07.384  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:07.384  6799  6965 I System.out: IsBluetoothEnabled
08-29 09:54:07.384  6799  6965 D BluetoothAdapter: disable(),
08-29 09:54:07.384  1016  1562 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-29 09:54:07.394  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:07.394  6799  6965 D BluetoothAdapter: enable()
,08-29 09:54:07.394  1016  3755 W ActivityManager: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 09:54:07.394  1016  3755 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 09:54:07.394  1016  3755 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 09:54:07.394  1016  3755 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 09:54:07.394  1016  3755 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 09:54:07.394  1016  3755 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 09:54:07.394  1016  3755 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 09:54:07.394  1016  3755 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 09:54:07.394  1016  3755 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 09:54:07.394  1016  3755 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 09:54:07.394  1016  3755 D SettingsProvider: name = bluetooth_on,
,08-29 09:54:07.404  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 09:54:07.404  1016  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 09:54:07.414  1016  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 09:54:07.414  3210  3283 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
,08-29 09:54:07.414  3210  3283 D BluetoothAdapterProperties: Setting state to 11,
,08-29 09:54:07.414  1016  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:07.414  3210  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 09:54:07.414  1016  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 09:54:07.414  3210  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 09:54:07.414  3210  3283 D BluetoothAdapterService: updateAdapterState state is 11
08-29 09:54:07.414  3210  3283 D BluetoothAdapterService: Autoconnection is available 
08-29 09:54:07.414  3210  3283 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-29 09:54:07.414  3210  3283 D BtConfig.SecureMode: isSecureModeOn:false
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
,08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 09:54:07.414  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 09:54:07.414  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 09:54:07.424  1016  1561 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:07.424  1016  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-29 09:54:07.424  1016  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 09:54:07.424  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 09:54:07.424  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 09:54:07.424  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 09:54:07.424  3210  3210 D HeadsetService: Received start request. Starting profile...
08-29 09:54:07.424  3210  3210 D HeadsetService: start()
08-29 09:54:07.424  3210  3210 D HeadsetStateMachine: make
,08-29 09:54:07.434  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:07.434  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,08-29 09:54:07.434  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 09:54:07.444  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:07.444  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-29 09:54:07.444  1887  1887 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 09:54:07.444  3210  3210 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 09:54:07.454  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
08-29 09:54:07.454  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 09:54:07.454  4753  4753 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:07.454  1016  1335 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:54:07.454  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:07.454  1016  3702 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 09:54:07.464  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 09:54:07.464  1016  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:07.464  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.464  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:07.464  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.464  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.464  1016  1136 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-29 09:54:07.464  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.474  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-29 09:54:07.474  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 09:54:07.474  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 09:54:07.474  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.474  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:07.474  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 09:54:07.474  1016  1328 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-29 09:54:07.474  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.474  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:07.474  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.474  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 09:54:07.474  1016  3755 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:07.474  1016  3755 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.474  1016  3755 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:07.474  1016  3755 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:07.474  1016  3755 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.484  3210  3210 I bluedroid: get_profile_interface handsfree
,08-29 09:54:07.484  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-29 09:54:07.484  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 09:54:07.484  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 09:54:07.484  1663  1663 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:07.484  1016  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:07.494  1016  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.494  1016  1562 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.494  1016  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.494  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.494  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 09:54:07.494  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:07.494  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 09:54:07.494  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-29 09:54:07.494  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 09:54:07.494  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.494  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.494  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.494  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 09:54:07.494  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 09:54:07.494  3210  3283 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 09:54:07.504  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:07.504  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.504  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.504  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.504  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.504  3210  3210 E DualScoManager: Dual Sco Manager already instantiated
,08-29 09:54:07.504  3210  3210 I DualScoManager: Set HeadsetServiceHelper
08-29 09:54:07.504  3210  3210 D BluetoothAtMessage: createCMTIContentObservers
,08-29 09:54:07.504  1016  1335 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-29 09:54:07.504  1016  1335 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 09:54:07.504  1016  1335 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 09:54:07.504  1016  1335 D SettingsProvider: selectionArgs: false
08-29 09:54:07.504  1016  1335 D SettingsProvider: selectionArgs: 1002
,08-29 09:54:07.504  1016  1335 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 09:54:07.514  1016  1335 D SettingsProvider: ret = -1
08-29 09:54:07.514  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-29 09:54:07.514  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 09:54:07.514  3210  3283 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 09:54:07.514  3210  7679 D HeadsetStateMachine: Enter Disconnected: -2
08-29 09:54:07.514  1016  3702 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:07.514  1016  3702 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.514  1016  3702 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:07.514  4753  4753 D BluetoothNotiBroadcastReceiver: onReceive
08-29 09:54:07.514  1016  3702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:07.514  1016  3702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.524  3210  3210 D HeadsetService: mStartError = false
08-29 09:54:07.524  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:07.524  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 09:54:07.524  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:54:07.524  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 09:54:07.524  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:54:07.524  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:54:07.524  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 09:54:07.524  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 09:54:07.524  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 09:54:07.524  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 09:54:07.524  3210  3283 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 09:54:07.524  3210  3283 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 09:54:07.524  3210  3283 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 09:54:07.524  3210  3283 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 09:54:07.524  3210  3210 D A2dpService: Received start request. Starting profile...
08-29 09:54:07.524  3210  3210 D A2dpService: start()
08-29 09:54:07.524  3210  3210 I bluedroid: get_profile_interface avrcp
08-29 09:54:07.524  3210  7679 D HeadsetStateMachine: Clear mHeadsetBrsf
08-29 09:54:07.524  3210  7679 D HeadsetStateMachine: map size, before remove : 0
08-29 09:54:07.524  3210  7679 D HeadsetStateMachine: map size, after remove: 0
,08-29 09:54:07.524  3210  3210 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 09:54:07.524  3210  3210 D Avrcp   : Initialize Media Controller
08-29 09:54:07.524  3210  3210 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 09:54:07.534  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.534  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 09:54:07.534  3210  3210 E Avrcp   : getActiveSessions
08-29 09:54:07.534  3210  3210 D Avrcp   : pick active media Controller
08-29 09:54:07.534  3210  3210 D Avrcp   : Get the active Media Controller 
,08-29 09:54:07.534  3210  3210 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 09:54:07.534  3210  7680 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 09:54:07.544  3210  3210 D A2dpStateMachine: make
,08-29 09:54:07.544  3210  3210 I bluedroid: get_profile_interface a2dp
,08-29 09:54:07.544  3210  7682 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-29 09:54:07.544  3210  3210 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 09:54:07.544  3210  3210 D A2dpService: mStartError = false
08-29 09:54:07.544  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:07.544  3210  3210 D HeadsetStateMachine: Proxy object connected
08-29 09:54:07.544  3210  3210 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 09:54:07.544  1437  1447 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 09:54:07.544  3210  7681 D A2dpStateMachine: Enter Disconnected: -2
,08-29 09:54:07.554  1437  1437 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-29 09:54:07.554  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 09:54:07.554  1437  1447 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 09:54:07.554  3210  3210 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 09:54:07.554  3210  7679 D HeadsetStateMachine: Disconnected process message: 11
,08-29 09:54:07.554  3210  3210 D HidService: Received start request. Starting profile...
,08-29 09:54:07.554  3210  3210 D HidService: start()
08-29 09:54:07.554  3210  3210 I bluedroid: get_profile_interface hidhost
08-29 09:54:07.554  3210  3210 D HidService: setHidService(): set to: null
08-29 09:54:07.554  3210  3210 D HidService: mStartError = false
08-29 09:54:07.554  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:07.554  3210  3210 D HealthService: Received start request. Starting profile...
08-29 09:54:07.554  3210  3210 D HealthService: start()
,08-29 09:54:07.554  3210  3210 I bluedroid: get_profile_interface health
,08-29 09:54:07.554  3210  3210 D HealthService: mStartError = false
08-29 09:54:07.554  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:07.554  3210  3210 D PanService: Received start request. Starting profile...
08-29 09:54:07.554  3210  3210 D PanService: start()
08-29 09:54:07.554  3210  3210 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 09:54:07.554  3210  3210 I bluedroid: get_profile_interface pan
08-29 09:54:07.554  3210  3210 D PanService: mStartError = false
08-29 09:54:07.554  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
08-29 09:54:07.554  3210  3210 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 09:54:07.554  3210  3210 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-29 09:54:07.554  3210  7679 D HeadsetStateMachine: Disconnected process message: 18
,08-29 09:54:07.564  3210  3210 D BluetoothMapService: Received start request. Starting profile...
,08-29 09:54:07.564  3210  3210 D BluetoothMapService: start()
08-29 09:54:07.564  3210  7680 D BluetoothMediaBrowser: no now playing list,
08-29 09:54:07.564  3210  7680 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 09:54:07.564  3210  3210 D BluetoothMapService: mStartError = false
,08-29 09:54:07.564  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:07.564  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-29 09:54:07.564  3210  3210 D SapService: Received start request. Starting profile...
,08-29 09:54:07.564  3210  3210 D SapService: start()
08-29 09:54:07.564  3210  3210 D BluetoothSAPServiceJni: initializeNative(L209): sap
,08-29 09:54:07.564  3210  3210 I bluedroid: get_profile_interface sap
08-29 09:54:07.564  3210  3210 D SapService: mStartError = false
08-29 09:54:07.564  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:07.564  3210  3210 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 09:54:07.564  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-29 09:54:07.564  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-29 09:54:07.564  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 09:54:07.564  3210  7679 D HeadsetStateMachine: Disconnected process message: 10
08-29 09:54:07.564  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-29 09:54:07.564  3210  7679 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 09:54:07.564  3210  7679 D HeadsetStateMachine: Disconnected process message: 11
,08-29 09:54:07.584  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-29 09:54:07.584  3210  3210 E BluetoothAdapterService(678692391): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true,
,08-29 09:54:07.584  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 09:54:07.584  3210  3283 I bluedroid: enable
,08-29 09:54:07.594  3210  3286 E bt-btif : Calling BTA_HhEnable
,08-29 09:54:07.594  3210  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-29 09:54:07.594  3210  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-29 09:54:07.594  3210  3286 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 09:54:07.594  3210  3286 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-29 09:54:07.594  3210  3286 E BluetoothServiceJni: populateRssiValuesNative
,08-29 09:54:07.594  3210  3286 I bluedroid: getModelRssiValues
,08-29 09:54:07.594  3210  3286 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-29 09:54:07.594  3210  3286 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 09:54:07.604  3210  3286 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-29 09:54:07.604  1016  1016 D SettingsProvider: name = bluetooth_name
,08-29 09:54:07.604  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:07.604  3210  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 09:54:07.604  3210  3286 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:54:07.604  3210  3286 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 09:54:07.604  3210  3286 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-29 09:54:07.604  3210  3286 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-29 09:54:07.604  3210  3286 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-29 09:54:07.614  3210  3286 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 09:54:07.614  3210  3286 E bt-btif : JVenable fails
,08-29 09:54:07.614  3210  3286 D bte_conf: Device ID record 1 : primary
,08-29 09:54:07.614  3210  3286 D bte_conf:   vendorId            = 0075
08-29 09:54:07.614  3210  3286 D bte_conf:   vendorIdSource      = 0001
08-29 09:54:07.614  3210  3286 D bte_conf:   product             = 0100
,08-29 09:54:07.614  3210  3286 D bte_conf:   version             = 0200
,08-29 09:54:07.614  3210  3286 D bte_conf:   clientExecutableURL = 
08-29 09:54:07.614  3210  3286 D bte_conf:   serviceDescription  = 
,08-29 09:54:07.614  3210  3286 D bte_conf:   documentationURL    = 
08-29 09:54:07.614  3210  3286 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 09:54:07.614  3210  3286 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 09:54:07.614  3210  3286 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 09:54:07.614  3210  3283 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 09:54:07.614  3210  3283 D BluetoothAdapterProperties: ScanMode =  20
,08-29 09:54:07.614  3210  3283 D BluetoothAdapterProperties: State =  11
,08-29 09:54:07.614  1016  1136 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 09:54:07.614  3210  3283 D BluetoothAdapterProperties: Setting state to 12
,08-29 09:54:07.614  3210  3283 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 09:54:07.624  3210  3286 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 09:54:07.624  3210  3286 D BluetoothAdapterProperties: Scan Mode:21
08-29 09:54:07.624  3210  3286 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 09:54:07.624  1016  1029 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-29 09:54:07.624  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 09:54:07.624  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 09:54:07.624  1016  1029 D SettingsProvider: selectionArgs: false
08-29 09:54:07.624  1016  1029 D SettingsProvider: selectionArgs: 1002
,08-29 09:54:07.624  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 09:54:07.624  1016  1029 D SettingsProvider: ret = -1
,08-29 09:54:07.624  3210  3283 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 09:54:07.624  3210  3283 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 09:54:07.624  1016  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:07.624  1016  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.624  1016  1562 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.624  1016  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.624  1016  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.624  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:07.624  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:07.624  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:07.624  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:07.624  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:07.624  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:07.624  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:07.624  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:07.624  3210  3283 D BluetoothAdapterService: Autoconnection is available 
08-29 09:54:07.624  3210  3283 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 09:54:07.624  3210  3283 D BluetoothAdapterService: starting service from this receiver
,08-29 09:54:07.624  1016  1343 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 09:54:07.624  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.634  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.634  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.634  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.634  3210  3283 I BluetoothAdapterState: Entering On State from state = 11
08-29 09:54:07.634  3210  3210 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 09:54:07.634  1437  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
08-29 09:54:07.634  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 09:54:07.634  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:54:07.634  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.634  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.634  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.644  1437  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:54:07.644  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:07.644  4753  7127 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 09:54:07.644  3210  3210 I BluetoothPbapService: Handler(): got msg=1
,08-29 09:54:07.784  1016  1045 I art     : Explicit concurrent mark sweep GC freed 62970(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.339ms total 140.799ms
08-29 09:54:07.784  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 09:54:07.784  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.784  1016  1561 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 09:54:07.784  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.784  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.784  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.784  6799  6807 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.784  6799  6807 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:54:07.784  4753  4763 D BluetoothPan: Binding service...
,08-29 09:54:07.794  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 09:54:07.794  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.794  3210  7687 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 09:54:07.794  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.794  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.794  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.794  4753  4753 D BluetoothPbap: Proxy object connected
,08-29 09:54:07.794  4753  4753 D PbapServerProfile: Bluetooth service connected
08-29 09:54:07.794  7128  7142 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.794  7128  7142 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:54:07.794  1016  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 09:54:07.794  4753  4753 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:54:07.794  4753  4753 D PanProfile: Bluetooth service connected
08-29 09:54:07.794  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 09:54:07.794  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 09:54:07.794  1016  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:54:07.794  1437  1447 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.794  1437  1447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:54:07.794  4753  7127 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:07.794  4753  7127 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:54:07.794  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 09:54:07.794  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.794  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.794  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.794  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.804  4753  4753 D BluetoothA2dp: Proxy object connected
,08-29 09:54:07.804  4753  4763 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.804  4753  4763 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:54:07.804  4753  4753 D A2dpProfile: Bluetooth service connected
08-29 09:54:07.804  3210  7687 D BluetoothSocket: bindListen(): myUserId = 0
08-29 09:54:07.804  3210  7687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:07.804  1437  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:54:07.804  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 09:54:07.804  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:54:07.804  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.804  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.804  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.804  1437  1457 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 09:54:07.804  1016  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:54:07.804  3210  7687 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-29 09:54:07.804  3210  7687 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 09:54:07.804  3210  7687 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 09:54:07.804  3210  7687 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34035477
08-29 09:54:07.804  3210  7687 D BluetoothSocket: channel: 19
08-29 09:54:07.804  3210  7687 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-29 09:54:07.804  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 09:54:07.804  1016  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 09:54:07.804  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.804  1611  1627 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.804  1611  1627 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:54:07.804  1016  1016 D BluetoothA2dp: Proxy object connected
,08-29 09:54:07.804  3210  7657 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 09:54:07.804  3210  7657 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:54:07.814  1016  1045 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 09:54:07.814  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.814  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.814  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.814  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.814  3210  3210 D BluetoothA2dp: Proxy object connected
08-29 09:54:07.814  3210  3210 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 09:54:07.814  1663  1678 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 09:54:07.814  1663  1678 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:54:07.814  1463  1656 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.814  1463  1656 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:54:07.814  4753  7127 D Bluetoothsap: onBluetoothStateChange: up=true
08-29 09:54:07.814  4753  7127 D Bluetoothsap: Binding service...
,08-29 09:54:07.814  4753  7127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 09:54:07.814  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-29 09:54:07.814  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.814  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.814  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:07.814  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.814  4753  7127 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 09:54:07.814  1463  2141 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:54:07.814  1016  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 09:54:07.814  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:54:07.824  4753  4753 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 09:54:07.824  4753  4753 D SapProfile: Bluetooth service connected
08-29 09:54:07.824  4753  4753 D Bluetoothsap: getConnectedDevices()
08-29 09:54:07.824  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.824  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.824  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.824  1463  2141 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 09:54:07.824  1016  1045 D BluetoothPan: Binding service...
,08-29 09:54:07.824  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 09:54:07.824  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:54:07.824  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-29 09:54:07.824  4753  4763 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 09:54:07.824  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-29 09:54:07.824  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.824  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:07.824  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.824  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.824  4753  4753 D BluetoothInputDevice: Proxy object connected
,08-29 09:54:07.824  4753  4753 D HidProfile: Bluetooth service connected
,08-29 09:54:07.824  1437  1447 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:54:07.834  1016  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 09:54:07.834  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:54:07.834  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.834  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:07.834  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.834  1437  1447 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:54:07.834  1450  1473 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.834  1450  1473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:54:07.834  4753  4767 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 09:54:07.834  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 09:54:07.834  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 09:54:07.834  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.834  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.834  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 09:54:07.834  4753  4767 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 09:54:07.834  4753  4753 D HeadsetProfile: Bluetooth service connected
08-29 09:54:07.834  3210  3327 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.834  3210  3327 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:54:07.834  1016  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.834  1016  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 09:54:07.834  1175  1607 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 09:54:07.834  1175  1607 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 09:54:07.834  4753  4763 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 09:54:07.834  1016  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 09:54:07.834  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.844  1016  1045 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.844  1016  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:07.844  1016  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.844  1016  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 09:54:07.844  1016  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 09:54:07.844  4753  4753 D BluetoothMap: Proxy object connected
08-29 09:54:07.844  4753  4753 D MapProfile: Bluetooth service connected
08-29 09:54:07.844  4753  4753 D BluetoothMap: getConnectedDevices()
,08-29 09:54:07.844  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.844  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
08-29 09:54:07.844  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 09:54:07.844  1437  1437 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@32e17a1b, true
,08-29 09:54:07.844  1437  1437 D BluetoothHeadset: registerMessageListener
,08-29 09:54:07.854  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-29 09:54:07.854  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 09:54:07.854  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:07.854  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-29 09:54:07.854  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:54:07.854  1887  1887 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 09:54:07.854  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:54:07.864  1175  1744 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 09:54:07.864  3210  3326 D HeadsetService: registerMessageListener
,08-29 09:54:07.864  3210  3326 D HeadsetService: registerMessageListener
,08-29 09:54:07.864  3210  7679 D HeadsetStateMachine: Disconnected process message: 70
08-29 09:54:07.864  3210  7679 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@343168e4
,08-29 09:54:07.864  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:07.864  4753  4753 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:54:07.864  1437  1437 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-29 09:54:07.874  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 09:54:07.874  1016  3755 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:54:07.874  4753  4753 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-29 09:54:07.874  1016  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-29 09:54:07.874  4753  4753 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 09:54:07.874  1437  1437 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 09:54:07.874  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 09:54:07.874  1437  1437 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-29 09:54:07.874  1437  1437 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 09:54:07.874  4753  4753 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 09:54:07.874  4753  4753 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-29 09:54:07.874  3210  7689 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 09:54:07.874  3210  7679 D HeadsetStateMachine: Disconnected process message: 9
08-29 09:54:07.874  3210  7679 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 09:54:07.884   290   714 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 09:54:07.884   290   714 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 09:54:07.884   290   714 V voice   : voice_set_parameters: exit with code(-2)
08-29 09:54:07.884   290   714 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 09:54:07.884   290   714 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 09:54:07.884   290   714 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 09:54:07.884   290   714 V audio_hw_primary: adev_set_parameters: exit
08-29 09:54:07.884  3210  7679 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 09:54:07.884  3210  7689 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 09:54:07.884  3210  7689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:07.884  4753  4753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:54:07.884  1016  1343 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 09:54:07.884  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.884  3210  7689 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-29 09:54:07.884  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:07.884  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:07.884  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-29 09:54:07.884  3210  7689 D BluetoothSocket: bindListen(), new LocalSocket 
,08-29 09:54:07.884  3210  7689 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-29 09:54:07.884  3210  7689 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b57514d
08-29 09:54:07.884  3210  7689 D BluetoothSocket: channel: 5
,08-29 09:54:07.894  1663  1663 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:54:07.894  4753  4753 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:54:07.904  4753  4753 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 09:54:07.904  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 09:54:07.904  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 09:54:07.914  3210  3210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@28740627
,08-29 09:54:07.914  3210  3210 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 09:54:07.914  1016  1343 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 09:54:07.914  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 09:54:07.914  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-29 09:54:07.914  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:07.914  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 09:54:07.924  1016  1474 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 09:54:07.934  3210  7694 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 09:54:07.934  3210  7694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:54:07.934  3210  7694 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
08-29 09:54:07.934  3210  7694 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 09:54:07.934  3210  7694 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 09:54:07.934  3210  7694 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2654b549
08-29 09:54:07.934  3210  7694 D BluetoothSocket: channel: 12
08-29 09:54:07.934  3210  7694 I BtOppRfcommListener: Accept thread started.
,08-29 09:54:08.424  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:08.424  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:08.424  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:08.424  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:54:08.424  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:08.424  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:08.424  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:08.424  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:08.424  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:08.424  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:08.424  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36ff3cce added. We now have 8 listener(s)
,08-29 09:54:08.424  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:08.424  1016  1136 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 09:54:08.434  1016  1136 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 09:54:08.434  1016  1136 D SecContentProvider2: mCursor = null
,08-29 09:54:08.434  1016  1136 D WifiService: setWifiEnabled: false pid=6799, uid=10170
,08-29 09:54:08.434  1016  1136 D SettingsProvider: name = wifi_on
,08-29 09:54:08.434  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:08.444  1016  3755 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 09:54:08.444  1016  3755 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 09:54:08.444  1016  3755 D SecContentProvider2: mCursor = null
,08-29 09:54:08.444  1016  3755 D WifiService: setWifiEnabled: true pid=6799, uid=10170
,08-29 09:54:08.444  1016  3755 W ActivityManager: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 09:54:08.444  1016  3755 W WifiService: Failed getting userId using ActivityManagerNative
08-29 09:54:08.444  1016  3755 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6799, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 09:54:08.444  1016  3755 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 09:54:08.444  1016  3755 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 09:54:08.444  1016  3755 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 09:54:08.444  1016  3755 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 09:54:08.444  1016  3755 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 09:54:08.444  1016  3755 D SettingsProvider: name = wifi_on
,08-29 09:54:08.454  1016  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 09:54:08.744   295   295 E SMD     : DCD OFF
,08-29 09:54:08.774  1016  1043 D Tethering: interfaceAdded wlan0
,08-29 09:54:08.784  1016  1131 E Tethering: No numeric data
,08-29 09:54:08.784  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 09:54:08.784  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
08-29 09:54:08.784  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:54:08.784  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:08.784  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 09:54:08.784  1175  1175 D HotspotTile: updateTetherState():false, false
08-29 09:54:08.784  1016  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 09:54:08.784  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 09:54:08.784  1016  1131 D Tethering: clearTetheredNotification()
08-29 09:54:08.784  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:54:08.784  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 09:54:08.784  1016  1131 D Tethering: InitialState.processMessage what=4
,08-29 09:54:08.794  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:08.794  1016  1125 V NetworkStats: performPollLocked() took 9ms
08-29 09:54:08.794  1016  1131 E Tethering: No numeric data
,08-29 09:54:08.794  1016  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 09:54:08.794  1016  1131 D Tethering: clearTetheredNotification()
08-29 09:54:08.794  1016  1043 D Tethering: interfaceAdded p2p0
,08-29 09:54:08.794  1016  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-29 09:54:08.794  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:08.804  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:08.804  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 09:54:08.804  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 09:54:08.804  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 09:54:08.804  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:08.804  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:08.804  1175  1175 D HotspotTile: updateTetherState():false, false
08-29 09:54:08.804  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-29 09:54:08.814  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:54:08.814  1016  1125 V NetworkStats: performPollLocked() took 9ms
08-29 09:54:08.814  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 09:54:08.814  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:08.814  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:08.814  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:08.814   282  1002 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-29 09:54:08.824   282  1002 D SoftapController: Softap fwReload - Ok
,08-29 09:54:08.824   282  1002 D CommandListener: Setting iface cfg
,08-29 09:54:08.824   282  1002 D CommandListener: Trying to bring down wlan0,
08-29 09:54:08.824   282  1002 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:54:08.834  1016  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 09:54:08.874  7706  7706 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-29 09:54:08.874  7706  7706 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 09:54:08.884  7706  7706 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 09:54:08.894  7706  7706 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-29 09:54:08.894   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7706
08-29 09:54:08.894   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 09:54:08.894  7706  7706 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 09:54:08.894  7706  7706 I wpa_supplicant: ssSupport state is = 1
08-29 09:54:08.894  7706  7706 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 09:54:08.894  7706  7706 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 09:54:08.894   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7706
08-29 09:54:08.894   393   393 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-29 09:54:08.934  1016  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 09:54:08.944  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-29 09:54:08.944  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:08.944  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-29 09:54:08.944  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:08.944  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:08.944  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 09:54:08.944  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:08.944  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 09:54:08.944  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:08.944  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 09:54:08.944  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-29 09:54:08.944  1175  1175 D HotspotTile: onReceive : 2, 0
,08-29 09:54:08.954  4753  4753 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 09:54:08.954  1016  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 09:54:08.954  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:54:08.954  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:08.954  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:08.954  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 09:54:08.954  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:54:08.954  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 09:54:08.954  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 09:54:08.964  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
08-29 09:54:08.964  7035  7035 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 09:54:08.964  2213  2213 I Hs20UtilService: Starting #19
08-29 09:54:08.964  2213  2228 I Hs20UtilService: Message received 5011
,08-29 09:54:09.044   393   393 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-29 09:54:09.044  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-29 09:54:09.094  7706  7706 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 09:54:09.094  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 09:54:09.104  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-29 09:54:09.104   393   393 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7706,
08-29 09:54:09.104   393   393 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 09:54:09.104  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 09:54:09.104  7706  7706 I wpa_supplicant: ssSupport state is = 1
08-29 09:54:09.104  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 09:54:09.104  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 09:54:09.104  7706  7706 E wpa_supplicant: SIM READ ERROR
08-29 09:54:09.104  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 09:54:09.104  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 09:54:09.104  7706  7706 E wpa_supplicant: SIM READ ERROR
08-29 09:54:09.104  7706  7706 I wpa_supplicant: Blacklist: Clear (all) 
08-29 09:54:09.104  7706  7706 I wpa_supplicant: wpa_default_ap_write_once
08-29 09:54:09.104  7706  7706 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-29 09:54:09.104  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 09:54:09.104  7706  7706 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 09:54:09.104  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 09:54:09.104  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-29 09:54:09.104  7706  7706 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-29 09:54:09.114  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 09:54:09.114  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 09:54:09.114  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-29 09:54:09.304  7706  7706 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-29 09:54:09.434  7706  7706 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-29 09:54:09.434  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-29 09:54:09.444  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 09:54:09.444   393   393 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7706,
08-29 09:54:09.444   393   393 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-29 09:54:09.454  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 09:54:09.454  7706  7706 I wpa_supplicant: ssSupport state is = 1
,08-29 09:54:09.454  7706  7706 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 09:54:09.454  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 09:54:09.464  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 09:54:09.464   393   393 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7706
08-29 09:54:09.464   393   393 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-29 09:54:09.464  7706  7706 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 09:54:09.464  7706  7706 I wpa_supplicant: ssSupport state is = 1
08-29 09:54:09.464  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 09:54:09.464  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 09:54:09.464  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 09:54:09.464  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 09:54:09.464  7706  7706 E wpa_supplicant: SIM READ ERROR
08-29 09:54:09.464  7706  7706 I wpa_supplicant: wpa_default_ap_write_once
08-29 09:54:09.464  7706  7706 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 09:54:09.464  7706  7706 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 09:54:09.464  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 09:54:09.464  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
08-29 09:54:09.464  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 09:54:09.464  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 09:54:09.514  7706  7706 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 09:54:09.514  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 09:54:09.584  7706  7706 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-29 09:54:09.584  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-29 09:54:09.584  7706  7706 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-29 09:54:09.594  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-29 09:54:09.594  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 09:54:09.594  7706  7706 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-29 09:54:09.604  7706  7706 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 09:54:09.604  7706  7706 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 09:54:09.604  7706  7706 E wpa_supplicant: SIM READ ERROR,
08-29 09:54:09.604  7706  7706 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 09:54:09.624  7706  7706 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
08-29 09:54:09.634  7706  7706 I wpa_supplicant: Skip scan - bUseNetwork false
08-29 09:54:09.634  1016  1128 D WifiConfigStore: Loading config and enabling all networks 
08-29 09:54:09.644  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:54:09.644  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:09.644  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:54:09.644  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:09.644  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:09.644  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:09.644  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:09.644  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:09.644  1175  1175 D HotspotTile: onReceive : 3, 0
08-29 09:54:09.644  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:09.644  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 09:54:09.644  4753  4753 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-29 09:54:09.644  1175  1744 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 09:54:09.654  1016  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:54:09.654  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:09.654  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:09.654  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:09.654  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:09.654  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:09.654  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:09.654  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:09.654  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:54:09.654  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 09:54:09.654  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:09.654  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:09.654  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 09:54:09.654  2213  2213 I Hs20UtilService: Starting #20
08-29 09:54:09.654  2213  2228 I Hs20UtilService: Message received 5011
08-29 09:54:09.654  1016  1128 E WifiConfigStore: Not a HS20
08-29 09:54:09.654  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:09.654  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 09:54:09.654  7035  7035 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 09:54:09.654  7035  7035 D SecurityLogAgent: StateMachine : Current State = 1
08-29 09:54:09.654  1016  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
08-29 09:54:09.654  7035  7035 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 09:54:09.664  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 09:54:09.664  7706  7706 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 09:54:09.664  7706  7706 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 09:54:09.664  7706  7706 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 09:54:09.664  7706  7706 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 09:54:09.664  7706  7706 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 09:54:09.664  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 09:54:09.664  7706  7706 I wpa_supplicant: First Scan Start
08-29 09:54:09.664  7706  7706 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 09:54:09.664  1016  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-29 09:54:09.664  1016  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:54:09.664  1016  1128 I WifiNative-HAL: startHal
08-29 09:54:09.664  1016  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f1c288c
08-29 09:54:09.664  1016  1128 I WifiNative-HAL: Could not start hal
08-29 09:54:09.674  7207  7207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:54:09.674  1016  1128 E WifiNative-wlan0: do suspend true,
,08-29 09:54:09.674  1016  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 09:54:09.674   282  1002 D CommandListener: Setting iface cfg
08-29 09:54:09.674   282  1002 D CommandListener: Trying to bring up p2p0
,08-29 09:54:09.674  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-29 09:54:09.674  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
,08-29 09:54:09.674  1016  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 09:54:09.674  1016  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:09.674  1016  1152 I WifiNative-HAL: startHal
08-29 09:54:09.674  1016  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e0849bc
08-29 09:54:09.674  1016  1127 D WifiP2pService: P2pEnablingState
08-29 09:54:09.674  1016  1152 I WifiNative-HAL: Could not start hal
08-29 09:54:09.684  1016  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-29 09:54:09.674  1016  1152 E WifiScanningService: could not start HAL
08-29 09:54:09.684  1016  1127 D WifiP2pService: P2p socket connection successful
08-29 09:54:09.674  1016  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 09:54:09.674  1016  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 09:54:09.674  1016  1128 E WifiNative-wlan0: invaild command id : 215
08-29 09:54:09.684  1016  1127 D WifiP2pService: P2pEnabledState
08-29 09:54:09.684  1016  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 09:54:09.684  1016  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 09:54:09.684  1016  1128 E WifiNative-wlan0: invaild command id : 215
08-29 09:54:09.684  1016  1016 D RttService: SCAN_AVAILABLE : 3,
08-29 09:54:09.684  1016  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:54:09.684  7706  7706 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 09:54:09.684  7706  7706 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 09:54:09.684  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 09:54:09.684  7706  7706 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 09:54:09.684  1016  1128 E WifiStateMachine: Failed to set frequency band 0
08-29 09:54:09.684  1016  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 09:54:09.684  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-29 09:54:09.684  1016  1046 D WifiDisplayController: disconnect
08-29 09:54:09.684  1016  1046 D WifiDisplayController: updateConnection
08-29 09:54:09.684  1016  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 09:54:09.684  1016  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 09:54:09.684  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:54:09.684  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 09:54:09.684  1016  1128 D SecContentProvider2: mCursor = null
08-29 09:54:09.684  1016  1130 E ConnectivityService: updateNetworkInfo()
,08-29 09:54:09.684  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 09:54:09.684  1016  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 09:54:09.694  1016  1562 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 09:54:09.694  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 09:54:09.694  1016  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-29 09:54:09.694  1016  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 09:54:09.694  1016  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-29 09:54:09.694  1016  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 09:54:09.694  1016  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 09:54:09.694  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-29 09:54:09.694  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:54:09.694  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:54:09.694  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 09:54:09.694  1016  1127 D WifiP2pService: DeviceAddress: 0a:75:42
08-29 09:54:09.694  1016  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  secondary type: null
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  wps: 0
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  grpcapab: 0
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  devcapab: 0
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  status: 3
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  wfdInfo: null
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  groupownerAddress: null
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  GOdeviceName: null
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  interfaceAddress: 
08-29 09:54:09.694  1016  1046 D WifiDisplayController:  SConnectInfo : null
,08-29 09:54:09.704  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 09:54:09.704  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:54:09.704  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 09:54:09.704  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 09:54:09.704  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 09:54:09.704  7588  7588 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 09:54:09.704  7588  7588 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 09:54:09.704  7588  7588 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 09:54:09.714  7192  7192 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 09:54:09.724  1016  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 09:54:09.724  1016  1127 D WifiP2pService: InactiveState
,08-29 09:54:09.724  1016  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-29 09:54:09.724  1016  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 09:54:09.724  7706  7706 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 09:54:09.724  1016  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-29 09:54:09.724  1016  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 09:54:09.784  1016  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 09:54:09.784  1016  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 09:54:09.784  1016  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-29 09:54:10.484  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:54:10.484  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:10.484  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:10.484  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:10.484  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:10.484  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:10.484  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:10.484  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:10.484  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:10.484  6799  6965 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 09:54:10.484  6799  6965 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 09:54:10.494  6799  6965 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@38f394ed Bundle[{}]
,08-29 09:54:10.494  6799  6965 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 09:54:10.494  6799  6965 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 09:54:10.494  6799  6965 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 09:54:10.494  6799  6965 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 09:54:10.494  6799  6965 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 09:54:10.494  6799  6965 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 09:54:10.504  6799  6965 I System.out: Running OutgoingSocketThread
,08-29 09:54:10.504  6799  7716 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1359)
,08-29 09:54:10.504  6799  7716 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38600
,08-29 09:54:10.504  6799  7716 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 09:54:10.534  1016  3363 D SSRM:n  : SIOP:: AP = 330
,08-29 09:54:10.884  7706  7706 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
,08-29 09:54:10.884  7706  7706 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 09:54:10.884  7706  7706 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 09:54:10.884  7706  7706 I wpa_supplicant: Trying to associate with  'G700'
,08-29 09:54:10.884  7706  7706 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-29 09:54:10.884  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-29 09:54:10.884  1016  7712 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-29 09:54:10.894  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:54:10.894  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:54:11.004  7706  7706 E wpa_supplicant: Cmd 35605 not handled
,08-29 09:54:11.004  7706  7706 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 09:54:11.004  7706  7706 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-29 09:54:11.004  7706  7706 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
08-29 09:54:11.004  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-29 09:54:11.004  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 09:54:11.004  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 09:54:11.004  1016  1043 D Tethering: interfaceStatusChanged wlan0, false,
,08-29 09:54:11.004  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-29 09:54:11.004  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
,08-29 09:54:11.004  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-29 09:54:11.004  7706  7706 I wpa_supplicant: Associated with F4.99.3E,
08-29 09:54:11.004  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
08-29 09:54:11.004  7706  7706 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 09:54:11.014  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 09:54:11.004  7706  7706 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 09:54:11.014  1175  1175 D HotspotTile: updateTetherState():false, false
08-29 09:54:11.004  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-29 09:54:11.004  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 09:54:11.004  1016  1043 D Tethering: interfaceStatusChanged wlan0, false
08-29 09:54:11.004  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 09:54:11.004  1016  1043 D Tethering: interfaceStatusChanged wlan0, false,
08-29 09:54:11.004  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-29 09:54:11.014  1016  1125 V NetworkStats: performPollLocked() took 8ms
08-29 09:54:11.004  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-29 09:54:11.004  1016  1131 E Tethering: No numeric data
08-29 09:54:11.004  1016  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 09:54:11.004  1016  1131 D Tethering: clearTetheredNotification()
08-29 09:54:11.014  1016  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 09:54:11.004  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:11.014  7706  7706 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-29 09:54:11.014  7706  7706 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-29 09:54:11.014  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 09:54:11.014  1016  1128 D SecContentProvider2: mCursor = null
08-29 09:54:11.014  7706  7706 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-29 09:54:11.014  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 09:54:11.014  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:54:11.014  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 09:54:11.014  7706  7706 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 09:54:11.014  7706  7706 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 09:54:11.014  7706  7706 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
08-29 09:54:11.014  7706  7706 I wpa_supplicant: Blacklist: Clear (temp) 
,08-29 09:54:11.014  7706  7706 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 09:54:11.014  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 09:54:11.014  1016  1128 D SecContentProvider2: mCursor = null
08-29 09:54:11.014  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:11.014  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-29 09:54:11.014  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 09:54:11.014  1016  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-29 09:54:11.014  1016  1043 D Tethering: interfaceStatusChanged wlan0, true
08-29 09:54:11.014  1016  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-29 09:54:11.024  1016  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 09:54:11.034  1016  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-29 09:54:11.034  1016  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 09:54:11.034  1016  1130 E ConnectivityService: updateNetworkInfo()
08-29 09:54:11.034  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:54:11.034  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:11.034  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:54:11.034  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:11.034  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:54:11.034  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.034  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.034  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.034  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:11.034  1016  1136 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-29 09:54:11.034  1016  1136 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:54:11.034  1016  1136 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:11.034  1016  1136 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:11.034  1016  1136 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 09:54:11.034  2213  2213 I Hs20UtilService: Starting #21
,08-29 09:54:11.044  2213  2228 I Hs20UtilService: Message received 5007
,08-29 09:54:11.044  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 09:54:11.044  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 09:54:11.044  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 09:54:11.044  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 09:54:11.044  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 09:54:11.044  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 09:54:11.054  4753  4753 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 09:54:11.054  4753  4838 V NearbySettings: MountReceiver.mPrefHandler - 7002,
08-29 09:54:11.054   282  1002 D CommandListener: Setting iface cfg
,08-29 09:54:11.064  1016  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,08-29 09:54:11.064  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 09:54:11.064  1016  1128 D SecContentProvider2: mCursor = null
,08-29 09:54:11.074  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:54:11.074  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 09:54:11.074  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 09:54:11.074  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.074  1016  1128 E WifiNative-wlan0: do suspend false
,08-29 09:54:11.074  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-29 09:54:11.074  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:11.074  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.074  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-29 09:54:11.074  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 09:54:11.074  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 09:54:11.074  1016  1128 D SecContentProvider2: mCursor = null,
,08-29 09:54:11.284  7719  7719 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 09:54:11.294  7719  7719 I dhcpcd  : version 5.5.6 starting,
,08-29 09:54:11.294  7719  7719 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 09:54:11.354  7719  7719 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 09:54:11.354  7719  7719 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-29 09:54:11.354  7719  7719 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-29 09:54:11.354  7719  7719 I dhcpcd  : bssid match,
08-29 09:54:11.354  7719  7719 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-29 09:54:11.434  7719  7719 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-29 09:54:11.494  7719  7719 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-29 09:54:11.504  6799  6965 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1360)
08-29 09:54:11.504  6799  6965 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1360)
,08-29 09:54:11.504  6799  6965 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1365),
,08-29 09:54:11.514  6799  6965 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 09:54:11.514  6799  6965 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1366)
,08-29 09:54:11.514  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-29 09:54:11.514  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@487d7ef added. We now have 2 listener(s)
08-29 09:54:11.514  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 09:54:11.514  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:11.514  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:11.514  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:11.514  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37bf2fc added. We now have 9 listener(s)
08-29 09:54:11.514  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:11.514  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:11.524  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-29 09:54:11.524  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:11.524  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:11.524  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:11.524  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:11.524  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:11.524  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:11.524  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:11.524  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:11.544  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-29 09:54:11.544  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:11.544  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:11.544  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:11.544  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:11.544  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5657da added. We now have 3 listener(s)
08-29 09:54:11.544  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 09:54:11.544  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:11.544  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:11.544  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:11.544  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@924040b added. We now have 10 listener(s)
08-29 09:54:11.544  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:11.544  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:11.544  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:11.544  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:54:11.554  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:11.554  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@487d7ef removed from the list,
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.554  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37bf2fc removed from the list
08-29 09:54:11.554  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:11.554  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.554  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37bf2fc not in the list
08-29 09:54:11.554  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.554  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@924040b removed from the list
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:11.554  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:11.554  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:11.554  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5657da removed from the list
08-29 09:54:11.554  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:11.554  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91342e8 added. We now have 2 listener(s)
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:54:11.554  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:11.554  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23065d01 added. We now have 9 listener(s),
08-29 09:54:11.554  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:11.564  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:11.564  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-29 09:54:11.574  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:11.574  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:11.574  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:11.574  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:11.574  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:11.574  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:11.574  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:11.574  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:11.584  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:54:11.584  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-29 09:54:11.584  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:11.584  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:54:11.584  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-29 09:54:11.584  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220cd5e7 added. We now have 3 listener(s)
08-29 09:54:11.584  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 09:54:11.584  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-29 09:54:11.584  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:11.584  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:11.584  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4da594 added. We now have 10 listener(s)
08-29 09:54:11.584  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-29 09:54:11.584  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:11.584  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:54:11.584  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-29 09:54:11.584  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:11.584  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:54:11.594  1016  1095 V AlarmManager: waitForAlarm result :4
,08-29 09:54:11.594  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:54:11.604   282   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 09:54:11.604   282   998 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-29 09:54:11.604  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:54:11.604  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:54:11.604  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-29 09:54:11.604  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:54:11.604  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 09:54:11.614  3210  3221 D BtGatt.GattService: registerClient() - UUID=ee113bb2-ec12-4ac1-b66a-9dcdc8f7ac56,
,08-29 09:54:11.624  1016  1041 W ActivityManager: userId = 0, bbcId = -10000,
08-29 09:54:11.624  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:54:11.624  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk,
,08-29 09:54:11.654  3210  3286 D BtGatt.GattService: onClientRegistered() - UUID=ee113bb2-ec12-4ac1-b66a-9dcdc8f7ac56, clientIf=6,
,08-29 09:54:11.654  6799  6807 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 09:54:11.654  3210  3219 D BtGatt.GattService: start scan with filters
08-29 09:54:11.654  3210  3335 D BtGatt.ScanManager: handling starting scan
08-29 09:54:11.654  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:54:11.654  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:54:11.654  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:54:11.654  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:54:11.664  3210  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 09:54:11.664  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.664  3210  3335 D BtGatt.ScanManager: allow scan with filters
08-29 09:54:11.664  3210  3335 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 09:54:11.664  3210  3335 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
08-29 09:54:11.664  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:11.664  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 09:54:11.664  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:54:11.664  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 09:54:11.664  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-29 09:54:11.664  3210  3335 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 09:54:11.664  3210  3335 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 09:54:11.664  3210  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 09:54:11.664  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.664  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-29 09:54:11.674  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 09:54:11.674  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.674  6799  6965 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:54:11.674  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:11.674  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:54:11.674  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.674  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:11.674  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:54:11.674  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:54:11.674  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:54:11.674  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:54:11.674  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:54:11.674  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:54:11.674  3210  3327 D BtGatt.GattService: stopScan() - queue size =1
,08-29 09:54:11.674  3210  3335 D BtGatt.ScanManager: filter size is 1
,08-29 09:54:11.674  3210  3335 D BtGatt.ScanManager: delete FilterIndex - 6
08-29 09:54:11.674  3210  7657 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 09:54:11.674  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:11.674  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:54:11.674  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:54:11.674  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 09:54:11.674  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:54:11.674  3210  3335 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:54:11.674  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 09:54:11.674  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 09:54:11.684  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:54:11.684  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:54:11.684  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:54:11.684  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,08-29 09:54:11.684  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 09:54:11.684  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:54:11.684  3210  3335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 09:54:11.694  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:11.694  3210  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 09:54:11.694  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.694  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:11.694  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:11.694  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:54:11.694  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:11.694  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:11.694  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 09:54:11.694  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:11.694  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.694  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:11.694  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:11.694  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91342e8 removed from the list
08-29 09:54:11.694  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.694  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23065d01 removed from the list,
08-29 09:54:11.694  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:11.694  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:11.694  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.694  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:11.704  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:54:11.704  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:11.704  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.704  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23065d01 not in the list
08-29 09:54:11.704  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.704  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-29 09:54:11.704  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:54:11.704  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:11.704  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.704  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4da594 removed from the list
08-29 09:54:11.704  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:11.704  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.704  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:11.704  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:11.704  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220cd5e7 removed from the list
08-29 09:54:11.704  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:11.704  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a298700 added. We now have 2 listener(s)
,08-29 09:54:11.714  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 09:54:11.714  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:11.714  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:11.714  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:54:11.714  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d0ab39 added. We now have 9 listener(s)
,08-29 09:54:11.714  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:11.714  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:11.724  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:11.724  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:11.724  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:11.724  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:11.724  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:11.724  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-29 09:54:11.724  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:11.724  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:11.724  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:11.734  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:11.734  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:11.734  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:11.734  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10849adf added. We now have 3 listener(s)
,08-29 09:54:11.734   295   295 E SMD     : DCD OFF
,08-29 09:54:11.734  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:11.734  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:11.744  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 09:54:11.744  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:11.744  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:11.744  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:11.744  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1720132c added. We now have 10 listener(s)
08-29 09:54:11.744  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:11.744  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:11.744  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:11.744  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-29 09:54:11.744  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-29 09:54:11.744  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:11.744  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 09:54:11.744  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:54:11.754  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-29 09:54:11.754  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:54:11.754  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:54:11.754  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 09:54:11.754  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 09:54:11.764  3210  7688 D BtGatt.GattService: registerClient() - UUID=9a140d24-b0bc-48bd-8ff7-723e207dbc7c
,08-29 09:54:11.814  3210  3286 D BtGatt.GattService: onClientRegistered() - UUID=9a140d24-b0bc-48bd-8ff7-723e207dbc7c, clientIf=6
,08-29 09:54:11.814  6799  6811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 09:54:11.814  3210  3219 D BtGatt.GattService: start scan with filters
,08-29 09:54:11.814  3210  3335 D BtGatt.ScanManager: handling starting scan
,08-29 09:54:11.814  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 09:54:11.814  3210  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 09:54:11.814  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.814  3210  3335 D BtGatt.ScanManager: allow scan with filters
08-29 09:54:11.814  3210  3335 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 09:54:11.814  3210  3335 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
08-29 09:54:11.814  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 09:54:11.814  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:54:11.814  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:54:11.814  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 09:54:11.814  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:54:11.814  3210  3335 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:54:11.814  3210  3335 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 09:54:11.814  3210  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 09:54:11.814  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.814  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 09:54:11.814  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:54:11.814  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:11.814  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 09:54:11.814  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:54:11.814  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:54:11.824  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 09:54:11.824  6799  6965 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 09:54:11.824  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:11.824  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:11.824  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:11.824  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:11.824  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a298700 removed from the list
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.824  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d0ab39 removed from the list
08-29 09:54:11.824  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:11.824  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 09:54:11.824  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.824  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34d0ab39 not in the list
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:54:11.824  3210  3221 D BtGatt.GattService: stopScan() - queue size =1
,08-29 09:54:11.824  3210  3335 D BtGatt.ScanManager: filter size is 1
,08-29 09:54:11.824  3210  3335 D BtGatt.ScanManager: delete FilterIndex - 7
,08-29 09:54:11.824  3210  3327 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 09:54:11.824  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 09:54:11.824  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:54:11.824  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:54:11.824  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 09:54:11.824  3210  3335 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:54:11.834  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:54:11.834  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 09:54:11.834  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:54:11.834  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 09:54:11.834  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:11.834  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 09:54:11.834  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.834  3210  3335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 09:54:11.834  3210  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 09:54:11.834  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.834  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:11.834  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:11.834  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.834  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1720132c removed from the list
08-29 09:54:11.834  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:11.834  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.834  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:11.834  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:11.834  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10849adf removed from the list
,08-29 09:54:11.834  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:11.834  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:11.834  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:11.834  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24113618 added. We now have 2 listener(s)
,08-29 09:54:11.834  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:54:11.844  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 09:54:11.844  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:11.844  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:11.844  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:11.844  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85f8871 added. We now have 9 listener(s)
08-29 09:54:11.844  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:54:11.844  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:11.844  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:11.844  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:11.844  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:11.844  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:11.844  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:11.844  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:11.844  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:54:11.844  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:54:11.844  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:54:11.844  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:54:11.844  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:54:11.844  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:11.854  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34a106d7 added. We now have 3 listener(s)
,08-29 09:54:11.854  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:11.854  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:11.854  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 09:54:11.854  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 09:54:11.854  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:54:11.854  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:11.854  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19ef9bc4 added. We now have 10 listener(s)
,08-29 09:54:11.854  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:11.854  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:11.854  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 09:54:11.854  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:54:11.854  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:54:11.854  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 09:54:11.864  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:54:11.864  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:54:11.864  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:54:11.864  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:54:11.864  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 09:54:11.864  6799  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 09:54:11.874  3210  7688 D BtGatt.GattService: registerClient() - UUID=acab5de0-bd6e-4263-8f88-64326b8cf66d
,08-29 09:54:11.874  1016  1128 E WifiNative-wlan0: do suspend true
,08-29 09:54:11.904  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-29 09:54:11.904  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 09:54:11.914  1016  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 09:54:11.914  1016  1128 E WifiStateMachine: VerifyingLinkState enter
,08-29 09:54:11.914  3210  3286 D BtGatt.GattService: onClientRegistered() - UUID=acab5de0-bd6e-4263-8f88-64326b8cf66d, clientIf=6
,08-29 09:54:11.914  6799  6807 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 09:54:11.914  3210  3219 D BtGatt.GattService: start scan with filters
,08-29 09:54:11.914  3210  3335 D BtGatt.ScanManager: handling starting scan
,08-29 09:54:11.914  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-29 09:54:11.914  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:54:11.914  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 09:54:11.914  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:54:11.924  1016  1130 E ConnectivityService: updateNetworkInfo()
,08-29 09:54:11.924  3210  3286 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 09:54:11.924  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.924  3210  3335 D BtGatt.ScanManager: allow scan with filters,
,08-29 09:54:11.924  3210  3335 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 09:54:11.924  1016  1130 D ConnectivityService: Adding iface wlan0 to network 504
08-29 09:54:11.924  3210  3335 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6,
08-29 09:54:11.924  1016  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-29 09:54:11.934  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:54:11.934  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:54:11.934  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:54:11.934  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:54:11.934  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:11.934  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:54:11.934  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.934  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.934  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.934  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:11.934  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 09:54:11.934  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.944  3210  3335 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:54:11.944  3210  3335 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 09:54:11.944  1016  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-29 09:54:11.944  1016  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 09:54:11.944  1016  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 09:54:11.944  1016  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 09:54:11.944  1016  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 09:54:11.954  3210  3286 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 09:54:11.954  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.954  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 09:54:11.954  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:11.964  1016  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-29 09:54:11.964  1016  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-29 09:54:11.964  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:54:11.974  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:54:11.974  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:11.974  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:54:11.974  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.974  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.974  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.974  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:11.974  1016  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-29 09:54:11.974  1016  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-29 09:54:11.974  1016  1343 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:54:11.974  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 09:54:11.974  1016  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 09:54:11.974  1016  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-29 09:54:11.974  1016  1130 D ConnectivityService: LTETest block dns file not exists
,08-29 09:54:11.974  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:11.974  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:11.974  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:54:11.984  1016  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 09:54:11.984  2213  2213 I Hs20UtilService: Starting #22
08-29 09:54:11.984  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 09:54:11.984  2213  2228 I Hs20UtilService: Message received 5007
,08-29 09:54:11.984  1016  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 09:54:11.984  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:54:11.984  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:54:11.984  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:11.984  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:54:11.984  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:11.984  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:54:11.984  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:54:11.984  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24113618 removed from the list
08-29 09:54:11.984  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:11.984  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85f8871 removed from the list
08-29 09:54:11.984  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:11.984  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-29 09:54:11.994  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 09:54:11.994  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
08-29 09:54:11.994  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
,08-29 09:54:11.994  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 09:54:11.994  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:11.994  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 09:54:11.994  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.994  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.994  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:11.994  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:12.004  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:12.004  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 09:54:12.004  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:12.004  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:12.004  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:12.004  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:12.014  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 09:54:12.014  1016  1130 V NetworkStats: updateIfacesLocked()
08-29 09:54:12.014  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.014  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-29 09:54:12.014  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:54:12.014  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:54:12.024  1016  1130 V NetworkStats: performPollLocked() took 7ms
08-29 09:54:12.024  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:12.024  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:12.024  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 09:54:12.024  1016  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-29 09:54:12.024  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:12.024  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 09:54:12.024  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:12.024  1016  1130 E ConnectivityService: updateNetworkInfo()
08-29 09:54:12.024  1016  1130 E ConnectivityService: updateNetworkInfo()
08-29 09:54:12.024  1016  1130 V NetworkStats: updateIfacesLocked()
08-29 09:54:12.024  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.024  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-29 09:54:12.024  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 09:54:12.024  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:54:12.024  4753  4753 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 09:54:12.024  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.024  1016  1130 V NetworkStats: performPollLocked() took 4ms
,08-29 09:54:12.024  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.024  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:12.024  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 09:54:12.024  1016  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504],
08-29 09:54:12.024  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 09:54:12.024  1016  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 09:54:12.024  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 09:54:12.034  1016  1130 D ConnectivityService:    accepting network in place of null
08-29 09:54:12.024  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85f8871 not in the list
08-29 09:54:12.034  1016  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-29 09:54:12.024  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:54:12.034  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 09:54:12.024  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-29 09:54:12.024  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:54:12.034  1016  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-29 09:54:12.024  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.024  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:54:12.024  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:54:12.024  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.024  1016  7717 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:12.024  1016  7717 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-29 09:54:12.024  1016  7717 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:54:12.024  1016  7717 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-29 09:54:12.034  3210  3219 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:54:12.034  1016  7717 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 09:54:12.034  3210  3335 D BtGatt.ScanManager: filter size is 1
08-29 09:54:12.034  3210  3335 D BtGatt.ScanManager: delete FilterIndex - 8
08-29 09:54:12.034  1016  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 09:54:12.034  1016  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 09:54:12.034  1016  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 09:54:12.034  3210  3221 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 09:54:12.034  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:54:12.034  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:54:12.034  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:54:12.034  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: Stat,e changed from [SCANNING] to [NOT_STARTED]
08-29 09:54:12.034  3210  3286 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 09:54:12.034  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 09:54:12.034  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:54:12.034  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 09:54:12.034  3210  3335 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:54:12.034  1016  1131 D Tethering: MasterInitialState.processMessage what=3
08-29 09:54:12.034  1463  1463 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 09:54:12.034  1463  1463 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 09:54:12.034   282   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 09:54:12.034   282   998 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-29 09:54:12.034  1016  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-29 09:54:12.034  1175  1734 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 09:54:12.044  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.044  1016  1125 V NetworkStats: updateIfacesLocked()
08-29 09:54:12.044  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:12.044  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-29 09:54:12.044  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:54:12.044  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:54:12.044  3210  3286 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 09:54:12.044  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:54:12.044  6799  6965 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 09:54:12.044  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:12.044  1016  1125 V NetworkStats: performPollLocked() took 4ms
08-29 09:54:12.044  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.044  3210  3335 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 09:54:12.044  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:54:12.044  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.044  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-29 09:54:12.044  1016  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 09:54:12.044  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 09:54:12.044  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-29 09:54:12.044  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-29 09:54:12.044  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.044  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.044  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:12.044  3210  3286 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 09:54:12.044  3210  3286 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 09:54:12.054  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-29 09:54:12.054  1016  3766 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:54:12.054  1016  3766 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:54:12.054  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.054  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:12.054  1016  3766 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:12.054  1016  3766 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:12.054  1016  3766 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:54:12.054  2213  2213 I Hs20UtilService: Starting #23
,08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-29 09:54:12.054  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-29 09:54:12.054  4753  4753 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 09:54:12.054  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:12.054  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:12.054  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:12.054  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-29 09:54:12.054  2213  2228 I Hs20UtilService: Message received 5007
,08-29 09:54:12.054  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:12.054  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:12.054  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:12.054  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19ef9bc4 removed from the list
08-29 09:54:12.054  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:12.054  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:12.054  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:12.054  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:12.054  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34a106d7 removed from the list
08-29 09:54:12.054  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:12.054  6799  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:54:12.054  6799  6799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:54:12.054  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:54:12.054  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2cb030 added. We now have 2 listener(s)
08-29 09:54:12.054  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 09:54:12.054  4753  4753 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-29 09:54:12.054  4753  4753 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 09:54:12.064  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 09:54:12.064  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:12.064  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:12.064  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:12.064  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d5d4a9 added. We now have 9 listener(s)
08-29 09:54:12.064  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:12.064  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:54:12.064  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:54:12.064  1016  3702 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 09:54:12.064  1016  3702 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 09:54:12.074  1016  3702 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:12.074  1016  3702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 09:54:12.074  1016  3702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 09:54:12.074  2213  2213 I Hs20UtilService: Starting #24
,08-29 09:54:12.074  2213  2228 I Hs20UtilService: Message received 5007
08-29 09:54:12.074  4753  4753 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 09:54:12.074  4753  4753 I NearbySettings: MountReceiver.onReceive - Keep current state
08-29 09:54:12.074  6799  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:54:12.074  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:12.074  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:12.074  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:12.074  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:12.074  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:12.074  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:12.074  6799  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:54:12.074  6799  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:54:12.074  6799  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:54:12.074  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:12.084  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:54:12.084  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6ff9cf added. We now have 3 listener(s)
08-29 09:54:12.084  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:54:12.084  1016  3755 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:54:12.084  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:54:12.084  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e49f5c added. We now have 10 listener(s)
08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:54:12.084  6799  6965 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:54:12.084  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:54:12.084  6799  6965 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:12.084  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:12.084  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2cb030 removed from the list
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:12.084  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d5d4a9 removed from the list
08-29 09:54:12.084  6799  6965 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:12.084  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:12.084  6799  6965 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d5d4a9 not in the list
,08-29 09:54:12.084  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:54:12.084  6799  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e49f5c removed from the list
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:54:12.084  6799  6965 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:54:12.084  6799  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:54:12.084  6799  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:54:12.084  6799  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6ff9cf removed from the list
,08-29 09:54:12.084  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 09:54:12.084  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 09:54:12.094  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 09:54:12.094  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:54:12.094  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 09:54:12.094  6799  6965 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 09:54:12.094  1016  3766 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-29 09:54:12.094  1016  3766 D SecContentProvider2: mCursor = null
,08-29 09:54:12.094  1016  1470 D SecContentProvider2: uri = 15 selection = getToastGravity
08-29 09:54:12.094  1016  1470 D SecContentProvider2: mCursor = null
,08-29 09:54:12.094  1016  7717 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 09:54:12.094  1016  1474 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-29 09:54:12.094  1016  1474 D SecContentProvider2: mCursor = null
,08-29 09:54:12.094  1016  1335 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-29 09:54:12.094  1016  1335 D SecContentProvider2: mCursor = null
,08-29 09:54:12.094  6799  7757 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1373, name: My test thread name)
,08-29 09:54:12.094  6799  7757 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1373, thread name: My test thread name)
08-29 09:54:12.094  6799  7757 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1373, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 09:54:12.104  1016  1029 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-29 09:54:12.104  1016  1029 D SecContentProvider2: mCursor = null
08-29 09:54:12.104  6799  7758 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1375, name: My test thread name)
,08-29 09:54:12.104  6799  7758 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1375, thread name: My test thread name)
08-29 09:54:12.104  6799  7758 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1375, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-29 09:54:12.104  1016  1343 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-29 09:54:12.104  1016  1343 D SecContentProvider2: mCursor = null
,08-29 09:54:12.104  6799  6965 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 09:54:12.104  6799  6965 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 09:54:12.104  6799  6965 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 09:54:12.104  6799  6965 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 09:54:12.104  6799  6965 D com.test.thalitest.ThaliTestRunner: Total duration: 23368 ms
,08-29 09:54:12.104  6799  6965 I jxcore-log: Total number of executed tests:  80
08-29 09:54:12.104  6799  6965 I jxcore-log: 
08-29 09:54:12.104  6799  6965 I jxcore-log: Number of passed tests:  80
08-29 09:54:12.104  6799  6965 I jxcore-log: 
08-29 09:54:12.104  6799  6965 I jxcore-log: Number of failed tests:  0
08-29 09:54:12.104  6799  6965 I jxcore-log: 
08-29 09:54:12.104  6799  6965 I jxcore-log: Number of ignored tests:  0
08-29 09:54:12.104  6799  6965 I jxcore-log: 
,08-29 09:54:12.104  6799  6965 I jxcore-log: Total duration:  23368
,08-29 09:54:12.104  6799  6965 I jxcore-log: 
08-29 09:54:12.104  6799  6965 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 09:54:12.104  6799  6965 I jxcore-log: 
08-29 09:54:12.114  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.114  6799  6965 I jxcore-log: 
,08-29 09:54:12.114  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.114  6799  6965 I jxcore-log: 
08-29 09:54:12.114  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.114  6799  6965 I jxcore-log: 
08-29 09:54:12.114  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.114  6799  6965 I jxcore-log: 
08-29 09:54:12.114  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.114  6799  6965 I jxcore-log: 
08-29 09:54:12.114  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.114  6799  6965 I jxcore-log: 
08-29 09:54:12.114  6799  6799 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.124  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.124  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
,08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
08-29 09:54:12.134  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.134  6799  6965 I jxcore-log: 
,08-29 09:54:12.144  1016  1028 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,08-29 09:54:12.144  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 09:54:12.194  6799  6799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-29 09:54:12.194  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-29 09:54:12.194  6799  6965 I jxcore-log: 
,08-29 09:54:12.254  1016  7717 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 07:54:12 GMT], X-Android-Received-Millis=[1472457252264], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472457252228]},
08-29 09:54:12.254  1016  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-29 09:54:12.254  1016  7717 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 09:54:12.254  1016  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504],
08-29 09:54:12.254  1016  7717 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 09:54:12.254  1016  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-29 09:54:12.254  1016  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-29 09:54:12.254  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
08-29 09:54:12.254  1175  1734 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 09:54:12.254  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
,08-29 09:54:12.254  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: updateDataNetType()
,08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-29 09:54:12.264  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 17 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 09:54:12.264  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 09:54:12.264  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 09:54:12.334  6799  6799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:54:12.344  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:54:12.344  6799  6965 I jxcore-log: 
,08-29 09:54:12.404  7760  7760 D AndroidRuntime: ,
08-29 09:54:12.404  7760  7760 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 09:54:12.414  7760  7760 D AndroidRuntime: CheckJNI is OFF,
08-29 09:54:12.414  7760  7760 D AndroidRuntime: readGMSProperty: start
08-29 09:54:12.414  7760  7760 D AndroidRuntime: readGMSProperty: already setted!!,
08-29 09:54:12.414  7760  7760 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 09:54:12.414  7760  7760 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 09:54:12.414  7760  7760 D AndroidRuntime: readGMSProperty: end
08-29 09:54:12.414  7760  7760 D AndroidRuntime: addProductProperty: start
,08-29 09:54:12.534  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-29 09:54:12.544  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,08-29 09:54:12.564  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 09:54:12.564  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:12.564  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:12.564  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:12.564  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
,08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:54:12.574  7760  7760 E AffinityControl: AffinityControl: registerfunction enter,
,08-29 09:54:12.574  6799  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:54:12.574  6799  6799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 09:54:12.574  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:54:12.574  6799  6965 I jxcore-log: 
08-29 09:54:12.574  6799  6965 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:54:12.574  6799  6965 I jxcore-log: 
,08-29 09:54:12.584  7768  7768 E Zygote  : MountEmulatedStorage()
,08-29 09:54:12.584  7768  7768 E Zygote  : v2
08-29 09:54:12.584  7768  7768 I libpersona: KNOX_SDCARD checking this for 1000
,08-29 09:54:12.584  7768  7768 I libpersona: KNOX_SDCARD not a persona
,08-29 09:54:12.584  1016  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 09:54:12.584  7768  7768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 09:54:12.594  7768  7768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 09:54:12.594  7768  7768 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:54:12.604  7760  7760 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 09:54:12.624  1016  3702 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-29 09:54:12.624  1016  3702 D PackageManager: START PACKAGE DELETE: observer{135336079}
08-29 09:54:12.624  1016  3702 D PackageManager: pkg{<packageName>}
08-29 09:54:12.624  1016  3702 D PackageManager: user{0}
08-29 09:54:12.624  1016  3702 D PackageManager: caller{2000}
08-29 09:54:12.624  1016  3702 D PackageManager: flags{2}
08-29 09:54:12.624  1016  3702 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-29 09:54:12.624  1016  3702 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-29 09:54:12.624  1016  3702 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 09:54:12.624  1016  3702 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-29 09:54:12.634  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-29 09:54:12.634  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-29 09:54:12.634  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-29 09:54:12.634  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-29 09:54:12.634  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-29 09:54:12.634  7768  7768 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 09:54:12.634  7768  7768 D ActivityThread: Added TimaKeyStore provider
,08-29 09:54:12.644  1016  1056 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-29 09:54:12.664  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-29 09:54:12.664  1016  1041 I ActivityManager: Killing 6799:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-29 09:54:12.664  1016  1041 I ActivityManager:   Force finishing activity ActivityRecord{197c786b u0 com.test.thalitest/.MainActivity t163},
,08-29 09:54:12.664  7768  7768 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-29 09:54:12.664  7768  7768 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 09:54:12.664  7768  7768 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-29 09:54:12.664  1016  1041 D InputDispatcher: Focus left window: 6799
,08-29 09:54:12.674   257   435 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-29 09:54:12.674   257  1054 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-29 09:54:12.704  1016  1041 D InputDispatcher: Focused application released
,08-29 09:54:12.704  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 09:54:12.704  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 09:54:12.784  7768  7768 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 09:54:12.784  7768  7768 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 09:54:12.784  7768  7768 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-29 09:54:12.784  7768  7768 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:54:12.794  1016  3702 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-29 09:54:12.794  1016  3702 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-29 09:54:12.794  1016  3702 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-29 09:54:12.794  1016  3702 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-29 09:54:12.794  1016  3702 I ActivityManager: Killing 7267:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-29 09:54:12.794  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 09:54:12.804  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:54:12.804  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:12.804  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:12.804  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:54:12.814  7786  7786 E Zygote  : MountEmulatedStorage(),
08-29 09:54:12.814  7786  7786 E Zygote  : v2
08-29 09:54:12.814  7786  7786 I libpersona: KNOX_SDCARD checking this for 10001,
08-29 09:54:12.814  7786  7786 I libpersona: KNOX_SDCARD not a persona
08-29 09:54:12.814  7786  7786 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 09:54:12.814  7786  7786 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:54:12.814  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7786 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:54:12.814  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed,
,08-29 09:54:12.824  7786  7786 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:54:12.824  1016  1056 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 09:54:12.834  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-29 09:54:12.864  2830  2830 I art     : Explicit concurrent mark sweep GC freed 16599(991KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 800us total 39.801ms
,08-29 09:54:12.874  1016  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 09:54:12.874  7786  7786 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 09:54:12.874  7786  7786 D ActivityThread: Added TimaKeyStore provider,
,08-29 09:54:12.884  1887  1887 E SamsungIME: mOCRHelper is null
,08-29 09:54:12.884  1611  1866 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 09:54:12.904  1450  1450 D PersonaManager: isKioskContainerExistOnDevice
,08-29 09:54:12.904  1016  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-29 09:54:12.904  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:12.904  1016  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-29 09:54:12.914  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 09:54:12.914  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:54:12.914  1016  1125 V NetworkStats: performPollLocked() took 11ms
08-29 09:54:12.914  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:12.924  1450  1450 D RegisteredServicesCache: empty dynamic service
,08-29 09:54:12.954  1450  1450 D RegisteredComponentCache: Collect Tech packages for Knox
,08-29 09:54:12.954  1450  1450 D PersonaManager: isKioskContainerExistOnDevice
,08-29 09:54:12.984  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:12.984  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:12.984  1016  1470 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 09:54:12.984  1016  1470 D SecContentProvider2: mCursor = null
,08-29 09:54:13.004  1016  1470 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-29 09:54:13.014  1016  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:13.014  1016  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:13.014  1016  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:13.014  1016  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:54:13.024  7804  7804 E Zygote  : MountEmulatedStorage(),
,08-29 09:54:13.024  7804  7804 E Zygote  : v2
08-29 09:54:13.024  7804  7804 I libpersona: KNOX_SDCARD checking this for 1000
08-29 09:54:13.024  7804  7804 I libpersona: KNOX_SDCARD not a persona
08-29 09:54:13.024  7804  7804 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:54:13.024  1016  1470 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7804 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-29 09:54:13.024  7804  7804 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:54:13.034  7804  7804 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 09:54:13.034  1016  1470 I ActivityManager: Killing 7282:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 09:54:13.034  1016  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 09:54:13.034  1016  1130 V NetworkStats: updateIfacesLocked()
08-29 09:54:13.034  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:13.034  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
,08-29 09:54:13.034  1016  1016 I art     : Explicit concurrent mark sweep GC freed 64702(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 2.797ms total 204.100ms
,08-29 09:54:13.034  1016  1056 I art     : WaitForGcToComplete blocked for 146.307ms for cause Explicit
,08-29 09:54:13.044  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 09:54:13.044  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 09:54:13.044  1016  1130 V NetworkStats: performPollLocked() took 10ms
08-29 09:54:13.044  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:13.044  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 09:54:13.044  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 09:54:13.054  1016  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-29 09:54:13.054  1016  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-29 09:54:13.054  1175  1734 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 09:54:13.054  1016  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-29 09:54:13.054  1175  1734 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 09:54:13.064  7804  7804 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:54:13.064  7804  7804 D ActivityThread: Added TimaKeyStore provider
,08-29 09:54:13.094  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-29 09:54:13.094  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-29 09:54:13.094  1016  1040 W TextServicesManagerService: no available spell checker services found
,08-29 09:54:13.094  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-29 09:54:13.094  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-29 09:54:13.104  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-29 09:54:13.104  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-29 09:54:13.104  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-29 09:54:13.104  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.104  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,08-29 09:54:13.104  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.114  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-29 09:54:13.124  7804  7804 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 09:54:13.134  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.144  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.224  1016  1056 I art     : Explicit concurrent mark sweep GC freed 14396(731KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 3.053ms total 182.913ms
,08-29 09:54:13.234  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-29 09:54:13.254  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.264  7804  7804 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-29 09:54:13.274  7804  7804 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
08-29 09:54:13.274  7804  7804 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-29 09:54:13.274  7804  7804 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 09:54:13.274  7804  7804 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-29 09:54:13.274  7804  7804 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
08-29 09:54:13.284  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.284  1016  1056 D PackageManager: delete codoeFile: 
,08-29 09:54:13.294  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-29 09:54:13.294  1016  1056 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-29 09:54:13.294  1016  1056 D PackageManager: result of delete: 1{135336079}
,08-29 09:54:13.294  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.304  7760  7760 D AndroidRuntime: Shutting down VM
,08-29 09:54:13.324  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 09:54:13.324  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 09:54:13.324  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 09:54:13.324  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.344  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.344  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-29 09:54:13.344  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicy: uID is 10170
08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 09:54:13.344  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.344  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 09:54:13.344  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 09:54:13.344  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 09:54:13.344  1016  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
08-29 09:54:13.344  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-29 09:54:13.344  1016  3363 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicy: uID is 10170
,08-29 09:54:13.344  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 09:54:13.354  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-29 09:54:13.354  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 09:54:13.354  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 09:54:13.354  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-29 09:54:13.354  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 09:54:13.354  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 09:54:13.354  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 09:54:13.354  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 09:54:13.354  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 09:54:13.354  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 09:54:13.354  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 09:54:13.354  1016  1016 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-29 09:54:13.354  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-29 09:54:13.354  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-29 09:54:13.374  1016  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-29 09:54:13.374  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 09:54:13.374  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-29 09:54:13.374  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:13.374  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-29 09:54:13.394  1016  1029 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7820 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 09:54:13.404  7820  7820 E Zygote  : MountEmulatedStorage()
,08-29 09:54:13.404  7820  7820 E Zygote  : v2
08-29 09:54:13.404  7820  7820 I libpersona: KNOX_SDCARD checking this for 10008
08-29 09:54:13.404  7820  7820 I libpersona: KNOX_SDCARD not a persona
,08-29 09:54:13.404  7820  7820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:54:13.404  7820  7820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:54:13.404  7820  7820 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-29 09:54:13.414   321   321 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 712us total 23.117ms,
,08-29 09:54:13.424  7820  7820 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:54:13.424  7820  7820 D ActivityThread: Added TimaKeyStore provider
,08-29 09:54:13.434   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 16.585ms
,08-29 09:54:13.454   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.404ms
,08-29 09:54:13.494  1016  1028 I ActivityManager: Killing 7324:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-29 09:54:13.504  7820  7820 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-29 09:54:13.514  7760  7760 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 09:54:13.514  7820  7820 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-29 09:54:13.514  7820  7820 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-29 09:54:13.524  7820  7820 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
08-29 09:54:13.524  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-29 09:54:13.524  1016  1056 D PackageManager: userId{-1}
08-29 09:54:13.524  1016  1056 D PackageManager: andCode{true}
,08-29 09:54:13.534  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-29 09:54:13.534  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:13.534  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:13.534  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 09:54:13.534  1016  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 09:54:13.554  7840  7840 E Zygote  : MountEmulatedStorage()
08-29 09:54:13.554  7840  7840 I libpersona: KNOX_SDCARD checking this for 10003
08-29 09:54:13.554  7840  7840 E Zygote  : v2
08-29 09:54:13.554  7840  7840 I libpersona: KNOX_SDCARD not a persona
08-29 09:54:13.554  1016  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7840 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 09:54:13.554  7840  7840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 09:54:13.554  7840  7840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 09:54:13.564  7840  7840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 09:54:13.574  1016  1328 I ActivityManager: Killing 7340:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-29 09:54:13.584  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-29 09:54:13.584  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 09:54:13.584  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 09:54:13.584  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 09:54:13.584  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 09:54:13.594  7840  7840 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 09:54:13.594  7840  7840 D ActivityThread: Added TimaKeyStore provider
,08-29 09:54:13.604   282   998 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 09:54:13.604   282   998 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-29 09:54:13.624  3210  3284 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,08-29 09:54:13.664  7297  7297 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,08-29 09:54:13.674  1016  3702 F PackageManager: Package Manager Crash
08-29 09:54:13.674  1016  3702 F PackageManager: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
08-29 09:54:13.674  1016  3702 F PackageManager: 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1668)
08-29 09:54:13.674  1016  3702 F PackageManager: 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:17239)
08-29 09:54:13.674  1016  3702 F PackageManager: 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:17084)
08-29 09:54:13.674  1016  3702 F PackageManager: 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1446)
08-29 09:54:13.674  1016  3702 F PackageManager: 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:3005)
08-29 09:54:13.674  1016  3702 F PackageManager: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 09:54:13.684  7297  7297 D AndroidRuntime: Shutting down VM
,08-29 09:54:13.684  7297  7297 E AndroidRuntime: FATAL EXCEPTION: main
08-29 09:54:13.684  7297  7297 E AndroidRuntime: Process: com.google.android.gms, PID: 7297
08-29 09:54:13.684  7297  7297 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.mdm.receivers.ConnectivityReceiver: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1546)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1493)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.content.pm.IPackageManager$Stub$Proxy.setComponentEnabledSetting(IPackageManager.java:4162)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.app.ApplicationPackageManager.setComponentEnabledSetting(ApplicationPackageManager.java:1905)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at com.google.android.gms.common.util.e.a(SourceFile:715)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at com.google.android.gms.common.util.e.a(SourceFile:723)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at com.google.android.gms.mdm.services.SitrepService.a(SourceFile:74)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at com.google.android.gms.mdm.services.SitrepService.a(SourceFile:56)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at com.google.android.gms.mdm.receivers.ConnectivityReceiver.onReceive(SourceFile:18)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-29 09:54:13.684  7297  7297 E AndroidRuntime: 	... 9 more
,08-29 09:54:13.684  1016  1041 E DropBoxManagerService: Can't write: system_server_wtf
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop29.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15787)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:15600)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15572)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 09:54:13.684  1016  1041 E DropBoxManagerService: 	... 13 more
,08-29 09:54:13.684  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,08-29 09:54:13.694  1016  7860 E DropBoxManagerService: Can't write: system_app_crash
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 09:54:13.694  1016  7860 E DropBoxManagerService: 	... 5 more
,08-29 09:54:13.694  7297  7297 I Process : Sending signal. PID: 7297 SIG: 9

```
