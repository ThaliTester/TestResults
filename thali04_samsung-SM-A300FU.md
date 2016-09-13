#### Test 85019474526c333_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
09-13 12:25:06.874  6702  6702 D CscParser: getInstance fileName =/system/csc/customer.xml
09-13 12:25:06.874  6702  6702 D Mms/MmsConfig:  enable multiwindow = false
09-13 12:25:06.884  6702  6702 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-13 12:25:06.884  6702  6702 E Mms/MessageUtils: updateCountryIso : update country iso info 
09-13 12:25:06.894  6702  6702 D Mms/MmsConfig: [end]    init() consume time = 134.720781
09-13 12:25:06.894  6702  6702 D Mms/Contact: [start]    init() consume time = 0.710156
09-13 12:25:06.894  6786  6786 E SQLiteLog: (284) automatic index on titles(filter_id)
09-13 12:25:06.894  6597  6701 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-13 12:25:06.904   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
09-13 12:25:06.914  1457  1467 D TP/MmsSmsProvider: query,matched:13, calling pid = 6702
09-13 12:25:06.914  6702  6702 D Mms/Contact: [end]    init consume time = 21.920208
09-13 12:25:06.914  1457  1467 D TP/MmsSmsProvider: match 13:Elapsed time : 1.220 ms
09-13 12:25:06.914  6786  6794 E SQLiteLog: (284) automatic index on titles(filter_id)
--------- beginning of system
09-13 12:25:06.914   979  1466 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
09-13 12:25:06.914   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:06.914   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:06.914   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:06.914   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:06.924  6702  6822 D Mms/DraftCache: [start]    rebuildCache consume time = 12.228386
09-13 12:25:06.934  6823  6823 E Zygote  : MountEmulatedStorage()
09-13 12:25:06.934  6823  6823 E Zygote  : v2
09-13 12:25:06.934  6823  6823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:06.934  6823  6823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:06.934  6823  6823 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:06.934  6823  6823 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:06.944  6823  6823 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:25:06.944  6665  6665 I Finsky  : [1] com.google.android.finsky.services.bd.a(1075): Restore complete with 0 success and 0 failed.
09-13 12:25:06.944   979  1466 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 12:25:06.954  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 12:25:06.954   979  1466 I ActivityManager: Killing 5890:com.google.android.talk/u0a102 (adj 15): empty #21
09-13 12:25:06.954   979  1010 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 12:25:06.954   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-13 12:25:06.964   979  1137 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:06.964   979  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:06.964   979  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 12:25:06.964   979  1137 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-13 12:25:06.964   979  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-13 12:25:06.974  1457  1475 D TP/MmsSmsProvider: query,matched:12, calling pid = 6702
09-13 12:25:06.974  1457  1475 D TP/MmsSmsProvider: match 12:Elapsed time : 1.476 ms
,09-13 12:25:06.974  6702  6702 D Mms/MethodReflector: getSubId is called
09-13 12:25:06.974  6702  6702 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 12:25:06.974  6823  6823 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:06.974  6823  6823 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:06.974  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 12:25:06.974  6702  6702 D Mms/MethodReflector: getTelephonyProperty is called
09-13 12:25:06.974  6702  6702 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 12:25:06.974  6702  6702 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 12:25:06.974  6702  6702 D Mms/DownloadManager: auto download without roaming -> true
09-13 12:25:06.974  6702  6702 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 12:25:06.974  6702  6702 D Mms/MethodReflector: getSubId is called
09-13 12:25:06.984  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 12:25:06.984  6702  6702 D Mms/MethodReflector: getDefaultSmsSubId is called
09-13 12:25:06.984  6702  6702 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-13 12:25:06.984  6702  6702 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-13 12:25:06.984  6702  6702 D Mms/MethodReflector: getTelephonyProperty is called
09-13 12:25:06.984  6702  6702 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-13 12:25:06.984  6702  6702 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 12:25:06.984  6702  6702 D Mms/DownloadManager: auto download without roaming -> true
09-13 12:25:06.984  6702  6702 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 12:25:06.984  6702  6702 D Mms/DownloadManager: auto download during roaming secondary -> false
09-13 12:25:06.984  6702  6702 D Mms/DownloadManager: mAutoDownload ------> true
09-13 12:25:06.984  6665  6665 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
09-13 12:25:06.984  6665  6665 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
09-13 12:25:07.004  6597  6701 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-13 12:25:07.004  6597  6701 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37d94f32: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-13 12:25:07.004  6597  6701 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-13 12:25:07.014  6702  6822 D Mms/DraftCache: [end]    rebuildCache consume time = 90.28875
09-13 12:25:07.024   979  1501 I ActivityManager: Killing 6489:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #21
09-13 12:25:07.034   979  1348 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 12:25:07.044   979  1348 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:07.044   979  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:07.044   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 12:25:07.054  6702  6702 D ComposerPerformance: 1473762307059 ms / [DONE] Composer constructor
09-13 12:25:07.054  6702  6702 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
09-13 12:25:07.054  6702  6702 I Mms/ReservationManager: ReservationManager()
09-13 12:25:07.054  6702  6702 I Mms/ReservationManager: resetAfterConnected()
09-13 12:25:07.054  6823  6823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
09-13 12:25:07.064  1457  1857 D TP/MmsSmsProvider: query,matched:7, calling pid = 6702
09-13 12:25:07.064   979  1479 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-13 12:25:07.064   979  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
09-13 12:25:07.064  1457  1857 D TP/MmsSmsProvider: match 7:Elapsed time : 1.621 ms
09-13 12:25:07.064   979  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:07.064   979  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:07.064   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
09-13 12:25:07.064  6746  6768 I FilterUnInstaller: FilterUninstaller.java : removeFromDB()
09-13 12:25:07.064  6702  6845 D Mms/Conversation: [start]    init() consume time = 51.814792
09-13 12:25:07.074   979  1472 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
09-13 12:25:07.074  6702  6748 D Mms/ArtClassLoader: init [DONE] art
09-13 12:25:07.074   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.074   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.074   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.074   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.104  6848  6848 E Zygote  : MountEmulatedStorage()
09-13 12:25:07.104  6848  6848 E Zygote  : v2
09-13 12:25:07.104  6848  6848 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:07.104  6848  6848 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:07.104  6848  6848 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:07.104   979  1472 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6848 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 12:25:07.104  6848  6848 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:07.104  6848  6848 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:25:07.104  6702  6702 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
09-13 12:25:07.114  1457  1653 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
09-13 12:25:07.114  1457  1653 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 12:25:07.114  1457  1653 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
09-13 12:25:07.114  6702  6702 D Mms/MmsApp: [end]    onCreate() consume time = 45.739739
09-13 12:25:07.114  1457  1653 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
09-13 12:25:07.114  6702  6702 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
09-13 12:25:07.114  6786  6794 D FilterProvider: delete when PACKAGE_NAME : 2002 
09-13 12:25:07.114  6786  6794 D FilterProvider: packageName : com.test.thalitest
09-13 12:25:07.124   979  1007 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-13 12:25:07.124   979  1007 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-13 12:25:07.124   979  1007 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:07.124   979  1007 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:07.124   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-13 12:25:07.124  6848  6848 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:07.124  1457  1653 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-13 12:25:07.124  1457  1653 D TP/MmsSmsProvider: need read changed broadcast:false
09-13 12:25:07.124  6848  6848 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:07.144  6702  6702 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
09-13 12:25:07.144  6702  6702 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
09-13 12:25:07.144  6702  6845 D Mms/Conversation: [end]    init consume time = 30.25974
09-13 12:25:07.144  6702  6845 D Mms/MessagingNotification: [start]    init() consume time = 2.748385
09-13 12:25:07.154  6702  6702 D Mms/MethodReflector: getSubId is called
09-13 12:25:07.154  6702  6702 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 12:25:07.154  6702  6702 D Mms/MethodReflector: getTelephonyProperty is called
09-13 12:25:07.154  6702  6702 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 12:25:07.154  6702  6702 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 12:25:07.154   979  1007 I ActivityManager: Killing 6289:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-13 12:25:07.154  6702  6702 D Mms/DownloadManager: auto download without roaming -> true
09-13 12:25:07.154  6702  6702 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 12:25:07.154  6702  6702 D Mms/DownloadManager: mAutoDownload ------> true
09-13 12:25:07.154  6746  6768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
09-13 12:25:07.154  6702  6863 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
09-13 12:25:07.154  6702  6863 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
09-13 12:25:07.244  6843  6843 D AndroidRuntime: 
09-13 12:25:07.244  6843  6843 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 12:25:07.254  6843  6843 D AndroidRuntime: CheckJNI is OFF
09-13 12:25:07.254  6843  6843 D AndroidRuntime: readGMSProperty: start
09-13 12:25:07.254  6843  6843 D AndroidRuntime: readGMSProperty: already setted!!
09-13 12:25:07.254  6843  6843 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 12:25:07.254  6843  6843 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 12:25:07.254  6843  6843 D AndroidRuntime: readGMSProperty: end
09-13 12:25:07.254  6843  6843 D AndroidRuntime: addProductProperty: start
09-13 12:25:07.314   979  1479 I art     : Explicit concurrent mark sweep GC freed 144486(8MB) AllocSpace objects, 6(1937KB) LOS objects, 33% free, 24MB/36MB, paused 2.598ms total 182.762ms
09-13 12:25:07.314   979  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 12:25:07.314   979  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:07.314   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:07.314   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
09-13 12:25:07.324   979  1481 I ActivityManager: Killing 6461:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-13 12:25:07.324  6702  6845 D Mms/MessagingNotification: [end]    init consume time = 180.805833
09-13 12:25:07.334  6702  6871 D Mms/Synchronizer: [start]    doSync consume time = 9.330886
09-13 12:25:07.344   979  1479 I ActivityManager: Killing 6123:com.sec.pcw.device/1000 (adj 15): empty #21
09-13 12:25:07.344  1457  1653 D TP/MmsSmsProvider: query,matched:0, calling pid = 6702
09-13 12:25:07.344  1457  1653 V TP/MmsSmsProvider: getSimpleConversations entered.
09-13 12:25:07.344  6702  6870 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 7.962708
09-13 12:25:07.344  1457  1475 D TP/MmsSmsProvider: update, matched:300, calling pid = 6702
09-13 12:25:07.344  1457  1653 D TP/MmsSmsProvider: match 0:Elapsed time : 0.978 ms
09-13 12:25:07.344  1457  1475 V TP/MmsSmsProvider: syncDBData start
09-13 12:25:07.344  1457  1475 V TP/MmsSmsProvider: syncDBData sms end
09-13 12:25:07.344   979  1748 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
09-13 12:25:07.344  1457  1475 V TP/MmsSmsProvider: syncDBData mms end
09-13 12:25:07.354  1457  1475 V TP/MmsSmsProvider: syncDBData end
09-13 12:25:07.354   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.354   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.354   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.354   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.354  1457  1857 D TP/MmsSmsProvider: query,matched:400, calling pid = 6702
09-13 12:25:07.354  6848  6872 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
09-13 12:25:07.354  6848  6872 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-13 12:25:07.364  6873  6873 E Zygote  : MountEmulatedStorage()
09-13 12:25:07.364  6873  6873 E Zygote  : v2
09-13 12:25:07.364  6873  6873 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:07.364  6873  6873 I libpersona: KNOX_SDCARD checking this for 10117
09-13 12:25:07.364  6873  6873 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:07.364   979  1748 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6873 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-13 12:25:07.364   979  1748 I ActivityManager: Killing 6033:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
09-13 12:25:07.374   979  1481 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-13 12:25:07.374   979  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-13 12:25:07.374  6873  6873 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:07.374  6873  6873 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 12:25:07.374  6702  6871 D Mms/Synchronizer: [end]    doSync consume time = 29.237344
09-13 12:25:07.374   979  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:07.374   979  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:07.374   979  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-13 12:25:07.384   979  1472 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
09-13 12:25:07.384  6848  6848 D AcmsService: Enter Oncreate
09-13 12:25:07.384   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.384  6848  6848 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 12:25:07.384   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.384  6848  6848 D AcmsService: creating AcmsCore
09-13 12:25:07.384   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.384  6848  6848 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-13 12:25:07.384   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.384  6848  6848 D AcmsCore: AcmsCore
09-13 12:25:07.394  6848  6848 D AcmsCore: init
09-13 12:25:07.394  6848  6848 D AcmsCore: Looper handler is not null
09-13 12:25:07.394  6848  6848 D AcmsCore: Post to AcmsCoreHandler
09-13 12:25:07.394  6848  6848 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 12:25:07.394  6848  6848 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-13 12:25:07.394  6848  6848 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-13 12:25:07.394  6848  6848 D AcmsService: onStartCommand
09-13 12:25:07.394  6848  6848 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-13 12:25:07.394  6848  6848 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-13 12:25:07.394  6848  6848 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-13 12:25:07.394  6848  6848 D AcmsService: Incremented Counter Value : onStartCommand
09-13 12:25:07.404  6843  6843 E AffinityControl: AffinityControl: registerfunction enter
09-13 12:25:07.404  6848  6881 D AcmsCertificateMngr: AcmsCertificateMngr
09-13 12:25:07.424  6848  6881 D AcmsRevocationMngr: AcmsRevocationMngr
09-13 12:25:07.424  6873  6873 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:07.424  6873  6873 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:07.434  6843  6843 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 12:25:07.434  6890  6890 E Zygote  : MountEmulatedStorage()
09-13 12:25:07.434  6890  6890 I libpersona: KNOX_SDCARD checking this for 10068
09-13 12:25:07.434  6890  6890 E Zygote  : v2
09-13 12:25:07.434  6890  6890 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:07.434  6890  6890 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:07.434   979  1472 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6890 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-13 12:25:07.434  6890  6890 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:07.444  6702  6870 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 65.164427
09-13 12:25:07.444  6890  6890 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 12:25:07.454   979  1483 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 12:25:07.454   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-13 12:25:07.454   979  1466 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-13 12:25:07.454  6848  6848 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-13 12:25:07.464  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 12:25:07.464   979  1479 E PersonaManagerService: inState():  stateMachine is null !!
09-13 12:25:07.464  6873  6873 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:07.464   979  1479 I PersonaManagerService: PersonaId don't exist
09-13 12:25:07.464   979  1479 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-13 12:25:07.474   979  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 12:25:07.484  6890  6890 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:07.484  6890  6890 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:07.494  6848  6848 D AcmsService: Inside handle Intent
09-13 12:25:07.494  6848  6848 D AcmsService: App removed - package name: com.test.thalitest
09-13 12:25:07.494  6848  6848 D AcmsCore: Post to AcmsCoreHandler
09-13 12:25:07.494  6848  6848 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 12:25:07.494  6848  6848 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-13 12:25:07.494  6848  6848 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
09-13 12:25:07.494  6848  6848 D AcmsService: Decremented Counter Value : handleStartIntent
09-13 12:25:07.494  6848  6848 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-13 12:25:07.504   979  1479 W ActivityManager: mDVFSHelper.acquire()
09-13 12:25:07.504   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-13 12:25:07.514   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-13 12:25:07.524   979  1479 D FocusedStackFrame: Set to : 0
09-13 12:25:07.534   979  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-13 12:25:07.534   979  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-13 12:25:07.544   979  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.544   979  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.544   979  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.544   979  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.544   979  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-13 12:25:07.544   979  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-13 12:25:07.544   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-13 12:25:07.554  6910  6910 E Zygote  : MountEmulatedStorage()
09-13 12:25:07.554  6910  6910 E Zygote  : v2
09-13 12:25:07.554  6910  6910 I libpersona: KNOX_SDCARD checking this for 10171
09-13 12:25:07.554  6910  6910 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:07.554  6910  6910 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:07.554   979  1479 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6910 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 12:25:07.554   979  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-13 12:25:07.554   979  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 12:25:07.554  6910  6910 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:07.554  6910  6910 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-13 12:25:07.564   979  1479 D InputDispatcher: Focused application set to: xxxx
09-13 12:25:07.564   979  1479 D InputDispatcher: Focus left window: 1484
09-13 12:25:07.564  6843  6843 D AndroidRuntime: Shutting down VM
09-13 12:25:07.594   979  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 12:25:07.594   979  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 12:25:07.604  6910  6910 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:07.604  6910  6910 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:07.604   979  1322 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-13 12:25:07.604   979   979 V ActivityManager: Display changed displayId=0
09-13 12:25:07.614   979  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 12:25:07.624  6890  6890 D BadgeProvider: onCreate
09-13 12:25:07.624  6890  6890 D BadgeProvider: DatabaseHelper
09-13 12:25:07.644   979  1322 D PersonaManager: isKioskContainerExistOnDevice
09-13 12:25:07.654   259   453 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-13 12:25:07.654   259  1156 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-13 12:25:07.654   979  1007 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 12:25:07.664  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{37e84028 token=android.os.BinderProxy@147dd52 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 12:25:07.664   979  1007 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:07.664   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:07.664   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
09-13 12:25:07.674  1484  1484 D Launcher: onTrimMemory. Level: 20
09-13 12:25:07.684   979   979 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-13 12:25:07.704   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 12:25:07.704   279   966 D Netd    : getNetworkForDns: using netid 502 for uid 10026
09-13 12:25:07.704  6702  6845 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
09-13 12:25:07.714  1457  1467 D TP/SmsProvider: query,matched:26, calling pid = 6702
09-13 12:25:07.714  1457  1467 D TP/SmsProvider: match 26:Elapsed time : 1.494 ms
09-13 12:25:07.724  1457  1653 D TP/MmsSmsProvider: query,matched:6, calling pid = 6702
09-13 12:25:07.724  1457  1653 D TP/MmsSmsProvider: match 6:Elapsed time : 1.607 ms
09-13 12:25:07.774   979  1501 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
09-13 12:25:07.774  6843  6843 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-13 12:25:07.784   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.784   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.784   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.784   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:07.794  6665  6720 I qtaguid : Tagging socket 49 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 6665, getuid(): 10026
,09-13 12:25:07.804  6928  6928 E Zygote  : MountEmulatedStorage(),
,09-13 12:25:07.804  6928  6928 E Zygote  : v2
,09-13 12:25:07.804  6928  6928 I libpersona: KNOX_SDCARD checking this for 10023
09-13 12:25:07.804  6928  6928 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:07.804  6928  6928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:07.804  6928  6928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:07.804  6928  6928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:07.814   979  1501 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6928 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,09-13 12:25:07.824  6910  6910 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500),
,09-13 12:25:07.834  6928  6928 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:07.834  6928  6928 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:07.844   979  1137 I ActivityManager: Killing 6305:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-13 12:25:07.854  6910  6910 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 4911-4914)
,09-13 12:25:07.854  6910  6910 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 12:25:07.894   979  1137 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,09-13 12:25:07.894   979  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-13 12:25:07.894   979  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:07.894   979  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:07.894   979  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-13 12:25:07.894  6910  6910 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d4edbae}
,09-13 12:25:07.904  6910  6910 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 12:25:07.914  6928  6928 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-13 12:25:07.914  6910  6910 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 12:25:07.924   979  1501 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 12:25:07.924   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-13 12:25:07.924   979  1501 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:07.924   979  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:07.924   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-13 12:25:07.934  6702  6845 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
09-13 12:25:07.934   979  1010 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REMOVED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-13 12:25:07.944  1440  1440 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
09-13 12:25:07.954   979  1483 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=20, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
09-13 12:25:07.954   979  1483 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,09-13 12:25:07.964  6259  6259 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,09-13 12:25:07.974  6259  6259 I AASAservice-TokenRule: parseToken()
,09-13 12:25:07.974  6910  6910 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 12:25:07.974   979  1007 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,09-13 12:25:07.974  6910  6910 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 12:25:07.974   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.974   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.974   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.974   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:07.974  6259  6259 W System.err: java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
09-13 12:25:07.974  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,09-13 12:25:07.974  6259  6259 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,09-13 12:25:07.984  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
09-13 12:25:07.984  6259  6259 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 12:25:07.984  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,09-13 12:25:07.984  6259  6259 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-13 12:25:07.984  6259  6259 W System.err: 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:86)
09-13 12:25:07.984  6259  6259 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:55)
,09-13 12:25:07.984  6259  6259 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-13 12:25:07.984  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
09-13 12:25:07.984  6259  6259 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-13 12:25:07.984  6259  6259 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-13 12:25:07.984  6259  6259 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,09-13 12:25:07.984  6259  6259 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-13 12:25:07.984  6259  6259 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 12:25:07.984  6259  6259 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:25:07.984  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
09-13 12:25:07.984  6259  6259 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,09-13 12:25:07.984  6259  6259 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 12:25:07.984  6259  6259 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 12:25:07.984  6259  6259 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
09-13 12:25:07.984  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-13 12:25:07.984  6259  6259 W System.err: 	at libcore.io.Posix.open(Native Method)
09-13 12:25:07.984  6259  6259 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 12:25:07.984  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-13 12:25:07.984  6259  6259 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 12:25:07.984  6259  6259 W System.err: 	... 14 more
,09-13 12:25:07.984  6259  6259 E AASAservice-TokenRule: parseToken() : TokenFile is null
09-13 12:25:07.984  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
09-13 12:25:07.984  6259  6259 E AASAservice-UpdateReceiver: AASARuleUpdateResult() : Rule file is not exist.
,09-13 12:25:07.994  6951  6951 E Zygote  : MountEmulatedStorage()
09-13 12:25:07.994  6951  6951 E Zygote  : v2
09-13 12:25:07.994  6951  6951 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:07.994  6951  6951 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:07.994  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-13 12:25:07.994  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-13 12:25:07.994  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-13 12:25:07.994  6259  6259 I art     : System.exit called, status: 0
,09-13 12:25:07.994  6259  6259 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-13 12:25:07.994  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
09-13 12:25:07.994  6910  6910 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 12:25:07.994  6928  6928 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
09-13 12:25:07.994  6951  6951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:08.004   979  1007 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6951 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 12:25:08.004  6951  6951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:08.004  6951  6951 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:08.014  6702  6702 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,09-13 12:25:08.024   979  1322 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-13 12:25:08.024   979  1322 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.024   979  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-13 12:25:08.024   979  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:08.024   979  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-13 12:25:08.024  6477  6477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,09-13 12:25:08.024   979  1466 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-13 12:25:08.024   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.024   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.024   979  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:08.024  6951  6951 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:08.024   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-13 12:25:08.024  6951  6951 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:08.034   979  1472 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-13 12:25:08.034   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.034   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.034   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.034   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.034  6702  6967 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,09-13 12:25:08.034  6702  6967 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,09-13 12:25:08.044  6969  6969 E Zygote  : MountEmulatedStorage()
,09-13 12:25:08.044  6969  6969 E Zygote  : v2
09-13 12:25:08.044  6969  6969 I libpersona: KNOX_SDCARD checking this for 10042,
09-13 12:25:08.044  6969  6969 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:08.044  6969  6969 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 12:25:08.054  6969  6969 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 12:25:08.054   979  1472 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6969 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,09-13 12:25:08.064  6969  6969 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL,
,09-13 12:25:08.074  6746  6746 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-13 12:25:08.074  6746  6746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-13 12:25:08.074   979  1481 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,09-13 12:25:08.074   979  1481 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-13 12:25:08.084   979  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.084   979  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 12:25:08.084   979  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-13 12:25:08.084  2735  2735 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected,
,09-13 12:25:08.084   979  1748 I ActivityManager: Process com.samsung.aasaservice (pid 6259)(adj 0) has died(144,672)
09-13 12:25:08.084   979  1748 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,09-13 12:25:08.094  6969  6969 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:08.094  6969  6969 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:08.094   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,09-13 12:25:08.094   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.094   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.094   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.094   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.094  6746  6746 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-13 12:25:08.104  6951  6951 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,09-13 12:25:08.104  6986  6986 E Zygote  : MountEmulatedStorage()
,09-13 12:25:08.104  6986  6986 I libpersona: KNOX_SDCARD checking this for 10014
09-13 12:25:08.104  6986  6986 E Zygote  : v2
09-13 12:25:08.104  6986  6986 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:08.104  6986  6986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:08.114  6986  6986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:08.114  6986  6986 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-13 12:25:08.114   979  1043 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6986 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,09-13 12:25:08.114  6746  6982 E FilterInstaller: installFilters
09-13 12:25:08.114  6769  6769 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
09-13 12:25:08.114  6769  6769 D PackageIntentReceiver: Not GearManger package! 
,09-13 12:25:08.134  6746  6982 E FilterInstaller: There is no requred permission
,09-13 12:25:08.134  6986  6986 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:08.144   979  1348 I ActivityManager: Killing 6170:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-13 12:25:08.144  6986  6986 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:08.144  6969  6969 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:08.144  6951  6951 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.PackageEventReceiver.onReceive:182 android.app.ActivityThread.handleReceiver:3125 
09-13 12:25:08.144  6969  6969 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 12:25:08.144  6969  6969 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 12:25:08.144   979  1483 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
09-13 12:25:08.144   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
09-13 12:25:08.144   309   309 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 677us total 35.933ms
,09-13 12:25:08.154   979  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.154   979  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:08.154   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,09-13 12:25:08.154   979  1043 W ActivityManager: Activity pause timeout for ActivityRecord{238d337a u0 com.test.thalitest/.MainActivity t2}
,09-13 12:25:08.164  6848  7001 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
09-13 12:25:08.164  6848  7001 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,09-13 12:25:08.164  6910  6910 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 12:25:08.164  6910  6910 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 12:25:08.164  6910  6910 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 12:25:08.164  6910  6910 I Adreno-EGL: Local Branch: 
09-13 12:25:08.164  6910  6910 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 12:25:08.164  6910  6910 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
,09-13 12:25:08.164  6910  6910 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 12:25:08.174   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 704us total 21.885ms
,09-13 12:25:08.184   979  1137 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink,
09-13 12:25:08.184   979  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.184   979  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-13 12:25:08.184   979  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-13 12:25:08.184   979  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-13 12:25:08.194  6848  6848 D AcmsService: onStartCommand
09-13 12:25:08.194  6848  6848 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-13 12:25:08.194  6848  6848 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 2
09-13 12:25:08.194  6848  6848 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-13 12:25:08.194  6848  6848 D AcmsService: Incremented Counter Value : onStartCommand
09-13 12:25:08.194  6848  6848 D AcmsService: Inside handle Intent
09-13 12:25:08.194  6848  6848 D AcmsService: App added - package name: com.test.thalitest
09-13 12:25:08.194  6848  6848 D AcmsCore: Post to AcmsCoreHandler
09-13 12:25:08.194  6848  6848 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 12:25:08.194  6848  6848 D AcmsServiceMonitor: Incrementing - Counter value: 4
09-13 12:25:08.194  6848  6848 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-13 12:25:08.194  6848  6848 D AcmsService: Decremented Counter Value : handleStartIntent
09-13 12:25:08.194  6848  6848 D AcmsServiceMonitor: Decrementing - Counter value: 3
,09-13 12:25:08.194  6632  6632 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-13 12:25:08.194  6632  6632 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-13 12:25:08.194  6632  6632 I TapandpayWidget:Utils: Clear T&P info.
09-13 12:25:08.194  6632  6632 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-13 12:25:08.204   979  1479 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,09-13 12:25:08.204   979  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.204   979  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.204   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.204   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
09-13 12:25:08.204   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 719us total 25.539ms
,09-13 12:25:08.204   979  1466 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-13 12:25:08.204   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.204   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.204   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.204   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.204  6969  6969 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-13 12:25:08.224  6665  6720 I qtaguid : Tagging socket 53 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 6665, getuid(): 10026,
09-13 12:25:08.224  7007  7007 E Zygote  : MountEmulatedStorage()
09-13 12:25:08.224  7007  7007 I libpersona: KNOX_SDCARD checking this for 10009
09-13 12:25:08.224  7007  7007 E Zygote  : v2
09-13 12:25:08.224  7007  7007 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:08.224  7007  7007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:08.224  7007  7007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:08.224   979  1466 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7007 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-13 12:25:08.234  7007  7007 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,09-13 12:25:08.234   285   285 E installd: system dir 0 : /system/app/
09-13 12:25:08.234   285   285 E installd: system dir 1 : /system/priv-app/
09-13 12:25:08.234   285   285 E installd: system dir 2 : /vendor/app/
09-13 12:25:08.234   979  1466 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-13 12:25:08.234   285   285 E installd: system dir 3 : /oem/app/
09-13 12:25:08.234   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.244   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.244   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.244   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-13 12:25:08.254   979  1348 I TactileAssist: enable value -1
09-13 12:25:08.254   979  1348 I TactileAssist: internal enable value -1
09-13 12:25:08.254   979  1348 I TactileAssist: intensity value -1
09-13 12:25:08.254   979  1348 I TactileAssist: saveAppList value true
,09-13 12:25:08.254   979  1348 I TactileAssist: List of disabled apps :
,09-13 12:25:08.274   979  1748 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,09-13 12:25:08.274   979  1748 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.274   979  1748 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.274   979  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.274   979  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
09-13 12:25:08.274  7007  7007 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:08.274  7007  7007 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:08.284   979  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-13 12:25:08.294   979  1137 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-13 12:25:08.294   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.294   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.294   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.294   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.314  7028  7028 E Zygote  : MountEmulatedStorage()
09-13 12:25:08.314  7028  7028 E Zygote  : v2
09-13 12:25:08.314  7028  7028 I libpersona: KNOX_SDCARD checking this for 10048
09-13 12:25:08.314  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:08.314  7028  7028 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:08.324  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 12:25:08.324  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 12:25:08.324   979  1137 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7028 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,09-13 12:25:08.334   979  1007 I ActivityManager: Killing 6511:com.sec.android.app.themechooser/u0a145 (adj 15): empty #21
,09-13 12:25:08.334  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:08.334  7028  7028 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:08.354   979  1479 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-13 12:25:08.354   979  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.354   979  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.354   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:08.354   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,09-13 12:25:08.364  7028  7028 D Compatibility: onReceive() it will make start service
,09-13 12:25:08.364   979  1322 I ActivityManager: Killing 6526:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-13 12:25:08.364   979  1466 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-13 12:25:08.364   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-13 12:25:08.374   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.374   979  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:08.374   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-13 12:25:08.374   979  1322 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-13 12:25:08.374   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.374   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.374   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.374   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.384  7057  7057 E Zygote  : MountEmulatedStorage()
09-13 12:25:08.384  7057  7057 E Zygote  : v2
09-13 12:25:08.384  7057  7057 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:08.384  7057  7057 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:08.384  7057  7057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:08.394   979  1322 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7057 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-13 12:25:08.394  7057  7057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:08.394   979  1322 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,09-13 12:25:08.394   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.394   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.394  7057  7057 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:25:08.394   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.394  7028  7056 D Compatibility: onHandleIntent()
09-13 12:25:08.394   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.394  7028  7056 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
09-13 12:25:08.404  6910  6910 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 12:25:08.414  7028  7056 D Compatibility: found: 2
09-13 12:25:08.414  6910  6910 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 12:25:08.414  6910  6910 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 12:25:08.424  7028  7056 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity,
,09-13 12:25:08.424  6910  6910 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-13 12:25:08.424  6910  6910 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 12:25:08.424  7028  7056 D Compatibility: skipping ResolveInfo{3a7da944 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,09-13 12:25:08.424  7028  7056 D Compatibility: considering ResolveInfo{1fabfa2d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-13 12:25:08.424  7028  7056 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 12:25:08.434  7072  7072 E Zygote  : MountEmulatedStorage()
,09-13 12:25:08.434  7072  7072 E Zygote  : v2
09-13 12:25:08.434  7072  7072 I libpersona: KNOX_SDCARD checking this for 10052
09-13 12:25:08.434  7072  7072 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:08.434  7072  7072 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:08.434   979  1322 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7072 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-13 12:25:08.434  7072  7072 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:08.434  7072  7072 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 12:25:08.444  7028  7056 D Compatibility: enabling receiver ResolveInfo{e416b62 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 12:25:08.444  7057  7057 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:08.444  7057  7057 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:08.454  7028  7056 D Compatibility: enabling receiver ResolveInfo{305ec4f3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 12:25:08.484  7072  7072 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:08.484  7072  7072 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:08.484  7028  7056 D Compatibility: enabling receiver ResolveInfo{3f4e15b0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 12:25:08.484   979  1748 I ActivityManager: Killing 6541:com.sec.knox.bridge/1000 (adj 15): empty #21
,09-13 12:25:08.484   979  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:08.484   979  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.484   979  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.484   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.484   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.494  4690  6673 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 12:25:08.494  7028  7056 D Compatibility: enabling receiver ResolveInfo{34fb0c29 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 12:25:08.494  4690  6657 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,09-13 12:25:08.504  7028  7056 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-13 12:25:08.514  7057  7057 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-13 12:25:08.514  7057  7057 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-13 12:25:08.514  7057  7057 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-13 12:25:08.514  4690  6673 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 12:25:08.514   979  1348 I ActivityManager: Killing 6554:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #21
,09-13 12:25:08.514   979  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:08.514   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.514   979  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.514   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.514   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.524  4690  4690 D AsyncTaskServiceImpl: Submit a task: nzm
,09-13 12:25:08.524   979  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:08.524   979  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.524   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.524   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.534  7057  7057 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-13 12:25:08.534  7057  7057 I PCWCLIENTTRACE_PushUtil: sales region : global
09-13 12:25:08.534  7057  7057 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 12:25:08.534  7057  7057 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,09-13 12:25:08.534   979  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-13 12:25:08.534   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.534   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.534   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.534   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.554  7091  7091 E Zygote  : MountEmulatedStorage()
09-13 12:25:08.554  7091  7091 I libpersona: KNOX_SDCARD checking this for 10029
09-13 12:25:08.554  7091  7091 E Zygote  : v2
09-13 12:25:08.554  7091  7091 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:08.554  7091  7091 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:08.554   979  1481 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7091 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-13 12:25:08.554   979  1481 I ActivityManager: Killing 6621:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-13 12:25:08.554  7091  7091 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:08.564  7091  7091 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:25:08.564   979  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:08.564   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
09-13 12:25:08.564   979  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.564   979  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.564   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.574   979  1007 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:08.574   979  1007 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.574   979  1007 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.574   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.574   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.584   979  1348 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:08.584   979  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.584   979  1348 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.584   979  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.584   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.594  4690  5024 D nzm     : Processing package: com.test.thalitest
,09-13 12:25:08.594  4690  6673 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 12:25:08.594  4690  6673 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-13 12:25:08.604  7091  7091 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:08.604  7091  7091 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:08.604   979  1007 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:08.604   979  1007 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.604  4690  5024 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-13 12:25:08.604  4690  5024 D nzm     : Found info for package com.test.thalitest in db.
,09-13 12:25:08.614   979  1007 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.614   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.614   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.624   979  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:08.624   979  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.624   979  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.624   979  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.624   979  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.634   979  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:08.634   979  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.634   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.634   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.634   979  1010 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:08.634  6910  6910 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 12:25:08.644   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.644   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.644   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.654   979  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.654   979  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.654   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.654   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.664  6910  6910 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 12:25:08.674   979  1348 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,09-13 12:25:08.674   979  1007 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 12:25:08.674   979  1007 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.674   979  1007 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:08.674   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:08.684   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 12:25:08.684   979  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:08.684   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.684  6910  6910 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-13 12:25:08.684  6910  6910 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-13 12:25:08.684   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.684   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.684   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.684   979  1348 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,09-13 12:25:08.684   979  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.684   979  1348 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.684   979  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.684   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 12:25:08.694   979  1348 I ActivityManager: Killing 6786:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #21
,09-13 12:25:08.694  6910  6910 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-13 12:25:08.694  7091  7111 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-13 12:25:08.704   979  1137 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 12:25:08.704   979  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.704   979  1466 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-13 12:25:08.714  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-13 12:25:08.714  6910  6910 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 12:25:08.714   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
09-13 12:25:08.714  6910  6910 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 12:25:08.714   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.714   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.714   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 12:25:08.714   979  1479 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-13 12:25:08.714   979  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.714   979  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.714   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.714   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-13 12:25:08.724  2735  2735 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,09-13 12:25:08.724   979  1007 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-13 12:25:08.724   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.724   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:08.724   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.724   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:08.734  6665  6665 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,09-13 12:25:08.744  7118  7118 E Zygote  : MountEmulatedStorage(),
09-13 12:25:08.744  7118  7118 I libpersona: KNOX_SDCARD checking this for 10032
09-13 12:25:08.744  7118  7118 E Zygote  : v2
09-13 12:25:08.744  7118  7118 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:08.744  7118  7118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:08.744   979  1007 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7118 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 12:25:08.744  7118  7118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:08.744  7118  7118 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-13 12:25:08.754   979  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:08.754   979  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 12:25:08.754   979  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.754   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:08.754   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:08.774   979  1010 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-13 12:25:08.774   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 12:25:08.774  7091  7111 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-13 12:25:08.774  7091  7111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 12:25:08.784  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:08.784  7091  7111 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 12:25:08.784  7091  7111 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-13 12:25:08.784  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:08.794  7091  7111 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-13 12:25:08.794  7091  7111 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 12:25:08.794  7091  7111 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 12:25:08.794  7091  7111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:08.794  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:08.794  6665  6665 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-13 12:25:08.794  7091  7111 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 12:25:08.794  6665  6665 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-13 12:25:08.804  6910  7134 D OpenGLRenderer: Render dirty regions requested: true
,09-13 12:25:08.814   979  1483 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 12:25:08.814  7118  7118 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:08.814  7118  7118 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:08.814   979  1483 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 12:25:08.814  4690  7115 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-13 12:25:08.814   979  1483 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-13 12:25:08.814   979   979 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-13 12:25:08.814   979   979 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 12:25:08.824  7091  7111 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 12:25:08.824  7091  7111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:08.824  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:08.834  7091  7111 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-13 12:25:08.834  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:08.834  7091  7111 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-13 12:25:08.854  7091  7111 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 12:25:08.854  7091  7111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 12:25:08.854  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:08.854  7091  7111 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-13 12:25:08.854  7091  7111 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 12:25:08.854  7091  7111 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 12:25:08.854  7091  7111 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 12:25:08.884  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:08.884  7091  7111 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 12:25:08.884  7091  7111 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 12:25:08.884  7091  7111 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-13 12:25:08.884  7091  7111 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 12:25:08.884  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:08.894  7091  7111 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 12:25:08.894   292   292 E SMD     : DCD OFF,
,09-13 12:25:08.914  7091  7111 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-13 12:25:08.914  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:08.914  7091  7111 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 12:25:08.914  7091  7111 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 12:25:08.934  6665  6665 I Finsky  : [1] com.google.android.finsky.selfupdate.f.a(166): Skipping DFE self-update. Local Version [80691500] >= Server Version [-1]
,09-13 12:25:08.954  7091  7111 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-13 12:25:08.954  7091  7111 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:08.954  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:08.954  7091  7111 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 12:25:08.964   979  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:25:08.964   979  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 12:25:08.964   979  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:25:08.964   979  1483 D BatteryService: stay LED for fully charged
,09-13 12:25:08.964   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:25:08.974   979   979 I MotionRecognitionService: Plugged
,09-13 12:25:08.974   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:25:08.974  7091  7111 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,09-13 12:25:08.974   979  1472 I art     : Explicit concurrent mark sweep GC freed 23800(1349KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.586ms total 166.641ms
,09-13 12:25:08.974  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:25:08.974  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:25:08.974  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:25:08.974  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:25:08.984  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:08.984  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:08.984   979  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:08.994  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:25:08.994  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:08.994  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:25:08.994   979  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:08.994   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:08.994   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:09.004  7091  7111 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 12:25:09.004  7091  7111 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-13 12:25:09.004  7091  7111 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 12:25:09.004  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:09.004  7091  7111 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 12:25:09.014  6910  6910 V ActivityThread: updateVisibility : ActivityRecord{25fdd309 token=android.os.BinderProxy@3ff9b8d3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-13 12:25:09.014  6910  7047 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-13 12:25:09.024   979  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:09.034   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:09.034   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:09.034   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:09.034   979  1479 D LocationManagerService: getProviders()=[passive]
,09-13 12:25:09.034   979  1748 I ActivityManager: Killing 6823:com.android.keychain/1000 (adj 15): empty #21
,09-13 12:25:09.034  7091  7111 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-13 12:25:09.034  7091  7111 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:09.044   979  1010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:09.044   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:09.044   979  1010 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:09.044   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:09.044  6910  6910 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-13 12:25:09.044   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 12:25:09.044  6910  6910 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-13 12:25:09.054  7091  7111 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,09-13 12:25:09.064   979  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:09.064   979  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:09.064   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:09.064   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 12:25:09.064   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:09.064   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.064   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.064   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:09.074   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-13 12:25:09.084  7144  7144 E Zygote  : MountEmulatedStorage(),
09-13 12:25:09.084  7144  7144 E Zygote  : v2
09-13 12:25:09.084  7144  7144 I libpersona: KNOX_SDCARD checking this for 10011
09-13 12:25:09.084  7144  7144 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:09.084  7144  7144 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:09.084  7144  7144 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 12:25:09.084   979  1466 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7144 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-13 12:25:09.084  7144  7144 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 12:25:09.094   979  1472 D InputDispatcher: Focus entered window: 6910
,09-13 12:25:09.094   979  1501 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 12:25:09.094   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 12:25:09.094   979  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-13 12:25:09.094   979  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 12:25:09.094   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.094   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.094   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.094   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.094  6910  6910 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 12:25:09.094  6910  7134 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 12:25:09.104  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:09.104  6910  7134 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-13 12:25:09.104  6910  7134 D OpenGLRenderer: Enabling debug mode 0
,09-13 12:25:09.114  7156  7156 E Zygote  : MountEmulatedStorage(),
09-13 12:25:09.114  7156  7156 E Zygote  : v2
09-13 12:25:09.114  7156  7156 I libpersona: KNOX_SDCARD checking this for 1000,
09-13 12:25:09.114  7156  7156 I libpersona: KNOX_SDCARD not a persona,
09-13 12:25:09.114   979  1043 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=7156 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 12:25:09.114  7156  7156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:09.124  7144  7144 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-13 12:25:09.124  7144  7144 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:09.124  6702  6702 I Mms/MmsApp:  start initViewCache mms
09-13 12:25:09.124  7156  7156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:09.124  6702  6702 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1683.994947
09-13 12:25:09.124  6702  6702 D Mms/ComposeMessageFragment: fillCache, easy = false
09-13 12:25:09.124  7156  7156 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:09.144  7118  7169 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-13 12:25:09.144  7118  7169 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-13 12:25:09.164   979  1348 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 12:25:09.164  7118  7169 D SPPClientService: PushLog.txt file is not deleted.
09-13 12:25:09.164  7118  7169 D SPPClientService: PushLog.txt file is not deleted.
09-13 12:25:09.164  7118  7169 D SPPClientService: ============PushLog. stop!
,09-13 12:25:09.184   979  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-13 12:25:09.194  1179  1179 I StatusBar: Icon Only
,09-13 12:25:09.194  1179  1179 D PanelView: There is/are notification(s) 
09-13 12:25:09.194   979  7180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-13 12:25:09.194  7156  7156 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:09.194  7156  7156 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:09.194   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.194   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.194   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:09.194   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:09.204  7182  7182 E Zygote  : MountEmulatedStorage()
09-13 12:25:09.204  7182  7182 E Zygote  : v2
09-13 12:25:09.214  7182  7182 I libpersona: KNOX_SDCARD checking this for 10039
09-13 12:25:09.214  7182  7182 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:09.214  7182  7182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:09.214   979  1481 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7182 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-13 12:25:09.214  7144  7144 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 12:25:09.214  7144  7144 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 12:25:09.214  7182  7182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:09.214  6910  6910 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-13 12:25:09.214  7182  7182 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:25:09.224   979  1048 I ActivityManager: Displayed Component not be shown by security: +1s567ms (total +1s691ms)
09-13 12:25:09.224   979  1048 W ActivityManager: mDVFSHelper.release()
09-13 12:25:09.224   979  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{238d337a u0 com.test.thalitest/.MainActivity t2} time:86284
09-13 12:25:09.224  6910  6910 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ff9b8d3 time:86287
,09-13 12:25:09.234  7072  7114 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-13 12:25:09.254   259   821 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-13 12:25:09.254   259   453 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-13 12:25:09.264   979  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:09.264   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:09.264   979  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:09.264   979  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:09.264   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:09.264  7182  7182 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:09.274  7182  7182 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:09.274  6910  6910 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6910
,09-13 12:25:09.324  1863  1863 I SamsungIME: getCurrentCandidateView
,09-13 12:25:09.334  7182  7182 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 12:25:09.334  7182  7182 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:09.334  7182  7182 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:09.334  7182  7182 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-13 12:25:09.334  7182  7182 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 12:25:09.334  7182  7182 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 12:25:09.334  7182  7182 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 12:25:09.344  7156  7156 D AASAservice: onCreate()
,09-13 12:25:09.344  7156  7156 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,09-13 12:25:09.344  2735  2735 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
,09-13 12:25:09.344   979  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:09.354   979  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:09.354   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:09.354   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 12:25:09.354   979  1748 I ActivityManager: Killing 6890:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-13 12:25:09.404   979  1348 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-13 12:25:09.404   979  1348 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-13 12:25:09.404   979  1348 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:09.404   979  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:09.404   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-13 12:25:09.414   979  1137 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 12:25:09.414   979  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 12:25:09.414  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:09.434  7144  7144 I MultiDex: VM with version 2.1.0 has multidex support
09-13 12:25:09.434  7144  7144 I MultiDex: install
09-13 12:25:09.434  7144  7144 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 12:25:09.484   979  1748 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:09.484  7144  7144 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 12:25:09.494   979  1748 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:09.494   979  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:09.494   979  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 12:25:09.494  6702  6702 D AbsListView: Get MotionRecognitionManager
,09-13 12:25:09.494   979  1481 D MotionRecognitionService:  ssp status : false
,09-13 12:25:09.504  6702  6702 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 379.648229
,09-13 12:25:09.564  1863  1863 D SamsungIME: Dismiss ExpandCandiate
,09-13 12:25:09.604  6910  6910 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 12:25:09.634   979  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:09.644   979  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:09.644   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:09.644   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,09-13 12:25:09.664  6702  6702 D Mms/BubbleViewCache: fillCache bubble = 1
,09-13 12:25:09.684  7144  7144 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 12:25:09.694   979  1010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:09.694   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:09.694  7144  7144 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23c0bca: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-13 12:25:09.694  7144  7144 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 12:25:09.694   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:09.694   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:09.704   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:09.724  6910  7181 D jxcore_app_log: JniHelper::setJavaVM(0xb89a42b0), pthread_self() = -1192027024
,09-13 12:25:09.734  7072  7114 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 491 ms] updated apps [took 491 ms] 
,09-13 12:25:09.734  6910  7181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 12:25:09.734  6910  7181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 12:25:09.734  6910  7181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 12:25:09.734  6910  7181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 12:25:09.734  6910  7181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 12:25:09.734  6910  7181 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1e33d4 added. We now have 1 listener(s)
,09-13 12:25:09.734  6910  7181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-13 12:25:09.744  6910  7181 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-13 12:25:09.744  6910  7181 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 12:25:09.744  6910  7181 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 12:25:09.744  7144  7144 D ChimeraCfgMgr: Reading stored module config
,09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 12:25:09.754  6910  7181 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ff27cc3 added. We now have 1 listener(s)
,09-13 12:25:09.754  6910  7181 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:25:09.754  6910  7181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:25:09.754  6910  7181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 12:25:09.764  6910  7181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-13 12:25:09.764  6910  7181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-13 12:25:09.764  6910  7181 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 12:25:09.764  6910  7181 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:25:09.764  6910  7181 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-13 12:25:09.774  6910  7181 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 12:25:09.774  6910  7181 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:09.774  6910  7181 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:09.774  6910  7181 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:09.774  6910  7181 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:09.774  6910  7181 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:09.774  6910  7181 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:09.774  6910  7181 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:09.774  6910  7181 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:09.774  6910  7181 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 12:25:09.774  6910  7181 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:25:09.774  6910  7181 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 12:25:09.784  6910  6910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:09.784  7182  7182 D NearbySource: Nearby Source Create!
,09-13 12:25:09.784  7182  7182 D NearbyContext: Nearby Context Create!
,09-13 12:25:09.784  6910  6910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:09.824   258   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-13 12:25:09.824   258   535 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:25:09.824  7182  7182 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-13 12:25:09.824  7182  7182 D SLinkSource: Samsung link source created
,09-13 12:25:09.834  6910  6910 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 12:25:09.944  7182  7215 D ContactProvider: getAllContactInfoList Start
,09-13 12:25:09.944   979  1007 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 12:25:09.954  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 12:25:09.964   979  1348 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 12:25:09.964  7182  7182 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-13 12:25:09.984  7182  7215 D ContactProvider: getAllContactInfoList End
,09-13 12:25:09.994  7182  7215 I syncContacts: thread: 1318, sync time = 88
,09-13 12:25:10.014   979  1010 I splitIntent: Queue : background intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart  false.
,09-13 12:25:10.014  7144  7212 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-13 12:25:10.024  7057  7057 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-13 12:25:10.024  7057  7057 I PCWCLIENTTRACE_PushUtil: sales region : global
09-13 12:25:10.024  7057  7057 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 12:25:10.024  7057  7057 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REPLACED
09-13 12:25:10.024  7057  7057 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_PACKAGE_REPLACED_START
,09-13 12:25:10.024   979  1466 I splitIntent: Split this intent : android.intent.action.PACKAGE_REPLACED, mSplitNum[0]=5, mSplitNum[1]=9, mSplitNum[2]=13, mBgSplitQueueNum=3 divideNum= 4 r.nextReceiver= 1 receivers.size=17
09-13 12:25:10.024   979  1466 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REPLACED !! Enqueue -> schedule it!!
,09-13 12:25:10.024  7028  7028 D Compatibility: onReceive() it will make start service
09-13 12:25:10.024   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-13 12:25:10.034   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:10.034   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:10.034   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:10.034   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:10.044  7220  7220 E Zygote  : MountEmulatedStorage(),
,09-13 12:25:10.044   979  1043 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=7220 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-13 12:25:10.044  7220  7220 E Zygote  : v2
09-13 12:25:10.044  7220  7220 I libpersona: KNOX_SDCARD checking this for 10110,
09-13 12:25:10.054  7220  7220 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:10.054  7220  7220 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:10.054  7220  7220 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:10.054  7220  7220 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 12:25:10.064   979  1479 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,09-13 12:25:10.074   979  1479 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-13 12:25:10.074   979  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.074   979  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:10.074   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-13 12:25:10.074   979  1501 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:10.074   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.074   979  1501 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.074   979  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:10.074   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:10.074  4690  6673 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-13 12:25:10.074   979  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:10.074   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.074   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.074   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:10.074   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:10.084   979  1010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:10.084   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.084   979  1010 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.084   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:10.084   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:10.084   979  1007 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:10.084   979  1007 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.084  4690  4690 D AsyncTaskServiceImpl: Submit a task: nzm
09-13 12:25:10.094   979  1007 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.094   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:10.094   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:10.094  4690  6673 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-13 12:25:10.094   979  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:10.094  7220  7220 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:10.094  7220  7220 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:10.094  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 12:25:10.104   979  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.104   979  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:10.104   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:10.104   979  1501 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:10.104   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.104   979  1501 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.104   979  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:10.104   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:10.114  1995  1995 E NetworkScheduler.SR: Invalid parameter app
,09-13 12:25:10.124  1995  1995 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-13 12:25:10.134  1863  1863 I SamsungIME: KeybaordView init() : load resources
,09-13 12:25:10.144  4690  5024 D nzm     : Processing package: com.test.thalitest
,09-13 12:25:10.164  6477  6477 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:168 android.app.ActivityThread.handleReceiver:3125 
,09-13 12:25:10.164   979  1483 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-13 12:25:10.164   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.164   979  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:10.164   979  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 12:25:10.164   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-13 12:25:10.174  1863  1863 I SamsungIME: getCurrentKeyboard
09-13 12:25:10.174  1863  1863 I SamsungIME: getTextKeyboard
,09-13 12:25:10.204  7028  7235 D Compatibility: onHandleIntent()
,09-13 12:25:10.204  7028  7235 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REPLACED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,09-13 12:25:10.204  7028  7235 D Compatibility: found: 2
09-13 12:25:10.204  7028  7235 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-13 12:25:10.204  7028  7235 D Compatibility: skipping ResolveInfo{2976dcdc com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-13 12:25:10.204  7028  7235 D Compatibility: considering ResolveInfo{d0f41e5 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-13 12:25:10.204  7028  7235 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-13 12:25:10.204  7028  7235 D Compatibility: enabling receiver ResolveInfo{11b104ba com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 12:25:10.214  7028  7235 D Compatibility: enabling receiver ResolveInfo{19abdf6b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-13 12:25:10.214  7028  7235 D Compatibility: enabling receiver ResolveInfo{402eac8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-13 12:25:10.224  7028  7235 D Compatibility: enabling receiver ResolveInfo{37771761 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-13 12:25:10.224  4690  5024 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-13 12:25:10.224  4690  5024 D nzm     : Found info for package com.test.thalitest in db.
,09-13 12:25:10.224  7028  7235 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-13 12:25:10.244   979  1348 I ActivityManager: Killing 6928:com.wsomacp/u0a23 (adj 15): empty #21
,09-13 12:25:10.274  1863  1863 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-13 12:25:10.284  7144  7144 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 12:25:10.284  7144  7144 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 12:25:10.334  1995  5108 I art     : Explicit concurrent mark sweep GC freed 49148(2MB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 10MB/17MB, paused 1.226ms total 75.890ms
,09-13 12:25:10.334   979  1010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:10.334   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.334   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:10.334   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:10.334   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:10.354   979  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:10.354   979  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.354   979  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.354   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:10.354   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:10.364  7144  7144 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
,09-13 12:25:10.364  7144  7144 D CAR.SERVICE: onBind
09-13 12:25:10.364  7144  7144 D CAR.SERVICE: CSB onClientsConnected
,09-13 12:25:10.374  4690  6086 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-13 12:25:10.374   979  1348 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-13 12:25:10.384   979  1348 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-13 12:25:10.384   979  1348 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:10.384   979  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 12:25:10.384   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-13 12:25:10.414   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:25:10.444  7144  7144 D CAR.TEL.Service: Binding to InCallService
,09-13 12:25:10.454   979  1501 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_action
09-13 12:25:10.454   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallService2; callingUser = 0; userId(target) = 0
09-13 12:25:10.454   979  1501 W ActivityManager: Unable to start service Intent { act=local_action cmp=com.google.android.gms/.car.InCallService2 } U=0: not found
,09-13 12:25:10.464  7144  7144 E CAR.TEL.Service: Failed to bind to InCallService
,09-13 12:25:10.464   979  1348 I ActivityManager: Killing 6568:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-13 12:25:10.504   979  1748 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 12:25:10.534  7144  7165 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
09-13 12:25:10.534  7144  7165 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,09-13 12:25:10.544  7144  7165 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,09-13 12:25:10.544  7144  7165 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000006@DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000006/DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk': Failed to open oat filename for reading: No such file or directory
,09-13 12:25:10.544  7144  7165 D ChimeraFileApk: Classloading successful. Optimized code found.
,09-13 12:25:10.554  7144  7165 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,09-13 12:25:10.634  7144  7165 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,09-13 12:25:10.634  7144  7165 D CAR.SERVICE: Package validated; name: com.android.vending
,09-13 12:25:10.634  7144  7165 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.
,09-13 12:25:10.664  6910  7214 W jxcore-log: Initializing JXcore engine
09-13 12:25:10.664  6910  7214 W jxcore-log: JXcore engine is ready
,09-13 12:25:10.704  4690  6086 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-13 12:25:10.734  2025  2025 E audit   : type=1400 msg=audit(1473762310.724:205): avc:  denied  { ioctl } for  pid=7214 comm="Thread-1275" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 12:25:10.734  2025  2025 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:10.734  2025  2025 E audit   : type=1300 msg=audit(1473762310.724:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9dc3f8f8 items=0 ppid=309 ppcomm=main pid=7214 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1275" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-13 12:25:10.734  2025  2025 E audit   : type=1320 msg=audit(1473762310.724:205): 
,09-13 12:25:10.734  4690  6086 I Icing   : Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,09-13 12:25:10.744  6910  7214 W jxcore-log: Starting JXcore engine
,09-13 12:25:10.824   258   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 12:25:10.824   258   535 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:25:10.824  7220  7246 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 12:25:10.834   258   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 12:25:10.834   258   535 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:25:10.834  7220  7220 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 12:25:10.834  7220  7220 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 12:25:10.834  7220  7220 I GAv4    :   adb logcat -s GAv4
,09-13 12:25:10.834  7220  7246 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 12:25:10.874  6910  7214 W jxcore-log: Platform android
09-13 12:25:10.874  6910  7214 W jxcore-log: 
09-13 12:25:10.874  6910  7214 W jxcore-log: Process ARCH arm
09-13 12:25:10.874  6910  7214 W jxcore-log: 
,09-13 12:25:10.874  7220  7220 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:25:10.874   979  1479 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 12:25:10.884  7220  7220 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:25:10.914  4690  6086 I Icing   : Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
,09-13 12:25:10.914  7220  7249 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 12:25:10.914   258   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 12:25:10.914   258   535 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:25:10.924  7220  7248 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 12:25:10.924   258   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 12:25:10.924   258   535 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:25:10.924  7220  7248 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 12:25:11.004  6848  6881 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-13 12:25:11.024  6848  6881 I AcmsKeyStoreHelper: Key Store exist
09-13 12:25:11.024  6848  6881 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-13 12:25:11.104  6910  7214 I jxcore-log: JXcore Cordova bridge is ready!
09-13 12:25:11.104  6910  7214 I jxcore-log: 
,09-13 12:25:11.104  6910  7214 W jxcore-log: JXcore engine is started
,09-13 12:25:11.104  6910  7181 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 12:25:11.114  6910  6910 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 12:25:11.124  6848  6881 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-13 12:25:11.124  6848  6881 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-13 12:25:11.124  6848  6881 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-13 12:25:11.124  6848  6881 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 12:25:11.124  6848  6881 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-13 12:25:11.124  6848  6881 D AcmsCertificateMngr: handleAppRemoved() Enter com.test.thalitest
,09-13 12:25:11.134   979  1483 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-13 12:25:11.134  6848  6881 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.provider: com.samsung.android.mirrorlink.acms.provider.AcmsDbProvider
,09-13 12:25:11.144  6848  6881 D AcmsAppEntryInterface: App not found in DB Hence ignore
09-13 12:25:11.144  6848  6881 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>5
09-13 12:25:11.144  6848  6881 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 12:25:11.144  6848  6881 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-13 12:25:11.144  6848  6881 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-13 12:25:11.144  6848  6881 D AcmsCore: This is NOT a valid MirrorLink app
09-13 12:25:11.144  6848  6881 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-13 12:25:11.144  6848  6881 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 12:25:11.144  6848  6881 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-13 12:25:11.144  6848  6881 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-13 12:25:11.144  6848  6848 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 12:25:11.144  6848  6848 D AcmsService: Enter onDestroy
09-13 12:25:11.144  6848  6848 I AcmsService: cleanUp(): inside service clean up
09-13 12:25:11.144  6848  6848 D AcmsCore: AcmsCore: inside DeInit
09-13 12:25:11.144  6848  6848 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-13 12:25:11.144  6848  6848 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-13 12:25:11.144  6848  6848 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-13 12:25:11.144  6848  6848 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-13 12:25:11.144  6848  6848 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-13 12:25:11.144  6848  6848 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-13 12:25:11.144  6848  6848 D AcmsService: killing acms process
09-13 12:25:11.144  6848  6848 I Process : Sending signal. PID: 6848 SIG: 9
,09-13 12:25:11.214   979  1501 I ActivityManager: Process ACMS.Process (pid 6848)(adj 0) has died(63,725)
,09-13 12:25:11.304   979  1007 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:11.314  7220  7220 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-13 12:25:11.314   979  1007 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:11.314   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:11.314   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-13 12:25:11.314   979  1481 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-13 12:25:11.314   979  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 12:25:11.324  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:11.344  7220  7220 I cr.library_loader: Time to load native libraries: 6 ms (timestamps 8398-8404)
,09-13 12:25:11.344  7220  7220 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 12:25:11.344   979  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:11.354   979  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:11.354   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:11.354   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 12:25:11.364   979  1322 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-13 12:25:11.364  7220  7220 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ef1d10f}
09-13 12:25:11.364  7220  7220 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-13 12:25:11.364  7220  7220 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 12:25:11.364   979  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 12:25:11.364  4690  6086 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-13 12:25:11.364  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:11.374  4690  6086 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-13 12:25:11.384  7220  7220 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 12:25:11.384  7220  7220 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 12:25:11.394  7220  7220 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 12:25:11.394   979  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:11.394   979  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:11.394   979  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:11.394   979  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 12:25:11.414   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-13 12:25:11.414   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:11.414   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:11.414   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:11.414  7220  7220 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 12:25:11.414  7220  7220 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 12:25:11.414  7220  7220 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 12:25:11.414  7220  7220 I Adreno-EGL: Local Branch: 
09-13 12:25:11.414  7220  7220 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 12:25:11.414  7220  7220 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 12:25:11.414  7220  7220 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 12:25:11.484  7220  7277 W cr.media: Requires BLUETOOTH permission
,09-13 12:25:11.484  7220  7220 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 12:25:11.494  7220  7220 I NSApplication: Starting up...
,09-13 12:25:11.494   979  1348 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 12:25:11.494   979  1483 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 12:25:11.504   979  1322 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-13 12:25:11.504   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:11.504   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:11.504   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:11.504   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:11.514  7282  7282 E Zygote  : MountEmulatedStorage()
,09-13 12:25:11.514  7282  7282 E Zygote  : v2
09-13 12:25:11.514  7282  7282 I libpersona: KNOX_SDCARD checking this for 10121
09-13 12:25:11.514  7282  7282 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:11.524  7282  7282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:11.524   979  1322 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7282 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-13 12:25:11.524  7282  7282 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 12:25:11.524   979  1322 I ActivityManager: Killing 6702:com.android.mms/u0a41 (adj 15): empty #21
09-13 12:25:11.524  7282  7282 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:11.544   309   309 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 678us total 26.360ms
,09-13 12:25:11.564   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.303ms
,09-13 12:25:11.564  7282  7282 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:11.564  7282  7282 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:11.584   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 18.725ms
,09-13 12:25:11.584  7282  7282 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:11.584  7282  7282 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 12:25:11.584  7282  7282 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 12:25:11.594  7282  7282 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.PACKAGE_REPLACED
,09-13 12:25:11.604  6632  6632 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-13 12:25:11.604  6632  6632 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REPLACED / mCurIndex :-10
09-13 12:25:11.604  6632  6632 I TapandpayWidget:Utils: Clear T&P info.
,09-13 12:25:11.604  6632  6632 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-13 12:25:11.604   979  1501 I ActivityManager: Killing 6597:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-13 12:25:11.614   979  1501 D CountryDetector: No listener is left
,09-13 12:25:11.614  1773  1773 D daemonapp: [MSC_Daemon]>>> AWDCDS:28 [0:0] AWD CD Act : androidintentactionPACKAGE_REPLACED
,09-13 12:25:11.624   979  1137 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REPLACED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-13 12:25:11.634   979   979 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,09-13 12:25:11.634   979   979 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,09-13 12:25:11.634   979  1392 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 12:25:11.634   979   979 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:11.634   979   979 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:11.634   979   979 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:11.644   979  1392 D AlarmManagerService: Setting time of day to sec=1473762312
09-13 12:25:11.644   979  1392 D AlarmManagerService: Trying to open a file
,09-13 12:25:11.644   979  1392 D AlarmManagerService: File Open Success
,09-13 12:25:11.644   979  1392 D AlarmManagerService: File Close Success
,09-13 12:25:11.644   979  1392 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,09-13 12:25:12.778   979  1392 W AlarmManagerService: Unable to set rtc to 1473762312: Invalid argument
09-13 12:25:12.778   979  1096 V AlarmManager: waitForAlarm result :65536
,09-13 12:25:12.778   979   979 I BackgroundCompactionService: onStart. jobID=801
,09-13 12:25:12.778   979   979 I BackgroundCompactionService: onStart done. jobID=801
,09-13 12:25:12.778   979  7297 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,09-13 12:25:12.787   979  7297 I BackgroundCompactionService: compact_memory command done
,09-13 12:25:12.787   979  1096 V AlarmManager: No more alarm at this time.nowELAPSED=88726 batch.start=92975
,09-13 12:25:12.797  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
,09-13 12:25:12.797  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:25:12.807  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 12:25:12.807  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 12:25:12.817  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:25:12.817  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,09-13 12:25:12.827  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:25:12.827  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:25:12.837  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:25:12.837   979   979 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1473762312840
,09-13 12:25:12.847   979   979 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,09-13 12:25:12.847   979   979 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,09-13 12:25:12.847   979   979 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 12:25:12.867   979   979 I DrmEventService:  no response from SecureClock 
,09-13 12:25:12.867   979   979 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
09-13 12:25:12.867   979   979 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,09-13 12:25:12.867   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,09-13 12:25:12.877   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:12.877   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:12.877   979  1479 D SettingsProvider: name = lockscreen_zoom_panning_effect
09-13 12:25:12.877   979  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 12:25:12.877   979  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 12:25:12.877   979  1479 D SettingsProvider: selectionArgs: false
09-13 12:25:12.877   979  1479 D SettingsProvider: selectionArgs: 10049
09-13 12:25:12.877   979  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 12:25:12.877   979  1479 D SettingsProvider: ret = -1
,09-13 12:25:12.877   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:12.877   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:12.887  1179  1179 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,09-13 12:25:12.897  7299  7299 E Zygote  : MountEmulatedStorage()
,09-13 12:25:12.897  7299  7299 E Zygote  : v2
09-13 12:25:12.897  7299  7299 I libpersona: KNOX_SDCARD checking this for 10058
09-13 12:25:12.897  7299  7299 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:12.897  1179  1179 D KeyguardEffectViewController: isPreloadedWallpaper=true
09-13 12:25:12.897  7299  7299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:12.897  1179  1179 I GeometricMosaic_Keyguard: update
09-13 12:25:12.907   979  1043 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7299 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 12:25:12.907   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
09-13 12:25:12.907  1179  1179 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
09-13 12:25:12.907   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:12.907   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:12.907   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:12.907   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:12.917  7299  7299 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:12.917  7299  7299 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:12.937  7308  7308 E Zygote  : MountEmulatedStorage(),
09-13 12:25:12.937  7308  7308 E Zygote  : v2
09-13 12:25:12.937  7308  7308 I libpersona: KNOX_SDCARD checking this for 10131,
09-13 12:25:12.937  7308  7308 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:12.937   979  1043 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7308 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-13 12:25:12.937  7308  7308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 12:25:12.937   979   979 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-13 12:25:12.937  7308  7308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:12.937   979   979 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:12.937  7308  7308 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 12:25:12.937   979   979 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:12.937   979   979 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:12.937   979   979 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:12.947  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
09-13 12:25:12.947  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
09-13 12:25:12.947  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:25:12.957  7299  7299 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:12.957  7299  7299 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:12.957  7324  7324 E Zygote  : MountEmulatedStorage()
09-13 12:25:12.957  7324  7324 I libpersona: KNOX_SDCARD checking this for 10008
09-13 12:25:12.957  7324  7324 E Zygote  : v2
09-13 12:25:12.957  7324  7324 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:12.957  7324  7324 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:12.957   979   979 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7324 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 12:25:12.967  7324  7324 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:12.967  7324  7324 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 12:25:12.967  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:25:12.977  7308  7308 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:12.977  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
09-13 12:25:12.977  7308  7308 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:13.007  7324  7324 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:13.007  7324  7324 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:13.017  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,09-13 12:25:13.027   292   292 E SMD     : DCD OFF
,09-13 12:25:13.037  1773  1773 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:25:13.037  1773  1773 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,09-13 12:25:13.037  1773  1773 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
09-13 12:25:13.037  1773  1773 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
09-13 12:25:13.037  1773  1773 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,09-13 12:25:13.037  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-13 12:25:13.037  7308  7308 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 12:25:13.037  7308  7308 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:13.037  7308  7308 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:13.037  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,09-13 12:25:13.047  1179  1179 I KeyguardEffectViewUtil: set current wallpaper info
,09-13 12:25:13.047   979  1481 D SettingsProvider: name = keyguard_current_wallpaper_type
09-13 12:25:13.047   979  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 12:25:13.047   979  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 12:25:13.047   979  1481 D SettingsProvider: selectionArgs: false
09-13 12:25:13.047   979  1481 D SettingsProvider: selectionArgs: 10049
09-13 12:25:13.047   979  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 12:25:13.047   979  1481 D SettingsProvider: ret = -1
,09-13 12:25:13.047   979  1472 D SettingsProvider: name = keyguard_current_wallpaper_file_path
09-13 12:25:13.047   979  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 12:25:13.047   979  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 12:25:13.047   979  1472 D SettingsProvider: selectionArgs: false
09-13 12:25:13.047   979  1472 D SettingsProvider: selectionArgs: 10049
09-13 12:25:13.047   979  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-13 12:25:13.047   979  1472 D SettingsProvider: ret = -1
,09-13 12:25:13.047   979  1010 D SettingsProvider: name = keyguard_current_wallpaper_res_id
,09-13 12:25:13.047   979  1010 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 12:25:13.047   979  1010 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-13 12:25:13.047   979  1010 D SettingsProvider: selectionArgs: false
09-13 12:25:13.047   979  1010 D SettingsProvider: selectionArgs: 10049
,09-13 12:25:13.047   979  1010 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-13 12:25:13.047   979  1010 D SettingsProvider: ret = -1
,09-13 12:25:13.057  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
09-13 12:25:13.057  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,09-13 12:25:13.057  1773  1773 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,09-13 12:25:13.057  1773  1773 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,09-13 12:25:13.057  1773  1773 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,09-13 12:25:13.087  1773  1773 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,09-13 12:25:13.087  1773  1773 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,09-13 12:25:13.137  1773  1781 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,09-13 12:25:13.147   979  1010 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-13 12:25:13.147   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-13 12:25:13.147   979  1010 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:13.147   979  1010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:13.147   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 12:25:13.147  1179  1652 D TEST    : run!!!
,09-13 12:25:13.147  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,09-13 12:25:13.157  7299  7299 I ExternalOEMControlProvider: onCreate
,09-13 12:25:13.167  1179  1652 I GeometricMosaic_Renderer: setBackgroundBitmap
,09-13 12:25:13.197   979  1137 I ActivityManager: Killing 6746:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-13 12:25:13.197  1684  1684 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,09-13 12:25:13.207  1684  1684 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-13 12:25:13.207   979  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,09-13 12:25:13.207   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.207   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.207   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.207   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.227  7350  7350 E Zygote  : MountEmulatedStorage(),
09-13 12:25:13.227  7350  7350 E Zygote  : v2
09-13 12:25:13.227  7350  7350 I libpersona: KNOX_SDCARD checking this for 10081,
09-13 12:25:13.227  7350  7350 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:13.227   979  1501 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7350 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 12:25:13.227  7350  7350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:13.227   979  1007 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,09-13 12:25:13.227  7350  7350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:13.237  7350  7350 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:13.237   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.237   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.237   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.237   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.257   979  1007 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7360 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-13 12:25:13.257  7360  7360 E Zygote  : MountEmulatedStorage(),
09-13 12:25:13.257  7360  7360 E Zygote  : v2
,09-13 12:25:13.257  7360  7360 I libpersona: KNOX_SDCARD checking this for 10037,
09-13 12:25:13.257  7360  7360 I libpersona: KNOX_SDCARD not a persona,
,09-13 12:25:13.257  7350  7350 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:13.257  7350  7350 D ActivityThread: Added TimaKeyStore provider,
,09-13 12:25:13.267  7360  7360 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:13.267  7360  7360 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:13.267  7360  7360 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 12:25:13.287  7360  7360 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:13.287  7360  7360 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:13.297   979  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:13.297   979  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,09-13 12:25:13.297   979  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:13.297   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:13.297   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:13.307  7350  7350 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-13 12:25:13.307  7350  7350 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 12:25:13.307  7350  7350 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:13.307  7350  7350 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:13.307  7350  7350 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-13 12:25:13.327  7360  7360 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,09-13 12:25:13.327  7324  7324 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-13 12:25:13.347   979  1010 I art     : Explicit concurrent mark sweep GC freed 25215(1377KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/37MB, paused 2.794ms total 167.628ms
,09-13 12:25:13.347   979  1501 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-13 12:25:13.347   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-13 12:25:13.357   979  1501 W ActivityManager: userId = 0, bbcId = -10000,
09-13 12:25:13.357   979  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:13.357   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 12:25:13.357   979  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-13 12:25:13.357   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.357  7299  7347 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,09-13 12:25:13.357   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.357   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.357   979  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.377  7360  7360 I CalendarProvider2: CalendarProvider2.onCreate() called
,09-13 12:25:13.377  7381  7381 E Zygote  : MountEmulatedStorage()
09-13 12:25:13.377  7381  7381 E Zygote  : v2,
,09-13 12:25:13.377  7381  7381 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:13.377  7381  7381 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:13.387  7381  7381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:13.377   979  1481 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7381 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 12:25:13.387  7381  7381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:13.387  7381  7381 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:13.407  7381  7381 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:13.407  7381  7381 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:13.417   979  1042 E libprocessgroup: failed to kill 1 processes for processgroup 6746
,09-13 12:25:13.427  7324  7324 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,09-13 12:25:13.427   979  1472 I ActivityManager: Killing 6769:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-13 12:25:13.427  2879  2879 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Sep 13 12:25:13 GMT+02:00 2016
,09-13 12:25:13.427   979  1466 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-13 12:25:13.437   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-13 12:25:13.437   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:13.437   979  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:13.437   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-13 12:25:13.437  2879  2879 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-13 12:25:13.437   979  1137 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-13 12:25:13.437   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.437   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.437   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.437   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.447  2879  2879 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-13 12:25:13.457  2879  2879 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 12:25:13.457  2879  2879 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,09-13 12:25:13.467  7399  7399 E Zygote  : MountEmulatedStorage(),
09-13 12:25:13.467  7399  7399 E Zygote  : v2
09-13 12:25:13.467  7399  7399 I libpersona: KNOX_SDCARD checking this for 10036,
09-13 12:25:13.467  7399  7399 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:13.467  7399  7399 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:13.467  2879  7398 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService },
,09-13 12:25:13.467  2879  7398 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED,
09-13 12:25:13.467  7399  7399 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 12:25:13.467  7399  7399 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
09-13 12:25:13.467  2879  7398 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Sep 13 12:25:13 GMT+02:00 2016,
,09-13 12:25:13.477   979  1137 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=7399 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 12:25:13.487   979  1322 D SettingsProvider: name = next_alarm_formatted
09-13 12:25:13.487   979  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 12:25:13.487   979  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 12:25:13.487   979  1322 D SettingsProvider: selectionArgs: false
09-13 12:25:13.487   979  1322 D SettingsProvider: selectionArgs: 10081
09-13 12:25:13.487   979  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 12:25:13.487   979  1322 D SettingsProvider: ret = -1
,09-13 12:25:13.497  2879  7398 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,09-13 12:25:13.517  7399  7399 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:13.517  2879  2879 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-13 12:25:13.517  7399  7399 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:13.547  7381  7381 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 12:25:13.547  7381  7381 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 12:25:13.547  7381  7381 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 12:25:13.567   979  1472 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,09-13 12:25:13.567   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.567   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.567   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.567   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.577  7399  7399 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@1ceaa7d6
,09-13 12:25:13.587  7418  7418 E Zygote  : MountEmulatedStorage(),
,09-13 12:25:13.587  7418  7418 E Zygote  : v2,
09-13 12:25:13.587   979  1472 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7418 uid=10153 gids={50153, 9997} abi=armeabi-v7a
09-13 12:25:13.587   979  1472 I ActivityManager: Killing 6969:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
09-13 12:25:13.587  7418  7418 I libpersona: KNOX_SDCARD checking this for 10153,
09-13 12:25:13.587  7418  7418 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:13.597  7399  7399 I SA      : [SSP] onCreated,
09-13 12:25:13.597  7418  7418 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:13.597  7418  7418 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:13.597   979  1481 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
09-13 12:25:13.597   979  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
09-13 12:25:13.597  7418  7418 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:13.607   979  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:13.607   979  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:13.607   979  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-13 12:25:13.627  7399  7399 I SA      : [TPM] There is no property file
,09-13 12:25:13.647  7399  7399 I SA      : [SCU] isHaveSA() - false
,09-13 12:25:13.647  7418  7418 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:13.647  7418  7418 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:13.647  7399  7399 I SA      : [TPM] getModelProperty : null
09-13 12:25:13.647  7399  7399 I SA      : [TPM] getCSCProperty : null
,09-13 12:25:13.647  7399  7399 I SA      : [DM] FLOATING AMOLED FEATURE: true
09-13 12:25:13.647  7399  7399 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-13 12:25:13.647  7399  7399 I SA      : [DM] TFT FEATURE: false
,09-13 12:25:13.667  7399  7399 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,09-13 12:25:13.667  7399  7399 I SA      : [DM] init START
,09-13 12:25:13.667  7418  7418 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:13.667  7399  7399 I SA      : [DM] This device is not a Vodafone
,09-13 12:25:13.677  7399  7399 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-13 12:25:13.677  7399  7399 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-13 12:25:13.677  7399  7399 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-13 12:25:13.677  7399  7399 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-13 12:25:13.677  7399  7399 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-13 12:25:13.677  7399  7399 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-13 12:25:13.687  7399  7399 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-13 12:25:13.697  7399  7399 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-13 12:25:13.697  7399  7399 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-13 12:25:13.697  7399  7399 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-13 12:25:13.697  7399  7399 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-13 12:25:13.697  7399  7399 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-13 12:25:13.697  7399  7399 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-13 12:25:13.697  7399  7399 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-13 12:25:13.697  7399  7399 I SA      : [SCU] isHaveSA() - false
,09-13 12:25:13.697  7399  7399 I SA      : support phone number id : false
09-13 12:25:13.697  7399  7399 I SA      : [DM] Supports Ref Jpn : true
,09-13 12:25:13.697  7399  7399 I SA      : [DM] init END
,09-13 12:25:13.717   979  1748 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,09-13 12:25:13.717   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.727   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.727   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.727   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.737  7438  7438 E Zygote  : MountEmulatedStorage(),
09-13 12:25:13.737  7438  7438 E Zygote  : v2
09-13 12:25:13.737  7438  7438 I libpersona: KNOX_SDCARD checking this for 1000,
09-13 12:25:13.737  7438  7438 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:13.737  7438  7438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 12:25:13.737  7438  7438 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:13.737  7438  7438 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:13.747   979  1748 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7438 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,09-13 12:25:13.747   979  1748 I ActivityManager: Killing 6801:com.samsung.helphub/1000 (adj 15): empty #21
,09-13 12:25:13.767  7350  7350 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 258.586ms
,09-13 12:25:13.777  7438  7438 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:13.777  7438  7438 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:13.807   979  1322 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,09-13 12:25:13.807   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.807   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.807   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.807   979  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.817  7453  7453 E Zygote  : MountEmulatedStorage(),
09-13 12:25:13.827  7453  7453 E Zygote  : v2
,09-13 12:25:13.827  7453  7453 I libpersona: KNOX_SDCARD checking this for 10041
09-13 12:25:13.827  7453  7453 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:13.827  7453  7453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-13 12:25:13.827   979  1322 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=7453 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
09-13 12:25:13.827   979  1322 I ActivityManager: Killing 6951:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-13 12:25:13.827  7453  7453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 12:25:13.837  7453  7453 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 12:25:13.857  7453  7453 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:13.857  7453  7453 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:13.867   979  1010 I ActivityManager: Killing 6873:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-13 12:25:13.867  7438  7438 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1473762313878
09-13 12:25:13.867  7438  7438 D         : TimeServiceNative: User Time to be set is 1473762313878
09-13 12:25:13.867  7438  7438 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
09-13 12:25:13.867  7438  7438 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
09-13 12:25:13.867  7438  7438 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1473762313878
,09-13 12:25:13.877   335   435 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-13 12:25:13.877  7438  7438 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,09-13 12:25:13.877   335  7468 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1473762313878
09-13 12:25:13.877   335  7468 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1473762313878, operation = 0
09-13 12:25:13.877   335  7468 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/11/71 14:0:30
,09-13 12:25:13.877   335  7468 D QC-time-services: Daemon:Value read from RTC seconds = 37548030000
09-13 12:25:13.877   335  7468 D QC-time-services: Daemon:new time 1473762313878 
09-13 12:25:13.877   335  7468 D QC-time-services: Daemon: delta 1436214283878 genoff 1436214283878 
09-13 12:25:13.877   335  7468 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214283878 to memory
09-13 12:25:13.877   335  7468 D QC-time-services: Daemon:Opening File: /data/time/ats_2
09-13 12:25:13.877   335  7468 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-13 12:25:13.877  7453  7453 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-13 12:25:13.877  7453  7453 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:13.877  7453  7453 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:13.877  7453  7453 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 12:25:13.877  7453  7453 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-13 12:25:13.887   335  7468 D QC-time-services: Updating the TOD offset
09-13 12:25:13.887   335  7468 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214283878 to memory
09-13 12:25:13.887   335  7468 D QC-time-services: Daemon:Opening File: /data/time/ats_1
09-13 12:25:13.887   335  7468 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,09-13 12:25:13.897   335  7468 E QC-time-services: Daemon:Update to modem bit set
09-13 12:25:13.897   335  7468 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
09-13 12:25:13.897   335  7468 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249483878
,09-13 12:25:13.897  7438  7438 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,09-13 12:25:13.897   979  1348 I ActivityManager: Killing 6986:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-13 12:25:13.897   335   432 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
09-13 12:25:13.897   335   435 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-13 12:25:13.927  7453  7453 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,09-13 12:25:13.957  6665  6665 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-13 12:25:13.957  6665  6665 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 12:25:13.957   979  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-13 12:25:13.957   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.957   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.957   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:13.957   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:13.987  7470  7470 E Zygote  : MountEmulatedStorage()
,09-13 12:25:13.987  7470  7470 E Zygote  : v2,
09-13 12:25:13.987  7470  7470 I libpersona: KNOX_SDCARD checking this for 10090
09-13 12:25:13.987  7470  7470 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:13.987  7470  7470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:13.987  7470  7470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:13.987  7470  7470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:13.987   979  1501 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7470 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-13 12:25:13.997   979  1501 I ActivityManager: Killing 7182:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-13 12:25:14.017   309   309 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 23.366ms
,09-13 12:25:14.017  7470  7470 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:14.027  7470  7470 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:14.037   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 656us total 17.411ms
,09-13 12:25:14.047  6665  6665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 12:25:14.047   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.950ms
,09-13 12:25:14.057  7470  7470 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,09-13 12:25:14.057  7470  7470 D elm:15121: ELMEngine.ELMEngine( context ).
,09-13 12:25:14.067  7470  7470 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-13 12:25:14.067   979  1501 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-13 12:25:14.067   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-13 12:25:14.067   979  1501 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:14.067   979  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:14.067   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-13 12:25:14.077  7470  7470 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,09-13 12:25:14.077   979  1007 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,09-13 12:25:14.077   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:14.077   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:14.077   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:14.077   979  1007 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:14.087  7470  7470 D elm:15121: ElmAgentService : onCreate()
,09-13 12:25:14.097  7470  7485 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,09-13 12:25:14.097  7470  7485 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,09-13 12:25:14.107  7470  7470 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). ,
09-13 12:25:14.107  7470  7470 D elm:15121: ModuleBase.ModifySetAlarm()
09-13 12:25:14.107  7470  7470 D elm:15121: MDMBridge.getInstance()
09-13 12:25:14.107  7470  7470 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK(),
,09-13 12:25:14.107  7488  7488 E Zygote  : MountEmulatedStorage()
09-13 12:25:14.107  7488  7488 I libpersona: KNOX_SDCARD checking this for 10130
09-13 12:25:14.107  7488  7488 E Zygote  : v2
09-13 12:25:14.107  7488  7488 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:14.107  7488  7488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:14.117  7488  7488 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 12:25:14.117  7488  7488 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-13 12:25:14.127   979  1007 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7488 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,09-13 12:25:14.137  7470  7470 D elm:15121: ElmAgentService : onDestroy().
,09-13 12:25:14.137   979  1748 I ActivityManager: Killing 7057:com.sec.pcw.device/1000 (adj 15): empty #21
,09-13 12:25:14.137  7453  7453 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 166.530ms
,09-13 12:25:14.147  7488  7488 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:14.147  7488  7488 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:14.167   979  1466 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-13 12:25:14.167   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-13 12:25:14.167   979  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:14.167   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:14.167   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 12:25:14.167  7488  7488 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:14.177  7488  7488 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,09-13 12:25:14.177  6665  6665 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(743): Logging device features
,09-13 12:25:14.187   979  1748 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:14.187   979  1748 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:14.187   979  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:14.187   979  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 12:25:14.197   979  1096 V AlarmManager: waitForAlarm result :4
,09-13 12:25:14.207   979  1322 I ActivityManager: Killing 7091:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,09-13 12:25:14.217  6665  6665 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(59): Cancelling accelerated self-Update check
,09-13 12:25:14.227  6665  6665 W InstanceID/Rpc: Found 10011
,09-13 12:25:14.237  7453  7503 D Mms/ArtClassLoader: init before art
,09-13 12:25:14.247  7453  7453 D Mms/TelephonyPermission: start operation mode monitor
,09-13 12:25:14.247  1995  2011 D DeviceConnectionService: client connected with version: 9080000
,09-13 12:25:14.257  7453  7453 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 12:25:14.267   979  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:14.267  7453  7453 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 12:25:14.267  7453  7453 D Mms/TelephonyPermission: isDefault true
,09-13 12:25:14.267   979  1137 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:14.267  7453  7453 D Mms/MmsApp: onCreate() com.android.mms
,09-13 12:25:14.267   979  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:14.267   979  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:14.277  6665  6665 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-13 12:25:14.277  6665  6665 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=hygiene due to Gms not connected
,09-13 12:25:14.277   979  1479 I ActivityManager: Killing 7118:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-13 12:25:14.277   979  1479 I ActivityManager: Killing 7007:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #22
,09-13 12:25:14.317  7453  7453 D Mms/MmsApp: [start]    initCountryIso consume time = 383.25625
,09-13 12:25:14.317   979  1481 D CountryDetector: The first listener is added
,09-13 12:25:14.317  7453  7453 D Mms/MmsApp: [end]    initCountryIso consume time = 6.699219
,09-13 12:25:14.317  7453  7453 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.629323
,09-13 12:25:14.327  7453  7453 D Mms/MmsConfig: before partial update
,09-13 12:25:14.337  7453  7453 D Mms/MmsConfig: Load Resize quality : 80
,09-13 12:25:14.347  7453  7453 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,09-13 12:25:14.347  7453  7453 D EasySignUpManager_1.0.1: isAuth is false
,09-13 12:25:14.347  7453  7453 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,09-13 12:25:14.357  1457  1475 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7453
,09-13 12:25:14.357  1457  1475 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.645 ms
,09-13 12:25:14.367  7453  7453 D EasySignUpManager_1.0.1: isAuth is false
09-13 12:25:14.367  7453  7453 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,09-13 12:25:14.367  7453  7453 E CscParser: mps_code.dat does not exist
,09-13 12:25:14.367  7453  7453 E CscParser: customer_path =/system/csc/customer.xml
,09-13 12:25:14.367  7453  7453 E CscParser: fileName + /system/csc/customer.xml
,09-13 12:25:14.377  7453  7453 E CscParser: mps_code.dat does not exist
,09-13 12:25:14.377  7453  7453 E CscParser: customer_path =/system/csc/customer.xml
,09-13 12:25:14.377  7453  7453 E CscParser: fileName + /system/csc/customer.xml
,09-13 12:25:14.387  7453  7453 D CscParser: getInstance fileName =/system/csc/customer.xml
,09-13 12:25:14.387  7453  7453 D Mms/MmsConfig:  enable multiwindow = false
,09-13 12:25:14.397  7453  7453 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-13 12:25:14.397  7453  7453 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-13 12:25:14.407  7453  7453 D Mms/MmsConfig: [end]    init() consume time = 83.7475
,09-13 12:25:14.407  7453  7453 D Mms/Contact: [start]    init() consume time = 0.725156
,09-13 12:25:14.417  1457  1475 D TP/MmsSmsProvider: query,matched:13, calling pid = 7453
,09-13 12:25:14.417  1457  1475 D TP/MmsSmsProvider: match 13:Elapsed time : 1.544 ms
,09-13 12:25:14.417  7453  7453 D Mms/Contact: [end]    init consume time = 14.748385
,09-13 12:25:14.427  7453  7510 D Mms/DraftCache: [start]    rebuildCache consume time = 5.962396
,09-13 12:25:14.437  1457  1857 D TP/MmsSmsProvider: query,matched:12, calling pid = 7453
,09-13 12:25:14.437  1457  1857 D TP/MmsSmsProvider: match 12:Elapsed time : 1.348 ms
,09-13 12:25:14.437  7453  7510 D Mms/DraftCache: [end]    rebuildCache consume time = 11.94349
,09-13 12:25:14.437  7453  7453 D Mms/MethodReflector: getSubId is called
09-13 12:25:14.437  7453  7453 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-13 12:25:14.437  7453  7453 D Mms/MethodReflector: getTelephonyProperty is called
,09-13 12:25:14.437  7453  7453 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 12:25:14.437  7453  7453 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,09-13 12:25:14.447  7453  7453 D Mms/DownloadManager: auto download without roaming -> true
09-13 12:25:14.447  7453  7453 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-13 12:25:14.447  7453  7453 D Mms/MethodReflector: getSubId is called
,09-13 12:25:14.447  7453  7453 D Mms/MethodReflector: getDefaultSmsSubId is called
,09-13 12:25:14.447  7453  7453 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-13 12:25:14.447  7453  7453 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
,09-13 12:25:14.447  7453  7453 D Mms/MethodReflector: getTelephonyProperty is called
09-13 12:25:14.447  7453  7453 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-13 12:25:14.447  7453  7453 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
,09-13 12:25:14.447  7453  7453 D Mms/DownloadManager: auto download without roaming -> true
09-13 12:25:14.447  7453  7453 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 12:25:14.447  7453  7453 D Mms/DownloadManager: auto download during roaming secondary -> false
09-13 12:25:14.447  7453  7453 D Mms/DownloadManager: mAutoDownload ------> true
,09-13 12:25:14.487  7453  7453 D ComposerPerformance: 1473762314495 ms / [DONE] Composer constructor
,09-13 12:25:14.487  7453  7453 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,09-13 12:25:14.487  7453  7453 I Mms/ReservationManager: ReservationManager()
09-13 12:25:14.487  7453  7453 I Mms/ReservationManager: resetAfterConnected()
,09-13 12:25:14.497  1457  1653 D TP/MmsSmsProvider: query,matched:7, calling pid = 7453
,09-13 12:25:14.497  1457  1653 D TP/MmsSmsProvider: match 7:Elapsed time : 1.669 ms
,09-13 12:25:14.497  7453  7511 D Mms/Conversation: [start]    init() consume time = 54.640208
,09-13 12:25:14.497  7453  7453 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-13 12:25:14.497  1457  1467 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,09-13 12:25:14.497  1457  1467 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,09-13 12:25:14.497  1457  1467 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-13 12:25:14.507  1457  1467 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,09-13 12:25:14.507  7453  7453 D Mms/MmsApp: [end]    onCreate() consume time = 10.926146
,09-13 12:25:14.507  1457  1467 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-13 12:25:14.507  1457  1467 D TP/MmsSmsProvider: need read changed broadcast:false
,09-13 12:25:14.507  7453  7511 D Mms/Conversation: [end]    init consume time = 5.496302
,09-13 12:25:14.507  7453  7511 D Mms/MessagingNotification: [start]    init() consume time = 0.69026
,09-13 12:25:14.517  7453  7511 D Mms/MessagingNotification: [end]    init consume time = 3.806875
,09-13 12:25:14.517  7453  7453 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,09-13 12:25:14.517   979  1007 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,09-13 12:25:14.517  7453  7453 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,09-13 12:25:14.517   979  1483 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 12:25:14.517   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,09-13 12:25:14.517   979  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:14.517   979  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:14.517  7453  7453 D Mms/MethodReflector: getSubId is called
09-13 12:25:14.517  7453  7453 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-13 12:25:14.527   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-13 12:25:14.527  7453  7512 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 11.291875
,09-13 12:25:14.527  7453  7453 D Mms/MethodReflector: getTelephonyProperty is called
,09-13 12:25:14.527  7453  7453 D Mms/DownloadManager: roaming -> false (slotId = 0)
,09-13 12:25:14.527  7453  7453 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 12:25:14.527  7453  7453 D Mms/DownloadManager: auto download without roaming -> true
09-13 12:25:14.527  7453  7453 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-13 12:25:14.527  7453  7453 D Mms/DownloadManager: mAutoDownload ------> true
,09-13 12:25:14.527  1457  1467 D TP/MmsSmsProvider: query,matched:400, calling pid = 7453
,09-13 12:25:14.537  1457  1475 D TP/MmsSmsProvider: query,matched:0, calling pid = 7453
09-13 12:25:14.537   979  1322 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:14.537   979  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:14.537   979  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-13 12:25:14.537  1457  1475 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-13 12:25:14.537  1457  1475 D TP/MmsSmsProvider: match 0:Elapsed time : 2.082 ms
,09-13 12:25:14.537  7453  7513 D Mms/Synchronizer: [start]    doSync consume time = 12.372136
,09-13 12:25:14.547  1457  1653 D TP/MmsSmsProvider: update, matched:300, calling pid = 7453
09-13 12:25:14.547  1457  1653 V TP/MmsSmsProvider: syncDBData start
,09-13 12:25:14.547  1457  1653 V TP/MmsSmsProvider: syncDBData sms end
,09-13 12:25:14.547  1457  1653 V TP/MmsSmsProvider: syncDBData mms end
,09-13 12:25:14.547  1457  1653 V TP/MmsSmsProvider: syncDBData end
,09-13 12:25:14.547  7453  7513 D Mms/Synchronizer: [end]    doSync consume time = 10.514739
09-13 12:25:14.547   979  1466 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,09-13 12:25:14.547   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:14.547   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:14.547   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:14.547   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:14.557  6665  7514 I Finsky  : [1235] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
09-13 12:25:14.557  7516  7516 I libpersona: KNOX_SDCARD checking this for 10068
09-13 12:25:14.557  7516  7516 E Zygote  : MountEmulatedStorage()
09-13 12:25:14.557  7516  7516 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:14.557  7516  7516 E Zygote  : v2,
09-13 12:25:14.567  7516  7516 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:14.567  7516  7516 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 12:25:14.567  7516  7516 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 12:25:14.567   979  1466 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7516 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
09-13 12:25:14.567  7453  7512 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 20.741771
,09-13 12:25:14.587  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:25:14.597  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:25:14.607  7516  7516 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:14.607  7516  7516 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:14.607  7453  7503 D Mms/ArtClassLoader: init [DONE] art
,09-13 12:25:14.617  7360  7360 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,09-13 12:25:14.617  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:25:14.617   979  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:14.617   979  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:14.617   979  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,09-13 12:25:14.617   979  1501 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 12:25:14.617   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 12:25:14.627   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,09-13 12:25:14.627   979  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:14.627   979  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:14.627   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,09-13 12:25:14.627  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:14.627   979  1348 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:14.627   979  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:14.627   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-13 12:25:14.637   979  1137 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,09-13 12:25:14.637   979  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,09-13 12:25:14.637   979  1137 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:14.637  7516  7516 D BadgeProvider: onCreate
,09-13 12:25:14.637   979  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:14.637  7516  7516 D BadgeProvider: DatabaseHelper
09-13 12:25:14.637   979  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 12:25:14.647   979  1748 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:14.647   979  1748 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:14.647   979  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,09-13 12:25:14.657   979  1472 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-13 12:25:14.657  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
09-13 12:25:14.657   979  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,09-13 12:25:14.657   979  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:14.657   979  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:14.657   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,09-13 12:25:14.667  6665  6737 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-13 12:25:14.667  6665  6737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:25:14.667  6665  6737 I System.out: (HTTPLog)-Static: isShipBuild true
09-13 12:25:14.667  6665  6737 I System.out: (HTTPLog)-Thread-1218-89976486: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-13 12:25:14.667  6665  6737 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:14.667   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 12:25:14.667   279   966 D Netd    : getNetworkForDns: using netid 502 for uid 10026
,09-13 12:25:14.677   979  1483 I ActivityManager: Killing 7028:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,09-13 12:25:14.677  7453  7511 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-13 12:25:14.677  1457  1857 D TP/SmsProvider: query,matched:26, calling pid = 7453
,09-13 12:25:14.677  1457  1857 D TP/SmsProvider: match 26:Elapsed time : 1.483 ms
,09-13 12:25:14.687  1457  1653 D TP/MmsSmsProvider: query,matched:6, calling pid = 7453
,09-13 12:25:14.687  1457  1653 D TP/MmsSmsProvider: match 6:Elapsed time : 1.408 ms
,09-13 12:25:14.717   979  1472 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,09-13 12:25:14.717   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:14.717   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:14.717   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:14.717   979  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:14.727  7535  7535 E Zygote  : MountEmulatedStorage()
,09-13 12:25:14.727  7535  7535 E Zygote  : v2
09-13 12:25:14.727  7535  7535 I libpersona: KNOX_SDCARD checking this for 10023
09-13 12:25:14.727  7535  7535 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:14.727  7535  7535 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:14.727  6665  6737 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 12:25:14.737  7535  7535 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:14.737  7535  7535 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:14.737   979  1472 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7535 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,09-13 12:25:14.757  7535  7535 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:14.757  7535  7535 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:14.757   979  1348 I ActivityManager: Killing 7220:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,09-13 12:25:14.807  7535  7535 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-13 12:25:14.827  7453  7511 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-13 12:25:14.837  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,09-13 12:25:14.847  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,09-13 12:25:14.847  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,09-13 12:25:14.847  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-13 12:25:14.847  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-13 12:25:14.847  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-13 12:25:14.847  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-13 12:25:14.857  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-13 12:25:14.857  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-13 12:25:14.857  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-13 12:25:14.857  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-13 12:25:14.857  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-13 12:25:14.857  7535  7535 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-13 12:25:14.957  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,09-13 12:25:14.957  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:25:14.967  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:25:14.977   979  1479 I ActivityManager: Killing 7072:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-13 12:25:14.977   979  1479 I ActivityManager: Killing 6477:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #22
,09-13 12:25:16.027   292   292 E SMD     : DCD OFF
,09-13 12:25:16.507  7453  7453 I Mms/MmsApp:  start initViewCache mms
,09-13 12:25:16.507  7453  7453 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1935.969062
,09-13 12:25:16.507  7453  7453 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-13 12:25:16.537   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:25:16.597  7453  7453 D AbsListView: Get MotionRecognitionManager
,09-13 12:25:16.597   979  1748 D MotionRecognitionService:  ssp status : false
,09-13 12:25:16.597  7453  7453 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 93.972865
,09-13 12:25:16.697  7453  7453 D Mms/BubbleViewCache: fillCache bubble = 1
,09-13 12:25:16.797   979  1050 I PowerManagerService: [PWL] Off : 30s ago
,09-13 12:25:16.797   979  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-13 12:25:16.797   979  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-13 12:25:16.797   979  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.auth.account.be.accountstate.LoginAccountsChangedIntentService' (uid=10011, pid=4690, ws=null) (elapsedTime=43883)
09-13 12:25:16.797   979  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=7350, ws=null) (elapsedTime=3394)
,09-13 12:25:16.817  7144  7144 D CAR.SERVICE: onUnbind
,09-13 12:25:16.817  7144  7144 D CAR.SERVICE: CSB onClientsDisconnected
09-13 12:25:16.817  7144  7144 D CAR.SERVICE: tearDown
,09-13 12:25:16.817  7144  7144 D CAR.SERVICE: tearDownCarState
09-13 12:25:16.817  7144  7144 D CAR.SERVICE: Skip, car not connected.
,09-13 12:25:16.817  7144  7144 D CAR.SERVICE: tearDownClientState
,09-13 12:25:16.827  7144  7144 D CAR.SERVICE: requestStop
,09-13 12:25:16.827  7144  7144 D CAR.SERVICE: onDestroy
,09-13 12:25:16.827  7144  7144 D CAR.SERVICE: tearDown
,09-13 12:25:16.827  7144  7144 D CAR.SERVICE: tearDownCarState
09-13 12:25:16.827  7144  7144 D CAR.SERVICE: Skip, car not connected.
09-13 12:25:16.827  7144  7144 D CAR.SERVICE: tearDownClientState
,09-13 12:25:16.827  7144  7144 D CAR.SERVICE: requestStop
,09-13 12:25:16.837  7144  7144 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@1d6fb7a that was originally bound here
09-13 12:25:16.837  7144  7144 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@1d6fb7a that was originally bound here
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 12:25:16.837  7144  7144 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 12:25:16.837   979  1472 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@361edeca
,09-13 12:25:17.037   979  1096 V AlarmManager: waitForAlarm result :4
,09-13 12:25:17.167   979  3316 D SSRM:n  : SIOP:: AP = 430
,09-13 12:25:18.697   979  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-13 12:25:19.027   292   292 E SMD     : DCD OFF
,09-13 12:25:19.417   979  1058 D PackageManager: [MSG] MCS_UNBIND
,09-13 12:25:19.417   979  1479 I ActivityManager: Killing 7282:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,09-13 12:25:20.147   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:25:20.147   979  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 12:25:20.147   979  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:25:20.147   979  1479 D BatteryService: stay LED for fully charged
,09-13 12:25:20.157   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:25:20.157   979   979 I MotionRecognitionService: Plugged
,09-13 12:25:20.157   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:25:20.157  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:25:20.157  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:25:20.157  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:25:20.157  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:25:20.177  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-13 12:25:20.177  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:25:20.187  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
09-13 12:25:20.187  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:20.187  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:21.537   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:25:22.027   292   292 E SMD     : DCD OFF,
,09-13 12:25:25.027   292   292 E SMD     : DCD OFF
,09-13 12:25:25.367   979  1007 I ActivityManager: Killing 6632:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-13 12:25:25.687   979  1096 V AlarmManager: waitForAlarm result :4
,09-13 12:25:25.687   979  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-13 12:25:25.697  6665  6740 I Finsky  : [1221] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,09-13 12:25:25.927  6665  6740 I Finsky  : [1221] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,09-13 12:25:25.927  6665  6665 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,09-13 12:25:26.547   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:25:27.197   979  3316 D SSRM:n  : SIOP:: AP = 400
,09-13 12:25:27.197   979  3316 D U       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,09-13 12:25:27.207   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.videoplayer, hostingType: broadcast
,09-13 12:25:27.207   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:27.207   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:27.207   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:27.207   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:27.217  1229  1229 D ContentApp:  LEVEL : -1
,09-13 12:25:27.217   979  1043 I ActivityManager: Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7557 uid=10045 gids={50045, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,09-13 12:25:27.217  7557  7557 E Zygote  : MountEmulatedStorage()
09-13 12:25:27.217  7557  7557 E Zygote  : v2
09-13 12:25:27.217  7557  7557 I libpersona: KNOX_SDCARD checking this for 10045
09-13 12:25:27.217  7557  7557 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:27.227  7557  7557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 12:25:27.227  7557  7557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 12:25:27.237  7557  7557 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 12:25:27.247  7557  7557 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:27.257  7557  7557 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:27.267  7557  7557 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-13 12:25:27.267  7557  7557 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 12:25:27.267  7557  7557 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:27.267  7557  7557 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 12:25:27.307  7557  7557 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,09-13 12:25:27.307  7557  7557 D videowall-Global: core_num = 4
,09-13 12:25:27.307  7557  7557 W linker  : libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,09-13 12:25:27.307  7557  7557 W linker  : libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,09-13 12:25:27.317  7557  7557 D videowall-Global: density : 1.5 width : 540 height : 960 Raw width : 540 Raw height : 960
,09-13 12:25:27.317  7557  7557 D videowall-Global: dsp : 540, swkey : false, Cores : 4, Clock : 0
,09-13 12:25:27.327   979  1466 I ActivityManager: Killing 7299:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-13 12:25:28.027   292   292 E SMD     : DCD OFF,
,09-13 12:25:30.207   979  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:25:30.207   979  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:25:30.207   979  1322 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 12:25:30.207   979  1322 D BatteryService: stay LED for fully charged
09-13 12:25:30.207   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:25:30.207   979   979 I MotionRecognitionService: Plugged
,09-13 12:25:30.207   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:25:30.217  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-13 12:25:30.217  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:25:30.217  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:25:30.217  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:25:30.227  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-13 12:25:30.227  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:25:30.237  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
09-13 12:25:30.237  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:25:30.237  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:30.467  4690  4708 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+metrics_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-13 12:25:30.467  4690  4708 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+help_responses_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-13 12:25:30.467  4690  4708 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+auto_complete_suggestions_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-13 12:25:31.027   292   292 E SMD     : DCD OFF
,09-13 12:25:31.387  6910  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 12:25:31.387  6910  7214 I jxcore-log: 
,09-13 12:25:31.387  6910  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 12:25:31.387  6910  7214 I jxcore-log: 
,09-13 12:25:31.397  6910  7214 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:31.397  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:31.397  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:31.397  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:31.397  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:31.397  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:31.397  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:31.397  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:31.397  6910  7214 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:25:31.397  6910  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 12:25:31.397  6910  7214 I jxcore-log: 
,09-13 12:25:31.407  6910  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 12:25:31.407  6910  7214 I jxcore-log: 
,09-13 12:25:31.857  6910  7214 I jxcore-log: Running unit tests
09-13 12:25:31.857  6910  7214 I jxcore-log: 
,09-13 12:25:31.857  6910  7214 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 12:25:31.857  6910  7214 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94e87fd added. We now have 2 listener(s)
,09-13 12:25:31.857  6910  7214 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-13 12:25:31.857  6910  7214 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 12:25:31.857  6910  7214 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 12:25:31.857  6910  7214 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 12:25:31.857  6910  7214 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8d2cf2 added. We now have 2 listener(s)
09-13 12:25:31.857  6910  7214 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 12:25:31.867  6910  7214 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 12:25:31.867  6910  7214 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 12:25:31.867  6910  7214 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 12:25:31.867  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 12:25:31.867  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 12:25:31.867  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 12:25:31.867  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 12:25:31.867  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 12:25:31.867  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 12:25:31.867  6910  7214 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 12:25:31.867  6910  7214 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 12:25:31.867  6910  7214 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 12:25:31.867  6910  7214 D executeNativeTests: Running unit tests
,09-13 12:25:31.877  6910  6910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:31.877  6910  6910 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 12:25:31.897  6910  7214 I jxcore-log: Total number of executed tests:  1
09-13 12:25:31.897  6910  7214 I jxcore-log: 
,09-13 12:25:31.897  6910  7214 I jxcore-log: Number of passed tests:  1
09-13 12:25:31.897  6910  7214 I jxcore-log: 
09-13 12:25:31.897  6910  7214 I jxcore-log: Number of failed tests:  0
09-13 12:25:31.897  6910  7214 I jxcore-log: 
09-13 12:25:31.897  6910  7214 I jxcore-log: Number of ignored tests:  0
09-13 12:25:31.897  6910  7214 I jxcore-log: 
09-13 12:25:31.897  6910  7214 I jxcore-log: Total duration:  4
09-13 12:25:31.897  6910  7214 I jxcore-log: 
,09-13 12:25:31.907  6910  7214 I jxcore-log: Unit Test app is loaded
09-13 12:25:31.907  6910  7214 I jxcore-log: 
,09-13 12:25:31.907  6910  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:25:31.907  6910  7214 I jxcore-log: 
,09-13 12:25:31.917  6910  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 12:25:31.917  6910  7214 I jxcore-log: 
,09-13 12:25:31.917  6910  6910 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 12:25:31.917  6910  7214 I jxcore-log: My device name is: samsung-SM-A300FU
09-13 12:25:31.917  6910  7214 I jxcore-log: 
,09-13 12:25:31.917  6910  7214 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 12:25:31.917  6910  7214 I jxcore-log: 
,09-13 12:25:31.917  6910  7214 I jxcore-log: Running for WIFI network type
09-13 12:25:31.917  6910  7214 I jxcore-log: 
,09-13 12:25:31.987   979  1324 E Watchdog: !@Sync 3,
,09-13 12:25:33.027   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-13 12:25:33.027   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 12:25:34.027   292   292 E SMD     : DCD OFF
,09-13 12:25:34.197  7574  7574 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
,09-13 12:25:34.197  7574  7574 W google-breakpad: V WebView:45.0.2454.95
,09-13 12:25:34.197  7574  7574 W google-breakpad: O A arm 04 samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys
09-13 12:25:34.197  7574  7574 W google-breakpad: S 0 9DC268FC 9DC26000 00008000
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26000 7077C29D4D8FEAB6A00FFFFF9494CC9C000000002057C29D8857C29DE8D533B9000000000857C29D0457C29DF82B8BBA0000000001000000010000000200000000EE739980833A9C452A33B900000000010DEFB6DAD7FD3480DA089DE40DEFB60000000090250EB9C8DABB9CC05DC29D3C61C29DA886C99C85D388B9A5D488B9E061C29D0000000000000000B8000000000000000600000003000000199042B990250EB9F47014B910763A9C4461C29D000000001C62C29DF460C29DF4A4C19C00000000E0010000445EC29D645EC29DE05EC29DE40DEFB6445EC29D90250EB990250EB91862C29D4461C29D3C61C29D2461C29DE87BCB9CB8F91E9CD807099D306AC29DE6FFFFFF9C250EB94461C29D0000000000000000E40DEFB690250EB9B461C29D50AFCB9C10763A9C50E17C9900000000000000000200000010763A9C0163B6BB009B329CE01D419C060000000000000090250EB97077C29D4D8FEAB6000FFFFF9494CC9C000000002057C29D8857C29DE8D533B9000000000857C29D
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26180 0457C29DF82B8BBA00000000DAD7FD3401000000010000001862C29D000000000000000090250EB901000000050000000084329CE01D419C0100000082FFFFFFF461C29D680ABE9C70BD0EB9A0D10EB9487014B900D48801E061C29DDAD7FD34D86BC29DE40DEFB67062C29D4862C29D0200000000000000B46BC29D3864BC9CE01D419C060000000000000001000000B8F91E9C90250EB9000000004062C29DC462C29D000000006C62C29D240FC89C010000001046C09CA300000054FCBE9C50817A9985FFFFFF5095789990250EB900000000E86BC29DC862C29DDAD7FD34586CC29DE40DEFB6F062C29DC862C29D0200000000000000346CC29D3864BC9C90250EB99062C29D020000000800000040E27C9988FFFFFFB095789988FFFFFFD862C29D010000003466C29DE0DBBB9C8A0000000700000000000000C462C29DFC62C29D50817A99D09978998A00000007000000686CC29D90250EB90000000000000000000000002063C29D00000000106EC29DF6FFFFFF9C250EB900000000
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26300 90250EB91063C29D020000000800000090E27C9988FFFFFF309A789988FFFFFF442F8BBAD47CC29D00000000000000002036349C00000000E0D57A9988FFFFFF0863C29D0000000042338BBAF3348BBAF3348BBA3F358BBAF3348BBA01000000000000003300000077358BBAB8358BBA02000000010000000161C29DE87BCB9C80DA089D2300000008000000E6FFFFFFE073C29D4461C29D0000000000000000E40DEFB6DAD7FD34186BC29DE40DEFB6B061C29D8861C29D0200000000000000F46AC29D3864BC9C019FB3BB009B329CE01D419C060000000000000090250EB97077C29D4D8FEAB62018309E830100002036349C00000000E098789988FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000301312B990250EB9E40DEFB6A865C29D000000004D8FEAB6E8BC0EB9487CAB9CE8BC0EB9000000006C65C29D6C65C29D2018309E830100002036349C00000000609D789988FFFFFF
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26480 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000301312B990250EB901000000E8C50EB9288B72B91C65C29DE464C29D886EA19CEC64C29DE8C50EB901000000E8C50EB9C026FEB91C0000000465C29D886EA19C0C65C29DE8C50EB91465C29D2CB3A69C01000000E8C50EB94046FAB96465C29D2C65C29D886EA19C3465C29DE8C50EB93C65C29D2CB3A69C030000003870349C5C65C29DE8B3A69C5465C29DE8C50EB9E8C50EB9607C95B901000000E8C50EB95853DEB9AC65C29D7465C29D886EA19C7C65C29DE8C50EB98465C29D2CB3A69C3853DEB93870349CA465C29DE8B3A69C9C65C29DE8C50EB9E8C50EB93853DEB901000000E8C50EB9D09017BAF465C29DBC65C29D886EA19CC465C29DE8C50EB901000000E8C50EB9D01918BA82000000DC65C29D886EA19CE465C29DE8C50EB9EC65C29D2CB3A69C01000000E8C50EB9483AFEB93C66C29D0466C29D886EA19C0C66C29DE8C50EB9
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26600 1466C29D2CB3A69C283AFEB93870349C3466C29DE8B3A69C2C66C29DE8C50EB9E8C50EB9283AFEB901000000E8C50EB9E8C62ABB8466C29D4C66C29D886EA19C5466C29DE8C50EB901000000E8C50EB948C72ABB1E0000006C66C29D886EA19C7466C29DE8C50EB97C66C29D2CB3A69C01000000E8C50EB9B0F721BACC66C29D9466C29D886EA19C9C66C29DE8C50EB901000000E8C50EB9D0F721BA0C000000B466C29D886EA19CBC66C29DE8C50EB9C466C29D2CB3A69C01000000E8C50EB9600364B91467C29DDC66C29D886EA19CE466C29DE8C50EB9EC66C29D2CB3A69C400364B93870349C0C67C29DE8B3A69C0467C29DE8C50EB9E8C50EB9400364B901000000E8C50EB908A464B95C67C29D2467C29D886EA19C2C67C29DE8C50EB901000000E8C50EB901000000E8C50EB980B9799AE8C50EB94C67C29D4C67C29D307B74BA307B74BA01000000E8C50EB9B82D36B9A467C29D6C67C29D886EA19C7467C29DE8C50EB901000000E8C50EB9408764B9920000008C67C29D886EA19C
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26780 9467C29DE8C50EB99C67C29D2CB3A69C01000000E8C50EB9F84E45B9EC67C29DB467C29D886EA19CBC67C29DE8C50EB9C467C29D2CB3A69C030000003870349CE467C29DE8B3A69CDC67C29DE8C50EB9E8C50EB9D84E45B901000000E8C50EB9D03F45B93468C29DFC67C29D886EA19C0468C29DE8C50EB90C68C29D2CB3A69C030000003870349C2C68C29DE8B3A69C2468C29DE8C50EB9E8C50EB9B03F45B901000000E8C50EB9980E5DBB7C68C29D4468C29D886EA19C4C68C29DE8C50EB901000000E8C50EB901000000E8C50EB900631C9CE8C50EB96C68C29D4078A19C10DC339C030000009468C29DE8F7C29C01000000E8C50EB930ED329C0300000000631C9CE8C50EB98832F59CE8C50EB9AC68C29D8C29C39C01000000E8BC0EB918D10EB90000000000000000E8C50EB918D10EB958FB099D2469C29D1CFBA19CE8C50EB950BE0EB90000C49DF068C29DE868C29DF468C29D445CFC9CF868C29D040000000000000001000000E8C50EB950F8F29BB069C29D0C69C29D0C69C29D
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26900 38F8C39DA006E7B92469C29D50C6A19CBC13E4B80000000074BE0EB92C74F49C7C69C29DCC13A29C000000004469C29D78C372BA000000C094080FB980C372BABC13E4B80000000094080FB9010000001ED4D757B44C01007C69C29DF011E4B878BE0EB9B069C29D50BE0EB90000000000000000BC13E4B8F469C29D88DCBC9C05000000000000000000000000000000E40DEFB6A069C29DE8C50EB9613C050074BE0EB974BE0EB9000000000000000074BE0EB974BE0EB90000000000000000BC13E4B8BC13E4B800000000DAD7FD340000000050BE0EB9E8BC0EB9006AC29D00000000E8BC0EB90000000000000000346AC29D7010BD9C00000000E8BC0EB9FFFFFFFFFFFFFF7FFFFFFF7FDC34F59C346AC29D0100000050BE0EB9000000004C6AC29D0000000078BE0EB900000000746AC29D6C1ABD9C050000000000000000000000000000001ED4D757E8BC0EB9E8BC0EB90000000050BE0EB950BE0EB98C6AC29D010000000500000000000000BC6AC29D141CBD9C0000000005000000
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26A80 0000000000000000087114B90100000003000000030000004011E4B8000000000000000058FB099D07000000D82D099D90250EB92C6BC29DD46AC29D1C21BD9C000000000500000000000000246BC29D0C6BC29D907EBE9C00000000000000000700000050000000176BC29DD82D099D90250EB958FB099D030000000700000040B0329C81FFFFFF5C6BC29D8851BF9C246BC29D070000000000000088FFFFFF90250EB9608B329C0000000098DE339C00000000400000002020202061742040FFFFFFFF0700000090250EB9E8BC0EB903000000B46BC29D946BC29D0469C09C03000000201A419C5003409CA099739907000000E86BC29D904D339CB09B789988FFFFFFC099739985FFFFFF81FFFFFFAC6BC29DD014CA9C030000001C6CC29DE86BC29DE46BC29DDC6BC29D6C3CCA9CFC6BC29D608B329C046CC29D10B5739906000000B000409C90250EB910B57399E86BC29D600F379CFC6BC29D103ECA9C06000000600F379C90250EB90000000081FFFFFF1C6CC29D82FFFFFF7486309E
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26C00 A035349C0C6CC29D2854139D0057139DB8F7419C2401959D40080000600F379CB8763A9CB09B789988FFFFFFC099739985FFFFFF81FFFFFF82FFFFFF9400959D40E579994C6CC29D0000000000000000000000005C00959D400400000100000010B5739988FFFFFF10EF789988FFFFFF0300000081FFFFFFD099739990E27C99309A7899009A789910B5739988FFFFFFA00F339CD0997899009A789920E57999B0280A9E80020000C036349C020000000000000082FFFFFFA00F339C88FFFFFFD099789988FFFFFF00000000D099789970997899A0997899A4460A9E800200000037349C000000007099789988FFFFFFE40DEFB6586EC29D010000004D8FEAB6E8BC0EB940B0329CB09273990037349C2018309E03020000603F379C0100000040B0329C88FFFFFFB092739985FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000090250EB9E40DEFB6
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26D80 D86EC29D0100000081FFFFFF306EC29D9C6EC29D14E4AB9C603F379C0000000000000000006EC29DB46DC29D3817309E58FB099D90250EB9487014B9D47CC29D000000000000000000000000010000000476C29D90250EB90001C29D0000000058450A9E00000000603F379C9072C29D020000000100000000000000000000000100000081FFFFFF003F379C80823A9C6872C29DF6FFFFFF9C250EB90100000090250EB9306EC29D00000000080000000100000090250EB91872C29D506EC29DCC71C29D2486C99C01000000000000001872C29D01000000D86EC29D90250EB9785B139D80823A9C00000000483AB3BB9C6EC29DDAD7FD340000000090250EB9D86EC29DA06EC29D603F379C80823A9C00000000483AB3BBC46EC29D2C85C99C00000000AC6EC29DC46EC29DE40DEFB60100000090250EB99872C29DD06EC29D4C72C29D2486C99C00000000000000009872C29D01000000E82C099D0100000080823A9CD06EC29D0000000000050000000000000000000000000000046FC29D
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC26F00 146FC29D146FC29D3074C29D146FC29D5C6FC29D84F9AF9C346FC29D4C3CF49C2C00000000000000F8CEB6BB5871C29D5C6FC29D3CF8AF9C24010000D072C29DE40DEFB6606FC29D102C1C9C50427999F8CEB6BB90250EB9D470C29D1CFEAF9C96D833B9A4D833B9A4D833B9D0D833B9A4D833B901000000000000003400000008D933B908D933B9010000000100000001BE329C0000000080DA089DEC6FC29D06000000010000004076C29D700000000000000090250EB908000000080000003A19FBB9F019FBB9641AFBB90E0000005473C29D58FB099D90250EB95473C29DB4F5B6BB2C73C29DFC6FC29DA86EBF9CFFFFFF005473C29D0C70C29D583378990000000058FB099D3C70C29D947ACB9CE40DEFB6D807099D4870C29D9C73C29D08010000A473C29DF474C29D0800000000000000000000000000000000000000000000000000000000000000CC73C29DE22E33B95C75C29DE874C29D080000000000000000000000000000000000000000000000000000000000000000000000
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC27080 00000000E40DEFB6BC70C29DB870C29D60DF419C1474C29D0100C29DC070C29D6875C29D0800000000000000000000000000000000000000000000000000000090250EB9DA75C29D30BD329C000000000000000000D7FD340876C29D01000000188D5F9E5000000000000000000000000000000000000000CC71C29D18BFCB9C00000000FFFFFF000100000000000000B4F5B6BB01000000000000004071C29DDC75C29D5871C29D0019FBB9A21AFBB9F019FB0000661C9C993718B9E40DEFB6000000000000000050BE329C000000000000000090250EB901000000050000000084329C60DF419C0073C29D60DF419CA471C29D680ABE9C70BD0EB9A0D10EB9487014B900FFFF000100000090250EB95833789990250EB940E27C9960DF419CCC71C29D7849BF9C0073C29D5473C29D2C73C29D90250EB958FB099D0100000000000000010000006472C29D38BFBF9C0073C29DFFFFFF00010000000000000090250EB92C73C29D6472C29D24DBBF9C9C250EB9E40DEFB69C01B99C8401B99C
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC27200 03000000583378991C72C29D88FFFFFF00B0329CA472C29D10C0329C85FFFFFF4C72C29D7849BF9C00000000DAD7FD34E40DEFB68872C29D90250EB93873C29D9872C29D483AB3BBF472C29DE48AC99C2C73C29D40E27C9990250EB940B0329C9872C29D01000000507DC29DF6FFFFFF9C250EB95874C29D90250EB98872C29D0300000008000000603F379C88FFFFFF40B0329C88FFFFFFB092739985FFFFFF5874C29D4873C29D0C73C29DC8C6BE9C010000006473C29D5874C29D800000003011B7BB6874C29D00000000DAD7FD340000100090250EB94873C29D3873C29D4073C29D3473C29D82FFFFFF403AB3BB2473C29D3875B99C403AB3BB4073C29D40B0329C88FFFFFF8473C29DB873C29D9874C29D010000005073C29D000000008473C29D200BDB9C4073C29D030000005874C29D40B0329C603F379C88FFFFFF0000000082FFFFFF01000000403AB3BB0000000082FFFFFF90250EB9000000006C37F49CB873C29DA873C29D984FD6B83052D6B890250EB99874C29D6C37F49C
09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC27380 F473C29DB81AD29CB873C29D431CECB6B0F7B6BB000000C0889AB6BBB8F7B6BB0C74C29D8D21ECB640B0329C88FFFFFF90250EB900000000B092739985FFFFFF90250EB900000000C4F7B6BB0874C29D4B0000002874C29D9874C29D1874C29D90250EB90C74C29D22000000984FD6B85C74C29DEC8AD39CE4F8F39C50FCF39C58FB099D22000000949AB6BBE4DBB6BB000000002C74C29D2200000000000000B075C29D000000004474C29D1455919CE074C29DB075C29D18E10A9DA874C29D00000000010000009874C29D8874C29D2200000090250EB9EC75C29D28B4D69CA8F6B6BB00000000102C1C9C30D1419C90250EB9C074C29DD874C29DE074C29D00000000000000000000000082FFFFFF0000000000010000220000000000000001250EB9DAD7FD3400FFFFFF90250EB9010000001076C29D2076C29D01927399A8F6B6BB4B0000004B0000000138309E504A79990074C29D90250EB982FFFFFF584D139D060000003CE10A9D3CE10A9D0600000018E10A9D00000000FFFFFFFF
,09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC27500 00000000F8F6B6BB2200000082FFFFFFA0A63A9C102C1C9C00E57999102C1C9CA09273991003409C88FFFFFF80FD369CD0C9359C01000000C0A63A9C1003409CE8D2099E80FD369CD0C9359C88FFFFFF6076C29D6CD4099E6076C29D6475C29DC075C29D000000000000000034D4099E40030000010000000000000085FFFFFF8092739985FFFFFF0100000081FFFFFF30BD329C9C75C29DA0CB429C909273994070379CC0EE789938040A9E00050000C0A63A9C010000000000000082FFFFFF8092739985FFFFFFC103000088FFFFFFF0F5B6BB00E57999102C1C9CA092739968F6B6BB1003409C82FFFFFFCCE6969D1003409CFC75C29DC0E47999000000000000000094E6969D40030000010000006049369C88FFFFFF00EA329C88FFFFFF504A799985FFFFFF00000000C088369C30BD329CA0C6359C504A799930BD329C8CE9309E82010000C080369C01000000A0C6359C88FFFFFF504A799985FFFFFFBC76C29DA8E837BBE09B5F9E01050000504A799985FFFFFFA0C6359C88FFFFFF
09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC27680 C080369C88FFFFFF0000000082FFFFFF0000000083FFFFFFD0487A9988FFFFFF5000000050BE329CE0B9359CFFFFFFFF0100000060897A9900000000808D429CF85C5D9E000A000020D5369C010000000000000082FFFFFF504A799985FFFFFF0000000082FFFFFF00000000C0D5369C50BE329C82FFFFFF0100000082FFFFFF504A799982FFFFFF0000000082FFFFFF0000000082FFFFFFA0D5369C50BE329CA0D5369C05000000F0897A9982FFFFFF0000000083FFFFFF20467499C0D5369C04000000E0FD299C0000000085FFFFFF0E0000000D0000000000000080FD2A9C00D5369C60C85099F0C5259C50BE329C8CE9309E0202000080D6369C0200000000D5369C88FFFFFF60C8509985FFFFFFF0C5259C88FFFFFF2478C29DF81861BAF44EA19D01080000F0C5259C88FFFFFF60C8509985FFFFFF00D5369C88FFFFFF80D6369C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFF0C5259C88FFFFFF60C8509985FFFFFFB022249C88FFFFFF00000000CCF65C9E
09-13 12:25:34.227  7574  7574 W google-breakpad: S 9DC27800 40030000010000008000000050BE329CE0E5329C88FFFFFF60C8509985FFFFFF000000005078C29D8CE9309E0202000000D9369C0200000000D5369C88FFFFFF60C8509985FFFFFFE00C229C88FFFFFF9C79C29D904146B908B8A09D01140000E00C229C88FFFFFF60C8509985FFFFFF00D5369C88FFFFFF00D9369C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000083FFFFFF9479C29D1091BF9CB088C29DE44BFC9C
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC27980 4001000050BE329C087AC29D90250EB9B079C29D58FB099D00000000087AC29D9016309E0403000020DB369C0200000000D5369C88FFFFFF60C8509985FFFFFFE00C229C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF8CE9309E0202000020DB369C0200000000D5369C88FFFFFF60C8509985FFFFFFE00C229C88FFFFFF947AC29D404B45B93C4D9A9D01080000E00C229C88FFFFFF60C8509985FFFFFF00D5369C88FFFFFF20DB369C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000006C06000080060000820600008000000050BE329C488BC29D00000000000000000800000000000000D87AC29D8CE9309E82030000E0D6369C0500000000D5369C88FFFFFF60C8509985FFFFFFE00C229C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF4C7BC29D184645B910669A9D810600000000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC27B00 E00C229C88FFFFFF60C8509985FFFFFF00D5369C88FFFFFFE0D6369C88FFFFFF010000000C0000008077C29D1499989C6800000050BE329C5E0100000100000060D850990000000000000000987BC29D8CE9309E0204000020D7369C06000000E00C229C88FFFFFF60C8509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000083FFFFFF147CC29D784C45B960629A9D010700000000000083FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF60C8509985FFFFFFE00C229C88FFFFFF20D7369C88FFFFFF15000000200000002E002F0042007500700000002022249C5500740069006C002E00660061006C0000000000587CC29D301A309E030400000028299C010000000000000082FFFFFF60C8509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC27C80 00000000000000000000000000000000000000000000000000000000207DC29D7018309E90250EB9D47CC29D000000000028299C207DC29D1C7DC29DB4D6A89C0028299C0000000000000100407DC29D0000000090250EB9487014B9EC7EC29D000000000000000000000000010000009891C29D90250EB900010EB900000000E40DEFB6507DC29D90250EB9D07EC29D707DC29D00000000DC7DC29DFCD9A89C20609A9D000000000028299C707DC29D060000000100000000000100000000000100000081FFFFFF00000000000000007883C29DF6FFFFFF9C250EB90000000090250EB9707DC29D06000000080000000000000082FFFFFF60C8509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000000000C47DC29D20E1A89C8046379CDAD7FD3490250EB990250EB9D07EC29D0000000000000000B07EC29D58FB099D907FC29D547FC29DF07DC99C0000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC27E00 0000000000000000000000000000000000000000000000000000000000000000000000005475FC9CEC7EC29DE40DEFB600E4119C00000000000000000028299C0000000002000000000000008046379C000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C090250EB9000000000000000082FFFFFF0000000082FFFFFFB85EDCB800000000B05B16B90100000034BD0EB9817EC29D90250EB9B4BD0EB9000000001079C29DE82C099D010000008046379CB07EC29D0000000000D7FD3450F590BB90250EB9487014B9E496C29D00000000000000000000000000000000907FC29DB85B16B93EEC90BB505B16B9505B16B9000000003C7FC29D20E1A89C00E4119CDAD7FD3490250EB990250EB9907FC29D587FC29DA028299C00E4119C0000000090250EB97C7FC29D0084C99C00000000E40DEFB600100000E40DEFB60010000090250EB9C0E790BB887FC29D0483C29D2486C99C
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC27F80 00000000E40DEFB6C0E790BB08000000E82C099D0100000000E4119C887FC29D0000000000E3119CC05BDCB80024359CD03A079D90250EB93000009D40B0329C0000000090250EB9000000000000000000000000000000000000000000000000A47FC29D0000000001000000C0EB90BB00000000E823359C00000000000000000000000068000000000000000000000000000000000000000100000058FB099D0F0000000000000001000000908EC29DFFFFFF00348DC29D908FC29D02000000000000000000000000000000DA774733A0D1419C010000009C01B99C724D82B8B07FC29D0000000080E3119C0000000090250EB98080C29D000000000000000058FB099D78E9F39C90250EB99880C29D0000000000000000F480C29DD080C29D000000000100000000000000FC00000090250EB958F590BB070000000004000001000000D080C29D90250EB950F190BB0600000000040000801D419C90250EB9060000000F0000000300000068D590BBB080C29DB088C29DE85BFC9C00000000
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28100 00000000000000000000000090250EB9010000000000000001000000000000000000000060A7C39A90250EB93881C29D00000000000000000000000020C490BB010000007C5BDCB8000000000000000090250EB96081C29D00000000000000000000000082FFFFFF90250EB97881C29D0000000000000000B881C29D8C81C29D00002100000000000181C29D9454D59C00000000B07FC29D0000000000000000040000000000000000000000000000000000000000000000FFFFFFFF000000000000000090250EB9B4BD0EB9F8D1B0B990250EB9E081C29D000000001000000008C490BB0082C29D38E790BB000000C034D590BB40E790BB50D590BB50D590BB40FD299C85FFFFFF48D590BB000000C058FB099D50D590BB984FD6B88D21ECB690250EB93082C29D0000000010000000984FD6B84D8FEAB601000000C0E2D79C00000000A882C29D9882C29D5C82C29D01000000A882C29DFC82C29DE4FFD79C20D590BB20D590BB0100000090250EB9648EC29D000000000000000090250EB9
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28280 0000000090250EB9B488C29DE5FFFFFF9C250EB9E482C29D90250EB9A882C29D00000000080000008B00000080000000B0E790BB0300000000000000431CECB600D0EEB60483C29D10000000800000005083C29DC0E790BB0000000090250EB90483C29DDAD7FD348090C29DE40DEFB67883C29D5083C29D0A00000000000000BC8CC29D3864BC9C6F0000007300000095000000D2000000E2000000E6000000E7000000ED00000017010000250100005A0100005C010000080000000A0000009483C29D9041F2962C84C29D487014B980C5259C90250EB99483C29D9090C29DCC83C29D080000000100000000000000C0E790BB080000006090C29DF6FFFFFF9C250EB9AC83C29D90250EB9B0E790BB0A00000010000000387B2D9C007B139C60D090BB01000000CC83C29D8888CB9C00000000387B2D9C90250EB958FB099D507B2D9C90250EB99C84C29D9C84C29DD87A2D9C087B2D9CD87A2D9C007B139C60D090BB010000000C84C29D8888CB9C0000000000000000009B329C10D090BB
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28400 2C84C29D0800000001000000E40DEFB6000000000000000060D090BB010000004484C29D90250EB901000000030000000084329C40BC419C3086C29D40BC419C7484C29D680ABE9C70BD0EB9A0D10EB9487014B90026299C90250EB990250EB9507B2D9C90250EB9007B139C40BC419C9C84C29D7849BF9C3086C29D1087C29D1487C29D90250EB958FB099D0000000000000000000000003485C29D38BFBF9C3086C29D080000000000000000000000DC84C29DDAD7FD3470BD0EB97000000090250EB9E40DEFB69C01B99C8401B99C007B139C507B2D9C90250EB9701F419C0085C29DCC0EBE9C70BD0EB9A0D10EB9487014B90087C29D8C87C29D387B2D9C0100000000000000388FC29DDAD7FD340E0000005D0100005E0100000000000060D8509900000000548BC29D00EAAF9C100000005701000058010000FCFFAF9C60C85099FC8BC29D90250EB9A08EC29D030000005801000059010000E40DEFB6F0D4419C8401B99CE6FFFFFF387B2D9C0E0000005A0100005B010000E085C29D
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28580 6006409CE801B99CA485C29DECF1C99C00000000000000000F0000000286C29D7AEE90BB78EE90BBC0EB90BB80EE90BB7CEE90BBC0C590BB000000000000000090250EB9D085C29D15000000200000002E002F004200750066006600650072005500740069006C002E00660061006C006C006200610063006B00000001000000010000000100000058FB099D01000000000000000000000000000100000100000000000000000000000000000000000000000000000000000101000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28700 00000000000000000000000000000000000000000000000000000100000100000000000000000000000000000000000000000100010000010101000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001000000010000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000010000000101000100000000000100010001000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000FF90250EB900000000D882C29D00000000
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28880 F85ADCB8085BDCB8B05BDCB800000000000000000000000034BD0EB90000000060D850994001000057010000F082C29DF03A079DDC82C29DFDFFFFFF9C250EB990250EB9B4BD0EB990250EB9D888C29D1000000080000000000000006E0000006F0000007300000095000000D2000000E2000000E6000000E7000000ED00000017010000250100005A0100005C0100005D010000FFFFFFFF000190BB0000000058450A9E00000000603F379CD08DC29D02000000010000000000000000000000007B139C88FFFFFF00000000D807099DA88DC29DF6FFFFFF9C250EB90100000090250EB97089C29D0000000008000000000000000000000000000000000000000000000000000000E22E33B902000000C489C29D0873999C188AC29D90250EB9785B139D048CC29D0100000090250EB958FB099D0100000000000000000000005C8AC29DB8C2BF9C908BC29D80823A9CDAD7FD3401000000048AC29D0C84C99C010000000800000000000000E40DEFB69C01B99C8401B99CD88DC29D108AC29D
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28A00 008DC29D2486C99C0000000090250EB9D88DC29D01000000E82C099D0100000080823A9C108AC29D00000000008F119CD8771D9CDAD7FD34000000000100000058FB099D048CC29D90250EB9148BC29D908BC29D083B079DF48AC29D30C5BF9C9C01B99C01000000908BC29D0000000000000000E6FFFFFF9C250EB9B48AC29D00000000E40DEFB69C01B99CAC8AC29DF8969F9DE88AC29DA49A9F9DE48AC29D00A6369C90250EB9B48AC29DB48AC29DCC8AC29DF0E8AF9C20000000E40DEFB6E8FC0EB9A49A9F9D048EC29D9CFFAF9CE8BC0EB958FB099D010000000E000000388FC29DB8D017B9030000005F010000600100006800000000000000000000000000000000000000010000006001000060010000908EC29DFFFFFF00348DC29D908FC29D020000000E0000005D0100005E0100000000000060D8509900000000548BC29D00EAAF9C100000005E0100005F010000FCFFAF9CE8BC0EB9FC8BC29D90250EB9A08EC29D00000000010000000F000000030000007AEE90BB78EE90BB
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28B80 C0EB90BB80EE90BB80EE90BBC0C590BB000000000000000090250EB9A88BC29D0000000020000000C48BC29DF0E8AF9C1F000000E40DEFB6E8FC0EB908A8999DFC8EC29D9CFFAF9CE8BC0EB9947ACB9C9890C29D0000000000000000E7F113B97892C29D0100000000000000000000000000010000010000000000000000000000000000000000000000000000000000010100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000DAD7FD3400000000E40DEFB60000000090250EB9045EBC9CC88CC29D00000000D091C29D4490C29DA886C99C00000000000000009090C29D0200000090250EB990250EB9288DC29DAC8DC29D1C8DC29D74E1CB9C90250EB9F88EC29D348DC29DE820CC9C008FC29D40B0329C
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28D00 0100000000000000AC8DC29D6C5B16B95834099DF032099D4C8DC29DF4B0C89C0000000080E3119C40B0329CF08EC29D4C8DC29D90250EB9605B16B9605B16B990250EB9605B16B9C48EC29DB4F7C89C0000000000000000000000000000000000000000E490C29D0000000000000000E091C29D08000000000000000000000000000000000000000000000000000000000000005475FC9C5C8EC29DE40DEFB680E3119C0000000000000000A028299C000000000200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000001010001000000000001000100010000000000000000000000000000000000000082FFFFFF0000000082FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000FF90250EB900000000B088C29D01000000F85ADCB890250EB9487014B9E496C29D00000000000000000000000000000000F08EC29DA05B16B9
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC28E80 7785D0B9605B16B9605B16B900000000AC8EC29D20E1A89C80E3119CDAD7FD3490250EB990250EB9F08EC29DC88EC29D0000000080E3119CDAD7FD3401000000EC8EC29D0C84C99C000000000C8FC29D0000000080E3119C7C8FC29D90250EB9F08EC29D588FC29D3C8FC29D0100000090250EB96066349C02000000A0F8369C80C5259C6066349C3C8FC29D781DBE9C70BD0EB9A0D10EB9487014B9008FC29DA08FC29D070000000200000088FFFFFFD891C29D90250EB96C8FC29D5474999C0100000000000000A08FC29D4C91C29D0700000090250EB958FB099D0100000000000000000000000490C29DB8C2BF9CD891C29D5470B99CD090C29D80E3119CD090C29D3C90C29D0700000082FFFFFFBC8FC29DE40DEFB69C01B99C8401B99CA028299C88FFFFFF008FC29DBC8FC29D00000000C08FC29DE48FC29DDC03DB9C0000000082FFFFFF90250EB9000000001C90C29DE48FC29D01000000DAD7FD343491C29D0100000058FB099D4C91C29D90250EB9BC90C29DD891C29D083B079D
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC29000 9C90C29D30C5BF9C9C01B99C01000000D891C29D000000000000000028C4139D28C4139DDAD7FD34E40DEFB68090C29D90250EB92891C29D9090C29DD091C29DEC90C29DE48AC99C0000000082FFFFFF90250EB9A028299C9090C29D020000004091C29DF6FFFFFF9C250EB990250EB990250EB98090C29D0400000008000000C0D0329C88FFFFFFA028299C88FFFFFFE0EB2E9C88FFFFFF80C5259C88FFFFFFC0D0329C000000000100000082FFFFFF0000000000000000000000000F0000007891C29DDAD7FD34E490C29DB091C29D4892C29D0200000090250EB9400364B9010000004F0000007491C29D588CA89CC091C29D8891C29DB091C29D0000000000000000000000002891C29D000000001C0600003DF313B9000000000045379C0100000008000000C0D0329C88FFFFFFA028299C88FFFFFF4C91C29D0A0000006097C29D040000009C250EB9B091C29D090000008891C29DA091C29D08A8999D4000000042000000400364B988FFFFFFD091C29D8896309EB091C29D8891C29D
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC29180 400000008891C29D0000000082FFFFFF503A139DD8FA419CE4D1309E820300004892C29D400364B902000000B091C29DC0D0329C88FFFFFFA028299C88FFFFFFE0EB2E9C88FFFFFF80C5259C88FFFFFF7492C29D400364B938B1999D8109000080C5259C88FFFFFFE0EB2E9C88FFFFFFA028299C88FFFFFFC0D0329C88FFFFFF80C5259C88FFFFFFA028299C88FFFFFFD0FD299C85FFFFFF0000000082FFFFFF0000000082FFFFFFB0FD299C85FFFFFF0028299C88FFFFFF70FD299C85FFFFFF0000000082FFFFFF0813A09D810400000000000081FFFFFF980000002022249C0037339C88FFFFFF70E0329CC0BA419C04000000B092C29D8CE9309E0203000040D7369C04000000E00C229C88FFFFFF50FD299C85FFFFFFE067289C85FFFFFF0000000082FFFFFF0000000082FFFFFF2493C29D18BF68B96085999D810600000000000082FFFFFF0000000082FFFFFFE067289C85FFFFFF50FD299C85FFFFFFE00C229C88FFFFFF40D7369C88FFFFFF50FD299C85FFFFFF2493C29DF0839A9C
09-13 12:25:34.237  7574  7574 W google-breakpad: S 9DC29300 2C93C29DF0839A9C6800000050BE329C000000005493C29D5493C29D45000000000000005893C29D8CE9309E8202000060D7369C0300000080E2369C88FFFFFFE00C229C88FFFFFFE067289C85FFFFFFA046269C88FFFFFFDC93C29DD8A068B9D470999D81070000A046269C88FFFFFFE067289C85FFFFFFE00C229C88FFFFFF80E2369C88FFFFFF60D7369C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC0F3299C85FFFFFF300D229C88FFFFFFE00C229C88FFFFFF7800000050BE329C0C94C29D3410A09D003F349C88FFFFFF000000001094C29D8CE9309E8202000000D7369C03000000E00C229C88FFFFFFE067289C85FFFFFFA046269C88FFFFFF0000000082FFFFFFA494C29DF0DC4CB918569A9D810800000000000082FFFFFFA046269C88FFFFFFE067289C85FFFFFFE00C229C88FFFFFF00D7369C88FFFFFF0100000083FFFFFFE00C229C88FFFFFF0000000082FFFFFF0000000087FFFFFF0000000082FFFFFFE067289C85FFFFFFE00C229C88FFFFFF
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC29480 90250EB900FEFFFF8800000050BE329CC494C29D44A9A79C970800009808000000000000E894C29D8CE9309E82030000E0D6369C0500000000D5369C88FFFFFFA0D4509985FFFFFFA046269C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF5C95C29D184645B910669A9D810600000000000082FFFFFF0000000082FFFFFF0000000082FFFFFFA046269C88FFFFFFA0D4509985FFFFFF00D5369C88FFFFFFE0D6369C88FFFFFF487014B9384C45B9B095C29D8046379C6800000050BE329C384C45B988FFFFFF8495C29D44A9A79C00000000A895C29D8CE9309E0204000020D7369C06000000A046269C88FFFFFFA0D4509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000083FFFFFF2496C29D784C45B960629A9D010700000000000083FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFA0D4509985FFFFFFA046269C88FFFFFF20D7369C88FFFFFF1300000020000000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC29600 2E002F005000650070000000C0D7219C73006100670065004400650066006C00000000006896C29D301A309E03040000E08D139C010000000000000082FFFFFFA0D4509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000003097C29D7018309E90250EB9E496C29D00000000E08D139C3097C29D2C97C29DB4D6A89CE08D139C00000000808E139C5097C29D0000000090250EB9487014B9FC98C29D00000000000000000000000001000000A8ABC29D90250EB900010EB900000000E40DEFB66097C29D90250EB9E098C29D8097C29D00000000EC97C29DFCD9A89C20609A9D00000000E08D139C8097C29D0600000001000000808E139C000000000100000081FFFFFF00250EB9A498C29D889DC29DF6FFFFFF9C250EB90000000090250EB98097C29D0600000008000000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC29780 0000000082FFFFFFA0D4509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000000000D497C29D20E1A89C8046379CDAD7FD3490250EB990250EB9E098C29D0000000000000000C098C29D58FB099DA099C29D6499C29DF07DC99C185B16B9000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000005475FC9CFC98C29DE40DEFB600E2119C0000000000000000E08D139C0000000002000000000000008046379C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000090250EB960BC419C0000000082FFFFFF0000000082FFFFFF40B0329C00000000285B16B901000000D080349C0199C29D90250EB9B4BD0EB9000000002093C29DE82C099D010000008046379CC098C29D0000000000D7FD3480E1119C90250EB9
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC29900 487014B9F4B0C29D00000000000000000000000000000000A099C29D305B16B96C1965BB805A16B9805A16B9000000004C99C29D20E1A89C00E2119CDAD7FD3490250EB990250EB9A099C29D6899C29D808E139C00E2119C0000000090250EB98C99C29D0084C99C00000000E40DEFB600100000E40DEFB60010000090250EB9289D66BB9899C29D149DC29D2486C99C00000000E40DEFB6289D66BB08000000E82C099D0100000000E2119C9899C29D0000000000E1119C0861DCB80024359CD03A079D90250EB94000009D40B0329C0000000090250EB9000000000000000000000000000000000000000000000000B499C29D0000000001000000E0B48FBB00000000E823359C00000000000000000000000068000000000000000000000000000000000000000100000058FB099D0F0000000000000001000000A0A8C29DFFFFFF0044A7C29DA0A9C29D02000000000000000000000000000000DA774733A0D1419C010000009C01B99C724D82B8C099C29D0000000080E1119C00000000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC29A80 90250EB9909AC29D000000000000000058FB099D78E9F39C90250EB9A89AC29D0000000000000000049BC29DE09AC29D0000000001000000000000007C1D000090250EB9A8F08FBB070000000004000001000000E09AC29D90250EB9F03865BB0900000000040000801D419C90250EB9060000003701000003000000E80666BBC09AC29DC0A2C29DE85BFC9C0000000000000000000000000000000090250EB90100000000000000010000000000000000000000A0A6C39A90250EB9489BC29D000000000000000000000000104266BB010000003C5BDCB8000000000000000090250EB9709BC29D00000000000000000000000082FFFFFF90250EB9889BC29D0000000000000000C89BC29D9C9BC29D0000210000000000019CC29D9454D59C00000000C099C29D0000000000000000320000000000000000000000000000000000000000000000FFFFFFFF000000000000000090250EB9B4BD0EB9F8D1B0B990250EB9F09BC29D0000000010000000E84166BB109CC29D580666BB000000C0
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC29C00 FC0366BB600666BB180466BB180466BBC0AC2E9C85FFFFFF100466BB000000C058FB099D180466BB984FD6B88D21ECB690250EB9409CC29D0000000010000000984FD6B84D8FEAB601000000C0E2D79C00000000B89CC29DA89CC29D6C9CC29D01000000B89CC29D0C9DC29DE4FFD79CE80366BBE80366BB0100000090250EB974A8C29D000000000000000090250EB90000000090250EB9C4A2C29DE5FFFFFF9C250EB9F49CC29D90250EB9B89CC29D0000000008000000000A980D3A000000189D66BB0300000000000000431CECB600D0EEB6149DC29D1000000080000000609DC29D289D66BB0000000090250EB9149DC29DDAD7FD3490AAC29DE40DEFB6889DC29D609DC29D0A00000000000000CCA6C29D3864BC9C86000000C3000000D3000000D7000000D8000000F700000012010000390100006201000096010000CE010000CF010000080000000A000000F5010000F60100001C0200003E020000F03C159C580200007E020000A0AAC29DB402000008000000EC020000EE020000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC29D80 289D66BB0800000070AAC29DF6FFFFFF9C250EB94303000090250EB9189D66BB0A000000100000008C0300009003000091030000CB030000F00300001404000083040000870400009E040000E7040000120500004A0500004B0500005E0500008F050000C3050000D3050000FA05000000060000100600001306000014060000180600004506000048060000570600005B0600005C0600008E060000B4060000C7060000F80600002C0700003C070000420700005207000055070000560700005A070000870700008A070000990700009D0700009E070000D0070000F6070000090800003A0800006E0800007E080000840800009408000097080000980800009C080000CE080000D1080000E0080000E4080000E50800001B0900006209000088090000B6090000E80900000E0A00001E0A0000340A00003F0A00005F0A00007D0A0000810A0000B00A0000B10A0000D90A0000DA0A0000ED0A00001E0B0000740B0000850B0000B30B0000D90B0000E90B0000F10B00003B0C00004D0C0000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC29F00 550C00005B0C00006B0C00006E0C0000010000003301000048A9C29DDAD7FD340E000000DA1D0000DB1D000000000000A006409C00E06F400000000000EAAF9C0E000000DD1D0000DE1D0000FCFFAF9CC031419C0000000000000000B0A8C29D10000000D71D0000D81D0000E40DEFB60007409C000000000000000068C5209C03000000D81D0000D91D0000F09FC29D0000000000E06F4000000000ECF1C99C01000000000000003701000002A0C29D9AF08FBB98F08FBBE0B48FBBA0F08FBB9CF08FBBA06066BB000000000000000090250EB9189D66BB050000004000000066006900720073007400200061007200670075006D0065006E00740020006D00750073007400200062006500200061002000760061006C006900640020006500000000000000000000000100000100000000000000000000000000000000000000000000000000000101000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2A080 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001000001000000000000000000000000000000000000000001000100000101010000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000010000000100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2A200 00000000000000000000000000000000000000000000000000000000000000010000000101000100000000000100010001000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000FF90250EB900000000E89CC29D00000000F85ADCB8085BDCB80C60DCB800000000000000000000000034BD0EB900000000C035419C061800000D180000009DC29DF03A079DEC9CC29DFDFFFFFF9C250EB990250EB9B4BD0EB990250EB9A8A766BB3801000000020000000000006400000086000000C3000000D3000000D7000000D8000000F700000012010000390100006201000096010000CE010000CF010000D3010000F1010000F5010000F60100001C0200003E0200003F020000580200007E0200009B020000B4020000D1020000EC020000EE020000EF020000F30200001203000016030000170300004303000044030000480300007A0300007D030000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2A380 8C0300009003000091030000CB030000F00300001404000083040000870400009E040000E7040000120500004A0500004B0500005E0500008F050000C3050000D3050000FA05000000060000100600001306000014060000180600004506000048060000570600005B0600005C0600008E060000B4060000C7060000F80600002C0700003C070000420700005207000055070000560700005A070000870700008A070000990700009D0700009E070000D0070000F6070000090800003A0800006E0800007E080000840800009408000097080000980800009C080000CE080000D1080000E0080000E4080000E50800001B0900006209000088090000B6090000E80900000E0A00001E0A0000340A00003F0A00005F0A00007D0A0000810A0000B00A0000B10A0000D90A0000DA0A0000ED0A00001E0B0000740B0000850B0000B30B0000D90B0000E90B0000F10B00003B0C00004D0C0000550C00005B0C00006B0C00006E0C0000010000003601000048A9C29DB8D017B903000000DF1D0000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2A500 E01D0000680000000000000000000000000000000000000001000000E01D0000E01D0000A0A8C29DFFFFFF0044A7C29DA0A9C29D020000000E000000DD1D0000DE1D0000FCFFAF9CC031419C0000000000000000B0A8C29D10000000DE1D0000DF1D0000FCFFAF9CE8BC0EB90CA6C29D90250EB9B0A8C29D000000000100000037010000030000009AF08FBB98F08FBBE0B48FBBA0F08FBBA0F08FBBA06066BB000000000000000090250EB9B8A5C29D0000000020000000D4A5C29DF0E8AF9C1F000000E40DEFB6E8FC0EB908A8999D0CA9C29D9CFFAF9CE8BC0EB9947ACB9CA8AAC29D0000000000000000E7F113B988ACC29D0100000000000000000000000000010000010000000000000000000000000000000000000000000000000000010100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2A680 000000000000000000000000000000000000000000000000000000000000000000000000DAD7FD3400000000E40DEFB60000000090250EB9045EBC9CD8A6C29D00000000E0ABC29D54AAC29DA886C99C0000000000000000A0AAC29D0200000090250EB990250EB938A7C29DBCA7C29D2CA7C29D74E1CB9C90250EB908A9C29D44A7C29DE820CC9C10A9C29D40B0329C0100000000000000BCA7C29D9C5A16B95834099DF032099D5CA7C29DF4B0C89C0000000080E1119C40B0329C00A9C29D5CA7C29D90250EB9905A16B9905A16B990250EB9905A16B9D4A8C29DB4F7C89C0000000000000000000000000000000000000000F4AAC29D0000000000000000F0ABC29D08000000000000000000000000000000000000000000000000000000000000005475FC9C6CA8C29DE40DEFB680E1119C0000000000000000808E139C00000000020000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000010000000101000100
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2A800 0000000001000100010000000000000000000000000000000000000082FFFFFF0000000082FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000FF90250EB900000000C0A2C29D01000000F85ADCB890250EB9487014B9F4B0C29D0000000000000000000000000000000000A9C29DD05A16B9D7AF66BB905A16B9905A16B900000000BCA8C29D20E1A89C80E1119CDAD7FD3490250EB990250EB900A9C29DD8A8C29D0000000080E1119CDAD7FD3401000000FCA8C29D0C84C99C000000001CA9C29D0000000080E1119C8CA9C29D90250EB900A9C29D68A9C29D4CA9C29D0100000090250EB96066349C02000000A0F8369CF03C159C6066349C4CA9C29D781DBE9C70BD0EB9A0D10EB9487014B900A9C29DB0A9C29D070000000200000088FFFFFFE8ABC29D90250EB97CA9C29D5474999C0100000000000000B0A9C29D5CABC29D0700000090250EB958FB099D01000000000000000000000014AAC29DB8C2BF9C
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2A980 E8ABC29D5470B99CE0AAC29D80E1119CE0AAC29D4CAAC29D0700000082FFFFFFCCA9C29DE40DEFB69C01B99C8401B99C808E139C88FFFFFF00A9C29DCCA9C29D00000000D0A9C29DF4A9C29DDC03DB9C0000000082FFFFFF90250EB9000000002CAAC29DF4A9C29D01000000DAD7FD3444ABC29D0100000058FB099D5CABC29D90250EB9CCAAC29DE8ABC29D083B079DACAAC29D30C5BF9C9C01B99C01000000E8ABC29D000000000000000028C4139D28C4139DDAD7FD34E40DEFB690AAC29D90250EB938ABC29DA0AAC29DE0ABC29DFCAAC29DE48AC99C0000000082FFFFFF90250EB9808E139CA0AAC29D0200000050ABC29DF6FFFFFF9C250EB990250EB990250EB990AAC29D0400000008000000C0D0329C88FFFFFF808E139C88FFFFFF90D1219C88FFFFFFF03C159C88FFFFFFC0D0329C000000000100000082FFFFFF0000000000000000000000000F00000088ABC29DDAD7FD34F4AAC29DC0ABC29D58ACC29D0200000090250EB9400364B9010000004F00000084ABC29D588CA89C
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2AB00 D0ABC29D98ABC29DC0ABC29D00000000000000000000000038ABC29D000000001C0600003DF313B9000000000045379C0100000008000000C0D0329C88FFFFFF808E139C88FFFFFF5CABC29D0A00000070B1C29D040000009C250EB9C0ABC29D0900000098ABC29DB0ABC29D08A8999D4000000042000000400364B988FFFFFFE0ABC29D8896309EC0ABC29D98ABC29D4000000098ABC29D0000000082FFFFFF503A139DD8FA419CE4D1309E8203000058ACC29D400364B902000000C0ABC29DC0D0329C88FFFFFF808E139C88FFFFFF90D1219C88FFFFFFF03C159C88FFFFFF84ACC29D400364B938B1999D81090000F03C159C88FFFFFF90D1219C88FFFFFF808E139C88FFFFFFC0D0329C88FFFFFFF03C159C88FFFFFF808E139C88FFFFFF50AD2E9C85FFFFFF0000000082FFFFFF0000000082FFFFFF30AD2E9C85FFFFFFE08D139C88FFFFFFF0AC2E9C85FFFFFF0000000082FFFFFF0813A09D810400000000000081FFFFFF98000000C0D7219C0037339C88FFFFFF70E0329CC0BA419C
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2AC80 04000000C0ACC29D8CE9309E0203000040D7369C04000000A046269C88FFFFFFD0AC2E9C85FFFFFF20982C9C85FFFFFF0000000082FFFFFF0000000082FFFFFF34ADC29D18BF68B96085999D810600000000000082FFFFFF0000000082FFFFFF20982C9C85FFFFFFD0AC2E9C85FFFFFFA046269C88FFFFFF40D7369C88FFFFFFD0AC2E9C85FFFFFF34ADC29DF0839A9C3CADC29DF0839A9C6800000050BE329C0000000064ADC29D64ADC29D450000000000000068ADC29D8CE9309E8202000060D7369C0300000080E2369C88FFFFFFA046269C88FFFFFF20982C9C85FFFFFFE037F19988FFFFFFECADC29DD8A068B9D470999D81070000E037F19988FFFFFF20982C9C85FFFFFFA046269C88FFFFFF80E2369C88FFFFFF60D7369C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFA0A32E9C85FFFFFFF046269C88FFFFFFA046269C88FFFFFF7800000050BE329C1CAEC29D3410A09D003F349C88FFFFFF0000000020AEC29D8CE9309E8202000000D7369C03000000
09-13 12:25:34.247  7574  7574 W google-breakpad: S 9DC2AE00 A046269C88FFFFFF20982C9C85FFFFFFE037F19988FFFFFF0000000082FFFFFFB4AEC29DF0DC4CB918569A9D810800000000000082FFFFFFE037F19988FFFFFF20982C9C85FFFFFFA046269C88FFFFFF00D7369C88FFFFFF0100000083FFFFFFA046269C88FFFFFF0000000082FFFFFF0000000087FFFFFF0000000082FFFFFF20982C9C85FFFFFFA046269C88FFFFFF90250EB900FEFFFF8800000050BE329CD4AEC29D44A9A79C90080000E708000000000000F8AEC29D8CE9309E82030000E0D6369C0500000000D5369C88FFFFFF80C9509985FFFFFFE037F19988FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF6CAFC29D184645B910669A9D810600000000000082FFFFFF0000000082FFFFFF0000000082FFFFFFE037F19988FFFFFF80C9509985FFFFFF00D5369C88FFFFFFE0D6369C88FFFFFF487014B9384C45B9C0AFC29D8046379C6800000050BE329C384C45B988FFFFFF94AFC29D44A9A79C00000000B8AFC29D8CE9309E0204000020D7369C06000000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2AF80 E037F19988FFFFFF80C9509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000083FFFFFF34B0C29D784C45B960629A9D010700000000000083FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80C9509985FFFFFFE037F19988FFFFFF20D7369C88FFFFFF07000000200000006D0065007300730070000000D07FF69941006D006F0075006E00740066006C000000000078B0C29D301A309E0304000000E4F299010000000000000082FFFFFF80C9509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000040B1C29D7018309E90250EB9F4B0C29D0000000000E4F29940B1C29D3CB1C29DB4D6A89C00E4F29900000000A0E4F29960B1C29D0000000090250EB9487014B90CB3C29D
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2B100 00000000000000000000000001000000B8C5C29D90250EB900010EB900000000E40DEFB670B1C29D90250EB9F0B2C29D90B1C29D00000000FCB1C29DFCD9A89C20609A9D0000000000E4F29990B1C29D0600000001000000A0E4F299000000000100000081FFFFFF00250EB90300000098B7C29DF6FFFFFF9C250EB90000000090250EB990B1C29D06000000080000000000000082FFFFFF80C9509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000000000E4B1C29D20E1A89C8046379CDAD7FD3490250EB990250EB9F0B2C29D0000000000000000D0B2C29D58FB099DB0B3C29D74B3C29DF07DC99C00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000005475FC9C0CB3C29DE40DEFB6804E999A000000000000000000E4F2990000000002000000000000008046379C00000000000000000000000000000000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2B280 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C090250EB9000000000000000082FFFFFF0000000082FFFFFF104954B900000000605A16B90100000034BD0EB901B3C29D90250EB9B4BD0EB90000000030ADC29DE82C099D010000008046379CD0B2C29D0000000000D7FD34004E999A90250EB9487014B904CBC29D00000000000000000000000000000000B0B3C29D685A16B9B2C818BB305916B9305916B9000000005CB3C29D20E1A89C804E999ADAD7FD3490250EB990250EB9B0B3C29D78B3C29DA0E4F299804E999A0000000090250EB99CB3C29D0084C99C00000000E40DEFB600100000E40DEFB60010000090250EB9C0A618BBA8B3C29D24B7C29D2486C99C00000000E40DEFB6C0A618BB08000000E82C099D01000000804E999AA8B3C29D00000000004E999AC83EDABA0024359CD03A079D90250EB95000009D40B0329C0000000090250EB9000000000000000000000000000000000000000000000000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2B400 C4B3C29D0000000001000000808E6DBB00000000E823359C00000000000000000000000068000000000000000000000000000000000000000100000058FB099D0F0000000000000001000000B0C2C29DFFFFFF0054C1C29DB0C3C29D02000000000000000000000000000000DA774733A0D1419C010000009C01B99C724D82B8D0B3C29D00000000004E999A0000000090250EB9A0B4C29D000000000000000058FB099D78E9F39C90250EB9B8B4C29D000000000000000014B5C29DF0B4C29D000000000100000000000000C765000090250EB918BB18BB070000000004000001000000F0B4C29D90250EB9588C18BB0900000000040000801D419C90250EB906000000AA03000003000000085817BBD0B4C29DD0BCC29DE85BFC9C0000000000000000000000000000000090250EB9010000000000000001000000000000000000000020A5C39A90250EB958B5C29D000000000000000000000000D02318BB010000007C5BDCB8000000000000000090250EB980B5C29D0000000000000000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2B580 0000000082FFFFFF90250EB998B5C29D0000000000000000D8B5C29DACB5C29D000021000000000001B6C29D9454D59C00000000D0B3C29D0000000000000000890000000000000000000000000000000000000000000000FFFFFFFF000000000000000090250EB9B4BD0EB9F8D1B0B990250EB900B6C29D0000000010000000A82318BB20B6C29D885717BB000000C02C5517BB905717BB485517BB485517BBE0ECFD9985FFFFFF405517BB000000C058FB099D485517BB984FD6B88D21ECB690250EB950B6C29D0000000010000000984FD6B84D8FEAB601000000C0E2D79C00000000C8B6C29DB8B6C29D7CB6C29D01000000C8B6C29D1CB7C29DE4FFD79C185517BB185517BB0100000090250EB984C2C29D000000000000000090250EB90000000090250EB9D4BCC29DE5FFFFFF9C250EB904B7C29D90250EB9C8B6C29D00000000080000000100000032000000B0A618BB0300000000000000431CECB600D0EEB624B7C29D100000008000000070B7C29DC0A618BB0000000090250EB9
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2B700 24B7C29DDAD7FD34A0C4C29DE40DEFB698B7C29D70B7C29D0A00000000000000DCC0C29D3864BC9C6F0000007300000095000000D2000000E2000000E6000000E7000000000100001B010000360100005301000072010000080000000A000000D1010000F20100001702000043020000402E089A9C02000,0D3020000B0C4C29D0703000008000000180300001C030000C0A618BB0800000080C4C29DF6FFFFFF9C250EB96603000090250EB9B0A618BB0A00000010000000DE030000E1030000F1030000200400005804000092040000A1040000A5040000D7040000F2040000F3040000440500007B05000094050000AA050000AE050000AF050000D6050000F5050000F9050000FA0500001D0600003106000035060000360600004D06000064060000830600009D060000B7060000CD060000E5060000E606000006070000430700004E0700008B0700008F070000910700009207000096070000B5070000B9070000E1070000E2070000E6070000F6070000FA0700004C08000087080000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2B880 8B0800008C08000090080000E7080000EA0800001B0900002A0900002E090000670900009B0900009C090000CE090000F6090000020A0000060A0000070A0000360A0000670A00007F0A0000850A0000910A0000950A0000960A0000A90A0000B10A0000DA0A0000F60A0000150B0000350B00006E0B0000960B0000970B0000CA0B0000E40B0000F30B0000530C00007B0C0000DC0C0000E40C0000EC0C0000010000007E03000058C3C29DDAD7FD34110000001D6600002366000000000000C079469C0000F03F0000000000EAAF9C030000002366000024660000FCFFAF9CF071409C00508F4000000000C0C2C29D0E0000002566000026660000E40DEFB69030479C000000000000000090AAF8990E000000286600002966000000BAC29DA0D5419C00408F4000000000ECF1C99C0300000000000000AA03000002BAC29DD05A6EBBCE5A6EBB808E6DBBD65A6EBBD25A6EBBB08A18BB000000000000000090250EB9B0A618BB050000004000000032003500380045004100460041003500
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2BA00 2D0045003900310034002D0034003700440041002D0039003500430041002D0043003500410042003000440043003800000000000000000000000100000100000000000000000000000000000000000000000000000000000101000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001000001000000000000000000000000000000000000000001000100000101010000000000000000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2BB80 00000000000000000000000001000000010000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000010000000101000100000000000100010001000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000FF90250EB900000000F8B6C29D00000000F85ADCB8085BDCB89C68DCB800000000000000000000000034BD0EB900000000C079469CCF650000D665000010B7C29DF03A079DFCB6C29DFDFFFFFF9C250EB990250EB9B4BD0EB990250EB910AB18BBAB03000000040000000000006E000000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2BD00 6F0000007300000095000000D2000000E2000000E6000000E7000000000100001B01000036010000530100007201000091010000B0010000D1010000F20100001702000043020000730200009C020000D302000006030000070300000B030000180300001C0300001D030000390300003A03000054030000550300006603000067030000BD030000BE030000C2030000DE030000E1030000F1030000200400005804000092040000A1040000A5040000D7040000F2040000F3040000440500007B05000094050000AA050000AE050000AF050000D6050000F5050000F9050000FA0500001D0600003106000035060000360600004D06000064060000830600009D060000B7060000CD060000E5060000E606000006070000430700004E0700008B0700008F070000910700009207000096070000B5070000B9070000E1070000E2070000E6070000F6070000FA0700004C080000870800008B0800008C08000090080000E7080000EA0800001B0900002A0900002E090000670900009B090000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2BE80 9C090000CE090000F6090000020A0000060A0000070A0000360A0000670A00007F0A0000850A0000910A0000950A0000960A0000A90A0000B10A0000DA0A0000F60A0000150B0000350B00006E0B0000960B0000970B0000CA0B0000E40B0000F30B0000530C00007B0C0000DC0C0000E40C0000EC0C000001000000A903000058C3C29DB8D017B9030000002A6600002B6600006800000000000000000000000000000000000000010000002B6600002B660000B0C2C29DFFFFFF0054C1C29DB0C3C29D020000000E000000286600002966000000BAC29DA0D5419C00408F4000000000ECF1C99C10000000296600002A660000FCFFAF9CE8BC0EB91CC0C29D90250EB9C0C2C29D0000000001000000AA03000003000000D05A6EBBCE5A6EBB808E6DBBD65A6EBBD65A6EBBB08A18BB000000000000000090250EB9C8BFC29D0000000020000000E4BFC29DF0E8AF9C1F000000E40DEFB6E8FC0EB908A8999D1CC3C29D9CFFAF9CE8BC0EB9947ACB9CB8C4C29D0000000000000000E7F113B9
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2C000 98C6C29D0100000000000000000000000000010000010000000000000000000000000000000000000000000000000000010100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000DAD7FD3400000000E40DEFB60000000090250EB9045EBC9CE8C0C29D00000000F0C5C29D64C4C29DA886C99C0000000000000000B0C4C29D0200000090250EB990250EB948C1C29DCCC1C29D3CC1C29D74E1CB9C90250EB918C3C29D54C1C29DE820CC9C20C3C29D40B0329C0100000000000000CCC1C29D4C5916B95834099DF032099D6CC1C29DF4B0C89C00000000004E999A40B0329C10C3C29D6CC1C29D90250EB9405916B9405916B990250EB9405916B9E4C2C29DB4F7C89C00000000000000000000000000000000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2C180 0000000004C5C29D000000000000000000C6C29D08000000000000000000000000000000000000000000000000000000000000005475FC9C7CC2C29DE40DEFB6004E999A0000000000000000A0E4F299000000000200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000001010001000000000001000100010000000000000000000000000000000000000082FFFFFF0000000082FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000FF90250EB900000000D0BCC29D01000000F85ADCB890250EB9487014B904CBC29D0000000000000000000000000000000010C3C29D805916B9CFDD06BB405916B9405916B900000000CCC2C29D20E1A89C004E999ADAD7FD3490250EB990250EB910C3C29DE8C2C29D00000000004E999ADAD7FD34010000000CC3C29D0C84C99C000000002CC3C29D00000000004E999A9CC3C29D90250EB9
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2C300 10C3C29D78C3C29D5CC3C29D0100000090250EB96066349C02000000A0F8369C402E089A6066349C5CC3C29D781DBE9C70BD0EB9A0D10EB9487014B900C3C29DC0C3C29D070000000200000088FFFFFFF8C5C29D90250EB98CC3C29D5474999C0100000000000000C0C3C29D6CC5C29D0700000090250EB958FB099D01000000000000000000000024C4C29DB8C2BF9CF8C5C29D5470B99CF0C4C29D004E999AF0C4C29D5CC4C29D0700000082FFFFFFDCC3C29DE40DEFB69C01B99C8401B99CA0E4F29988FFFFFF00C3C29DDCC3C29D00000000E0C3C29D04C4C29DDC03DB9C0000000082FFFFFF90250EB9000000003CC4C29D04C4C29D01000000DAD7FD3454C5C29D0100000058FB099D6CC5C29D90250EB9DCC4C29DF8C5C29D083B079DBCC4C29D30C5BF9C9C01B99C01000000F8C5C29D000000000000000028C4139D28C4139DDAD7FD34E40DEFB6A0C4C29D90250EB948C5C29DB0C4C29DF0C5C29D0CC5C29DE48AC99C0000000082FFFFFF90250EB9A0E4F299B0C4C29D02000000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2C480 60C5C29DF6FFFFFF9C250EB990250EB990250EB9A0C4C29D0400000008000000C0D0329C88FFFFFFA0E4F29988FFFFFFA079F69988FFFFFF402E089A88FFFFFFC0D0329C000000000100000082FFFFFF0000000000000000000000000F00000098C5C29DDAD7FD3404C5C29DD0C5C29D68C6C29D0200000090250EB9400364B9010000004F00000094C5C29D588CA89CE0C5C29DA8C5C29DD0C5C29D00000000000000000000000048C5C29D000000001C0600003DF313B9000000000045379C0100000008000000C0D0329C88FFFFFFA0E4F29988FFFFFF6CC5C29D0A00000080CBC29D040000009C250EB9D0C5C29D09000000A8C5C29DC0C5C29D08A8999D4000000042000000400364B988FFFFFFF0C5C29D8896309ED0C5C29DA8C5C29D40000000A8C5C29D0000000082FFFFFF503A139DD8FA419CE4D1309E8203000068C6C29D400364B902000000D0C5C29DC0D0329C88FFFFFFA0E4F29988FFFFFFA079F69988FFFFFF402E089A88FFFFFF94C6C29D400364B938B1999D81090000
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2C600 402E089A88FFFFFFA079F69988FFFFFFA0E4F29988FFFFFFC0D0329C88FFFFFF402E089A88FFFFFFA0E4F29988FFFFFF70EDFD9985FFFFFF0000000082FFFFFF0000000082FFFFFF50EDFD9985FFFFFF00E4F29988FFFFFF10EDFD9985FFFFFF0000000082FFFFFF0813A09D810400000000000081FFFFFF98000000D07FF6990037339C88FFFFFF70E0329CC0BA419C04000000D0C6C29D8CE9309E0203000040D7369C04000000E037F19988FFFFFFF0ECFD9985FFFFFFB0D1FA9985FFFFFF0000000082FFFFFF0000000082FFFFFF44C7C29D18BF68B96085999D810600000000000082FFFFFF0000000082FFFFFFB0D1FA9985FFFFFFF0ECFD9985FFFFFFE037F19988FFFFFF40D7369C88FFFFFFF0ECFD9985FFFFFF44C7C29DF0839A9C4CC7C29DF0839A9C6800000050BE329C0000000074C7C29D74C7C29D450000000000000078C7C29D8CE9309E8202000060D7369C0300000080E2369C88FFFFFFE037F19988FFFFFFB0D1FA9985FFFFFF309DF99988FFFFFFFCC7C29DD8A068B9
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2C780 D470999D81070000309DF99988FFFFFFB0D1FA9985FFFFFFE037F19988FFFFFF80E2369C88FFFFFF60D7369C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF20E4FD9985FFFFFF3038F19988FFFFFFE037F19988FFFFFF7800000050BE329C2CC8C29D3410A09D003F349C88FFFFFF0000000030C8C29D8CE9309E8202000000D7369C03000000E037F19988FFFFFFB0D1FA9985FFFFFF309DF99988FFFFFF0000000082FFFFFFC4C8C29DF0DC4CB918569A9D810800000000000082FFFFFF309DF99988FFFFFFB0D1FA9985FFFFFFE037F19988FFFFFF00D7369C88FFFFFF0100000083FFFFFFE037F19988FFFFFF0000000082FFFFFF0000000087FFFFFF0000000082FFFFFFB0D1FA9985FFFFFFE037F19988FFFFFF487014B900250EB98800000050BE329C78D9C29D0000000000000000000000000000000008C9C29D8CE9309E82030000E0D6369C0500000000D5369C88FFFFFFC0C8509985FFFFFF309DF99988FFFFFF0000000082FFFFFF0000000082FFFFFF
09-13 12:25:34.257  7574  7574 W google-breakpad: S 9DC2C900 0000000082FFFFFF7CC9C29D184645B910669A9D810600000000000082FFFFFF0000000082FFFFFF0000000082FFFFFF309DF99988FFFFFFC0C8509985FFFFFF00D5369C88FFFFFFE0D6369C88FFFFFF0100000030000000B0C5C29D1499989C6800000050BE329CF8030000E40DEFB6A0C8469C0000000000000000C8C9C29D8CE9309E0204000020D7369C06000000309DF99988FFFFFFC0C8509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000083FFFFFF44CAC29D784C45B960629A9D010700000000000083FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC0C8509985FFFFFF309DF99988FFFFFF20D7369C88FFFFFF0E000000200000002E002F006C00690070000000F0EDF999630065006900760065007200740053000000000088CAC29D301A309E03040000A085FB99010000000000000082FFFFFFC0C8509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2CA80 0000000082FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000050CBC29D7018309E90250EB904CBC29D00000000A085FB9950CBC29D4CCBC29DB4D6A89CA085FB99000000004086FB9970CBC29D0000000090250EB9487014B91CCDC29D00000000000000000000000001000000C8DFC29D90250EB900010EB900000000E40DEFB680CBC29D90250EB900CDC29DA0CBC29D000000000CCCC29DFCD9A89C20609A9D00000000A085FB99A0CBC29D06000000010000004086FB99000000000100000081FFFFFF00B0329C804D999AA8D1C29DF6FFFFFF9C250EB90000000090250EB9A0CBC29D06000000080000000000000082FFFFFFC0C8509985FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000000000F4CBC29D20E1A89C8046379CDAD7FD3490250EB990250EB900CDC29D0000000000000000E0CCC29D
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2CC00 58FB099DC0CDC29D84CDC29DF07DC99C00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000005475FC9C1CCDC29DE40DEFB6804D999A0000000000000000A085FB990000000002000000000000008046379C000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000C090250EB9000000000000000082FFFFFF0000000082FFFFFFB463DCB800000000285916B90100000034BD0EB901CDC29D90250EB9B4BD0EB90000000040C7C29DE82C099D010000008046379CE0CCC29D0000000000D7FD3470EAB9BA90250EB9487014B914E5C29D00000000000000000000000000000000C0CDC29D305916B9DDE059BBC85816B9C85816B9000000006CCDC29D20E1A89C804D999ADAD7FD3490250EB990250EB9C0CDC29D88CDC29D4086FB99804D999A0000000090250EB9
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2CD80 ACCDC29D0084C99C00000000E40DEFB600100000E40DEFB60010000090250EB910E059BBB8CDC29D34D1C29D2486C99C00000000E40DEFB610E059BB08000000E82C099D01000000804D999AB8CDC29D00000000004D999A305CDCB80024359CD03A079D90250EB96000009D40B0329C0000000090250EB9000000000000000000000000000000000000000000000000D4CDC29D000000000100000018CD59BB00000000E823359C00000000000000000000000068000000000000000000000000000000000000000100000058FB099D0F0000000000000001000000C0DCC29DFFFFFF0064DBC29DC0DDC29D02000000000000000000000000000000DA774733A0D1419C010000009C01B99C724D82B8E0CDC29D00000000004D999A0000000090250EB9B0CEC29D000000000000000058FB099D78E9F39C90250EB9C8CEC29D000000000000000024CFC29D00CFC29D0000000001000000000000001F04000090250EB978EAB9BA07000000000400000100000000CFC29D90250EB980A159BB
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2CF00 0600000000040000801D419C90250EB9060000003300000003000000A89F59BBE0CEC29DE0D6C29DE85BFC9C0000000000000000000000000000000090250EB90100000000000000010000000000000000000000C0A4C39A90250EB968CFC29D00000000000000000000000020A859BB010000007C5BDCB8000000000000000090250EB990CFC29D00000000000000000000000082FFFFFF90250EB9A8CFC29D0000000000000000E8CFC29DBCCFC29D000021000000000001D0C29D9454D59C00000000E0CDC29D0000000000000000060000000000000000000000000000000000000000000000FFFFFFFF000000000000000090250EB9B4BD0EB9F8D1B0B990250EB910D0C29D0000000010000000F8A759BB30D0C29D209F59BB000000C03C9D59BB289F59BB589D59BB589D59BB5009F99985FFFFFF509D59BB000000C058FB099D589D59BB984FD6B88D21ECB690250EB960D0C29D0000000010000000984FD6B84D8FEAB601000000C0E2D79C00000000D8D0C29DC8D0C29D8CD0C29D
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2D080 01000000D8D0C29D2CD1C29DE4FFD79C289D59BB289D59BB0100000090250EB994DCC29D000000000000000090250EB90000000090250EB9E4D6C29DE5FFFFFF9C250EB914D1C29D90250EB9D8D0C29D00000000080000008B000000002F000000E059BB0300000000000000431CECB600D0EEB634D1C29D100000008000000080D1C29D10E059BB0000000090250EB934D1C29DDAD7FD34B0DEC29DE40DEFB6A8D1C29D80D1C29D0A00000000000000ECDAC29D3864BC9C6F0000007300000095000000D2000000E2000000E6000000E70000001D0100001E0100004C010000710100009A010000080000000A000000C1010000C4010000EE01000024020000502A089A4B0200004F020000C0DEC29DAD02000008000000D0020000F102000010E059BB0800000090DEC29DF6FFFFFF9C250EB90F03000090250EB900E059BB0A00000010000000B2030000C1030000C50300000804000028040000290400004B040000660400006A0400006B0400007C0400007F04000080040000FFFFFFFF
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2D200 200EFC99500EFC99200EFC9950ABF999189959BB010000003CD2C29D8888CB9C0000000000000000009B329CC89859BB5CD2C29D0800000001000000E40DEFB60000000000000000189959BB0100000074D2C29D90250EB901000000030000000084329C40BC419C60D4C29D40BC419CA4D2C29D680ABE9C70BD0EB9A0D10EB9487014B90084FB9990250EB990250EB9980EFC9990250EB950ABF99940BC419CCCD2C29D7849BF9C60D4C29D40D5C29D44D5C29D90250EB958FB099D00000000000000000000000064D3C29D38BFBF9C60D4C29D0800000000000000000000000CD3C29DDAD7FD3470BD0EB97000000090250EB9E40DEFB69C01B99C8401B99C50ABF999980EFC9990250EB9701F419C00D3C29DCC0EBE9C70BD0EB9A0D10EB9487014B900D5C29DBCD5C29D800EFC99010000002F00000068DDC29DDAD7FD340E0000007C0400007D04000000000000002C419C0000000084D9C29D00EAAF9C030000007D0400007E040000FCFFAF9CC04D409C2CDAC29D90250EB9D0DCC29D
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2D380 0E0000008004000081040000E40DEFB6A06F4A9C8401B99CE6FFFFFF800EFC99030000007A0400007B04000010D4C29D205E429CE801B99CD4D3C29DECF1C99C02000000000000003300000002D4C29D18D659BB16D659BB18CD59BB1ED659BB1AD659BBE02B59BB000000000000000090250EB900D4C29D04000000200000006F00700065006E00740069006F006E006F006E0069007600650072007400530065007200760065007200000001000000010000000100000058FB099D01000000000000000000000000000100000100000000000000000000000000000000000000000000000000000101000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2D500 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001000001000000000000000000000000000000000000000001000100000101010000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000010000000100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000001010001000000000001000100010000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2D680 00000000000000000000000000000000000000000000000000000000000000FF90250EB90000000008D1C29D00000000F85ADCB8085BDCB8FC5BDCB800000000000000000000000034BD0EB900000000A06F4A9C590400005F04000020D1C29DF03A079D0CD1C29DFDFFFFFF9C250EB990250EB9B4BD0EB990250EB908D7C29D3400000080000000000000006E0000006F0000007300000095000000D2000000E2000000E6000000E70000001D0100001E0100004C010000710100009A0100009B0100009F010000C1010000C4010000EE010000240200003C0200004B0200004F02000086020000AD020000AE020000D0020000F1020000F5020000F6020000070300000A0300000B0300000F03000035030000380300007A030000A1030000B2030000C1030000C50300000804000028040000290400004B040000660400006A0400006B0400007C0400007F04000080040000FFFFFFFF0100000090250EB958FB099D0100000000000000000000008CD8C29DB8C2BF9CC0D9C29D80823A9C
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2D800 DAD7FD340100000034D8C29D0C84C99C010000000800000000000000E40DEFB69C01B99C8401B99C08DCC29D40D8C29D00DBC29D2486C99C0000000090250EB908DCC29D01000000E82C099D0100000080823A9C40D8C29D0000000000680F9AD8771D9CDAD7FD34000000000100000058FB099D34DAC29D90250EB944D9C29DC0D9C29D083B079D24D9C29D30C5BF9C9C01B99C01000000C0D9C29D0000000000000000E6FFFFFF9C250EB9E4D8C29D00000000E40DEFB69C01B99CDCD8C29DF8969F9D18D9C29DA49A9F9D14D9C29D00A6369C90250EB9E4D8C29DE4D8C29DFCD8C29DF0E8AF9C20000000E40DEFB6E8FC0EB9A49A9F9D34DCC29D9CFFAF9CE8BC0EB958FB099D010000003200000068DDC29DB8D017B90300000082040000830400006800000000000000000000000000000000000000010000008304000083040000C0DCC29DFFFFFF0064DBC29DC0DDC29D020000000E0000008004000081040000E40DEFB6A06F4A9C8401B99CE6FFFFFF800EFC991000000081040000
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2D980 82040000FCFFAF9CE8BC0EB92CDAC29D90250EB9D0DCC29D0000000001000000330000000300000018D659BB16D659BB18CD59BB1ED659BB1ED659BBE02B59BB000000000000000090250EB9D8D9C29D0000000020000000F4D9C29DF0E8AF9C1F000000E40DEFB6E8FC0EB908A8999D2CDDC29D9CFFAF9CE8BC0EB9947ACB9CC8DEC29D0000000000000000E7F113B9A8E0C29D0100000000000000000000000000010000010000000000000000000000000000000000000000000000000000010100000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000DAD7FD3400000000E40DEFB60000000090250EB9045EBC9CF8DAC29D0000000000E0C29D74DEC29DA886C99C0000000000000000C0DEC29D02000000
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2DB00 90250EB990250EB958DBC29DDCDBC29D4CDBC29D74E1CB9C90250EB928DDC29D64DBC29DE820CC9C30DDC29D40B0329C0100000000000000DCDBC29DE45816B95834099D64DBC29D3089999DA0DBC29D44A8999D9CDBC29D0045379C90250EB96CDBC29D6CDBC29D84DBC29DF0E8AF9C30000000E40DEFB6E8FC0EB944A8999DBCDEC29D9CFFAF9C00000000000000000000000014DFC29D00000000F4F113B9A8E0C29D0100000044A8999D9000000000000000000000000000000000000000000000005475FC9C8CDCC29DE40DEFB6004D999A00000000000000004086FB99000000000200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100000001010001000000000001000100010000000000000000000000000000000000000082FFFFFF0000000082FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000FF90250EB900000000
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2DC80 E0D6C29D01000000F85ADCB890250EB9487014B914E5C29D0000000000000000000000000000000020DDC29D185916B9B72D94B9D85816B9D85816B900000000DCDCC29D20E1A89C004D999ADAD7FD3490250EB990250EB920DDC29DF8DCC29D00000000004D999ADAD7FD34010000001CDDC29D0C84C99C000000003CDDC29D00000000004D999AACDDC29D90250EB920DDC29D88DDC29D6CDDC29D0100000090250EB96066349C02000000A0F8369C502A089A6066349C6CDDC29D781DBE9C70BD0EB9A0D10EB9487014B900DDC29DD0DDC29D070000000200000088FFFFFF08E0C29D90250EB99CDDC29D5474999C0100000000000000D0DDC29D7CDFC29D0700000090250EB958FB099D01000000000000000000000034DEC29DB8C2BF9C08E0C29D5470B99C00DFC29D004D999A00DFC29D6CDEC29D0700000082FFFFFFECDDC29DE40DEFB69C01B99C8401B99C4086FB9988FFFFFF00DDC29DECDDC29D00000000F0DDC29D14DEC29DDC03DB9C0000000082FFFFFF90250EB900000000
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2DE00 4CDEC29D14DEC29D01000000DAD7FD3464DFC29D0100000058FB099D7CDFC29D90250EB9ECDEC29D08E0C29D083B079DCCDEC29D30C5BF9C9C01B99C0100000008E0C29D000000000000000028C4139D28C4139DDAD7FD34E40DEFB6B0DEC29D90250EB958DFC29DC0DEC29D00E0C29D1CDFC29DE48AC99C0000000082FFFFFF90250EB94086FB99C0DEC29D0200000070DFC29DF6FFFFFF9C250EB990250EB990250EB9B0DEC29D0400000008000000C0D0329C88FFFFFF4086FB9988FFFFFFC0E7F99988FFFFFF502A089A88FFFFFFC0D0329C000000000100000082FFFFFF0000000000000000000000000F000000A8DFC29DDAD7FD3414DFC29DE0DFC29D78E0C29D0200000090250EB9400364B9010000004F000000A4DFC29D588CA89CF0DFC29DB8DFC29DE0DFC29D00000000000000000000000058DFC29D000000001C0600003DF313B9000000000045379C0100000008000000C0D0329C88FFFFFF4086FB9988FFFFFF7CDFC29D0A00000090E5C29D040000009C250EB9E0DFC29D
09-13 12:25:34.267  7574  7574 W google-breakpad: S 9DC2DF80 09000000B8DFC29DD0DFC29D08A8999D400000003E000000400364B988FFFFFF00E0C29D8896309EE0DFC29DB8DFC29D40000000B8DFC29D0000000082FFFFFF503A139DD8FA419CE4D1309E8203000078E0C29D400364B902000000E0DFC29DC0D0329C88FFFFFF4086FB9988FFFFFFC0E7F99988FFFFFF502A089A88FFFFFF
09-13 12:25:34.267  7574  7574 W google-breakpad: C 06000040000000001469C29D0200000000000000E8C50EB900000000B069C29D105AE7B9BC13E4B8E8C50EB950BE0EB90C69C29D00000000FC68C29DD080A19CD47FA19C100007600000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
09-13 12:25:34.277  7574  7574 W google-breakpad: M B6F12000 00000000 00003000 C076D4C24C77979D0F88BE887CB5F0160 app_process32
09-13 12:25:34.277  7574  7574 W google-breakpad: M 9C64D000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M A0C55000 00000000 00003000 C92C8D5B6B698181A7DD1FB7E563E88A0 libqdMetaData.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M A0C58000 00000000 0000A000 22DE2F7A850976271F596FD7120471AC0 libqservice.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M A0C63000 00000000 00009000 EC3B3774E5CB032EE6BC192244EC0E1A0 libqdutils.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M A0C6D000 00000000 00006000 91673970C17AB2DD7AB97FE633A7CC7F0 libmemalloc.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M A0C76000 00000000 00006000 FA30956B63451E4E9F4B6C7001FBD0F90 gralloc.msm8916.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M A255E000 00000000 0046A000 F1E6740F7B2AC1EADD232024D3726E350 libsc-a3xx.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M A4C84000 00000000 01AEE000 6DC83C69BA92FC15D9BFC15CAA444FA30 libwebviewchromium.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AB084000 00000000 00141000 A2F46E5CA0880CEF1C04E302488BB4E60 libGLESv2_adreno.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEA88000 00000000 00009000 15E68926F10C52B9E1C918455B33395D0 librs_jni.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEDE1000 00000000 0001B000 409A264B865DAA353D92FE1A41BA42010 libjavacrypto.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEDFC000 00000000 00006000 DCD8843E6E58F548A2F9F918E0F2250C0 libaudioeffect_jni.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEE02000 00000000 00004000 430912DAAB9CCB0652C6C67ED71BD34A0 libsoundpool.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEE06000 00000000 0000E000 65B4EE8C28DFCF943EF3BAB5CE2CF57E0 libstagefright_amrnb_common.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEE14000 00000000 0001A000 F596654166444B073C7B57DA85DDA86F0 libvorbisidec.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEE2E000 00000000 00004000 840EEE8827F765C9EEB69A82A5385D860 libstagefright_yuv.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEE32000 00000000 00020000 6A5DDC8F80D9496F56416E0CDC30C7860 libstagefright_omx.so
09-13 12:25:34.277  7574  7574 W google-breakpad: M AEE52000 00000000 00003000 03B0255D304C04BA1CB893EF055C0D880 libstagefright_enc_common.so
09-13 12:25:34.287  7574  7574 W google-breakpad: M AEE55000 00000000 00007000 BE9998F628EA6A5C32345D001998B9DE0 libstagefright_avc_common.so
09-13 12:25:34.287  7574  7574 W google-breakpad: M AEE5C000 00000000 0000B000 E431EED302BEFED523DB8D7341DEEFBD0 libsfextcp.so
09-13 12:25:34.287  7574  7574 W google-breakpad: M AEE67000 00000000 0000A000 BBE7244283F7E662D7E34D745C8451F80 libsecuibc.so
09-13 12:25:34.287  7574  7574 W google-breakpad: M AEE71000 00000000 0005F000 098C11FE4C1E5783837B86006532FAB50 libsavsff.so
09-13 12:25:34.287  7574  7574 W google-breakpad: M AEED5000 00000000 0004E000 DF97B63F6B72A8BB76A1D8FBA29896010 libsavscmn.so
09-13 12:25:34.287  7574  7574 W google-breakpad: M AEF23000 00000000 00005000 89B5E9B7BF6412D458C721055A152C4A0 libpowermanager.so
09-13 12:25:34.287  7574  7574 W google-breakpad: M AEF28000 00000000 00039000 34D438FC59A243B4B79B29B3300A98C30 libopus.so
09-13 12:25:34.287  7574  7574 W google-breakpad: M AEF61000 00000000 0001C000 1DA76B6D81AB593736F5F89F03BB089E0 libdrmframework.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AEF7D000 00000000 003B4000 BD3C4CE5F3F0FA413707AB0A9757E0830 libMMFW_scone_stub.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF33C000 00000000 00164000 4320EC321DE6EADC7528366646D5CA740 libstagefright.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF4A0000 00000000 00014000 C2FFC5B6A88CE765BBB0762DF08836520 libmtp.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF4B4000 00000000 0000B000 F8D7FA4760673A60E9A957A1FF0991BD0 libjhead.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF4C0000 00000000 0002C000 7FE1E6C0CA754D8F79E50A1CB5A2F4AF0 libexif.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF4EC000 00000000 0003C000 07D5EEA8D30C78E1DBD86B63E0447FA50 libmedia_jni.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF64A000 00000000 00003000 07E50F790CF258618C54CBF3C74A6A1E0 libwebviewchromium_loader.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF64D000 00000000 00003000 1042592D6A7B2C021C7008CB35D370AA0 libjnigraphics.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF650000 00000000 00008000 F5D3384E9BEEEDF600C2C4D02CB7146A0 libcompiler_rt.so
09-13 12:25:34.297  7574  7574 W google-breakpad: M AF658000 00000000 00034000 684DED99CC59C3906C82B7457EDB45F00 libGLESv1_CM_adreno.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M AF68C000 00000000 00035000 D4318DD5004755DA26AE6B0BBAF281DE0 libgsl.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M AF6C1000 00000000 0002A000 020C64D887DAD39ADBA1263F72513FED0 libEGL_adreno.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B09A5000 00000000 00010000 C7EB647818605F38532F9A290DDB69010 libandroid.so,
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B09BA000 00000000 00004000 7969E81D0F5763BFDBC09C2B6D2F08250 libadreno_utils.so,
09-13 12:25:34.307  7574  7574 W google-breakpad: M B0BD3000 00000000 00003000 B4D861A3F3ACFD7D321C59CB7177B7ED0 libqti-perfd-client.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B0BD6000 00000000 00003000 900F180B6ED1813B019148541FEBC4850 memtrack.msm8916.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B0BEE000 00000000 0000B000 77FE3A801397BE328D22A2C6CEDD5D190 eglsubAndroid.so,
09-13 12:25:34.307  7574  7574 W google-breakpad: M B22FC000 00000000 00038000 032BBF3A646CEC0E92F02F2607486BCA0 libjavacore.so
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B4849000 00000000 00004000 D8D9004A312C20C7AEAEE0BE3D460C970 libwebviewchromium_plat_support.so,
09-13 12:25:34.307  7574  7574 W google-breakpad: M B4DDC000 00000000 00008000 BABBF80B8FC90D8583D80A696A57B2130 libbacktrace_libc++.so
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B4DE4000 00000000 002FE000 E28D8FF4E9F5563C0B0777FF0B95B6720 libart.so
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B5104000 00000000 00004000 62EFD3D29964E6B599D4FAE01272421C0 libusbhost.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B5108000 00000000 0003F000 8F93763230E70AC1012CE2797EBDCD180 libssl.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B5147000 00000000 0000E000 5531DBDE929DBC5D9C2D2973F0ACB63E0 libsoundtrigger.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B5155000 00000000 00012000 F53050926856F9ED174D0B9FB54900510 libpcre.so
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B5167000 00000000 00012000 094A62A7F00C732AD95FB394CA44D7300 libselinux.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B5179000 00000000 00004000 099B10F2EAA0144B6769F0BF764BE16D0 libprocessgroup.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B517D000 00000000 00447000 F96B93C6164BBEFDAF535E909BE475720 libpdfium.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B55C9000 00000000 00004000 2C94DBD2926E0C0A51C840F6C94B0A120 libnetd_client.so
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B55CD000 00000000 00007000 8870FC1A3B0A0C618D77747DF2C5239F0 libnativehelper.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B55D4000 00000000 00004000 BF30FE88A9C8EE464CC8F0BB519494960 libnativebridge.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B55D8000 00000000 0000B000 0984D19CFFD7280D6559EA579517C0560 libminikin.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B55E3000 00000000 00003000 E8D81805B27BF1C2BADC1C385C9D44110 libmemtrack.so
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B55E6000 00000000 00014000 AB30B4F28663E54089CB0393F16EC42A0 libstagefright_foundation.so,
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B55FA000 00000000 00009000 DF257BF35EC3333D10EF36A5C95A55CE0 libsec_km.so,
09-13 12:25:34.307  7574  7574 W google-breakpad: M B5604000 00000000 00007000 09E0E8E3AC05172EE6B3DC26270D49F70 libsdp_crypto.so
,09-13 12:25:34.307  7574  7574 W google-breakpad: M B560B000 00000000 00004000 678D29883C80386905E16BBCE7CF2E570 libpersona.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B5610000 00000000 00085000 176AE350351B5C616895DE24B70FE7570 libsqlite.so
09-13 12:25:34.307  7574  7574 W google-breakpad: M B5697000 00000000 00050000 2FF9202116C3611BE6EFBD00407235750 libomafldrm.so,
09-13 12:25:34.317  7574  7574 W google-breakpad: M B56E8000 00000000 00050000 F8171C0B0A8FBD6C5438EA18037AAFE80 libsonivox.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B573D000 00000000 00005000 B928740DB1DCEFFD56EE67AE84B8EFC10 libsecnativefeature.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5742000 00000000 00008000 C04C622FA1AEFB29F88FEED961B34D680 lib_SamsungVAD_v01007.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B574C000 00000000 00003000 E8AD41C2097B7B0A26463F3E900952FE0 libsamsungvad.so
,09-13 12:25:34.317  7574  7574 W google-breakpad: M B574F000 00000000 0000F000 0F206C184F10DAF8B580B1CA47FA6EC80 libcommon_time_client.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B575E000 00000000 0000A000 ADDFBB302FF2440C1B86D12D70317C8F0 libnbaio.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5768000 00000000 000BD000 BE2C9C97A647438CAB5EE6F3F9C6EB610 libmedia.so
,09-13 12:25:34.317  7574  7574 W google-breakpad: M B5826000 00000000 00040000 E7102D00C0372AA9E97071DD4BF6FDCC0 libinputflinger.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5866000 00000000 0001B000 BB5BED8E5ADF4A119D5B2DA31DBAEC580 libinput.so
,09-13 12:25:34.317  7574  7574 W google-breakpad: M B5881000 00000000 0000D000 C17942DF5B7EBECE9049E849149CA1120 libimg_utils.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B588E000 00000000 0001E000 18C32F00634AB7BB4010F2D59861567F0 libquramimagecodec.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B58AC000 00000000 00032000 8F255D73F53B095B1764C82186FE28FC0 libjpeg.so
,09-13 12:25:34.317  7574  7574 W google-breakpad: M B58DE000 00000000 00264000 4DCD73A518FC633987387494509BE53D0 libskia.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5B48000 00000000 00011000 5F14FC290F6EBD6AFCC7BDA3F439C3E90 libsamsungeffect.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5B59000 00000000 0001D000 90BC6412D2B13FFD96428D1B517BEDD00 libRScpp.so,
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5B77000 00000000 00027000 CA02F8123591B96EE9266BAA11675EEA0 libpng.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5B9F000 00000000 00059000 54828C4F4B56D81127BD1BAF9A48D64E0 libft2.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5BF8000 00000000 0003C000 A0A13C2D329CE4F443247914FBF76EA40 libbcinfo.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5C34000 00000000 00022000 E421E96697C14EB985E7F06B412DFB2B0 libbcc.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B5C76000 00000000 0008C000 D2E4B8E2C12DFE9B2752E15EF016991E0 libc++.so
,09-13 12:25:34.317  7574  7574 W google-breakpad: M B5D03000 00000000 008FE000 1E521DDD13333E86CCC3043C7BB1C7EF0 libLLVM.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6608000 00000000 00036000 2F058C02160C453D2C194C7A4498C7510 libRS.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B663E000 00000000 00051000 7A9A46F8FEF9C704ACEEEFE03C2F36DE0 libhwui.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B668F000 00000000 000FF000 24D205C2C90637FA33CF50299F7199690 libicuuc.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6792000 00000000 00006000 6AC3328D55BE7167DD1549E59E88D8420 libgabi++.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6798000 00000000 0014A000 30D014A51C507F017588CD57CC7ABDAD0 libicui18n.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B68E2000 00000000 00048000 58C7C20B9121CD68E9A3B78D8C6CF7190 libharfbuzz_ng.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B692A000 00000000 00005000 1AB401385CC88F656E0CB80273DA89860 libwpa_client.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B692F000 00000000 00007000 ACC103A77586F28DE7F6DA309DF82D320 libnetutils.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6936000 00000000 00007000 67762CE3DAA2297C6E0F58843AAAB3910 libhardware_legacy.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B693E000 00000000 00017000 D1B3203E3493EE80553E5CF9C9905E320 libexpat.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6955000 00000000 00142000 2727DE264BD767080C4068EDB1F581960 libcrypto.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6A99000 00000000 00003000 6E72A700CCC315909A66D3E4D2AAAE410 libcc_manager.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6A9C000 00000000 00003000 7C24A254F6B1768D1FF8ADFB9A8A11500 libsync.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6A9F000 00000000 00003000 0C360DD265129CA1197EE36C44A162570 libhardware.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6AA3000 00000000 0000C000 AB61E5F34C506C41C8ACF65F1DF7A7690 libui.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6AAF000 00000000 0000B000 3EBFA8F358F7A386E377C708170C6A0B0 libremotedesktop_client.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6ABA000 00000000 0004C000 D41F8C8CDABD00A9D5F6E03D9131C6FE0 libgui.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6B06000 00000000 00008000 D86968593275725A009907DF162762E60 libcamera_metadata.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6B0E000 00000000 00041000 8F4B2C50A29960551F2159E0DAB20E260 libcamera_client.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6B4F000 00000000 00006000 20E951BEE083EAAC8A0EC8C9659BC90C0 libspeexresampler.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6B55000 00000000 00006000 556F9F9B6E57A78532BC16CE0DAFDB920 libaudioutils.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6B5B000 00000000 00019000 6FF245A929534129A0A09E804082C1F90 libz.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6B74000 00000000 0002D000 10C485FADAF2C720FDA5625DC38ABF2A0 libbinder.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6BA1000 00000000 00026000 65C138E33F598CC3AF5D7A6804A6293D0 libandroidfw.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6BC7000 00000000 0000D000 FE94ED4BD906E283008A8207B21F731F0 libGLESv2.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6BD4000 00000000 00008000 E20B832545D307124FB21DEB3AFA1EFA0 libGLESv1_CM.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6BDC000 00000000 00004000 C10A3FF24BC314BDB4276E3588B5CFEF0 libETC1.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6BE0000 00000000 00004000 9A82E5E5DC0FF6464E020C95D6C265430 libunwind-ptrace.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6BE4000 00000000 0000E000 FCC4CF7B44EE2AEE89CCE84DDB0A34E30 libunwind.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6C38000 00000000 00007000 9AD603917CEBD0A26C5300A4455555250 libgccdemangle.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6C41000 00000000 00008000 809C179831A89482ABA,EF5D7DAE451C00 libbacktrace.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6C4A000 00000000 00016000 F1EB1C81CF043EF6ACD6D977257B90FA0 libutils.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6C60000 00000000 00036000 A86B4524AFE0B8B31C00A4A9DA14FB720 libstlport.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6C96000 00000000 0000D000 C5A05BA0312495F273F4D3DF9ECCA8830 libcutils.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6CA4000 00000000 0006B000 0003812AEBDD6FD4750BAB0D29164BB90 libGLES_trace.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6D0F000 00000000 0006A000 7F16035A8648874F086D60A0C922D76C0 libEGL.so
09-13 12:25:34.317  7574  7574 W google-breakpad: M B6D7C000 00000000 000F5000 C5F797DCDC70EF17BB357C3E2C8A5E4C0 libandroid_runtime.so
09-13 12:25:34.327  7574  7574 W google-breakpad: M B6E76000 00000000 00004000 D44FDF94BA8D734E5BC46C426F7316DE0 libstdc++.so
09-13 12:25:34.327  7574  7574 W google-breakpad: M B6E7A000 00000000 00018000 3D2BCD0A8F5E726801091CC87EA86DCC0 libm.so
09-13 12:25:34.327  7574  7574 W google-breakpad: M B6E93000 00000000 00006000 D777457560B88DEC8383D062CA85BD860 liblog.so
09-13 12:25:34.327  7574  7574 W google-breakpad: M B6E9A000 00000000 00056000 D779447DA8EFA50115E42F43400903DD0 libc.so
09-13 12:25:34.327  7574  7574 W google-breakpad: M B6EFA000 00000000 00003000 6942576880529816BD6C80C55563D51C0 libsigchain.so
09-13 12:25:34.327  7574  7574 W google-breakpad: M B6F02000 00000000 0000F000 1A12EEA227DCC44493A0CB9F6FAD897C0 linker
09-13 12:25:34.327  7574  7574 W google-breakpad: -----END BREAKPAD MICRODUMP-----
,09-13 12:25:34.337  6910  7214 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
09-13 12:25:34.337  6910  7214 W google-breakpad: Chrome build fingerprint:
,09-13 12:25:34.337  6910  7214 W google-breakpad: 0.0.1
09-13 12:25:34.337  6910  7214 W google-breakpad: 19
09-13 12:25:34.337  6910  7214 W google-breakpad: 3287cb47-323f-452a-9071-08e954855982
09-13 12:25:34.337  6910  7214 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
09-13 12:25:34.337  6910  7214 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x0 in tid 7214 (Thread-1275)
,09-13 12:25:34.347   280   280 I DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***,
,09-13 12:25:34.347   280   280 I DEBUG   : Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys'
,09-13 12:25:34.347   280   280 I DEBUG   : Revision: '1'
,09-13 12:25:34.357   280   280 I DEBUG   : ABI: 'arm'
,09-13 12:25:34.357   280   280 I DEBUG   : pid: 6910, tid: 7214, name: Thread-1275  >>> com.test.thalitest <<<,
09-13 12:25:34.357   280   280 I DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
,09-13 12:25:34.377   280   280 I DEBUG   :     r0 00000000  r1 9dc26914  r2 00000002  r3 00000000,
09-13 12:25:34.377   280   280 I DEBUG   :     r4 b90ec5e8  r5 00000000  r6 9dc269b0  r7 b9e75a10
,09-13 12:25:34.377   280   280 I DEBUG   :     r8 b8e413bc  r9 b90ec5e8  sl b90ebe50  fp 9dc2690c
,09-13 12:25:34.377   280   280 I DEBUG   :     ip 00000000  sp 9dc268fc  lr 9ca180d0  pc 9ca17fd4  cpsr 60070010
,09-13 12:25:34.377   280   280 I DEBUG   : ,
09-13 12:25:34.377   280   280 I DEBUG   : backtrace:
09-13 12:25:34.377   280   280 I DEBUG   :     #00 pc 003cafd4  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so (_Z20ThingIsPermanentAtomIN2JS6SymbolEEbPT_+4)
,09-13 12:25:34.377   280   280 I DEBUG   :     #01 pc 003cb0cc  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so
09-13 12:25:34.377   280   280 I DEBUG   :     #02 pc e5943000  <unknown>
,09-13 12:25:35.267   280   280 I DEBUG   : 
09-13 12:25:35.267   280   280 I DEBUG   : Tombstone written to: /data/tombstones/tombstone_09
09-13 12:25:35.267   280   280 E         : ro.product_ship = true
09-13 12:25:35.267   280   280 E         : ro.debug_level = 0x4f4c
,09-13 12:25:35.267   979  1044 I BootReceiver: Copying /data/tombstones/tombstone_09 to DropBox (SYSTEM_TOMBSTONE)
,09-13 12:25:35.267  2025  2025 E audit   : type=1701 msg=audit(1473762335.267:206): auid=4294967295 uid=10171 gid=10171 ses=4294967295 subj=u:r:untrusted_app:s0 pid=7214 comm="Thread-1275" reason="memory violation" sig=11
,09-13 12:25:35.267   979  3236 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,09-13 12:25:35.277   979  7577 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,09-13 12:25:35.287   979  7577 D FocusedStackFrame: Set to : 0
,09-13 12:25:35.287   979  7577 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 12:25:35.287   979  7577 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,09-13 12:25:35.287   979  7577 D InputDispatcher: Focused application set to: xxxx
,09-13 12:25:35.287   979  7577 D InputDispatcher: Focus left window: 6910
,09-13 12:25:35.287   979  7577 I ActivityManager: Killing 6587:com.samsung.android.sm/1000 (adj 15): empty #21
09-13 12:25:35.287   256   256 E lowmemorykiller: Error writing /proc/6910/oom_score_adj; errno=22
,09-13 12:25:35.297   979  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 12:25:35.297   979  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 12:25:35.307   979  1043 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 12:25:35.327   979  1043 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.sm/com.samsung.android.sm.common.SmartManagerReceiver}
09-13 12:25:35.327   979  1043 W BroadcastQueue: android.os.TransactionTooLargeException
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:195)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 12:25:35.327   979  1043 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 12:25:35.327   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,09-13 12:25:35.327   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.327   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.327   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.327   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:35.347  7579  7579 E Zygote  : MountEmulatedStorage()
,09-13 12:25:35.347  7579  7579 E Zygote  : v2
,09-13 12:25:35.347  7579  7579 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:25:35.347  7579  7579 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:35.347  7579  7579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:35.347  7579  7579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:35.347  7579  7579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:35.357   979  1043 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7579 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 12:25:35.367   979   979 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys
09-13 12:25:35.367   979   979 D CrashAnrDetector: Hardware: MSM8916
09-13 12:25:35.367   979   979 D CrashAnrDetector: Revision: 1
09-13 12:25:35.367   979   979 D CrashAnrDetector: Bootloader: A300FUXXS1BPE1
09-13 12:25:35.367   979   979 D CrashAnrDetector: Radio: unknown
09-13 12:25:35.367   979   979 D CrashAnrDetector: Kernel: Linux version 3.10.49-6027881 (dpi@SWDD6014) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 6 21:20:10 KST 2016
09-13 12:25:35.367   979   979 D CrashAnrDetector: 
09-13 12:25:35.367   979   979 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
09-13 12:25:35.367   979   979 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys'
09-13 12:25:35.367   979   979 D CrashAnrDetector: Revision: '1'
09-13 12:25:35.367   979   979 D CrashAnrDetector: ABI: 'arm'
09-13 12:25:35.367   979   979 D CrashAnrDetector: pid: 6910, tid: 7214, name: Thread-1275  >>> com.test.thalitest <<<
09-13 12:25:35.367   979   979 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
09-13 12:25:35.367   979   979 D CrashAnrDetector:     r0 00000000  r1 9dc26914  r2 00000002  r3 00000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     r4 b90ec5e8  r5 00000000  r6 9dc269b0  r7 b9e75a10
09-13 12:25:35.367   979   979 D CrashAnrDetector:     r8 b8e413bc  r9 b90ec5e8  sl b90ebe50  fp 9dc2690c
09-13 12:25:35.367   979   979 D CrashAnrDetector:     ip 00000000  sp 9dc268fc  lr 9ca180d0  pc 9ca17fd4  cpsr 60070010
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d16 646f6d20200a7b20  d17 6f7078652e656c75
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d20 0000000000000001  d21 0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d26 0002000200020001  d27 0002000200020002
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
09-13 12:25:35.367   979   979 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
09-13 12:25:35.367   979   979 D CrashAnrDetector:     scr 30000013
09-13 12:25:35.367   979   979 D CrashAnrDetector: 
09-13 12:25:35.367   979   979 D CrashAnrDetector: backtrace:
09-13 12:25:35.367   979   979 D CrashAnrDetector:     #00 pc 003cafd4  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so (_Z20ThingIsPermanentAtomIN2JS6SymbolEEbPT_+4)
09-13 12:25:35.367   979   979 D CrashAnrDetector:     #01 pc 003cb0cc  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so
09-13 12:25:35.367   979   979 D CrashAnrDetector:     #02 pc e5943000  <unknown>
09-13 12:25:35.367   979   979 D CrashAnrDetector: 
09-13 12:25:35.367   979   979 D CrashAnrDetector: stack:
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc2687c  00000003  
09-13 12:25:35.367   979   979 D CrashAnrDetector:       ,   9dc26880  9c1c6300  [anon:js-gc-heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26884  b90ec5e8  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26888  9cf53288  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc2688c  b90ec5e8  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26890  9dc268ac  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26894  9cc3298c  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so (_ZN8JSScript12markChildrenEP8JSTracer+404)
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26898  00000001  
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc2689c  b90ebce8  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268a0  b90ed118  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268a4  00000000  
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268a8  00000000  
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268ac  b90ec5e8  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268b0  b90ed118  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268b4  9d09fb58  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268b8  9dc26924  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268bc  9ca1fb1c  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so (_ZN2js2gc9GCRuntime26markConservativeStackRootsEP8JSTracerb+1308)
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268c0  b90ec5e8  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268c4  b90ebe50  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268c8  9dc40000  
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268cc  9dc268f0  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268d0  9dc268e8  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268d4  9dc268f4  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268d8  9cfc5c44  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268dc  9dc268f8  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268e0  00000004  
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268e4  00000000  
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268e8  00000001  
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268ec  b90ec5e8  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268f0  9bf2f850  [anon:js-gc-heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268f4  9dc269b0  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc268f8  9dc2690c  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:     #00  9dc268fc  9dc2690c  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26900  9dc3f838  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26904  b9e706a0  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26908  9dc26924  [stack:7214]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc2690c  9ca1c650  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so (_ZN2js2gc13MarkValueRootEP8JSTracerPN2JS5ValueEPKc+80)
09-13 12:25:35.367   979   979 D CrashAnrDetector:     #01  9dc26910  b8e413bc  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26914  00000000  
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26918  b90ebe74  [heap]
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc2691c  9cf4742c  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc26920  9dc2697c  [stack:7214]
09-13 12:25:35.36,7   979   979 D CrashAnrDetector:          9dc26924  9ca213cc  /data/app/com.test.thalitest-2/lib/arm/libjxcore.so (_ZN2js2gc9GCRuntime11markRuntimeEP8JSTracerNS1_18TraceOrMarkRuntimeENS1_21TraceRootsOrUsedSavedE+1456)
09-13 12:25:35.367   979   979 D CrashAnrDetector:          9dc2
09-13 12:25:35.367   979   979 D CrashAnrDetector: processName:com.test.thalitest
09-13 12:25:35.367   979   979 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
09-13 12:25:35.367   979   979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
09-13 12:25:35.377  7579  7579 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:25:35.377  7579  7579 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:35.397  7579  7579 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:35.417   979  1007 I ActivityManager: Process com.test.thalitest (pid 6910)(adj 9) has died(135,727)
,09-13 12:25:35.417   979  1010 I WindowState: WIN DEATH: Window{33158692 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 12:25:35.417   259   821 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
09-13 12:25:35.417   259   453 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-13 12:25:35.427   259  1156 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-13 12:25:35.427   979  1007 W ActivityManager: mDVFSHelper.acquire()
,09-13 12:25:35.437   309   309 I Zygote  : Process 6910 exited due to signal (11)
,09-13 12:25:35.437   979  1007 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.am.SmartAdjustManager.SPCMLocked:1235 com.android.server.am.ActivityManagerService.updateOomAdjLocked:22618 com.android.server.am.ActivityStack.resumeTopActivityInnerLocked:2721 com.android.server.am.ActivityStack.resumeTopActivityLocked:2240 
,09-13 12:25:35.437   979  1007 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false,
,09-13 12:25:35.447  7579  7579 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.sm.common.SmartManagerReceiver.b:199 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:93 
,09-13 12:25:35.447   979  1137 D ActivityManager: startService callerProcessName:com.samsung.android.sm, calleePkgName: com.samsung.android.sm
09-13 12:25:35.447   979  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.sm/com.samsung.android.sm.common.notification.CrashedAppLoggingService; callingUser = 0; userId(target) = 0
,09-13 12:25:35.447   979  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.447   979  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 12:25:35.447   979  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.sm, destAppInfo.processName = com.samsung.android.sm
,09-13 12:25:35.457  1484  1484 D Launcher: onRestart, Launcher: 219103717
,09-13 12:25:35.467  1484  1484 D Launcher: onStart, Launcher: 219103717
09-13 12:25:35.467  1484  1484 D Launcher.HomeView: onStart
,09-13 12:25:35.467  1484  1484 D Launcher: onResume, Launcher: 219103717
,09-13 12:25:35.467   979  1007 D SettingsProvider: name = kids_home_mode
09-13 12:25:35.467   979  1007 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 12:25:35.467   979  1007 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 12:25:35.467   979  1007 D SettingsProvider: selectionArgs: false
09-13 12:25:35.467   979  1007 D SettingsProvider: selectionArgs: 10006
09-13 12:25:35.467   979  1007 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 12:25:35.467   979  1007 D SettingsProvider: ret = -1
09-13 12:25:35.467  1484  1484 D Launcher.HomeView: onResume
,09-13 12:25:35.477   979  1007 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:35.477  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-13 12:25:35.477   979  1007 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.477   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:35.477   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:35.487  1484  1484 D MenuAppsGridFragment: onResume
,09-13 12:25:35.497  1484  1484 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-13 12:25:35.497   979  1748 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:35.507   979  1748 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.507  1484  1484 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
09-13 12:25:35.507   979  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:35.507   979  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:35.507   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.507   979  1010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 12:25:35.507   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,09-13 12:25:35.517   979  1483 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
09-13 12:25:35.517   979  1483 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,09-13 12:25:35.517   979  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.517   979  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.517   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
09-13 12:25:35.517   979  1483 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-13 12:25:35.517   979  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:35.517   979  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.517   979  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:35.517   979  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:35.537  7597  7597 E Zygote  : MountEmulatedStorage()
09-13 12:25:35.537  7597  7597 I libpersona: KNOX_SDCARD checking this for 10039
09-13 12:25:35.537  7597  7597 E Zygote  : v2
09-13 12:25:35.537  7597  7597 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:35.537  7597  7597 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:35.537   979  1483 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7597 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-13 12:25:35.537  7597  7597 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:35.537   979  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.537   979  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.537   979  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,09-13 12:25:35.547   979  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.547   979  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.547   979  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
09-13 12:25:35.547   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
09-13 12:25:35.547  7597  7597 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:35.547   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.547   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.547   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.547   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:35.567  7607  7607 E Zygote  : MountEmulatedStorage()
09-13 12:25:35.567  7607  7607 E Zygote  : v2
09-13 12:25:35.567  7607  7607 I libpersona: KNOX_SDCARD checking this for 10089
09-13 12:25:35.567  7607  7607 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:35.567  7607  7607 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:35.567   979  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7607 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,09-13 12:25:35.567   979  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.567   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast,
09-13 12:25:35.567   979  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.567   979  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
09-13 12:25:35.567  7607  7607 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:35.567  7607  7607 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-13 12:25:35.567   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.567   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.567   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.567   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:35.587  7597  7597 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:35.587  7621  7621 E Zygote  : MountEmulatedStorage()
,09-13 12:25:35.587  7597  7597 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:35.587  7621  7621 I libpersona: KNOX_SDCARD checking this for 10139
09-13 12:25:35.587  7621  7621 E Zygote  : v2
,09-13 12:25:35.587  7621  7621 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:35.587  7621  7621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:35.597   979  1479 D ActivityManager: handle home activity for 0
,09-13 12:25:35.597   979  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7621 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
09-13 12:25:35.597  7621  7621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:25:35.597   979  1479 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-13 12:25:35.597   979   979 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,09-13 12:25:35.597   979  1479 D KnoxTimeoutHandler: post home show event for user 0
09-13 12:25:35.597   979   979 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 12:25:35.597   979  1479 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 12:25:35.597   979  1479 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 12:25:35.597   979  1479 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-13 12:25:35.597   979   979 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-13 12:25:35.597   979   979 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-13 12:25:35.597  1484  1484 D Launcher.HomeView: onPause
09-13 12:25:35.597  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
09-13 12:25:35.597  7621  7621 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-13 12:25:35.617   979   979 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-13 12:25:35.617   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.617   979  1466 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1484, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
09-13 12:25:35.617   979  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.617   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
09-13 12:25:35.617   979  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.617   979  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.617   979  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,09-13 12:25:35.627  2566  2566 D Recents_RecreateReceiver: onReceive by home
,09-13 12:25:35.627   979  1010 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.627   979  1010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.627   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
09-13 12:25:35.627   979  1010 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
09-13 12:25:35.627  7621  7621 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:35.627  7607  7607 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:35.627  7607  7607 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:35.627  7621  7621 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:35.637   979  1010 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.637   979  1010 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.637   979  1010 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.637   979  1010 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:35.637  7597  7597 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 12:25:35.647  7597  7597 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:25:35.647  7597  7597 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:35.647  7597  7597 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-13 12:25:35.647  7597  7597 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 12:25:35.647  7597  7597 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 12:25:35.647  7597  7597 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 12:25:35.657  7642  7642 E Zygote  : MountEmulatedStorage()
09-13 12:25:35.657  7642  7642 I libpersona: KNOX_SDCARD checking this for 10084
09-13 12:25:35.657  7642  7642 E Zygote  : v2
09-13 12:25:35.657  7642  7642 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:35.657  7642  7642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:35.657   979  1010 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7642 uid=10084 gids={50084, 9997} abi=armeabi-v7a
09-13 12:25:35.667   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,09-13 12:25:35.667  7642  7642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:35.667   979  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-13 12:25:35.677  7642  7642 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-13 12:25:35.687   979  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-13 12:25:35.687   979  1748 D InputDispatcher: Focus entered window: 1484
,09-13 12:25:35.697   979  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 12:25:35.697   979  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_6587/cgroup.procs: No such file or directory
09-13 12:25:35.697   979  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 12:25:35.697  1484  1484 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 12:25:35.717  7642  7642 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:35.717  7642  7642 D ActivityThread: Added TimaKeyStore provider
09-13 12:25:35.717  7607  7607 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:35.727  7607  7607 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,09-13 12:25:35.737  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{37e84028 token=android.os.BinderProxy@147dd52 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-13 12:25:35.737  1484  1484 D Launcher.HomeView: onStop
,09-13 12:25:35.737   979  1748 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 12:25:35.737   979  1748 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6910 uid 10171
,09-13 12:25:35.737  1179  1179 I StatusBar: Icon Only
,09-13 12:25:35.747  1179  1179 D PanelView: There is/are notification(s) 
,09-13 12:25:35.747  7642  7642 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 12:25:35.747   979  7658 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:25:35.747  1863  1863 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-13 12:25:35.757  7621  7621 V TaskCloserActivity: TaskCloserActivity enter()
,09-13 12:25:35.757  7621  7621 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,09-13 12:25:35.767   979  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.767   979  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 12:25:35.767   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,09-13 12:25:35.777  1484  1484 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@147dd52 time:111718
,09-13 12:25:35.787   979  1137 I ActivityManager: Killing 7350:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-13 12:25:35.797   979  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:35.797   979  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.797   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:35.797   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:35.807   979  1048 W ActivityManager: mDVFSHelper.release()
,09-13 12:25:35.807   979  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{35e692bf u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:111744
,09-13 12:25:35.807   979  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:35.807   979  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.817   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:35.817   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:35.817   979  1348 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.817   979  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.817   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,09-13 12:25:35.817   979  1348 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,09-13 12:25:35.817   979  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.817   979  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.817   979  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:35.817   979  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:35.827  7664  7664 E Zygote  : MountEmulatedStorage(),
09-13 12:25:35.827  7664  7664 I libpersona: KNOX_SDCARD checking this for 10135
09-13 12:25:35.827  7664  7664 E Zygote  : v2
,09-13 12:25:35.827  7664  7664 I libpersona: KNOX_SDCARD not a persona
09-13 12:25:35.827  7664  7664 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:25:35.827   979  1348 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7664 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
09-13 12:25:35.837   979  1348 I ActivityManager: Killing 7324:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
09-13 12:25:35.837   979  1007 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:35.837  7664  7664 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:35.837   979  1007 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.837   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:35.837   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 12:25:35.837  7664  7664 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 12:25:35.857  7664  7664 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:35.857  7664  7664 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:35.867   979  1501 D PersonaManager: isKioskContainerExistOnDevice
,09-13 12:25:35.877  7664  7664 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-13 12:25:35.877  7664  7664 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 12:25:35.877  7664  7664 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-13 12:25:35.877  7664  7664 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
09-13 12:25:35.877  7664  7664 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 12:25:35.877  7597  7597 D NearbySource: Nearby Source Create!
,09-13 12:25:35.877  7597  7597 D NearbyContext: Nearby Context Create!
,09-13 12:25:35.917   258   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-13 12:25:35.917   258   535 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:25:35.917  7597  7597 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-13 12:25:35.917  7597  7597 D SLinkSource: Samsung link source created
,09-13 12:25:35.957  7597  7679 D ContactProvider: getAllContactInfoList Start
,09-13 12:25:35.967   979  1010 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 12:25:35.977   979  1007 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 12:25:35.977  7597  7597 D GalleryCacheReady: Receive : home resume
,09-13 12:25:35.977   979  1348 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:35.977   979  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.977   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,09-13 12:25:35.987  7453  7453 D Mms/UIEventReceiver: ui event
,09-13 12:25:35.987   979  1472 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
09-13 12:25:35.987   979  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:35.987   979  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:25:35.987   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,09-13 12:25:35.997  7621  7621 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,09-13 12:25:35.997   979  1472 I ActivityManager: Killing 7381:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,09-13 12:25:36.007  7597  7679 D ContactProvider: getAllContactInfoList End
,09-13 12:25:36.007  7597  7679 I syncContacts: thread: 1413, sync time = 53
,09-13 12:25:36.027   979  1483 I art     : Explicit concurrent mark sweep GC freed 31979(2010KB) AllocSpace objects, 26(1575KB) LOS objects, 33% free, 24MB/37MB, paused 2.633ms total 149.862ms
,09-13 12:25:36.037   979  1322 I ActivityManager: Killing 7399:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-13 12:25:36.047  4690  7596 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,09-13 12:25:36.067  4690  7596 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,09-13 12:25:36.067   979  1007 I ActivityManager: Killing 7360:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-13 12:25:36.807   979  1050 I PowerManagerService: [PWL] Off : 50s ago
,09-13 12:25:37.037   292   292 E SMD     : DCD OFF,
,09-13 12:25:37.237   979  3316 D SSRM:n  : SIOP:: AP = 380
,09-13 12:25:38.027   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:25:39.027   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:25:40.027   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:25:40.037   292   292 E SMD     : DCD OFF,
,09-13 12:25:40.277   979  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:25:40.277   979  1472 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:25:40.277   979  1472 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:25:40.277   979  1472 D BatteryService: stay LED for fully charged,
09-13 12:25:40.277   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:25:40.277   979   979 I MotionRecognitionService: Plugged,
09-13 12:25:40.277   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:25:40.287  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:25:40.287  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
,09-13 12:25:40.287  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:25:40.287  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:25:40.297  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:25:40.297  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:25:40.307  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:40.307  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:40.307  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:41.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:25:41.187  5637  5637 D FactoryTest: Not factory mode
,09-13 12:25:41.187  5637  5637 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-13 12:25:41.187  5637  5637 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-13 12:25:41.187  5637  5637 D MTPRx   : still no open session command from host, so toast
,09-13 12:25:41.187  5637  5637 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
,09-13 12:25:41.187  5637  5637 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
,09-13 12:25:41.197  5637  5637 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:117133,
09-13 12:25:41.197   979  1501 E PersonaManagerService: inState():  stateMachine is null !!
09-13 12:25:41.197   979  1501 I PersonaManagerService: PersonaId don't exist
,09-13 12:25:41.197   979  1501 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-13 12:25:41.207   979  1501 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-13 12:25:41.207   979  1501 W ActivityManager: userId = 0, bbcId = -10000,
,09-13 12:25:41.207   979  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 12:25:41.207   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-13 12:25:41.207   979  1501 W ActivityManager: mDVFSHelper.acquire()
,09-13 12:25:41.217   979  1501 D FocusedStackFrame: Set to : 0
,09-13 12:25:41.227   979  1501 D PersonaManager: isKioskContainerExistOnDevice
,09-13 12:25:41.237   979  1501 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-13 12:25:41.237   979  1501 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-13 12:25:41.237   979  1501 D InputDispatcher: Focused application set to: xxxx
,09-13 12:25:41.237   979  1501 D InputDispatcher: Focus left window: 1484
,09-13 12:25:41.237  5637  5637 E MTPRx   : started activity for popup
,09-13 12:25:41.237   979  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-13 12:25:41.237   979   979 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,09-13 12:25:41.237   979  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 12:25:41.267  5637  5637 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-13 12:25:41.267  5637  5637 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-13 12:25:41.267  5637  5637 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 12:25:41.267  5637  5637 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 12:25:41.267  5637  5637 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:25:41.267  5637  5637 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 12:25:41.287  5637  5637 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-13 12:25:41.287   979  1481 D FocusedStackFrame: Set to : 0
,09-13 12:25:41.287   979  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-13 12:25:41.287   979  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,09-13 12:25:41.287   979  1481 D InputDispatcher: Focused application set to: xxxx
,09-13 12:25:41.287   979  1481 D InputDispatcher: Focus entered window: 1484
,09-13 12:25:41.297   979  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 12:25:41.297   979  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 12:25:41.297   979  1472 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-13 12:25:41.297   979  1472 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@96d8a2a attribute=null, token = android.os.BinderProxy@1b6fc30
,09-13 12:25:41.337  5637  5637 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-13 12:25:41.337  5637  5637 D PhoneWindow: *FMB* installDecor mIsFloating : true
,09-13 12:25:41.337  5637  5637 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-13 12:25:42.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:25:43.037   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-13 12:25:43.037   292   292 E SMD     : DCD OFF
,09-13 12:25:44.217   979  1043 W ActivityManager: mDVFSHelper.release()
,09-13 12:25:44.537   979  1096 V AlarmManager: waitForAlarm result :4
,09-13 12:25:44.537   979  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-13 12:25:44.587  1995  1995 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-13 12:25:44.637   979  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:44.637   979  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-13 12:25:44.637   979  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:44.637   979  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:44.637   979  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:44.697  4690  4690 D ConnectivityManager: CallingUid : 10011, CallingPid : 4690
,09-13 12:25:44.697   979  1481 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 12:25:44.697   979  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-13 12:25:44.697   979  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-13 12:25:44.697   979  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,09-13 12:25:44.697  4690  7687 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 12:25:44.747  4690  7688 W DriveInitializer: Background init thread started
,09-13 12:25:44.767   258   535 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-13 12:25:44.767   258   535 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 12:25:44.767  4690  7688 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-13 12:25:44.807   979  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:44.807   979  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-13 12:25:44.817   979  1322 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:44.817   979  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:44.817   979  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:44.837   979  1501 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-13 12:25:44.837   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-13 12:25:44.857   979  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:25:44.857   979  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-13 12:25:44.857   979  1137 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:44.857  4690  7688 W DriveInitializer: Background init thread ended
,09-13 12:25:44.857   979  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:44.857   979  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:44.897  4690  7696 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-13 12:25:44.897  4690  7696 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-13 12:25:44.897  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:44.927   979  1043 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:44.927   979  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:44.927   979  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.037   979  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:45.037   979  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-13 12:25:45.047   979  1472 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:45.047   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:45.047   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.087   979  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:45.087   979  1472 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-13 12:25:45.087   979  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.087   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:45.087   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.167   979  1010 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.167   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.167   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:45.167   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.177   979  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.187   979  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.187   979  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:45.187   979  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.267   979  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.267   979  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.267   979  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:45.267   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.277   979  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:45.277   979  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:25:45.277   979  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 12:25:45.277   979  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-13 12:25:45.287  7703  7703 E Zygote  : MountEmulatedStorage()
09-13 12:25:45.287  7703  7703 E Zygote  : v2
09-13 12:25:45.287  7703  7703 I libpersona: KNOX_SDCARD checking this for 10011
09-13 12:25:45.287  7703  7703 I libpersona: KNOX_SDCARD not a persona
,09-13 12:25:45.297  7703  7703 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 12:25:45.297  7703  7703 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 12:25:45.297   979  1483 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7703 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-13 12:25:45.307  7703  7703 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-13 12:25:45.327   309   309 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 782us total 30.419ms
,09-13 12:25:45.337  7703  7703 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 12:25:45.337  7703  7703 D ActivityThread: Added TimaKeyStore provider
,09-13 12:25:45.347   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 701us total 20.403ms
,09-13 12:25:45.367  7703  7703 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 12:25:45.367  7703  7703 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-13 12:25:45.367   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 709us total 20.405ms
,09-13 12:25:45.407  7703  7703 I MultiDex: VM with version 2.1.0 has multidex support
09-13 12:25:45.407  7703  7703 I MultiDex: install
09-13 12:25:45.407  7703  7703 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-13 12:25:45.437  7703  7703 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-13 12:25:45.507  7703  7703 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-13 12:25:45.507  7703  7703 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23c0bca: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-13 12:25:45.507  7703  7703 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-13 12:25:45.527   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-13 12:25:45.537  7703  7703 D ChimeraCfgMgr: Reading stored module config
,09-13 12:25:45.537   979  1322 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.537   979  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.537   979  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:45.537   979  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.547   979  1748 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.557   979  1748 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:45.557   979  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:45.557   979  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.587  1995  1995 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=853ccb10-dcf4-4129-a171-88e6b70befd4
,09-13 12:25:45.607   979  1748 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-13 12:25:45.607   979  1748 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-13 12:25:45.607   979  1748 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.607   979  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:45.607   979  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.607  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:45.607  1995  1995 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-13 12:25:45.617  7703  7722 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-13 12:25:45.627   979  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.627   979  1501 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.627   979  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:45.627   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.637  7703  7716 W art     : Suspending all threads took: 8.230ms
,09-13 12:25:45.637  7703  7703 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 12:25:45.637  7703  7716 I art     : Background partial concurrent mark sweep GC freed 960(193KB) AllocSpace objects, 1(101KB) LOS objects, 40% free, 7MB/12MB, paused 12.054ms total 40.024ms
,09-13 12:25:45.637  7703  7703 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-13 12:25:45.707  4305  4313 I art     : Explicit concurrent mark sweep GC freed 1378(47KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 678us total 20.671ms
,09-13 12:25:45.747   284   792 D WVCdm   : Instantiating CDM.
,09-13 12:25:45.747   284   284 I WVCdm   : CdmEngine::OpenSession
,09-13 12:25:45.747   284   284 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-13 12:25:45.767   284   284 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-13 12:25:45.787   284   284 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,09-13 12:25:45.847   284   284 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-13 12:25:45.847   284   792 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-13 12:25:45.847   284   792 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-13 12:25:45.847   284   792 I WVCdm   : CdmEngine::GenerateKeyRequest
,09-13 12:25:45.847  7703  7711 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-13 12:25:45.847  7703  7711 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:25:45.847  7703  7711 I System.out: (HTTPLog)-Static: isShipBuild true
09-13 12:25:45.847  7703  7711 I System.out: (HTTPLog)-Thread-1434-787599631: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-13 12:25:45.847  7703  7711 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:45.847   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 12:25:45.847   279   966 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 12:25:45.857  1995  2151 W GCoreFlp: No location to return for getLastLocation()
,09-13 12:25:45.857   284   792 D WVCdm   : PrepareKeyRequest: nonce=1990848514
,09-13 12:25:45.887   979  1466 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.887   979  1466 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.887   979  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:45.887   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.887   979  1348 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.887   979  1348 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.887   979  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:45.887   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.887   979  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:45.897   979  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:45.897   979  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:45.897   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:45.907  1995  2154 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 12:25:45.907  7703  7711 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 12:25:45.907  7703  7711 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 7703, getuid(): 10011
,09-13 12:25:45.917  4690  7697 D UdcContextInitService: registered all accounts: true
,09-13 12:25:45.917  1995  2175 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-13 12:25:46.027  1995  2175 I art     : Explicit concurrent mark sweep GC freed 52889(3MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 11MB/18MB, paused 1.649ms total 73.072ms
,09-13 12:25:46.037   292   292 E SMD     : DCD OFF
,09-13 12:25:46.127   979  1501 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-13 12:25:46.127   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-13 12:25:46.127   979  1501 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:46.127   979  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:25:46.127   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:46.187  7703  7711 I qtaguid : Untagging socket 30
,09-13 12:25:46.217   979  1481 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-13 12:25:46.217   979  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-13 12:25:46.217   979  1481 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:25:46.217   979  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:46.217   979  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:46.247  1995  2175 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-13 12:25:46.247  1995  2175 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 12:25:46.247  1995  2175 I System.out: (HTTPLog)-Static: isShipBuild true
09-13 12:25:46.247  1995  2175 I System.out: (HTTPLog)-Thread-195-812125375: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-13 12:25:46.247  1995  2175 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:46.247   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 12:25:46.247   279   966 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 12:25:46.257  1995  2175 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 12:25:46.257  1995  2175 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1995, getuid(): 10011
,09-13 12:25:46.287  1995  2175 I qtaguid : Tagging socket 63 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1995, getuid(): 10011
,09-13 12:25:46.487  7732  7732 I dex2oat : ----------------------------------------------------
09-13 12:25:46.487  7732  7732 I dex2oat : <SS>: S T A R T I N G . . .
09-13 12:25:46.487  7732  7732 I dex2oat : <SS>: Zip is absent. Canceled.
,09-13 12:25:46.487  7732  7732 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-13 12:25:46.547   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:25:46.547  7732  7732 I dex2oat : dex2oat took 54.679ms (threads: 4)
,09-13 12:25:46.557  7703  7711 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 12:25:46.557  7703  7711 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 12:25:46.557  7703  7711 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 12:25:46.557  7703  7711 I Adreno-EGL: Local Branch: 
09-13 12:25:46.557  7703  7711 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 12:25:46.557  7703  7711 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 12:25:46.557  7703  7711 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 12:25:46.627  7703  7711 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 12:25:46.627  7703  7711 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 12:25:46.627  7703  7711 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 12:25:46.627  7703  7711 I Adreno-EGL: Local Branch: 
09-13 12:25:46.627  7703  7711 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 12:25:46.627  7703  7711 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 12:25:46.627  7703  7711 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 12:25:46.977  7703  7711 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 12:25:46.977  7703  7711 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 12:25:46.977  7703  7711 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 12:25:46.977  7703  7711 I Adreno-EGL: Local Branch: 
09-13 12:25:46.977  7703  7711 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 12:25:46.977  7703  7711 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 12:25:46.977  7703  7711 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 12:25:47.077  1995  7699 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:47.077  1995  7699 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-13 12:25:47.077  1995  7699 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1995, getuid(): 10011
,09-13 12:25:47.137  1995  7699 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1995, getuid(): 10011
,09-13 12:25:47.267   979  3316 D SSRM:n  : SIOP:: AP = 350
,09-13 12:25:47.337  1995  2175 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 12:25:47.337  1995  2175 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-13 12:25:47.347  1995  2175 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-13 12:25:46.058+0200, stopTime=2016-09-13 12:25:47.354+0200, duration=1296ms
,09-13 12:25:47.357  1995  7740 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:47.367   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 12:25:47.367   279   966 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 12:25:47.367  1995  7740 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-13 12:25:47.367  1995  7740 I qtaguid : Tagging socket 71 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1995, getuid(): 10011
,09-13 12:25:47.387   979  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-13 12:25:47.397  1995  7740 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1995, getuid(): 10011
,09-13 12:25:47.397   284   796 I WVCdm   : CdmEngine::CloseSession
,09-13 12:25:47.407   284   796 I WVCdm   : L3 Terminate.
,09-13 12:25:47.637  1995  7740 I qtaguid : Untagging socket 71
,09-13 12:25:47.687   979  1010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 12:25:47.687   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-13 12:25:47.687   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:47.687   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:47.687   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:47.717  1995  2175 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-13 12:25:47.787   979  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:47.787   979  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:47.787   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:47.787   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:47.807   979  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:47.817   979  1501 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:47.817   979  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:47.817   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:47.867   979  1748 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:47.867   979  1748 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:47.867   979  1748 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:47.867   979  1748 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:47.867  1995  7748 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 12:25:47.867  1995  7746 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 12:25:47.867   979  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:47.867   979  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:47.877   979  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:47.877   979  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:47.897   979  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:47.897   979  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:47.897   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:47.897   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:47.897  1995  7748 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 12:25:47.897  1995  7746 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 12:25:47.897   979  1010 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:47.897   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:47.897   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:47.897   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:47.927   979  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:25:47.927   979  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:25:47.927   979  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:25:47.927   979  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:25:47.927  1995  7748 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-13 12:25:47.927  1995  7746 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-13 12:25:47.927  1995  7746 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-13 12:25:47.937  1995  7746 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 12:25:47.987   979  1472 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:25:48.027  1995  7746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:48.027   279   966 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 12:25:48.027   279   966 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,09-13 12:25:48.037  1995  7746 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-13 12:25:48.037  1995  7746 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1995, getuid(): 10011
09-13 12:25:48.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:25:48.067  1995  7746 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1995, getuid(): 10011
,09-13 12:25:48.337   979  1322 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:25:48.347  1995  7746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:48.347  1995  7746 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1995, getuid(): 10011
,09-13 12:25:48.457   979  1010 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:25:48.467  1995  7746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:48.467  1995  7746 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1995, getuid(): 10011
,09-13 12:25:48.607   979  1322 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:25:48.617  1995  7746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:48.617  1995  7746 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1995, getuid(): 10011
,09-13 12:25:48.767   979  1466 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:25:48.767  1995  7746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:48.777  1995  7746 I qtaguid : Tagging socket 81 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1995, getuid(): 10011
,09-13 12:25:48.927   979  1472 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:25:48.957  1995  7746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:48.967  1995  7746 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1995, getuid(): 10011
,09-13 12:25:49.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:25:49.037   292   292 E SMD     : DCD OFF
,09-13 12:25:49.117  1995  7746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:49.117  1995  7746 I qtaguid : Tagging socket 81 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1995, getuid(): 10011
,09-13 12:25:49.287   979  1348 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-13 12:25:49.307  1995  7746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:49.307  1995  7746 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1995, getuid(): 10011
,09-13 12:25:49.457  1995  7742 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-13 12:25:49.457  1995  7742 I qtaguid : Tagging socket 71 with tag 1000310200000000{268448002,0} for uid 10011, pid: 1995, getuid(): 10011
,09-13 12:25:49.667  1995  7742 I qtaguid : Untagging socket 71
,09-13 12:25:49.677  1995  2176 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-13 12:25:49.867   979  1501 I art     : Explicit concurrent mark sweep GC freed 32574(1725KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 24MB/36MB, paused 2.375ms total 154.052ms
,09-13 12:25:49.867   979  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-13 12:25:50.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:25:50.337   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:25:50.337   979  1007 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
09-13 12:25:50.337   979  1007 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-13 12:25:50.337   979  1007 D BatteryService: stay LED for fully charged,
,09-13 12:25:50.337   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 12:25:50.347   979   979 I MotionRecognitionService: Plugged
,09-13 12:25:50.347   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:25:50.347  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:25:50.347  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:25:50.357  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:25:50.357  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:25:50.367  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:25:50.367  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:25:50.377  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:50.377  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:25:50.377  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:25:51.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:25:51.527   979   979 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,09-13 12:25:52.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:25:52.037   292   292 E SMD     : DCD OFF,
,09-13 12:25:52.077   979  1007 I ActivityManager: Killing 7418:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-13 12:25:53.037   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-13 12:25:55.037   292   292 E SMD     : DCD OFF
,09-13 12:25:57.297   979  3316 D SSRM:n  : SIOP:: AP = 330
,09-13 12:25:58.047   292   292 E SMD     : DCD OFF
,09-13 12:25:59.997   979  1096 V AlarmManager: waitForAlarm result :8
,09-13 12:26:00.397   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:26:00.397   979  1007 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:26:00.397   979  1007 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-13 12:26:00.397   979  1007 D BatteryService: stay LED for fully charged
09-13 12:26:00.397   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 12:26:00.407   979   979 I MotionRecognitionService: Plugged
09-13 12:26:00.407   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:26:00.407  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-13 12:26:00.407  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:26:00.407  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-13 12:26:00.407  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:26:00.417  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:26:00.417  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:26:00.417  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:26:00.427  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:26:00.427  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:26:01.047   292   292 E SMD     : DCD OFF
,09-13 12:26:01.807   979  1050 I PowerManagerService: [PWL] Off : 75s ago
,09-13 12:26:01.987   979  1324 E Watchdog: !@Sync 4
,09-13 12:26:03.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:04.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:04.047   292   292 E SMD     : DCD OFF,
,09-13 12:26:05.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:26:06.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:06.537   979  2072 V SAMP_SPCM_test: CSC File load.. 
,09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
09-13 12:26:06.547   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-13 12:26:06.547   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.D,eviceAdminManager.AdminReceiver}: mdm-data-time
,09-13 12:26:06.587   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-13 12:26:06.587   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-13 12:26:06.587   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,09-13 12:26:06.587   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-13 12:26:06.587   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,09-13 12:26:06.587   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-13 12:26:06.587   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
,09-13 12:26:06.597   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknow,n tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-13 12:26:06.607   979  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-13 12:26:06.637   979  2072 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-13 12:26:07.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:07.047   292   292 E SMD     : DCD OFF
,09-13 12:26:07.337   979  3316 D SSRM:n  : SIOP:: AP = 310
,09-13 12:26:08.037   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-13 12:26:10.047   292   292 E SMD     : DCD OFF,
,09-13 12:26:10.457   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:26:13.047   292   292 E SMD     : DCD OFF
,09-13 12:26:16.057   292   292 E SMD     : DCD OFF,
,09-13 12:26:17.367   979  3316 D SSRM:n  : SIOP:: AP = 300,
,09-13 12:26:19.057   292   292 E SMD     : DCD OFF,
,09-13 12:26:20.517   979  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:20.517   979  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:26:20.517   979  1466 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:26:20.517   979  1466 D BatteryService: stay LED for fully charged
09-13 12:26:20.517   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:26:20.527  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,09-13 12:26:20.527  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:26:20.527  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:26:20.527  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,09-13 12:26:20.537   979   979 I MotionRecognitionService: Plugged
,09-13 12:26:20.537   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:26:20.537  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:26:20.537  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:26:20.537  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:26:20.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:26:20.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:26:22.057   292   292 E SMD     : DCD OFF,
,09-13 12:26:23.037   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:24.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:25.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:26:25.057   292   292 E SMD     : DCD OFF,
,09-13 12:26:26.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:26:26.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:26:27.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:26:27.407   979  3316 D SSRM:n  : SIOP:: AP = 290
,09-13 12:26:28.047   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,09-13 12:26:28.057   292   292 E SMD     : DCD OFF,
,09-13 12:26:30.577   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:31.057   292   292 E SMD     : DCD OFF
,09-13 12:26:31.817   979  1050 I PowerManagerService: [PWL] Off : 105s ago,
,09-13 12:26:31.987   979  1324 E Watchdog: !@Sync 5,
,09-13 12:26:34.057   292   292 E SMD     : DCD OFF
,09-13 12:26:34.247  4690  5105 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 12:26:37.067   292   292 E SMD     : DCD OFF
,09-13 12:26:37.437   979  3316 D SSRM:n  : SIOP:: AP = 290,
,09-13 12:26:40.067   292   292 E SMD     : DCD OFF
,09-13 12:26:40.637   979  1010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:26:43.067   292   292 E SMD     : DCD OFF
,09-13 12:26:46.067   292   292 E SMD     : DCD OFF
,09-13 12:26:46.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:26:47.467   979  3316 D SSRM:n  : SIOP:: AP = 290
,09-13 12:26:48.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:49.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:49.067   292   292 E SMD     : DCD OFF
,09-13 12:26:50.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:26:50.697   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:26:51.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:26:52.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:26:52.077   292   292 E SMD     : DCD OFF
,09-13 12:26:53.047   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-13 12:26:55.077   292   292 E SMD     : DCD OFF
,09-13 12:26:57.507   979  3316 D SSRM:n  : SIOP:: AP = 290,
,09-13 12:26:58.077   292   292 E SMD     : DCD OFF
,09-13 12:27:00.747   979  1010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:27:01.077   292   292 E SMD     : DCD OFF
,09-13 12:27:01.987   979  1324 E Watchdog: !@Sync 6
,09-13 12:27:04.077   292   292 E SMD     : DCD OFF
,09-13 12:27:06.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:27:06.847   979  1050 I PowerManagerService: [PWL] Off : 140s ago,
,09-13 12:27:07.077   292   292 E SMD     : DCD OFF,
,09-13 12:27:07.547   979  3316 D SSRM:n  : SIOP:: AP = 290
,09-13 12:27:08.777   979  1096 V AlarmManager: waitForAlarm result :4
,09-13 12:27:08.777  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-13 12:27:08.777  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:27:08.797  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,09-13 12:27:08.797  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1,
,09-13 12:27:08.807  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:27:08.807  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-13 12:27:08.807  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,09-13 12:27:08.817  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:27:08.837  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:27:08.847  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:27:08.857  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:27:10.087   292   292 E SMD     : DCD OFF
,09-13 12:27:10.817   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:27:13.087   292   292 E SMD     : DCD OFF
,09-13 12:27:16.087   292   292 E SMD     : DCD OFF
,09-13 12:27:17.577   979  3316 D SSRM:n  : SIOP:: AP = 290,
,09-13 12:27:18.047   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-13 12:27:18.047   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 12:27:19.087   292   292 E SMD     : DCD OFF
,09-13 12:27:20.877   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:27:22.087   292   292 E SMD     : DCD OFF
,09-13 12:27:25.097   292   292 E SMD     : DCD OFF
,09-13 12:27:26.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:27:27.617   979  3316 D SSRM:n  : SIOP:: AP = 280,
,09-13 12:27:28.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:28.097   292   292 E SMD     : DCD OFF
,09-13 12:27:29.047   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:27:30.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:27:30.927   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:27:31.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:31.097   292   292 E SMD     : DCD OFF
,09-13 12:27:31.987   979  1324 E Watchdog: !@Sync 7
,09-13 12:27:32.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:27:33.057   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-13 12:27:34.097   292   292 E SMD     : DCD OFF
,09-13 12:27:37.097   292   292 E SMD     : DCD OFF,
,09-13 12:27:37.647   979  3316 D SSRM:n  : SIOP:: AP = 270,
,09-13 12:27:38.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:27:39.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:40.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:40.097   292   292 E SMD     : DCD OFF
,09-13 12:27:40.987   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:27:41.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:42.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:43.057   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-13 12:27:43.107   292   292 E SMD     : DCD OFF
,09-13 12:27:46.107   292   292 E SMD     : DCD OFF
,09-13 12:27:46.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:27:46.887   979  1050 I PowerManagerService: [PWL] Off : 180s ago
,09-13 12:27:47.687   979  3316 D SSRM:n  : SIOP:: AP = 270,
,09-13 12:27:49.107   292   292 E SMD     : DCD OFF
,09-13 12:27:49.447  1995  3072 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 12:27:51.047   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:27:51.047   979  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:27:51.047   979  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:27:51.047   979  1481 D BatteryService: stay LED for fully charged
09-13 12:27:51.047   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 12:27:51.047   979   979 I MotionRecognitionService: Plugged,
09-13 12:27:51.047   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:27:51.057  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-13 12:27:51.057  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:27:51.057  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:27:51.057  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:27:51.067  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-13 12:27:51.067  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:27:51.077  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:51.087  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:51.087  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:27:52.107   292   292 E SMD     : DCD OFF
,09-13 12:27:53.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:27:54.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:55.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:55.107   292   292 E SMD     : DCD OFF
,09-13 12:27:56.057   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:27:57.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:27:57.717   979  3316 D SSRM:n  : SIOP:: AP = 270
,09-13 12:27:58.067   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-13 12:27:58.107   292   292 E SMD     : DCD OFF
,09-13 12:27:59.997   979  1096 V AlarmManager: waitForAlarm result :8
,09-13 12:28:01.107   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:01.117   292   292 E SMD     : DCD OFF
,09-13 12:28:01.987   979  1324 E Watchdog: !@Sync 8
,09-13 12:28:04.117   292   292 E SMD     : DCD OFF
,09-13 12:28:06.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:28:07.117   292   292 E SMD     : DCD OFF
,09-13 12:28:07.747   979  3316 D SSRM:n  : SIOP:: AP = 270
,09-13 12:28:10.117   292   292 E SMD     : DCD OFF
,09-13 12:28:11.167   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:28:13.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:28:13.117   292   292 E SMD     : DCD OFF
,09-13 12:28:14.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:28:15.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:28:16.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:28:16.117   292   292 E SMD     : DCD OFF
,09-13 12:28:17.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:28:17.777   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:28:18.067   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,09-13 12:28:19.127   292   292 E SMD     : DCD OFF
,09-13 12:28:21.227   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:22.127   292   292 E SMD     : DCD OFF
,09-13 12:28:25.127   292   292 E SMD     : DCD OFF
,09-13 12:28:26.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:28:27.807   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:28:28.127   292   292 E SMD     : DCD OFF,
,09-13 12:28:31.127   292   292 E SMD     : DCD OFF
,09-13 12:28:31.287   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:28:31.927   979  1050 I PowerManagerService: [PWL] Off : 225s ago,
,09-13 12:28:31.987   979  1324 E Watchdog: !@Sync 9,
,09-13 12:28:34.137   292   292 E SMD     : DCD OFF
,09-13 12:28:37.137   292   292 E SMD     : DCD OFF
,09-13 12:28:37.837   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:28:38.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:28:39.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:28:40.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:28:40.137   292   292 E SMD     : DCD OFF
,09-13 12:28:41.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:28:41.347   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:28:42.067   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:28:43.067   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,09-13 12:28:43.137   292   292 E SMD     : DCD OFF
,09-13 12:28:46.137   292   292 E SMD     : DCD OFF
,09-13 12:28:46.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:28:47.867   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:28:49.137   292   292 E SMD     : DCD OFF
,09-13 12:28:51.407   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:28:52.147   292   292 E SMD     : DCD OFF
,09-13 12:28:55.147   292   292 E SMD     : DCD OFF
,09-13 12:28:57.897   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:28:58.147   292   292 E SMD     : DCD OFF
,09-13 12:28:58.957   979  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
09-13 12:28:58.957   979  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:28:58.957   979  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000,
,09-13 12:28:58.967   979  1087 I TLC_TIMA_PKM_initialize: initializing...,
09-13 12:28:58.967   979  1087 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
09-13 12:28:58.967   979  1087 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
09-13 12:28:58.967   979  1087 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
09-13 12:28:58.967   979  1087 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
09-13 12:28:58.967   979  1087 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
09-13 12:28:58.967   979  1087 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040,
09-13 12:28:58.967   979  1087 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
09-13 12:28:58.967   979  1087 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
09-13 12:28:58.967   979  1087 D QSEECOMAPI: : App is not loaded in QSEE
,09-13 12:28:58.997   979  1087 D QSEECOMAPI: : Loaded image: APP id = 12
,09-13 12:28:59.007   979  1087 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,09-13 12:28:59.007   979  1087 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,09-13 12:29:00.957   979  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:29:00.957   979  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:29:00.967   979  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:29:00.967   979  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:29:01.147   292   292 E SMD     : DCD OFF
,09-13 12:29:01.467   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:29:01.467   979  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:29:01.467   979  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:29:01.467   979  1481 D BatteryService: stay LED for fully charged
,09-13 12:29:01.467   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:01.467   979   979 I MotionRecognitionService: Plugged
,09-13 12:29:01.467   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:29:01.477  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:29:01.477  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:29:01.477  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:29:01.477  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:29:01.487  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-13 12:29:01.487  3146  3250 D HeadsetStateMachine: Disconnected process message: 10,
,09-13 12:29:01.497  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:01.497  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:01.497  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:01.987   979  1324 E Watchdog: !@Sync 10
,09-13 12:29:04.147   292   292 E SMD     : DCD OFF
,09-13 12:29:06.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:29:07.147   292   292 E SMD     : DCD OFF
,09-13 12:29:07.927   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:29:08.067   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-13 12:29:08.067   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 12:29:10.157   292   292 E SMD     : DCD OFF
,09-13 12:29:11.527   979  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:29:11.527   979  1472 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:29:11.527   979  1472 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:29:11.527   979  1472 D BatteryService: stay LED for fully charged
09-13 12:29:11.527   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:11.527   979   979 I MotionRecognitionService: Plugged
09-13 12:29:11.527   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:29:11.537  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:29:11.537  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:29:11.537  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:29:11.537  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:29:11.547  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:11.547  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:29:11.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:11.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:11.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:13.157   292   292 E SMD     : DCD OFF
,09-13 12:29:16.157   292   292 E SMD     : DCD OFF
,09-13 12:29:17.957   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:29:19.157   292   292 E SMD     : DCD OFF
,09-13 12:29:21.587   979  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:29:21.587   979  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:29:21.587   979  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:29:21.587   979  1483 D BatteryService: stay LED for fully charged,
09-13 12:29:21.587   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 12:29:21.587   979   979 I MotionRecognitionService: Plugged
09-13 12:29:21.587   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:29:21.597  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-13 12:29:21.597  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:29:21.597  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:29:21.597  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:29:21.607  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:21.607  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:29:21.617  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:21.617  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:21.617  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:21.927   979  1050 I PowerManagerService: [PWL] Off : 275s ago
,09-13 12:29:22.157   292   292 E SMD     : DCD OFF
,09-13 12:29:23.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:24.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:25.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:25.167   292   292 E SMD     : DCD OFF,
,09-13 12:29:26.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:26.617   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:29:27.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:27.997   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:29:28.077   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-13 12:29:28.167   292   292 E SMD     : DCD OFF,
,09-13 12:29:31.167   292   292 E SMD     : DCD OFF
,09-13 12:29:31.647   979  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:29:31.987   979  1324 E Watchdog: !@Sync 11,
,09-13 12:29:33.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:34.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:34.167   292   292 E SMD     : DCD OFF
,09-13 12:29:35.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:36.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:37.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:37.167   292   292 E SMD     : DCD OFF
,09-13 12:29:38.027   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:29:38.077   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-13 12:29:40.167   292   292 E SMD     : DCD OFF
,09-13 12:29:41.697   979  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:29:41.697   979  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:29:41.697   979  1322 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:29:41.697   979  1322 D BatteryService: stay LED for fully charged
09-13 12:29:41.697   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:41.707  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:29:41.707   979   979 I MotionRecognitionService: Plugged
09-13 12:29:41.707  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-13 12:29:41.707   979   979 I MotionRecognitionService: mGripSensorEnabled= false
09-13 12:29:41.707  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:29:41.707  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:29:41.717  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:41.717  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:29:41.727  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
09-13 12:29:41.727  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:41.727  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:43.177   292   292 E SMD     : DCD OFF
,09-13 12:29:46.177   292   292 E SMD     : DCD OFF
,09-13 12:29:46.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:29:48.067   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:29:48.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:29:49.077   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:29:49.177   292   292 E SMD     : DCD OFF
,09-13 12:29:50.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:51.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:29:51.757   979  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:29:51.757   979  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:29:51.757   979  1748 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-13 12:29:51.757   979  1748 D BatteryService: stay LED for fully charged
09-13 12:29:51.757   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:29:51.767   979   979 I MotionRecognitionService: Plugged
09-13 12:29:51.767   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:29:51.767  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-13 12:29:51.777  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:29:51.777  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:29:51.777  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:29:51.787  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:29:51.787  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:29:51.797  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:51.797  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:29:51.797  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:29:52.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:29:52.177   292   292 E SMD     : DCD OFF
,09-13 12:29:53.087   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-13 12:29:55.177   292   292 E SMD     : DCD OFF,
,09-13 12:29:58.097   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:29:58.177   292   292 E SMD     : DCD OFF
,09-13 12:30:01.187   292   292 E SMD     : DCD OFF
,09-13 12:30:01.827   979  1010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:30:01.997   979  1324 E Watchdog: !@Sync 12,
,09-13 12:30:04.187   292   292 E SMD     : DCD OFF
,09-13 12:30:06.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:30:07.187   292   292 E SMD     : DCD OFF
,09-13 12:30:07.647  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:30:07.657  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:30:08.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:30:08.137   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:30:09.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:30:10.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:30:10.187   292   292 E SMD     : DCD OFF
,09-13 12:30:11.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:30:11.887   979  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:30:12.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:30:13.087   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,09-13 12:30:13.187   292   292 E SMD     : DCD OFF
,09-13 12:30:14.677  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-13 12:30:14.677  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:30:16.187   292   292 E SMD     : DCD OFF
,09-13 12:30:16.957   979  1050 I PowerManagerService: [PWL] Off : 330s ago
,09-13 12:30:18.177   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:30:19.197   292   292 E SMD     : DCD OFF
,09-13 12:30:21.947   979  1010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:30:21.947   979  1010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:30:21.947   979  1010 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:30:21.947   979  1010 D BatteryService: stay LED for fully charged
09-13 12:30:21.947   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,09-13 12:30:21.947  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:30:21.947  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:30:21.957  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:30:21.957  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:30:21.957   979   979 I MotionRecognitionService: Plugged
09-13 12:30:21.957  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 12:30:21.957   979   979 I MotionRecognitionService: mGripSensorEnabled= false
09-13 12:30:21.957  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
09-13 12:30:21.957  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:30:21.957  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:21.977  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:30:22.197   292   292 E SMD     : DCD OFF
,09-13 12:30:25.197   292   292 E SMD     : DCD OFF
,09-13 12:30:26.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:30:28.197   292   292 E SMD     : DCD OFF
,09-13 12:30:28.207   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:30:31.197   292   292 E SMD     : DCD OFF
,09-13 12:30:31.997   979  1324 E Watchdog: !@Sync 13,
,09-13 12:30:32.007   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:33.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:30:34.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:30:34.197   292   292 E SMD     : DCD OFF
,09-13 12:30:35.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:30:36.087   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:30:37.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:30:37.207   292   292 E SMD     : DCD OFF
,09-13 12:30:38.097   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-13 12:30:38.247   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:30:40.207   292   292 E SMD     : DCD OFF
,09-13 12:30:42.067   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:30:43.207   292   292 E SMD     : DCD OFF
,09-13 12:30:46.207   292   292 E SMD     : DCD OFF,
,09-13 12:30:46.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:30:48.277   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:30:49.207   292   292 E SMD     : DCD OFF,
,09-13 12:30:52.127   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:30:52.217   292   292 E SMD     : DCD OFF,
,09-13 12:30:55.217   292   292 E SMD     : DCD OFF
,09-13 12:30:58.217   292   292 E SMD     : DCD OFF,
,09-13 12:30:58.317   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:30:59.997  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-13 12:30:59.997   979  1096 V AlarmManager: waitForAlarm result :8
09-13 12:30:59.997  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 12:30:59.997   979  1096 V AlarmManager: No more alarm at this time.nowELAPSED=435932 batch.start=808706
09-13 12:31:00.007  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
09-13 12:31:00.007  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
09-13 12:31:00.007  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-13 12:31:00.007  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-13 12:31:00.007  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,09-13 12:31:00.027  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:31:00.047  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:31:00.057  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:31:00.067  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:31:01.217   292   292 E SMD     : DCD OFF,
,09-13 12:31:01.997   979  1324 E Watchdog: !@Sync 14,
,09-13 12:31:02.187   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:03.097   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-13 12:31:03.097   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 12:31:04.217   292   292 E SMD     : DCD OFF,
,09-13 12:31:06.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:31:07.217   292   292 E SMD     : DCD OFF
,09-13 12:31:08.347   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:31:10.227   292   292 E SMD     : DCD OFF,
,09-13 12:31:12.257   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:13.227   292   292 E SMD     : DCD OFF,
,09-13 12:31:16.227   292   292 E SMD     : DCD OFF,
,09-13 12:31:16.967   979  1050 I PowerManagerService: [PWL] Off : 390s ago,
,09-13 12:31:18.387   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:31:19.227   292   292 E SMD     : DCD OFF,
,09-13 12:31:22.227   292   292 E SMD     : DCD OFF,
,09-13 12:31:22.317   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:31:23.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:24.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:25.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:25.237   292   292 E SMD     : DCD OFF,
,09-13 12:31:26.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:26.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:31:27.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:28.097   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-13 12:31:28.237   292   292 E SMD     : DCD OFF,
,09-13 12:31:28.417   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:31:31.237   292   292 E SMD     : DCD OFF,
,09-13 12:31:31.997   979  1324 E Watchdog: !@Sync 15,
,09-13 12:31:32.377   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:31:33.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:34.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:34.237   292   292 E SMD     : DCD OFF,
,09-13 12:31:35.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:36.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:37.097   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:37.237   292   292 E SMD     : DCD OFF,
,09-13 12:31:38.097   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-13 12:31:38.457   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:31:40.237   292   292 E SMD     : DCD OFF,
,09-13 12:31:42.437   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:43.247   292   292 E SMD     : DCD OFF
,09-13 12:31:46.247   292   292 E SMD     : DCD OFF,
,09-13 12:31:46.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:31:48.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:48.487   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:31:49.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:49.247   292   292 E SMD     : DCD OFF,
,09-13 12:31:50.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:51.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:51.147   326   326 I bootchecker: bootchecker wake up!!,
,09-13 12:31:52.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:31:52.247   292   292 E SMD     : DCD OFF,
,09-13 12:31:52.497   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:31:52.497   979  1348 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:31:52.497   979  1348 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 12:31:52.497   979  1348 D BatteryService: stay LED for fully charged
,09-13 12:31:52.497   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:31:52.497   979   979 I MotionRecognitionService: Plugged
,09-13 12:31:52.497  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:31:52.497   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:31:52.507  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-13 12:31:52.507  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:31:52.507  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:31:52.507  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-13 12:31:52.507  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:31:52.527  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:52.527  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:31:52.527  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:31:53.107   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-13 12:31:55.247   292   292 E SMD     : DCD OFF,
,09-13 12:31:58.247   292   292 E SMD     : DCD OFF,
,09-13 12:31:58.527   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:31:59.997   979  1096 V AlarmManager: waitForAlarm result :8,
,09-13 12:32:01.247   292   292 E SMD     : DCD OFF,
,09-13 12:32:01.997   979  1324 E Watchdog: !@Sync 16,
,09-13 12:32:02.547   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:32:04.257   292   292 E SMD     : DCD OFF,
,09-13 12:32:06.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:32:07.257   292   292 E SMD     : DCD OFF,
,09-13 12:32:08.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:08.567   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:32:09.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:10.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:10.257   292   292 E SMD     : DCD OFF,
,09-13 12:32:11.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:12.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:12.607   979  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:32:13.107   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,09-13 12:32:13.257   292   292 E SMD     : DCD OFF,
,09-13 12:32:16.257   292   292 E SMD     : DCD OFF,
,09-13 12:32:18.597   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:32:19.257   292   292 E SMD     : DCD OFF,
,09-13 12:32:21.997   979  1050 I PowerManagerService: [PWL] Off : 455s ago,
,09-13 12:32:22.267   292   292 E SMD     : DCD OFF,
,09-13 12:32:22.677   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:32:25.267   292   292 E SMD     : DCD OFF
,09-13 12:32:26.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:32:28.267   292   292 E SMD     : DCD OFF,
,09-13 12:32:28.637   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:32:31.267   292   292 E SMD     : DCD OFF
,09-13 12:32:31.997   979  1324 E Watchdog: !@Sync 17
,09-13 12:32:32.737   979  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:32:33.107   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:34.117   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 12:32:34.267   292   292 E SMD     : DCD OFF,
,09-13 12:32:35.117   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:36.117   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:37.117   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 12:32:37.267   292   292 E SMD     : DCD OFF
,09-13 12:32:38.117   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,09-13 12:32:38.677   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:32:40.277   292   292 E SMD     : DCD OFF,
,09-13 12:32:42.787   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:32:43.277   292   292 E SMD     : DCD OFF,
,09-13 12:32:46.277   292   292 E SMD     : DCD OFF,
,09-13 12:32:46.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:32:48.707   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:32:49.277   292   292 E SMD     : DCD OFF,
,09-13 12:32:52.277   292   292 E SMD     : DCD OFF,
,09-13 12:32:52.847   979  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:32:55.277   292   292 E SMD     : DCD OFF,
,09-13 12:32:58.287   292   292 E SMD     : DCD OFF,
,09-13 12:32:58.747   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:33:01.287   292   292 E SMD     : DCD OFF,
,09-13 12:33:01.997   979  1324 E Watchdog: !@Sync 18,
,09-13 12:33:02.907   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:33:03.117   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-13 12:33:03.117   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 12:33:04.287   292   292 E SMD     : DCD OFF,
,09-13 12:33:06.627   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:33:07.287   292   292 E SMD     : DCD OFF,
,09-13 12:33:08.787   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:33:10.287   292   292 E SMD     : DCD OFF,
,09-13 12:33:12.967   979  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:33:13.297   292   292 E SMD     : DCD OFF,
,09-13 12:33:16.297   292   292 E SMD     : DCD OFF
,09-13 12:33:18.817   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:33:19.297   292   292 E SMD     : DCD OFF
,09-13 12:33:22.297   292   292 E SMD     : DCD OFF,
,09-13 12:33:23.037   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:33:23.037   979  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:33:23.037   979  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:33:23.037   979  1479 D BatteryService: stay LED for fully charged
09-13 12:33:23.037   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:33:23.037   979   979 I MotionRecognitionService: Plugged
09-13 12:33:23.037   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:33:23.037  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-13 12:33:23.037  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:33:23.037  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:33:23.037  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:33:23.047  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:33:23.047  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:33:23.067  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:23.067  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:33:23.067  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:25.297   292   292 E SMD     : DCD OFF
,09-13 12:33:26.637   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:33:28.117   333   333 I Atfwd_Daemon: Stop the daemon....,
,09-13 12:33:28.297   292   292 E SMD     : DCD OFF
,09-13 12:33:28.857   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:33:31.307   292   292 E SMD     : DCD OFF,
,09-13 12:33:31.997   979  1324 E Watchdog: !@Sync 19,
,09-13 12:33:32.007   979  1050 I PowerManagerService: [PWL] Off : 525s ago,
,09-13 12:33:33.097   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:33:33.097   979  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:33:33.097   979  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:33:33.097   979  1479 D BatteryService: stay LED for fully charged
09-13 12:33:33.097   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:33:33.097  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:33:33.097   979   979 I MotionRecognitionService: Plugged,
09-13 12:33:33.097   979   979 I MotionRecognitionService: mGripSensorEnabled= false
09-13 12:33:33.107  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:33:33.107  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:33:33.107  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:33:33.107  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:33.107  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:33:33.107  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:33:33.127  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:33.127  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:34.307   292   292 E SMD     : DCD OFF
,09-13 12:33:37.307   292   292 E SMD     : DCD OFF,
,09-13 12:33:38.897   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:33:40.307   292   292 E SMD     : DCD OFF,
,09-13 12:33:43.147   979  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:33:43.147   979  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:33:43.147   979  1466 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:33:43.147   979  1466 D BatteryService: stay LED for fully charged
09-13 12:33:43.147   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:33:43.157  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:33:43.157   979   979 I MotionRecognitionService: Plugged
09-13 12:33:43.157  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:33:43.157   979   979 I MotionRecognitionService: mGripSensorEnabled= false
09-13 12:33:43.157  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:33:43.157  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:33:43.167  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:33:43.167  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:33:43.177  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:43.187  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:33:43.187  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:33:43.307   292   292 E SMD     : DCD OFF,
,09-13 12:33:46.307   292   292 E SMD     : DCD OFF,
,09-13 12:33:46.637   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 12:33:48.927   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:33:49.307   292   292 E SMD     : DCD OFF
,09-13 12:33:52.317   292   292 E SMD     : DCD OFF,
,09-13 12:33:53.217   979  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:33:55.317   292   292 E SMD     : DCD OFF,
,09-13 12:33:58.317   292   292 E SMD     : DCD OFF,
,09-13 12:33:58.957   979  1087 D TimaService: TIMA: TimaService scheduler is intialized. ,
,09-13 12:33:58.957   979  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
09-13 12:33:58.957   979  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:33:58.967   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:33:59.797   979  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:33:59.797   979  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:33:59.797   979  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:33:59.797   979  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:34:01.317   292   292 E SMD     : DCD OFF,
,09-13 12:34:01.997   979  1324 E Watchdog: !@Sync 20,
,09-13 12:34:03.287   979  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:34:04.317   292   292 E SMD     : DCD OFF,
,09-13 12:34:06.637   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:34:07.327   292   292 E SMD     : DCD OFF,
,09-13 12:34:09.007   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:34:10.327   292   292 E SMD     : DCD OFF,
,09-13 12:34:13.327   292   292 E SMD     : DCD OFF,
,09-13 12:34:13.337   979  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:34:16.327   292   292 E SMD     : DCD OFF,
,09-13 12:34:19.047   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:34:19.327   292   292 E SMD     : DCD OFF,
,09-13 12:34:22.327   292   292 E SMD     : DCD OFF,
,09-13 12:34:23.407   979  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:34:25.337   292   292 E SMD     : DCD OFF,
,09-13 12:34:26.637   979  3355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 12:34:28.337   292   292 E SMD     : DCD OFF
,09-13 12:34:29.077   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:34:31.337   292   292 E SMD     : DCD OFF,
,09-13 12:34:31.997   979  1324 E Watchdog: !@Sync 21,
,09-13 12:34:33.467   979  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:34:34.337   292   292 E SMD     : DCD OFF,
,09-13 12:34:37.337   292   292 E SMD     : DCD OFF,
,09-13 12:34:39.117   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:34:40.337   292   292 E SMD     : DCD OFF
,09-13 12:34:43.347   292   292 E SMD     : DCD OFF
,09-13 12:34:43.527   979  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:34:46.347   292   292 E SMD     : DCD OFF,
,09-13 12:34:47.047   979  1050 I PowerManagerService: [PWL] Off : 600s ago,
,09-13 12:34:49.157   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:34:49.347   292   292 E SMD     : DCD OFF,
,09-13 12:34:52.347   292   292 E SMD     : DCD OFF,
,09-13 12:34:53.587   979  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:34:55.347   292   292 E SMD     : DCD OFF,
,09-13 12:34:58.347   292   292 E SMD     : DCD OFF,
,09-13 12:34:59.187   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:35:01.357   292   292 E SMD     : DCD OFF,
,09-13 12:35:01.997   979  1324 E Watchdog: !@Sync 22
,09-13 12:35:03.647   979  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:35:04.357   292   292 E SMD     : DCD OFF,
,09-13 12:35:07.357   292   292 E SMD     : DCD OFF,
,09-13 12:35:09.227   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:35:10.357   292   292 E SMD     : DCD OFF,
,09-13 12:35:13.357   292   292 E SMD     : DCD OFF,
,09-13 12:35:13.707   979  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:35:13.707   979  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:35:13.707   979  1322 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 12:35:13.707   979  1322 D BatteryService: stay LED for fully charged
09-13 12:35:13.707   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:35:13.717   979   979 I MotionRecognitionService: Plugged
,09-13 12:35:13.717  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:35:13.717   979   979 I MotionRecognitionService: mGripSensorEnabled= false
09-13 12:35:13.717  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:35:13.717  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:35:13.717  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:35:13.727  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:35:13.727  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:35:13.737  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:13.737  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:13.737  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:14.777  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:35:14.777  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:35:16.357   292   292 E SMD     : DCD OFF,
,09-13 12:35:19.267   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:35:19.367   292   292 E SMD     : DCD OFF,
,09-13 12:35:22.367   292   292 E SMD     : DCD OFF
,09-13 12:35:23.767   979  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:35:23.767   979  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:35:23.767   979  1748 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:35:23.767   979  1748 D BatteryService: stay LED for fully charged
,09-13 12:35:23.767   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:35:23.777   979   979 I MotionRecognitionService: Plugged
,09-13 12:35:23.777   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:35:23.777  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:35:23.777  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:35:23.777  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:35:23.787  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:35:23.797  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:35:23.797  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:35:23.807  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:23.807  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:23.807  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:25.367   292   292 E SMD     : DCD OFF,
,09-13 12:35:28.367   292   292 E SMD     : DCD OFF,
,09-13 12:35:29.307   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:35:31.367   292   292 E SMD     : DCD OFF
,09-13 12:35:31.997   979  1324 E Watchdog: !@Sync 23,
,09-13 12:35:33.827   979  1010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:35:33.827   979  1010 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:35:33.827   979  1010 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:35:33.827   979  1010 D BatteryService: stay LED for fully charged
09-13 12:35:33.827   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:35:33.827   979   979 I MotionRecognitionService: Plugged
09-13 12:35:33.827   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:35:33.837  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:35:33.837  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:35:33.837  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:35:33.837  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:35:33.847  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:35:33.847  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:35:33.857  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:33.857  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:35:33.857  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:34.367   292   292 E SMD     : DCD OFF
,09-13 12:35:37.377   292   292 E SMD     : DCD OFF,
,09-13 12:35:39.337   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:35:40.377   292   292 E SMD     : DCD OFF
,09-13 12:35:43.377   292   292 E SMD     : DCD OFF
,09-13 12:35:43.887   979  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:35:43.887   979  1481 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:35:43.887   979  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:35:43.887   979  1481 D BatteryService: stay LED for fully charged
,09-13 12:35:43.887   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:35:43.897   979   979 I MotionRecognitionService: Plugged
,09-13 12:35:43.897   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:35:43.897  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:35:43.897  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:35:43.897  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:35:43.897  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:35:43.907  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:35:43.907  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:35:43.927  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:43.927  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:35:43.927  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:35:46.377   292   292 E SMD     : DCD OFF,
,09-13 12:35:49.377   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:35:49.377   292   292 E SMD     : DCD OFF
,09-13 12:35:52.377   292   292 E SMD     : DCD OFF,
,09-13 12:35:53.947   979  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:35:55.387   292   292 E SMD     : DCD OFF,
,09-13 12:35:58.387   292   292 E SMD     : DCD OFF,
,09-13 12:35:59.417   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:36:01.387   292   292 E SMD     : DCD OFF,
,09-13 12:36:01.997   979  1324 E Watchdog: !@Sync 24,
,09-13 12:36:04.007   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:36:04.387   292   292 E SMD     : DCD OFF,
,09-13 12:36:07.077   979  1050 I PowerManagerService: [PWL] Off : 681s ago,
,09-13 12:36:07.387   292   292 E SMD     : DCD OFF,
,09-13 12:36:09.457   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:36:10.387   292   292 E SMD     : DCD OFF,
,09-13 12:36:13.397   292   292 E SMD     : DCD OFF,
,09-13 12:36:14.067   979  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:36:16.397   292   292 E SMD     : DCD OFF,
,09-13 12:36:19.397   292   292 E SMD     : DCD OFF,
,09-13 12:36:19.497   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:36:22.397   292   292 E SMD     : DCD OFF,
,09-13 12:36:24.127   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:36:25.397   292   292 E SMD     : DCD OFF,
,09-13 12:36:28.397   292   292 E SMD     : DCD OFF,
,09-13 12:36:29.537   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:36:31.407   292   292 E SMD     : DCD OFF,
,09-13 12:36:31.997   979  1324 E Watchdog: !@Sync 25,
,09-13 12:36:34.187   979  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:36:34.407   292   292 E SMD     : DCD OFF,
,09-13 12:36:37.407   292   292 E SMD     : DCD OFF,
,09-13 12:36:39.577   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:36:40.407   292   292 E SMD     : DCD OFF,
,09-13 12:36:43.407   292   292 E SMD     : DCD OFF,
,09-13 12:36:44.247   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:36:46.407   292   292 E SMD     : DCD OFF,
,09-13 12:36:49.417   292   292 E SMD     : DCD OFF,
,09-13 12:36:49.617   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:36:52.417   292   292 E SMD     : DCD OFF,
,09-13 12:36:54.307   979  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:36:55.417   292   292 E SMD     : DCD OFF
,09-13 12:36:58.417   292   292 E SMD     : DCD OFF,
,09-13 12:36:59.647   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:37:01.417   292   292 E SMD     : DCD OFF,
,09-13 12:37:01.997   979  1324 E Watchdog: !@Sync 26,
,09-13 12:37:04.367   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:37:04.427   292   292 E SMD     : DCD OFF,
,09-13 12:37:07.427   292   292 E SMD     : DCD OFF,
,09-13 12:37:09.687   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:37:10.427   292   292 E SMD     : DCD OFF,
,09-13 12:37:12.767   979  1096 V AlarmManager: waitForAlarm result :4,
,09-13 12:37:12.777  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
09-13 12:37:12.777  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:37:12.797  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
09-13 12:37:12.797  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 12:37:12.797   979  1010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 12:37:12.797   979  1010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,09-13 12:37:12.797   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:37:12.807   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:37:12.807   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 12:37:12.807  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-13 12:37:12.807  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-13 12:37:12.807  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,09-13 12:37:12.827   979  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:37:12.837   979  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:37:12.837   979  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:37:12.837   979  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:37:12.847  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:37:12.847  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:37:12.847  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:37:12.867  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:37:12.887  4690  8033 I EventLogChimeraService: Aggregate from 1473760696044 (log), 1473760696044 (data)
,09-13 12:37:12.967   979  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:37:12.977   979  1501 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:37:12.977   979  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:37:12.977   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:37:12.997   979  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:37:12.997   979  1501 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:37:12.997   979  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 12:37:12.997   979  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:37:12.997   979  1010 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:37:13.007   979  1010 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:37:13.007   979  1010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:37:13.007   979  1010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:37:13.017   979  1348 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 12:37:13.017   979  1348 W ActivityManager: userId = 0, bbcId = -10000
,09-13 12:37:13.017   979  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:37:13.017   979  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 12:37:13.117  4690  5104 I art     : Explicit concurrent mark sweep GC freed 26293(1605KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 12MB/17MB, paused 1.296ms total 77.528ms
,09-13 12:37:13.127  4690  8034 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,09-13 12:37:13.147  4690  8034 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,09-13 12:37:13.427   292   292 E SMD     : DCD OFF
,09-13 12:37:14.427   979  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:37:16.427   292   292 E SMD     : DCD OFF,
,09-13 12:37:19.427   292   292 E SMD     : DCD OFF
,09-13 12:37:19.727   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:37:22.427   292   292 E SMD     : DCD OFF,
,09-13 12:37:24.487   979  1010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:37:25.437   292   292 E SMD     : DCD OFF,
,09-13 12:37:28.437   292   292 E SMD     : DCD OFF,
,09-13 12:37:29.767   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:37:31.437   292   292 E SMD     : DCD OFF,
,09-13 12:37:31.997   979  1324 E Watchdog: !@Sync 27,
,09-13 12:37:32.097   979  1050 I PowerManagerService: [PWL] Off : 766s ago,
,09-13 12:37:34.437   292   292 E SMD     : DCD OFF,
,09-13 12:37:34.547   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:37:37.437   292   292 E SMD     : DCD OFF,
,09-13 12:37:39.807   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:37:40.437   292   292 E SMD     : DCD OFF,
,09-13 12:37:43.447   292   292 E SMD     : DCD OFF,
,09-13 12:37:44.607   979  1010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:37:46.447   292   292 E SMD     : DCD OFF,
,09-13 12:37:49.447   292   292 E SMD     : DCD OFF,
,09-13 12:37:49.847   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:37:52.447   292   292 E SMD     : DCD OFF,
,09-13 12:37:54.667   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:37:55.447   292   292 E SMD     : DCD OFF,
,09-13 12:37:58.447   292   292 E SMD     : DCD OFF,
,09-13 12:37:59.887   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:37:59.997   979  1096 V AlarmManager: waitForAlarm result :8,
,09-13 12:38:01.457   292   292 E SMD     : DCD OFF,
,09-13 12:38:02.007   979  1324 E Watchdog: !@Sync 28,
,09-13 12:38:04.457   292   292 E SMD     : DCD OFF,
,09-13 12:38:04.727   979  1010 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:38:07.457   292   292 E SMD     : DCD OFF,
,09-13 12:38:09.927   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:38:10.457   292   292 E SMD     : DCD OFF,
,09-13 12:38:13.457   292   292 E SMD     : DCD OFF,
,09-13 12:38:14.787   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-13 12:38:14.787   979  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:38:14.787   979  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 12:38:14.787   979  1479 D BatteryService: stay LED for fully charged
09-13 12:38:14.787   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:38:14.797   979   979 I MotionRecognitionService: Plugged
,09-13 12:38:14.797   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:38:14.797  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 12:38:14.797  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:38:14.797  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-13 12:38:14.797  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 12:38:14.807  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:38:14.807  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:38:14.817  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:14.817  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:38:14.817  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:16.457   292   292 E SMD     : DCD OFF,
,09-13 12:38:19.467   292   292 E SMD     : DCD OFF,
,09-13 12:38:19.967   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:38:22.467   292   292 E SMD     : DCD OFF,
,09-13 12:38:24.847   979  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:38:24.847   979  1479 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:38:24.847   979  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-13 12:38:24.847   979  1479 D BatteryService: stay LED for fully charged
,09-13 12:38:24.847   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
09-13 12:38:24.847   979   979 I MotionRecognitionService: Plugged
09-13 12:38:24.857  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-13 12:38:24.847   979   979 I MotionRecognitionService: mGripSensorEnabled= false
09-13 12:38:24.857  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:38:24.857  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:38:24.857  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:38:24.867  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:38:24.867  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:38:24.877  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:24.877  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:24.877  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:25.467   292   292 E SMD     : DCD OFF
,09-13 12:38:28.467   292   292 E SMD     : DCD OFF,
,09-13 12:38:30.007   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:38:31.467   292   292 E SMD     : DCD OFF,
,09-13 12:38:32.007   979  1324 E Watchdog: !@Sync 29,
,09-13 12:38:34.467   292   292 E SMD     : DCD OFF,
,09-13 12:38:34.907   979  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:38:34.907   979  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 12:38:34.907   979  1466 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:38:34.907   979  1466 D BatteryService: stay LED for fully charged
09-13 12:38:34.907   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:38:34.917   979   979 I MotionRecognitionService: Plugged
09-13 12:38:34.917   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:38:34.917  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:38:34.917  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:38:34.917  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 12:38:34.917  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:38:34.927  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:38:34.927  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:38:34.937  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:34.937  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:34.937  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:38:37.467   292   292 E SMD     : DCD OFF,
,09-13 12:38:40.047   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:38:40.477   292   292 E SMD     : DCD OFF,
,09-13 12:38:43.477   292   292 E SMD     : DCD OFF,
,09-13 12:38:44.967   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:38:46.477   292   292 E SMD     : DCD OFF
,09-13 12:38:49.477   292   292 E SMD     : DCD OFF
,09-13 12:38:50.097   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:38:52.477   292   292 E SMD     : DCD OFF,
,09-13 12:38:55.027   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:38:55.487   292   292 E SMD     : DCD OFF,
,09-13 12:38:58.487   292   292 E SMD     : DCD OFF,
,09-13 12:38:58.957   979  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
09-13 12:38:58.957   979  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
09-13 12:38:58.957   979  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:39:00.137   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:39:00.917   979  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:39:00.917   979  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:39:00.927   979  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:39:00.927   979  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:39:01.487   292   292 E SMD     : DCD OFF
,09-13 12:39:02.007   979  1324 E Watchdog: !@Sync 30,
,09-13 12:39:02.097   979  1050 I PowerManagerService: [PWL] Off : 856s ago
,09-13 12:39:04.487   292   292 E SMD     : DCD OFF,
,09-13 12:39:05.087   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:39:07.487   292   292 E SMD     : DCD OFF,
,09-13 12:39:10.177   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:39:10.487   292   292 E SMD     : DCD OFF,
,09-13 12:39:13.487   292   292 E SMD     : DCD OFF,
,09-13 12:39:15.157   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:16.497   292   292 E SMD     : DCD OFF,
,09-13 12:39:19.497   292   292 E SMD     : DCD OFF,
,09-13 12:39:20.217   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:39:22.497   292   292 E SMD     : DCD OFF,
,09-13 12:39:25.217   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:25.497   292   292 E SMD     : DCD OFF
,09-13 12:39:28.497   292   292 E SMD     : DCD OFF,
,09-13 12:39:30.267   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:39:31.497   292   292 E SMD     : DCD OFF,
,09-13 12:39:32.007   979  1324 E Watchdog: !@Sync 31,
,09-13 12:39:34.507   292   292 E SMD     : DCD OFF,
,09-13 12:39:35.277   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:37.507   292   292 E SMD     : DCD OFF,
,09-13 12:39:40.307   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:39:40.507   292   292 E SMD     : DCD OFF,
,09-13 12:39:43.507   292   292 E SMD     : DCD OFF,
,09-13 12:39:45.347   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:46.507   292   292 E SMD     : DCD OFF,
,09-13 12:39:49.507   292   292 E SMD     : DCD OFF,
,09-13 12:39:50.347   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:39:52.507   292   292 E SMD     : DCD OFF,
,09-13 12:39:55.417   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:39:55.517   292   292 E SMD     : DCD OFF
,09-13 12:39:58.517   292   292 E SMD     : DCD OFF,
,09-13 12:40:00.397   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:40:01.517   292   292 E SMD     : DCD OFF,
,09-13 12:40:02.007   979  1324 E Watchdog: !@Sync 32,
,09-13 12:40:04.517   292   292 E SMD     : DCD OFF,
,09-13 12:40:05.477   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:40:07.517   292   292 E SMD     : DCD OFF
,09-13 12:40:10.447   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:40:10.527   292   292 E SMD     : DCD OFF,
,09-13 12:40:13.527   292   292 E SMD     : DCD OFF,
,09-13 12:40:14.877  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(787): Preparing logs for uploading,
09-13 12:40:14.877  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:40:15.057  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(787): Preparing logs for uploading,
09-13 12:40:15.057  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:40:15.537   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:40:16.527   292   292 E SMD     : DCD OFF
,09-13 12:40:19.527   292   292 E SMD     : DCD OFF,
,09-13 12:40:20.487   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:40:22.527   292   292 E SMD     : DCD OFF
,09-13 12:40:25.527   292   292 E SMD     : DCD OFF,
,09-13 12:40:25.597   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:40:28.527   292   292 E SMD     : DCD OFF
,09-13 12:40:30.527   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:40:31.537   292   292 E SMD     : DCD OFF,
,09-13 12:40:32.007   979  1324 E Watchdog: !@Sync 33,
,09-13 12:40:34.537   292   292 E SMD     : DCD OFF,
,09-13 12:40:35.657   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:40:37.187   979  1050 I PowerManagerService: [PWL] Off : 951s ago
,09-13 12:40:37.537   292   292 E SMD     : DCD OFF,
,09-13 12:40:40.537   292   292 E SMD     : DCD OFF,
,09-13 12:40:40.577   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:40:43.537   292   292 E SMD     : DCD OFF,
,09-13 12:40:45.717   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:40:46.537   292   292 E SMD     : DCD OFF,
,09-13 12:40:49.547   292   292 E SMD     : DCD OFF,
,09-13 12:40:50.627   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:40:52.547   292   292 E SMD     : DCD OFF,
,09-13 12:40:55.547   292   292 E SMD     : DCD OFF,
,09-13 12:40:55.777   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:40:58.547   292   292 E SMD     : DCD OFF,
,09-13 12:41:00.677   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:41:01.547   292   292 E SMD     : DCD OFF,
,09-13 12:41:02.007   979  1324 E Watchdog: !@Sync 34,
,09-13 12:41:04.547   292   292 E SMD     : DCD OFF,
,09-13 12:41:05.847   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:41:07.557   292   292 E SMD     : DCD OFF
,09-13 12:41:10.557   292   292 E SMD     : DCD OFF,
,09-13 12:41:10.717   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:41:13.557   292   292 E SMD     : DCD OFF,
,09-13 12:41:15.907   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:41:16.557   292   292 E SMD     : DCD OFF
,09-13 12:41:19.557   292   292 E SMD     : DCD OFF
,09-13 12:41:20.757   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:41:22.557   292   292 E SMD     : DCD OFF,
,09-13 12:41:25.567   292   292 E SMD     : DCD OFF,
,09-13 12:41:25.967   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:41:28.567   292   292 E SMD     : DCD OFF,
,09-13 12:41:30.807   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:41:31.567   292   292 E SMD     : DCD OFF,
,09-13 12:41:32.007   979  1324 E Watchdog: !@Sync 35,
,09-13 12:41:34.567   292   292 E SMD     : DCD OFF,
,09-13 12:41:36.027   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:41:37.567   292   292 E SMD     : DCD OFF,
,09-13 12:41:40.567   292   292 E SMD     : DCD OFF,
,09-13 12:41:40.847   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:41:43.577   292   292 E SMD     : DCD OFF,
,09-13 12:41:46.087   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:41:46.577   292   292 E SMD     : DCD OFF,
,09-13 12:41:49.577   292   292 E SMD     : DCD OFF,
,09-13 12:41:50.887   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:41:52.577   292   292 E SMD     : DCD OFF,
,09-13 12:41:55.577   292   292 E SMD     : DCD OFF,
,09-13 12:41:56.147   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:41:58.577   292   292 E SMD     : DCD OFF,
,09-13 12:42:00.937   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:42:01.577   292   292 E SMD     : DCD OFF,
,09-13 12:42:02.007   979  1324 E Watchdog: !@Sync 36,
,09-13 12:42:04.587   292   292 E SMD     : DCD OFF,
,09-13 12:42:06.217   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:42:07.587   292   292 E SMD     : DCD OFF,
,09-13 12:42:10.587   292   292 E SMD     : DCD OFF,
,09-13 12:42:10.977   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:42:13.587   292   292 E SMD     : DCD OFF,
,09-13 12:42:16.277   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:42:16.587   292   292 E SMD     : DCD OFF,
,09-13 12:42:17.287   979  1050 I PowerManagerService: [PWL] Off : 1051s ago,
,09-13 12:42:19.587   292   292 E SMD     : DCD OFF
,09-13 12:42:21.017   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:42:22.597   292   292 E SMD     : DCD OFF,
,09-13 12:42:25.597   292   292 E SMD     : DCD OFF,
,09-13 12:42:26.337   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:42:28.597   292   292 E SMD     : DCD OFF,
,09-13 12:42:31.067   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:42:31.597   292   292 E SMD     : DCD OFF,
,09-13 12:42:32.007   979  1324 E Watchdog: !@Sync 37,
,09-13 12:42:34.597   292   292 E SMD     : DCD OFF,
,09-13 12:42:36.397   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:42:37.597   292   292 E SMD     : DCD OFF,
,09-13 12:42:40.607   292   292 E SMD     : DCD OFF,
,09-13 12:42:41.107   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:42:43.607   292   292 E SMD     : DCD OFF,
,09-13 12:42:46.447   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:42:46.607   292   292 E SMD     : DCD OFF
,09-13 12:42:49.607   292   292 E SMD     : DCD OFF
,09-13 12:42:51.147   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:42:52.607   292   292 E SMD     : DCD OFF,
,09-13 12:42:55.607   292   292 E SMD     : DCD OFF
,09-13 12:42:56.517   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:42:58.617   292   292 E SMD     : DCD OFF
,09-13 12:43:01.197   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:43:01.617   292   292 E SMD     : DCD OFF
,09-13 12:43:02.007   979  1324 E Watchdog: !@Sync 38
,09-13 12:43:04.617   292   292 E SMD     : DCD OFF
,09-13 12:43:06.577   979  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 12:43:06.577   979  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 12:43:06.577   979  1466 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 12:43:06.577   979  1466 D BatteryService: stay LED for fully charged
09-13 12:43:06.577   979   979 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 12:43:06.577   979   979 I MotionRecognitionService: Plugged
09-13 12:43:06.577   979   979 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 12:43:06.577  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 12:43:06.587  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 12:43:06.587  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-13 12:43:06.587  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 12:43:06.597  3146  3146 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 12:43:06.597  3146  3250 D HeadsetStateMachine: Disconnected process message: 10
,09-13 12:43:06.607  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:43:06.607  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-13 12:43:06.607  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-13 12:43:07.617   292   292 E SMD     : DCD OFF
,09-13 12:43:10.617   292   292 E SMD     : DCD OFF
,09-13 12:43:11.227   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:43:13.617   292   292 E SMD     : DCD OFF
,09-13 12:43:16.627   292   292 E SMD     : DCD OFF,
,09-13 12:43:16.637   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:43:19.627   292   292 E SMD     : DCD OFF,
,09-13 12:43:21.277   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:43:22.627   292   292 E SMD     : DCD OFF
,09-13 12:43:25.627   292   292 E SMD     : DCD OFF,
,09-13 12:43:26.697   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:43:28.627   292   292 E SMD     : DCD OFF,
,09-13 12:43:31.317   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:43:31.627   292   292 E SMD     : DCD OFF,
,09-13 12:43:32.007   979  1324 E Watchdog: !@Sync 39,
,09-13 12:43:34.627   292   292 E SMD     : DCD OFF,
,09-13 12:43:36.767   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:43:37.637   292   292 E SMD     : DCD OFF,
,09-13 12:43:40.637   292   292 E SMD     : DCD OFF,
,09-13 12:43:41.367   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:43:43.637   292   292 E SMD     : DCD OFF,
,09-13 12:43:46.637   292   292 E SMD     : DCD OFF,
,09-13 12:43:46.827   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:43:49.637   292   292 E SMD     : DCD OFF,
,09-13 12:43:51.407   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:43:52.637   292   292 E SMD     : DCD OFF,
,09-13 12:43:55.647   292   292 E SMD     : DCD OFF,
,09-13 12:43:56.887   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:43:58.647   292   292 E SMD     : DCD OFF,
,09-13 12:43:58.957   979  1087 D TimaService: TIMA: TimaService scheduler is intialized. ,
09-13 12:43:58.957   979  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
09-13 12:43:58.957   979  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,09-13 12:43:59.577   979  1042 I UsageStatsService: User[0] Flushing usage stats to disk,
,09-13 12:43:59.617   979  1103 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,09-13 12:43:59.617   979  1103 I ApplicationUsage: Updating Usage Statistics in DB @ 1473763439622
,09-13 12:43:59.627   979  1103 I ApplicationPolicy: updateDataUsageMap
,09-13 12:43:59.797   979  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,09-13 12:43:59.797   979  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,09-13 12:43:59.797   979  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:43:59.797   979  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,09-13 12:44:00.127   979  1103 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,09-13 12:44:00.127   979  1103 I NetworkDataUsageDb: ::isTableExists: Table exists 
,09-13 12:44:00.147   979  1103 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1473763440157
,09-13 12:44:01.447   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:44:01.647   292   292 E SMD     : DCD OFF,
,09-13 12:44:02.007   979  1324 E Watchdog: !@Sync 40,
,09-13 12:44:02.297   979  1050 I PowerManagerService: [PWL] Off : 1156s ago,
,09-13 12:44:04.647   292   292 E SMD     : DCD OFF
,09-13 12:44:06.947   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:44:07.647   292   292 E SMD     : DCD OFF,
,09-13 12:44:10.647   292   292 E SMD     : DCD OFF,
,09-13 12:44:11.497   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:44:13.657   292   292 E SMD     : DCD OFF,
,09-13 12:44:16.657   292   292 E SMD     : DCD OFF,
,09-13 12:44:17.007   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:44:19.657   292   292 E SMD     : DCD OFF,
,09-13 12:44:21.507   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:44:22.657   292   292 E SMD     : DCD OFF,
,09-13 12:44:25.657   292   292 E SMD     : DCD OFF,
,09-13 12:44:27.067   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:44:28.667   292   292 E SMD     : DCD OFF
,09-13 12:44:31.547   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:44:31.667   292   292 E SMD     : DCD OFF,
,09-13 12:44:32.007   979  1324 E Watchdog: !@Sync 41,
,09-13 12:44:34.667   292   292 E SMD     : DCD OFF
,09-13 12:44:37.127   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:44:37.667   292   292 E SMD     : DCD OFF,
,09-13 12:44:40.667   292   292 E SMD     : DCD OFF,
,09-13 12:44:41.597   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:44:43.677   292   292 E SMD     : DCD OFF
,09-13 12:44:46.677   292   292 E SMD     : DCD OFF,
,09-13 12:44:47.187   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:44:49.677   292   292 E SMD     : DCD OFF
,09-13 12:44:51.607   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:44:52.677   292   292 E SMD     : DCD OFF,
,09-13 12:44:55.677   292   292 E SMD     : DCD OFF
,09-13 12:44:57.247   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:44:58.687   292   292 E SMD     : DCD OFF,
,09-13 12:45:01.647   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:45:01.687   292   292 E SMD     : DCD OFF,
,09-13 12:45:02.017   979  1324 E Watchdog: !@Sync 42,
,09-13 12:45:04.687   292   292 E SMD     : DCD OFF,
,09-13 12:45:07.307   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:45:07.687   292   292 E SMD     : DCD OFF,
,09-13 12:45:10.687   292   292 E SMD     : DCD OFF
,09-13 12:45:11.697   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:45:13.687   292   292 E SMD     : DCD OFF,
,09-13 12:45:14.977  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:45:14.977  6665  7515 I PlayCommon: [1236] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:45:15.157  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-13 12:45:15.157  6665  6737 I PlayCommon: [1218] com.google.android.play.a.l.e(789): No file ready to send
,09-13 12:45:16.687   292   292 E SMD     : DCD OFF,
,09-13 12:45:17.367   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:45:19.697   292   292 E SMD     : DCD OFF,
,09-13 12:45:21.707   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:45:22.697   292   292 E SMD     : DCD OFF,
,09-13 12:45:25.697   292   292 E SMD     : DCD OFF,
,09-13 12:45:27.437   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:45:28.697   292   292 E SMD     : DCD OFF
,09-13 12:45:31.707   292   292 E SMD     : DCD OFF,
,09-13 12:45:31.757   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:45:32.017   979  1324 E Watchdog: !@Sync 43,
,09-13 12:45:34.707   292   292 E SMD     : DCD OFF,
,09-13 12:45:37.487   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:45:37.707   292   292 E SMD     : DCD OFF
,09-13 12:45:40.707   292   292 E SMD     : DCD OFF,
,09-13 12:45:41.797   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:45:43.707   292   292 E SMD     : DCD OFF,
,09-13 12:45:46.707   292   292 E SMD     : DCD OFF,
,09-13 12:45:47.547   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:45:49.717   292   292 E SMD     : DCD OFF
,09-13 12:45:51.817   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:45:52.397   979  1050 I PowerManagerService: [PWL] Off : 1266s ago,
,09-13 12:45:52.717   292   292 E SMD     : DCD OFF,
,09-13 12:45:55.717   292   292 E SMD     : DCD OFF,
,09-13 12:45:57.607   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:45:58.717   292   292 E SMD     : DCD OFF,
,09-13 12:46:01.717   292   292 E SMD     : DCD OFF,
,09-13 12:46:01.857   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:46:02.017   979  1324 E Watchdog: !@Sync 44,
,09-13 12:46:04.717   292   292 E SMD     : DCD OFF,
,09-13 12:46:07.677   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:46:07.717   292   292 E SMD     : DCD OFF
,09-13 12:46:10.727   292   292 E SMD     : DCD OFF,
,09-13 12:46:11.907   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:46:13.727   292   292 E SMD     : DCD OFF,
,09-13 12:46:16.727   292   292 E SMD     : DCD OFF,
,09-13 12:46:17.737   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:46:19.727   292   292 E SMD     : DCD OFF,
,09-13 12:46:21.917   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:46:22.727   292   292 E SMD     : DCD OFF,
,09-13 12:46:25.727   292   292 E SMD     : DCD OFF,
,09-13 12:46:27.787   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:46:28.737   292   292 E SMD     : DCD OFF
,09-13 12:46:31.737   292   292 E SMD     : DCD OFF,
,09-13 12:46:31.967   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:46:32.017   979  1324 E Watchdog: !@Sync 45,
,09-13 12:46:34.737   292   292 E SMD     : DCD OFF,
,09-13 12:46:37.737   292   292 E SMD     : DCD OFF,
,09-13 12:46:37.857   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:46:40.737   292   292 E SMD     : DCD OFF,
,09-13 12:46:42.007   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:46:43.737   292   292 E SMD     : DCD OFF,
,09-13 12:46:46.737   292   292 E SMD     : DCD OFF,
,09-13 12:46:47.917   979  1348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:46:49.747   292   292 E SMD     : DCD OFF,
,09-13 12:46:52.027   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:46:52.747   292   292 E SMD     : DCD OFF,
,09-13 12:46:55.747   292   292 E SMD     : DCD OFF,
,09-13 12:46:57.977   979  1007 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:46:58.747   292   292 E SMD     : DCD OFF,
,09-13 12:47:00.147   979  1096 V AlarmManager: waitForAlarm result :4,
,09-13 12:47:00.147  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-13 12:47:00.147  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 12:47:00.167  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 12:47:00.167  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 12:47:00.167  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:47:00.177  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-13 12:47:00.177  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,09-13 12:47:00.207  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:47:00.207  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:47:00.217  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:47:00.227  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 12:47:01.747   292   292 E SMD     : DCD OFF,
,09-13 12:47:02.017   979  1324 E Watchdog: !@Sync 46,
,09-13 12:47:02.067   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:47:04.747   292   292 E SMD     : DCD OFF
,09-13 12:47:07.757   292   292 E SMD     : DCD OFF
,09-13 12:47:08.037   979  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:47:10.757   292   292 E SMD     : DCD OFF,
,09-13 12:47:12.087   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:47:13.757   292   292 E SMD     : DCD OFF,
,09-13 12:47:16.757   292   292 E SMD     : DCD OFF,
,09-13 12:47:18.097   979  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:47:19.757   292   292 E SMD     : DCD OFF
,09-13 12:47:22.107   979  3316 D SSRM:n  : SIOP:: AP = 260
,09-13 12:47:22.757   292   292 E SMD     : DCD OFF,
,09-13 12:47:25.767   292   292 E SMD     : DCD OFF,
,09-13 12:47:28.157   979  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,09-13 12:47:28.767   292   292 E SMD     : DCD OFF
,09-13 12:47:31.767   292   292 E SMD     : DCD OFF
,09-13 12:47:32.017   979  1324 E Watchdog: !@Sync 47,
,09-13 12:47:32.147   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:47:34.767   292   292 E SMD     : DCD OFF,
,09-13 12:47:37.767   292   292 E SMD     : DCD OFF,
,09-13 12:47:38.217   979  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:47:40.767   292   292 E SMD     : DCD OFF,
,09-13 12:47:42.197   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:47:43.777   292   292 E SMD     : DCD OFF,
,09-13 12:47:46.777   292   292 E SMD     : DCD OFF,
,09-13 12:47:47.437   979  1050 I PowerManagerService: [PWL] Off : 1381s ago,
,09-13 12:47:48.277   979  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:47:49.777   292   292 E SMD     : DCD OFF
,09-13 12:47:52.207   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:47:52.777   292   292 E SMD     : DCD OFF,
,09-13 12:47:55.777   292   292 E SMD     : DCD OFF,
,09-13 12:47:58.337   979  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:47:58.777   292   292 E SMD     : DCD OFF
,09-13 12:47:59.997   979  1096 V AlarmManager: waitForAlarm result :8,
,09-13 12:48:01.787   292   292 E SMD     : DCD OFF,
,09-13 12:48:02.017   979  1324 E Watchdog: !@Sync 48,
,09-13 12:48:02.257   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:48:04.787   292   292 E SMD     : DCD OFF,
,09-13 12:48:07.787   292   292 E SMD     : DCD OFF,
,09-13 12:48:08.397   979  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:48:10.787   292   292 E SMD     : DCD OFF,
,09-13 12:48:12.307   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:48:13.787   292   292 E SMD     : DCD OFF,
,09-13 12:48:16.787   292   292 E SMD     : DCD OFF,
,09-13 12:48:18.457   979  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:48:19.797   292   292 E SMD     : DCD OFF,
,09-13 12:48:22.327   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:48:22.797   292   292 E SMD     : DCD OFF,
,09-13 12:48:25.797   292   292 E SMD     : DCD OFF,
,09-13 12:48:28.517   979  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 12:48:28.797   292   292 E SMD     : DCD OFF,
,09-13 12:48:31.797   292   292 E SMD     : DCD OFF,
,09-13 12:48:32.017   979  1324 E Watchdog: !@Sync 49,
,09-13 12:48:32.367   979  3316 D SSRM:n  : SIOP:: AP = 260,
,09-13 12:48:34.797   292   292 E SMD     : DCD OFF,
,09-13 12:48:37.807   292   292 E SMD     : DCD OFF,
,09-13 12:48:38.577   979  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,TIME-OUT KILL (timeout was 1400000ms),09-13 12:48:39.287  8312  8312 D AndroidRuntime: 
09-13 12:48:39.287  8312  8312 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 12:48:39.287  8312  8312 D AndroidRuntime: CheckJNI is OFF
09-13 12:48:39.287  8312  8312 D AndroidRuntime: readGMSProperty: start
09-13 12:48:39.287  8312  8312 D AndroidRuntime: readGMSProperty: already setted!!
09-13 12:48:39.287  8312  8312 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 12:48:39.287  8312  8312 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 12:48:39.287  8312  8312 D AndroidRuntime: readGMSProperty: end
09-13 12:48:39.287  8312  8312 D AndroidRuntime: addProductProperty: start
09-13 12:48:39.427  8312  8312 E AffinityControl: AffinityControl: registerfunction enter
09-13 12:48:39.457  8312  8312 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-13 12:48:39.467   979  1481 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-13 12:48:39.467   979  1481 D PackageManager: START PACKAGE DELETE: observer{953465850}
09-13 12:48:39.467   979  1481 D PackageManager: pkg{<packageName>}
09-13 12:48:39.467   979  1481 D PackageManager: user{0}
09-13 12:48:39.467   979  1481 D PackageManager: caller{2000}
09-13 12:48:39.467   979  1481 D PackageManager: flags{2}
09-13 12:48:39.467   979  1481 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 12:48:39.467   979  1481 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-13 12:48:39.467   979  1481 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 12:48:39.467   979  1481 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 12:48:39.477   979  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-13 12:48:39.477   979  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-13 12:48:39.477   979  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 12:48:39.477   979  1058 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
09-13 12:48:39.477   979  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 12:48:39.477   979  1043 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
09-13 12:48:39.477   979  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-13 12:48:39.577   979  1058 W PackageSettings: Skipping PackageSetting{2b99eb32 com.example.hello/10168} due to missing metadata
09-13 12:48:39.617   979  1058 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
09-13 12:48:39.627   979  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
09-13 12:48:39.667  2618  2618 I art     : Explicit concurrent mark sweep GC freed 2497(121KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 865us total 33.863ms
09-13 12:48:39.687  1863  1863 E SamsungIME: mOCRHelper is null
09-13 12:48:39.687   979  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 12:48:39.697  1995  2154 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 12:48:39.707   979  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-13 12:48:39.707   979  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 12:48:39.707   979  1124 V NetworkStats: performPollLocked(flags=0x3)
09-13 12:48:39.707   979  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 12:48:39.707   979  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 12:48:39.727  4690  4690 I art     : Explicit concurrent mark sweep GC freed 283(10KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/17MB, paused 1.200ms total 101.861ms
09-13 12:48:39.737   979  1124 V NetworkStats: performPollLocked() took 29ms
09-13 12:48:39.737   979  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 12:48:39.747  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
09-13 12:48:39.757  1440  1440 D RegisteredServicesCache: empty dynamic service
09-13 12:48:39.787  2879  2879 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 13 12:48:39 GMT+02:00 2016
09-13 12:48:39.787   979  1466 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-13 12:48:39.787   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-13 12:48:39.787   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:48:39.787   979  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:48:39.787   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
09-13 12:48:39.787   979  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
09-13 12:48:39.787   979  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-13 12:48:39.787   979  1042 W TextServicesManagerService: no available spell checker services found
09-13 12:48:39.797  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
09-13 12:48:39.797   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:39.807  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
09-13 12:48:39.807  2879  2879 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
09-13 12:48:39.817   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:39.827   979  1472 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
09-13 12:48:39.827   979  1472 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
09-13 12:48:39.827  7470  7470 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-13 12:48:39.827   979  1483 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-13 12:48:39.827   979  1483 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-13 12:48:39.827   979  1483 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:48:39.827   979  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:48:39.827   979  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
09-13 12:48:39.837  2879  2879 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
09-13 12:48:39.837  7470  7470 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
09-13 12:48:39.837   979  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 12:48:39.847   979  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 12:48:39.847  7470  7470 D elm:15121: ElmAgentService : onCreate()
09-13 12:48:39.847  7470  8324 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-13 12:48:39.847  7470  8324 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-13 12:48:39.847  2879  2879 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-13 12:48:39.847  7470  8324 D elm:15121: MDMBridge.getInstance()
09-13 12:48:39.847  7470  8324 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-13 12:48:39.847  7470  8324 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-13 12:48:39.857   979  1483 I TactileAssist: enable value -1
09-13 12:48:39.857   979  1483 I TactileAssist: internal enable value -1
09-13 12:48:39.857   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
09-13 12:48:39.857   979  1483 I TactileAssist: intensity value -1
09-13 12:48:39.857   979  1483 I TactileAssist: saveAppList value true
09-13 12:48:39.877   979  1483 I TactileAssist: List of disabled apps :
09-13 12:48:39.877   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.877   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.877   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.877   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.877  2879  2879 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-13 12:48:39.887   979   979 I art     : Explicit concurrent mark sweep GC freed 49129(5MB) AllocSpace objects, 218(3MB) LOS objects, 33% free, 24MB/37MB, paused 3.404ms total 250.666ms
09-13 12:48:39.887   979  1058 I art     : WaitForGcToComplete blocked for 244.794ms for cause Explicit
09-13 12:48:39.897  8325  8325 E Zygote  : MountEmulatedStorage()
09-13 12:48:39.897  8325  8325 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:48:39.897  8325  8325 E Zygote  : v2
09-13 12:48:39.897  8325  8325 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:39.897   979  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8325 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 12:48:39.897  8325  8325 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:39.897  8325  8325 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:39.897   979  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
09-13 12:48:39.897   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.897   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.897   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.897   979  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.897  8325  8325 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:48:39.917  8336  8336 E Zygote  : MountEmulatedStorage()
09-13 12:48:39.917  8336  8336 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:48:39.917  8336  8336 E Zygote  : v2
09-13 12:48:39.917  8336  8336 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:39.917  8336  8336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:39.917  8336  8336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:39.917   979  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=8336 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 12:48:39.917  2879  8323 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-13 12:48:39.917  8336  8336 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:48:39.927   979  1501 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-13 12:48:39.927   979  1501 D SecContentProvider2: mCursor = null
09-13 12:48:39.927  7470  7470 D elm:15121: ElmAgentService : onDestroy().
09-13 12:48:39.937   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:39.937  2879  8323 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
09-13 12:48:39.937  2879  8323 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
09-13 12:48:39.947   979  1748 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
09-13 12:48:39.947  2879  8323 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
09-13 12:48:39.947   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.947   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.947   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.947   979  1748 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:39.947  8325  8325 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:48:39.947  8325  8325 D ActivityThread: Added TimaKeyStore provider
09-13 12:48:39.957  8352  8352 E Zygote  : MountEmulatedStorage()
09-13 12:48:39.957  8352  8352 I libpersona: KNOX_SDCARD checking this for 10048
09-13 12:48:39.957  8352  8352 E Zygote  : v2
09-13 12:48:39.957  8352  8352 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:39.957  8352  8352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:39.957   979  1748 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8352 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
09-13 12:48:39.957  8352  8352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:39.957  8352  8352 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 12:48:39.977  8336  8336 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:48:39.977  8336  8336 D ActivityThread: Added TimaKeyStore provider
09-13 12:48:39.977   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.007  8352  8352 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:48:40.007  8352  8352 D ActivityThread: Added TimaKeyStore provider
09-13 12:48:40.007   979   979 D RCPManagerService: PackageReceiver onReceive()
09-13 12:48:40.007   979   979 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-13 12:48:40.007   979   979 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-13 12:48:40.007   979   979 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 12:48:40.007   979   979 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
09-13 12:48:40.017   979   979 I OTPFW   : ProvisionData::getAllEntries Enter
09-13 12:48:40.027   979   979 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-13 12:48:40.037  8336  8336 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
09-13 12:48:40.037   979  1501 D SecContentProvider2: uri = -1 selection = getSealedState
09-13 12:48:40.037   979  1501 D SecContentProvider2: mCursor = null
09-13 12:48:40.037  8336  8336 I PopupuiReceiver_KNOX: getSealedState : true
09-13 12:48:40.037  8325  8325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
09-13 12:48:40.037   979  1322 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-13 12:48:40.037   979  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
09-13 12:48:40.037   979  1137 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
09-13 12:48:40.037   979  1137 D SecContentProvider2: mCursor = null
09-13 12:48:40.037   979  1322 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:48:40.037   979  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:48:40.037   979  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
09-13 12:48:40.047   979  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
09-13 12:48:40.047  8336  8336 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
09-13 12:48:40.047   979  1748 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-13 12:48:40.047   979  1748 D SecContentProvider2: mCursor = null
09-13 12:48:40.047  8336  8336 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-13 12:48:40.047  8336  8336 D PopupuiReceiver: Action package removed
09-13 12:48:40.047   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.047   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.047   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.047   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.067  8371  8371 E Zygote  : MountEmulatedStorage()
09-13 12:48:40.067  8371  8371 E Zygote  : v2
09-13 12:48:40.067  8371  8371 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:48:40.067  8371  8371 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:40.067  8371  8371 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:40.067  8352  8352 D Compatibility: onReceive() it will make start service
09-13 12:48:40.067   979  1501 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=8371 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 12:48:40.067   979  1466 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-13 12:48:40.077   979  1466 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:48:40.067   979  1466 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
09-13 12:48:40.077   979  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 12:48:40.077   979  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
09-13 12:48:40.077  8371  8371 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:40.077  8371  8371 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:48:40.077  2879  8323 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
09-13 12:48:40.077   979  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
09-13 12:48:40.087   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.087   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.087   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.087   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.087  2879  8323 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
09-13 12:48:40.097  2879  8323 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
09-13 12:48:40.097  8381  8381 E Zygote  : MountEmulatedStorage()
09-13 12:48:40.097  8381  8381 E Zygote  : v2
09-13 12:48:40.097  8381  8381 I libpersona: KNOX_SDCARD checking this for 10145
09-13 12:48:40.097  8381  8381 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:40.097  8381  8381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:40.097   979  1501 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=8381 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 12:48:40.107  8371  8371 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:48:40.107   979  1501 I ActivityManager: Killing 7438:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-13 12:48:40.107  8371  8371 D ActivityThread: Added TimaKeyStore provider
09-13 12:48:40.107  8381  8381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:40.107  8381  8381 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:48:40.117  8352  8378 D Compatibility: onHandleIntent()
09-13 12:48:40.117  8352  8378 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
09-13 12:48:40.117  2879  2879 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
09-13 12:48:40.117   979  1501 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
09-13 12:48:40.117   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.117   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.117   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.117   979  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.117  8352  8378 D Compatibility: found: 2
09-13 12:48:40.137  8352  8378 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-13 12:48:40.147  8381  8381 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:48:40.147  8381  8381 D ActivityThread: Added TimaKeyStore provider
09-13 12:48:40.147  8404  8404 I libpersona: KNOX_SDCARD checking this for 10052
09-13 12:48:40.147  8404  8404 E Zygote  : MountEmulatedStorage()
09-13 12:48:40.147  8404  8404 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:40.147  8404  8404 E Zygote  : v2
09-13 12:48:40.147  8404  8404 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:40.147  8352  8378 D Compatibility: skipping ResolveInfo{3a7da944 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-13 12:48:40.147   979  1501 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8404 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
09-13 12:48:40.147  8352  8378 D Compatibility: considering ResolveInfo{1fabfa2d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-13 12:48:40.147  8352  8378 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
09-13 12:48:40.157  8404  8404 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:40.157   979  1010 I ActivityManager: Killing 7144:com.google.android.gms:car/u0a11 (adj 15): empty #21
09-13 12:48:40.157  8404  8404 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 12:48:40.167   979  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
09-13 12:48:40.167  8352  8378 D Compatibility: enabling receiver ResolveInfo{e416b62 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-13 12:48:40.177  8352  8378 D Compatibility: enabling receiver ResolveInfo{305ec4f3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-13 12:48:40.177  8371  8371 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:48:40.177   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.187  8404  8404 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:48:40.187  8404  8404 D ActivityThread: Added TimaKeyStore provider
09-13 12:48:40.197   979  1058 I art     : Explicit concurrent mark sweep GC freed 11390(651KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/37MB, paused 3.182ms total 308.559ms
09-13 12:48:40.197  8352  8378 D Compatibility: enabling receiver ResolveInfo{3f4e15b0 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-13 12:48:40.197   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.207  8352  8378 D Compatibility: enabling receiver ResolveInfo{34fb0c29 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-13 12:48:40.207  8371  8371 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
09-13 12:48:40.207  8381  8381 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-13 12:48:40.207  8381  8381 D ThemeInfoUtil: isCurrentFestival = false
09-13 12:48:40.217   979  1466 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-13 12:48:40.217   979  1466 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
09-13 12:48:40.217  8352  8378 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
09-13 12:48:40.217   979  1137 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-13 12:48:40.217   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.217   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.217   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.217   979  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.227  8419  8419 E Zygote  : MountEmulatedStorage()
09-13 12:48:40.227  8419  8419 E Zygote  : v2
09-13 12:48:40.227  8419  8419 I libpersona: KNOX_SDCARD checking this for 10148
09-13 12:48:40.227  8419  8419 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:40.237  8419  8419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:40.237  8419  8419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:40.237   979  1137 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=8419 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-13 12:48:40.237   979  1137 I ActivityManager: Killing 7516:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
09-13 12:48:40.247  8419  8419 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:48:40.247   979  1466 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
09-13 12:48:40.247   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.247   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.247   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.247   979  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.267  8428  8428 E Zygote  : MountEmulatedStorage()
09-13 12:48:40.267  8428  8428 E Zygote  : v2
09-13 12:48:40.267  8428  8428 I libpersona: KNOX_SDCARD checking this for 10087
09-13 12:48:40.267  8428  8428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:40.267  8428  8428 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:40.267  8428  8428 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:40.267  8428  8428 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 12:48:40.267   979  1466 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8428 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
09-13 12:48:40.277   979  1466 I ActivityManager: Killing 7488:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-13 12:48:40.277   979  1058 D PackageManager: delete codoeFile: 
09-13 12:48:40.277   979  1466 I ActivityManager: Killing 7308:com.android.calendar/u0a131 (adj 15): empty #21
09-13 12:48:40.287   979  1058 I AASA_removePackage: UID=10171 Target=com.test.thalitest
09-13 12:48:40.287   979  1058 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
09-13 12:48:40.297   979  1058 D PackageManager: result of delete: 1{953465850}
09-13 12:48:40.297  8419  8419 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:48:40.297  8419  8419 D ActivityThread: Added TimaKeyStore provider
09-13 12:48:40.307  8312  8312 D AndroidRuntime: Shutting down VM
09-13 12:48:40.317  8428  8428 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 12:48:40.317  8428  8428 D ActivityThread: Added TimaKeyStore provider
09-13 12:48:40.327   979   979 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 12:48:40.327   979   979 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicy: uID is 10171
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-13 12:48:40.327   979   979 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-13 12:48:40.327   979  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 12:48:40.327   979  1058 D PackageManager: userId{-1}
09-13 12:48:40.327   979  1058 D PackageManager: andCode{true}
09-13 12:48:40.337   979   979 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicy: uID is 10171
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-13 12:48:40.337   979  3316 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-13 12:48:40.337   979  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-13 12:48:40.337   979   979 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-13 12:48:40.347   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.347   979  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 12:48:40.347   979  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 12:48:40.347   979  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 12:48:40.347   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.357   979  1163 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
09-13 12:48:40.357   979   979 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
09-13 12:48:40.367   979   979 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.367   979   979 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.367   979   979 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.367   979   979 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 12:48:40.377   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.377  8419  8419 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-13 12:48:40.377  8450  8450 E Zygote  : MountEmulatedStorage()
09-13 12:48:40.377  8450  8450 E Zygote  : v2
09-13 12:48:40.377  8450  8450 I libpersona: KNOX_SDCARD checking this for 1000
09-13 12:48:40.377  8450  8450 I libpersona: KNOX_SDCARD not a persona
09-13 12:48:40.377  8450  8450 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 12:48:40.377   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.387  8450  8450 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 12:48:40.387   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.387   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-13 12:48:40.387  8450  8450 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 12:48:40.387   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.387   979   979 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 12:48:40.397   979   979 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
09-13 12:48:40.397   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.397   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-13 12:48:40.407   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.407   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-13 12:48:40.407   979  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 12:48:40.407   979  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-13 12:48:40.407   979  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-13 12:48:40.407   979  1007 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-13 12:48:40.407   979  1007 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-13 12:48:40.417   979  1007 W ActivityManager: userId = 0, bbcId = -10000
09-13 12:48:40.417   979  1007 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 12:48:40.417   979  1007 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
09-13 12:48:40.417   979  1483 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-13 12:48:40.417   979  1466 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider

```
