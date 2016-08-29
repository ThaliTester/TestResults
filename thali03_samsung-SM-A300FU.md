#### Test 83070177977a8d1_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-29 13:44:20.634  1463  2018 D TP/MmsSmsProvider: query,matched:13, calling pid = 6340
08-29 13:44:20.634  1463  2018 D TP/MmsSmsProvider: match 13:Elapsed time : 0.918 ms
08-29 13:44:20.644  6340  6340 D Mms/Contact: [end]    init consume time = 28.549948
--------- beginning of system
08-29 13:44:20.644  1017  1493 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
08-29 13:44:20.644  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.644  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.644  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.644  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.654  1017  1493 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=6524 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:44:20.654  1017  1493 I ActivityManager: Killing 5925:com.google.android.gm/u0a99 (adj 15): empty #21
08-29 13:44:20.664  6524  6524 E Zygote  : MountEmulatedStorage()
08-29 13:44:20.664  6524  6524 E Zygote  : v2
08-29 13:44:20.664  6524  6524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:20.664  6524  6524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:20.664  6524  6524 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:44:20.664  6340  6523 D Mms/DraftCache: [start]    rebuildCache consume time = 19.360885
08-29 13:44:20.664  6524  6524 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:44:20.664  6524  6524 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:20.674  6340  6340 D Mms/MethodReflector: getSubId is called
08-29 13:44:20.674  6340  6340 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-29 13:44:20.684  1463  1482 D TP/MmsSmsProvider: query,matched:12, calling pid = 6340
08-29 13:44:20.694  6340  6340 D Mms/MethodReflector: getTelephonyProperty is called
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: auto download without roaming -> true
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-29 13:44:20.694  6340  6340 D Mms/MethodReflector: getSubId is called
08-29 13:44:20.694  1463  1482 D TP/MmsSmsProvider: match 12:Elapsed time : 10.846 ms
08-29 13:44:20.694  6340  6340 D Mms/MethodReflector: getDefaultSmsSubId is called
08-29 13:44:20.694  6340  6340 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-29 13:44:20.694  6340  6340 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-29 13:44:20.694  6340  6340 D Mms/MethodReflector: getTelephonyProperty is called
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: auto download without roaming -> true
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: auto download during roaming secondary -> false
08-29 13:44:20.694  6340  6340 D Mms/DownloadManager: mAutoDownload ------> true
08-29 13:44:20.704  6340  6523 D Mms/DraftCache: [end]    rebuildCache consume time = 33.860521
08-29 13:44:20.704  6524  6524 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:20.704  6524  6524 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:20.744  6524  6524 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
08-29 13:44:20.764  6340  6340 D ComposerPerformance: 1472471060774 ms / [DONE] Composer constructor
08-29 13:44:20.764  6340  6340 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-29 13:44:20.764  6340  6340 I Mms/ReservationManager: ReservationManager()
08-29 13:44:20.764  6340  6340 I Mms/ReservationManager: resetAfterConnected()
08-29 13:44:20.764  1463  1482 D TP/MmsSmsProvider: query,matched:7, calling pid = 6340
08-29 13:44:20.764  1463  1482 D TP/MmsSmsProvider: match 7:Elapsed time : 1.522 ms
08-29 13:44:20.774  6340  6340 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-29 13:44:20.794  6340  6541 D Mms/Conversation: [start]    init() consume time = 92.561667
08-29 13:44:20.794  6340  6340 D Mms/MmsApp: [end]    onCreate() consume time = 0.404687
08-29 13:44:20.794  1463  1475 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-29 13:44:20.794  1463  1475 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-29 13:44:20.794  1463  1475 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-29 13:44:20.804  1463  1475 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-29 13:44:20.804  1463  1475 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-29 13:44:20.804  1463  1475 D TP/MmsSmsProvider: need read changed broadcast:false
08-29 13:44:20.804  6340  6541 D Mms/Conversation: [end]    init consume time = 11.526302
08-29 13:44:20.814  6340  6541 D Mms/MessagingNotification: [start]    init() consume time = 3.960157
08-29 13:44:20.814  6340  6541 D Mms/MessagingNotification: [end]    init consume time = 2.405572
08-29 13:44:20.814  1463  1741 D TP/MmsSmsProvider: query,matched:0, calling pid = 6340
08-29 13:44:20.814  1463  1741 V TP/MmsSmsProvider: getSimpleConversations entered.
08-29 13:44:20.814  1463  1741 D TP/MmsSmsProvider: match 0:Elapsed time : 1.817 ms
08-29 13:44:20.834  6340  6545 D Mms/Synchronizer: [start]    doSync consume time = 16.30474
08-29 13:44:20.834  1463  2018 D TP/MmsSmsProvider: update, matched:300, calling pid = 6340
08-29 13:44:20.834  1463  2018 V TP/MmsSmsProvider: syncDBData start
08-29 13:44:20.834  1463  2018 V TP/MmsSmsProvider: syncDBData sms end
08-29 13:44:20.834  1463  2018 V TP/MmsSmsProvider: syncDBData mms end
08-29 13:44:20.834  1463  2018 V TP/MmsSmsProvider: syncDBData end
08-29 13:44:20.834  6340  6545 D Mms/Synchronizer: [end]    doSync consume time = 7.165677
08-29 13:44:20.834  1017  1219 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-29 13:44:20.844  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.844  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.844  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.844  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.844  6340  6544 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 7.396823
08-29 13:44:20.844  6340  6340 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-29 13:44:20.844  6340  6340 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-29 13:44:20.844  6340  6340 D Mms/MethodReflector: getSubId is called
08-29 13:44:20.844  6340  6340 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-29 13:44:20.854  6340  6340 D Mms/MethodReflector: getTelephonyProperty is called
08-29 13:44:20.854  6340  6340 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-29 13:44:20.854  6340  6340 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-29 13:44:20.854  6340  6340 D Mms/DownloadManager: auto download without roaming -> true
08-29 13:44:20.854  6340  6340 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-29 13:44:20.854  6340  6340 D Mms/DownloadManager: mAutoDownload ------> true
08-29 13:44:20.854  6546  6546 E Zygote  : MountEmulatedStorage()
08-29 13:44:20.854  6546  6546 E Zygote  : v2
08-29 13:44:20.854  6546  6546 I libpersona: KNOX_SDCARD checking this for 10068
08-29 13:44:20.854  6546  6546 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:20.854  6546  6546 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:20.864  6546  6546 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:20.864  6546  6546 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 13:44:20.864  1017  1219 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6546 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-29 13:44:20.874  1017  3977 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-29 13:44:20.874  1017  3977 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.874  1017  3977 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.874  1017  3977 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.884  1017  3977 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.884  1463  1482 D TP/MmsSmsProvider: query,matched:400, calling pid = 6340
08-29 13:44:20.884  6340  6340 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-29 13:44:20.894  6560  6560 E Zygote  : MountEmulatedStorage()
08-29 13:44:20.894  6560  6560 E Zygote  : v2
08-29 13:44:20.894  6560  6560 I libpersona: KNOX_SDCARD checking this for 10152
08-29 13:44:20.894  6560  6560 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:20.894  6560  6560 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:20.914  1937  1961 W art     : Suspending all threads took: 35.523ms
08-29 13:44:20.914  6560  6560 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:20.914  6560  6560 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:44:20.914  6340  6492 W art     : Verification of int com.android.mms.util.HandleComposerAttachment.getAvailableSlideCount(int) took 135.028ms
08-29 13:44:20.914  1937  6376 I qtaguid : Untagging socket 97
08-29 13:44:20.924  1937  1937 I ConfigFetchService: fetch service done; releasing wakelock
08-29 13:44:20.924  1017  3977 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6560 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-29 13:44:20.924  1017  3977 I ActivityManager: Killing 6108:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
08-29 13:44:20.934  1937  1937 I ConfigFetchService: stopping self
08-29 13:44:20.934  6546  6546 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:20.934  1017  1447 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-29 13:44:20.934  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-29 13:44:20.934  6546  6546 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:20.934  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:20.934  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:20.934  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-29 13:44:20.944  1017  3970 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-29 13:44:20.944  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.944  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.944  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.944  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:20.954  6340  6576 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-29 13:44:20.954  6340  6576 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-29 13:44:20.954  6560  6560 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:20.954  6560  6560 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:20.974  1017  3970 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6577 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-29 13:44:20.974  6577  6577 E Zygote  : MountEmulatedStorage()
08-29 13:44:20.974  6577  6577 E Zygote  : v2
08-29 13:44:20.974  6577  6577 I libpersona: KNOX_SDCARD checking this for 10042
08-29 13:44:20.974  6340  6544 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 134.434219
08-29 13:44:20.984  6577  6577 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:20.984  6577  6577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:20.984  1017  3970 I ActivityManager: Killing 6133:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #21
08-29 13:44:20.994  6577  6577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:20.994  6577  6577 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-29 13:44:20.994  1017  3970 I ActivityManager: Killing 5958:com.google.android.music:main/u0a108 (adj 15): empty #22
08-29 13:44:20.994  6542  6542 D AndroidRuntime: 
08-29 13:44:20.994  6542  6542 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 13:44:20.994  1017  1493 I art     : Explicit concurrent mark sweep GC freed 142698(7MB) AllocSpace objects, 6(1895KB) LOS objects, 33% free, 23MB/34MB, paused 2.782ms total 222.169ms
08-29 13:44:20.994  6542  6542 D AndroidRuntime: CheckJNI is OFF
08-29 13:44:20.994  6542  6542 D AndroidRuntime: readGMSProperty: start
08-29 13:44:20.994  6542  6542 D AndroidRuntime: readGMSProperty: already setted!!
08-29 13:44:20.994  6542  6542 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 13:44:20.994  6542  6542 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 13:44:20.994  6542  6542 D AndroidRuntime: readGMSProperty: end
08-29 13:44:20.994  6542  6542 D AndroidRuntime: addProductProperty: start
08-29 13:44:21.024  6546  6546 D BadgeProvider: onCreate
08-29 13:44:21.024  6546  6546 D BadgeProvider: DatabaseHelper
08-29 13:44:21.034  6577  6577 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:21.034  6577  6577 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:21.054  6340  6541 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-29 13:44:21.054  1463  1741 D TP/SmsProvider: query,matched:26, calling pid = 6340
08-29 13:44:21.054  1463  1741 D TP/SmsProvider: match 26:Elapsed time : 2.028 ms
08-29 13:44:21.064  6560  6560 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-29 13:44:21.064  6577  6577 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:44:21.064  6560  6560 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
08-29 13:44:21.064  6577  6577 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 13:44:21.064  6577  6577 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-29 13:44:21.084  1463  2018 D TP/MmsSmsProvider: query,matched:6, calling pid = 6340
08-29 13:44:21.084  1463  2018 D TP/MmsSmsProvider: match 6:Elapsed time : 1.151 ms
08-29 13:44:21.104  1017  1504 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-29 13:44:21.114  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.114  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.114  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.114  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.124   288   288 E SMD     : DCD OFF
08-29 13:44:21.144  6598  6598 E Zygote  : MountEmulatedStorage()
08-29 13:44:21.144  6598  6598 E Zygote  : v2
08-29 13:44:21.144  6598  6598 I libpersona: KNOX_SDCARD checking this for 10023
08-29 13:44:21.144  6598  6598 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:21.144  6598  6598 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:21.144  6542  6542 E AffinityControl: AffinityControl: registerfunction enter
08-29 13:44:21.154  6598  6598 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:21.154  1017  1504 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6598 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-29 13:44:21.154  6560  6560 I TapandpayWidget:Utils: Clear T&P info.
08-29 13:44:21.154  6598  6598 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:44:21.174  6542  6542 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 13:44:21.184  6598  6598 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:21.184  6560  6560 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-29 13:44:21.184  6598  6598 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:21.184  1017  1219 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-29 13:44:21.184  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.184  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.184  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.184  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.204  1017  1219 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6616 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-29 13:44:21.204  1017  1219 I ActivityManager: Killing 6005:com.android.calendar/u0a131 (adj 15): empty #21
08-29 13:44:21.204  6616  6616 E Zygote  : MountEmulatedStorage()
08-29 13:44:21.204  6616  6616 E Zygote  : v2
08-29 13:44:21.204  6616  6616 I libpersona: KNOX_SDCARD checking this for 10009
08-29 13:44:21.204  6616  6616 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:21.204  6616  6616 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:21.204  6616  6616 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:21.204  6616  6616 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-29 13:44:21.214  1017  1323 I ActivityManager: Killing 6190:com.android.defcontainer/u0a3 (adj 15): empty #21
08-29 13:44:21.244  1017  1480 E PersonaManagerService: inState():  stateMachine is null !!
08-29 13:44:21.244  1017  1480 I PersonaManagerService: PersonaId don't exist
08-29 13:44:21.244  1017  1480 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-29 13:44:21.254  6577  6577 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-29 13:44:21.264  1017  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 13:44:21.264  6616  6616 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:21.264  6616  6616 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:21.274  6340  6492 D Mms/ArtClassLoader: init [DONE] art
08-29 13:44:21.274  1017  1480 W ActivityManager: mDVFSHelper.acquire()
08-29 13:44:21.284  1017  1480 D FocusedStackFrame: Set to : 0
08-29 13:44:21.294  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.294  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.294  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.294  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.294  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 13:44:21.294  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-29 13:44:21.314  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 13:44:21.314  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 13:44:21.314   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-29 13:44:21.324  1017  1480 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6633 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 13:44:21.324  1017  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-29 13:44:21.324  6633  6633 E Zygote  : MountEmulatedStorage()
08-29 13:44:21.324  6633  6633 I libpersona: KNOX_SDCARD checking this for 10170
08-29 13:44:21.324  6633  6633 E Zygote  : v2
08-29 13:44:21.324  6633  6633 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:21.324  1017  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 13:44:21.324  6633  6633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:21.324  6633  6633 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:21.324  6633  6633 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 13:44:21.334  1017  1480 D InputDispatcher: Focused application set to: xxxx
08-29 13:44:21.334  1017  1480 D InputDispatcher: Focus left window: 1488
08-29 13:44:21.334  6542  6542 D AndroidRuntime: Shutting down VM
08-29 13:44:21.334  1017  3970 I ActivityManager: Killing 5838:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-29 13:44:21.344  1017  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-29 13:44:21.344  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-29 13:44:21.344  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.344  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.344  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.344  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:21.344  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 13:44:21.344  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 13:44:21.344  6598  6598 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-29 13:44:21.364   304   304 I art     : Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 38.491ms
08-29 13:44:21.374  6633  6633 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:21.374  6633  6633 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:21.384   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.673ms
08-29 13:44:21.394  6340  6541 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-29 13:44:21.404   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.468ms
08-29 13:44:21.424  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6648 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-29 13:44:21.424  6648  6648 E Zygote  : MountEmulatedStorage()
08-29 13:44:21.424  6648  6648 E Zygote  : v2
08-29 13:44:21.424  6648  6648 I libpersona: KNOX_SDCARD checking this for 10003
08-29 13:44:21.424  6648  6648 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:21.424  6648  6648 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:21.424  1017  1493 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-29 13:44:21.424  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-29 13:44:21.434  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-29 13:44:21.434  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-29 13:44:21.434  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-29 13:44:21.434  6648  6648 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:21.434  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-29 13:44:21.434  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-29 13:44:21.434  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-29 13:44:21.434  1017  1017 V ActivityManager: Display changed displayId=0
08-29 13:44:21.434  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-29 13:44:21.444  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-29 13:44:21.444  6648  6648 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:44:21.444  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-29 13:44:21.444  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-29 13:44:21.444  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-29 13:44:21.444  6598  6598 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-29 13:44:21.444  1017  1047 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-29 13:44:21.454  1017  1047 W DisplayManagerService: Failed to notify process 5838 that displays changed, assuming it died.
08-29 13:44:21.454  1017  1047 W DisplayManagerService: android.os.TransactionTooLargeException
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 13:44:21.454  1017  1047 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 13:44:21.464  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-29 13:44:21.464  6648  6648 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:21.464  6648  6648 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:21.484  1017  1493 D PersonaManager: isKioskContainerExistOnDevice
08-29 13:44:21.504  1017  1504 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 13:44:21.514  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-29 13:44:21.514   258  1098 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-29 13:44:21.514   258  6119 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-29 13:44:21.524  1488  1488 D Launcher: onTrimMemory. Level: 20
08-29 13:44:21.524  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{3a5f56e2 token=android.os.BinderProxy@109b961a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-29 13:44:21.544  6542  6542 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 13:44:21.554   284   284 E installd: system dir 0 : /system/app/
08-29 13:44:21.554   284   284 E installd: system dir 1 : /system/priv-app/
08-29 13:44:21.554   284   284 E installd: system dir 2 : /vendor/app/
08-29 13:44:21.554   284   284 E installd: system dir 3 : /oem/app/
08-29 13:44:21.624  1017  1447 I ActivityManager: Killing 6239:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-29 13:44:21.624  1937  3996 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-29 13:44:21.624  6633  6633 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-29 13:44:21.644  1017  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-29 13:44:21.654  6633  6633 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 5354-5358)
08-29 13:44:21.654  6633  6633 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 13:44:21.684  6633  6633 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26bcef91}
08-29 13:44:21.684  6633  6633 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 13:44:21.684  6633  6633 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 13:44:21.694  6430  6491 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-29 13:44:21.694  6430  6491 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 13:44:21.694  6430  6491 I GAv4    :   adb logcat -s GAv4
08-29 13:44:21.714  1937  3996 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-29 13:44:21.734  6430  6491 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-29 13:44:21.734  6633  6633 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-29 13:44:21.734  1017  1504 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 13:44:21.734  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:44:21.744  6633  6633 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 13:44:21.754  6430  6491 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-29 13:44:21.764  6633  6633 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 13:44:21.764  6633  6633 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 13:44:21.764  6633  6633 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 13:44:21.764  6633  6633 I Adreno-EGL: Local Branch: 
08-29 13:44:21.764  6633  6633 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 13:44:21.764  6633  6633 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 13:44:21.764  6633  6633 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-29 13:44:21.764  6430  6676 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-29 13:44:21.784  6430  6491 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-29 13:44:21.804  1937  3996 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-29 13:44:21.824  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-29 13:44:21.834  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:21.834  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:21.834  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 13:44:21.844  6633  6633 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 13:44:21.854  6633  6633 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-29 13:44:21.854  6633  6633 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-29 13:44:21.864  6633  6633 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-29 13:44:21.864  6633  6633 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-29 13:44:21.994  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{d07c43 u0 com.test.thalitest/.MainActivity t163}
08-29 13:44:21.994  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:44:22.004  6633  6633 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-29 13:44:22.014  1017  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-29 13:44:22.014  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:22.014  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:22.014  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:22.014  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:22.024  1017  2857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-29 13:44:22.024  6633  6633 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 13:44:22.024  6633  6633 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-29 13:44:22.034  6699  6699 E Zygote  : MountEmulatedStorage()
08-29 13:44:22.034  6699  6699 E Zygote  : v2
08-29 13:44:22.034  6699  6699 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:44:22.034  6699  6699 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:22.034  6699  6699 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:22.034  6699  6699 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:22.034  6699  6699 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:44:22.034  1017  1480 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6699 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:44:22.034  1017  1480 I ActivityManager: Killing 6255:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-29 13:44:22.044  6633  6633 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-29 13:44:22.054  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:44:22.054  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-29 13:44:22.064  6699  6699 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:22.064  6699  6699 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:22.094  6633  6718 D OpenGLRenderer: Render dirty regions requested: true
08-29 13:44:22.094  1017  1447 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 13:44:22.104  1017  1447 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 13:44:22.104  1017  1447 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-29 13:44:22.104  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 13:44:22.104  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-29 13:44:22.104  6699  6699 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-29 13:44:22.104  6699  6699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-29 13:44:22.104  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-29 13:44:22.104  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-29 13:44:22.104  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:22.114  6633  6686 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-29 13:44:22.114  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:22.114  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-29 13:44:22.114  1017  1078 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-29 13:44:22.124  6633  6633 V ActivityThread: updateVisibility : ActivityRecord{33258a71 token=android.os.BinderProxy@2375a58a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-29 13:44:22.124  6633  6633 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 13:44:22.124  6633  6633 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 13:44:22.124  6699  6699 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-29 13:44:22.144   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-29 13:44:22.144  6430  6697 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-29 13:44:22.144  6430  6697 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-29 13:44:22.144  1017  1017 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-29 13:44:22.144  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-29 13:44:22.144  1017  1388 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:22.154  6699  6720 E FilterInstaller: installFilters
08-29 13:44:22.154  1017  1388 D AlarmManagerService: Setting time of day to sec=1472471063
08-29 13:44:22.154  1017  1388 D AlarmManagerService: Trying to open a file
08-29 13:44:22.154  6699  6720 E FilterInstaller: There is no requred permission
08-29 13:44:22.154  1017  1388 D AlarmManagerService: File Open Success
08-29 13:44:22.154  1017  1388 D AlarmManagerService: File Close Success
08-29 13:44:22.154  1017  1388 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-29 13:44:23.124  1017  1096 V AlarmManager: waitForAlarm result :65536
08-29 13:44:23.124  1017  1030 I ActivityManager: Killing 6270:com.sec.spp.push/u0a32 (adj 15): empty #21
08-29 13:44:23.124  1017  1388 W AlarmManagerService: Unable to set rtc to 1472471063: Invalid argument
08-29 13:44:23.124  1017  1493 D InputDispatcher: Focus entered window: 6633
08-29 13:44:23.124  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 13:44:23.124  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 13:44:23.133  6633  6633 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-29 13:44:23.133  6633  6718 I OpenGLRenderer: Initialized EGL, version 1.4
08-29 13:44:23.133  1017  1096 V AlarmManager: No more alarm at this time.nowELAPSED=95875 batch.start=107984
08-29 13:44:23.133  1017  1042 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-29 13:44:23.143  6633  6718 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-29 13:44:23.143  6633  6718 D OpenGLRenderer: Enabling debug mode 0
08-29 13:44:23.153  6430  6697 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-29 13:44:23.173  1017  1219 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-29 13:44:23.173  1017  1219 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4211, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-29 13:44:23.173  1017  1219 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 13:44:23.173  1017  1219 D BatteryService: stay LED for charging
08-29 13:44:23.183  1017  1042 W ActivityManager: Failed to update preferences for: com.sec.spp.push
08-29 13:44:23.183  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-29 13:44:23.193  1172  1172 D KeyguardUpdateMonitor: handleTimeUpdate
08-29 13:44:23.193  1172  1172 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-29 13:44:23.193  1172  1172 D SecKeyguardClockView: HomeTimezone(): 1
08-29 13:44:23.203  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 13:44:23.213  1172  1172 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-29 13:44:23.213  1172  1172 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
08-29 13:44:23.213  1017  1480 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-29 13:44:23.213  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-29 13:44:23.213  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-29 13:44:23.213  1172  1172 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 13:44:23.223  1017  6725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-29 13:44:23.223  6430  6697 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-29 13:44:23.223  6430  6697 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@25478e25: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-29 13:44:23.223  6430  6697 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-29 13:44:23.223  1017  1029 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-29 13:44:23.223  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:44:23.223  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:44:23.223  1017  1029 D SettingsProvider: selectionArgs: false
08-29 13:44:23.223  1017  1029 D SettingsProvider: selectionArgs: 10049
08-29 13:44:23.223  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:44:23.223  1017  1029 D SettingsProvider: ret = -1
,08-29 13:44:23.223  1172  1172 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,08-29 13:44:23.233  1172  1172 D KeyguardEffectViewController: isPreloadedWallpaper=true
,08-29 13:44:23.233  1172  1172 I GeometricMosaic_Keyguard: update
,08-29 13:44:23.233  1017  1017 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472471063244
,08-29 13:44:23.233  1172  1172 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,08-29 13:44:23.243  6633  6633 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-29 13:44:23.243  6633  6633 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2375a58a time:95982
08-29 13:44:23.243  1017  1017 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,08-29 13:44:23.243  1017  1017 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,08-29 13:44:23.243  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 13:44:23.243  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 13:44:23.243  1017  1017 I BackgroundCompactionService: onStart. jobID=801
,08-29 13:44:23.243  6321  6366 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-29 13:44:23.253  1017  1017 I BackgroundCompactionService: onStart done. jobID=801
,08-29 13:44:23.253  1017  1017 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:23.253  2758  2758 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 13:44:23.253  2758  2884 D HeadsetStateMachine: Disconnected process message: 10
,08-29 13:44:23.253  1017  1047 I ActivityManager: Displayed Component not be shown by security: +807ms (total +1s6ms)
,08-29 13:44:23.253  1017  1047 W ActivityManager: mDVFSHelper.release()
,08-29 13:44:23.263  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d07c43 u0 com.test.thalitest/.MainActivity t163} time:95999
,08-29 13:44:23.263  1017  6727 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-29 13:44:23.263  1017  6727 I BackgroundCompactionService: compact_memory command done
08-29 13:44:23.263  1017  1487 I ActivityManager: Killing 4658:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
,08-29 13:44:23.263   258  1098 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-29 13:44:23.273   258  6119 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-29 13:44:23.283  6321  6366 I AcmsKeyStoreHelper: Key Store exist
08-29 13:44:23.283  6321  6366 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-29 13:44:23.283  1872  1872 I SamsungIME: getCurrentCandidateView
,08-29 13:44:23.323  1172  1172 I KeyguardEffectViewUtil: set current wallpaper info,
08-29 13:44:23.323  1017  1447 D SettingsProvider: name = keyguard_current_wallpaper_type
08-29 13:44:23.323  1017  1447 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:44:23.323  1017  1447 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:44:23.323  1017  1447 D SettingsProvider: selectionArgs: false
08-29 13:44:23.323  1017  1447 D SettingsProvider: selectionArgs: 10049
08-29 13:44:23.323  1017  1447 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:44:23.323  1017  1447 D SettingsProvider: ret = -1,
,08-29 13:44:23.333  1017  1030 D SettingsProvider: name = keyguard_current_wallpaper_file_path,
08-29 13:44:23.333  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-29 13:44:23.333  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:44:23.333  1017  1030 D SettingsProvider: selectionArgs: false,
08-29 13:44:23.333  1017  1030 D SettingsProvider: selectionArgs: 10049
08-29 13:44:23.333  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 13:44:23.333  1017  1030 D SettingsProvider: ret = -1
,08-29 13:44:23.333  1017  1078 D SettingsProvider: name = keyguard_current_wallpaper_res_id
08-29 13:44:23.333  1017  1078 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:44:23.333  1017  1078 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:44:23.333  1017  1078 D SettingsProvider: selectionArgs: false
08-29 13:44:23.333  1017  1078 D SettingsProvider: selectionArgs: 10049
08-29 13:44:23.333  1017  1078 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:44:23.333  1017  1078 D SettingsProvider: ret = -1
,08-29 13:44:23.333  1017  1017 I DrmEventService:  no response from SecureClock ,
08-29 13:44:23.333  1017  1017 I MotionRecognitionService: Plugged
08-29 13:44:23.333  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-29 13:44:23.343  1017  1017 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-29 13:44:23.343  1017  1017 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-29 13:44:23.343  1017  1017 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-29 13:44:23.343  1017  1017 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
,08-29 13:44:23.343  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-29 13:44:23.353  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:23.353  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:23.353  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:23.353  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:23.363  6730  6730 E Zygote  : MountEmulatedStorage()
08-29 13:44:23.363  6730  6730 E Zygote  : v2
08-29 13:44:23.363  6730  6730 I libpersona: KNOX_SDCARD checking this for 10008
08-29 13:44:23.363  6730  6730 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:23.363  6730  6730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:23.363  1017  1017 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6730 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:23.363  6730  6730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:23.363  6730  6730 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 13:44:23.383  6730  6730 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:23.383  6730  6730 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:23.383  6321  6366 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-29 13:44:23.383  6321  6366 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-29 13:44:23.383  6321  6366 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-29 13:44:23.383  6321  6366 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-29 13:44:23.383  6321  6366 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-29 13:44:23.383  6321  6366 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-29 13:44:23.393  6321  6366 D AcmsCore: This is NOT a valid MirrorLink app
08-29 13:44:23.393  6321  6366 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-29 13:44:23.393  6321  6366 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-29 13:44:23.393  6321  6366 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-29 13:44:23.393  6321  6366 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-29 13:44:23.393  6321  6321 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-29 13:44:23.403  6321  6321 D AcmsService: Enter onDestroy
08-29 13:44:23.403  6321  6321 I AcmsService: cleanUp(): inside service clean up
08-29 13:44:23.403  6321  6321 D AcmsCore: AcmsCore: inside DeInit
,08-29 13:44:23.403  6321  6321 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-29 13:44:23.403  6321  6321 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,08-29 13:44:23.403  6321  6321 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-29 13:44:23.403  6321  6321 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-29 13:44:23.403  6321  6321 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-29 13:44:23.403  6321  6321 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-29 13:44:23.403  6321  6321 D AcmsService: killing acms process
08-29 13:44:23.403  6321  6321 I Process : Sending signal. PID: 6321 SIG: 9
,08-29 13:44:23.413  1172  1668 D TEST    : run!!!
,08-29 13:44:23.423  1172  1668 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-29 13:44:23.433  1172  1172 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-29 13:44:23.433  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 13:44:23.433  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-29 13:44:23.433  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:23.433  1172  1172 D PanelView: There is/are notification(s) 
08-29 13:44:23.433  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:23.443  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 13:44:23.463  1017  3977 I ActivityManager: Process ACMS.Process (pid 6321)(adj 0) has died(18,783)
,08-29 13:44:23.493  6730  6730 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
08-29 13:44:23.493  1872  1872 D SamsungIME: Dismiss ExpandCandiate
,08-29 13:44:23.503  6730  6730 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-29 13:44:23.513  1017  3971 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:44:23.513  6633  6633 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6633
,08-29 13:44:23.523  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
08-29 13:44:23.523  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:23.523  1017  3971 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:23.523  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:44:23.543  1017  3977 I ActivityManager: Killing 6279:com.samsung.helphub/1000 (adj 15): empty #21
,08-29 13:44:23.573  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:44:23.573  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,08-29 13:44:23.573  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:23.573  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:23.573  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:44:23.583  2899  2899 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Aug 29 13:44:23 GMT+02:00 2016
,08-29 13:44:23.583  1017  1219 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 13:44:23.583  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 13:44:23.583  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:23.583  1017  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:23.583  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 13:44:23.593  2899  2899 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 13:44:23.593  1017  1078 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 13:44:23.593  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:23.593  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:23.593  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:23.593  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:23.613  2899  2899 I KLMS-2.5.123: : KLMSIntentService(): onCreate(),
,08-29 13:44:23.613  6752  6752 E Zygote  : MountEmulatedStorage()
08-29 13:44:23.613  6752  6752 E Zygote  : v2
08-29 13:44:23.613  6752  6752 I libpersona: KNOX_SDCARD checking this for 10036,
08-29 13:44:23.613  6752  6752 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:23.613  1017  1078 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6752 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:23.613  2899  2899 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-29 13:44:23.613  6752  6752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:23.613  2899  2899 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 13:44:23.623  6752  6752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:23.623  6752  6752 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-29 13:44:23.623  2899  6751 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-29 13:44:23.623  2899  6751 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,08-29 13:44:23.633  2899  6751 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Mon Aug 29 13:44:23 GMT+02:00 2016
,08-29 13:44:23.643  6752  6752 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:23.643  6752  6752 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:23.643  2899  6751 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,08-29 13:44:23.653  2899  2899 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 13:44:23.673  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c,
,08-29 13:44:23.683  6752  6752 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3df0ce59
,08-29 13:44:23.693  6752  6752 I SA      : [SSP] onCreated
,08-29 13:44:23.703  6752  6752 I SA      : [TPM] There is no property file
,08-29 13:44:23.703  6752  6752 I SA      : [SCU] isHaveSA() - false
,08-29 13:44:23.713  6752  6752 I SA      : [TPM] getModelProperty : null
08-29 13:44:23.713  6752  6752 I SA      : [TPM] getCSCProperty : null
,08-29 13:44:23.713  6752  6752 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-29 13:44:23.713  6752  6752 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 13:44:23.713  6752  6752 I SA      : [DM] TFT FEATURE: false
,08-29 13:44:23.723  6752  6752 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-29 13:44:23.723  6752  6752 I SA      : [DM] init START
,08-29 13:44:23.723  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 13:44:23.723  6752  6752 I SA      : [DM] This device is not a Vodafone
,08-29 13:44:23.733  6752  6752 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-29 13:44:23.733  6752  6752 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 13:44:23.733  1872  1872 I SamsungIME: KeybaordView init() : load resources
,08-29 13:44:23.733  6752  6752 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-29 13:44:23.733  6752  6752 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-29 13:44:23.733  6752  6752 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75),
08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-29 13:44:23.743  6752  6752 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-29 13:44:23.753  6340  6340 I Mms/MmsApp:  start initViewCache mms
08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-29 13:44:23.753  6752  6752 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-29 13:44:23.753  6340  6340 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1818.257707
,08-29 13:44:23.753  6340  6340 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-29 13:44:23.763  1872  1872 I SamsungIME: getCurrentKeyboard
08-29 13:44:23.763  1872  1872 I SamsungIME: getTextKeyboard
,08-29 13:44:23.773  6752  6752 I SA      : [SCU] isHaveSA() - false,
08-29 13:44:23.773  6752  6752 I SA      : support phone number id : false
08-29 13:44:23.773  6752  6752 I SA      : [DM] Supports Ref Jpn : true
,08-29 13:44:23.773  6752  6752 I SA      : [DM] init END,
,08-29 13:44:23.773  6633  6633 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 13:44:23.793  1872  1872 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-29 13:44:23.873  6633  6738 D jxcore_app_log: JniHelper::setJavaVM(0xb7eb42b0), pthread_self() = -1203494760
,08-29 13:44:23.883  6633  6738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 13:44:23.883  6633  6738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 13:44:23.883  6633  6738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 13:44:23.883  6633  6738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 13:44:23.883  6633  6738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 13:44:23.883  6633  6738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c230bcf added. We now have 1 listener(s)
,08-29 13:44:23.883  6340  6340 D AbsListView: Get MotionRecognitionManager
,08-29 13:44:23.893  6633  6738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
08-29 13:44:23.893  1017  1480 D MotionRecognitionService:  ssp status : false
,08-29 13:44:23.893  6633  6738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:44:23.893  6633  6738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:44:23.893  6633  6738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:44:23.893  6340  6340 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 138.796875
,08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 13:44:23.903  6633  6738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c8a853a added. We now have 1 listener(s)
,08-29 13:44:23.903  6633  6738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:23.903  6633  6738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:44:23.903  6633  6738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 13:44:23.903  6633  6738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 13:44:23.903  6633  6738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 13:44:23.903  6633  6738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 13:44:23.913  6633  6738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:23.913  6633  6738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41,
,08-29 13:44:23.913  6633  6738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 13:44:23.913  6633  6738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:23.913  6633  6738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:23.913  6633  6738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:23.913  6633  6738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:23.913  6633  6738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:23.913  6633  6738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:23.913  6633  6738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:23.913  6633  6738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:23.923  6633  6738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register,
08-29 13:44:23.923  6633  6738 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-29 13:44:23.923  6633  6738 I io.jxcore.node.LifeCycleMonitor: start: OK,
,08-29 13:44:23.923  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:23.923  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:23.953  6633  6633 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 13:44:23.993  6340  6340 D Mms/BubbleViewCache: fillCache bubble = 1
,08-29 13:44:23.993  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-29 13:44:23.993  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:23.993  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:23.993  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:23.993  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.013  6776  6776 E Zygote  : MountEmulatedStorage(),
,08-29 13:44:24.013  6776  6776 I libpersona: KNOX_SDCARD checking this for 10058
08-29 13:44:24.013  6776  6776 E Zygote  : v2
08-29 13:44:24.013  6776  6776 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:24.013  6776  6776 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:24.013  1017  1504 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6776 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:24.013  6776  6776 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:24.013  1017  1504 I ActivityManager: Killing 5430:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-29 13:44:24.013  6776  6776 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:24.033  6776  6776 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:24.033  6776  6776 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:24.083  6776  6776 I ExternalOEMControlProvider: onCreate
,08-29 13:44:24.093  6776  6791 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-29 13:44:24.103  1017  3977 I ActivityManager: Killing 6302:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-29 13:44:24.103  1783  1783 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-29 13:44:24.103  1783  1783 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 13:44:24.113  1017  1219 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-29 13:44:24.113  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.113  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.113  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.113  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.123  6792  6792 E Zygote  : MountEmulatedStorage()
,08-29 13:44:24.123  6792  6792 E Zygote  : v2
,08-29 13:44:24.123  6792  6792 I libpersona: KNOX_SDCARD checking this for 10081
,08-29 13:44:24.123  6792  6792 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:24.123  6792  6792 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:24.123  6792  6792 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:24.133  1017  1219 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6792 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:24.133  6792  6792 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:24.143  6792  6792 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:24.143  6792  6792 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:24.163  6792  6792 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 13:44:24.163  6792  6792 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 13:44:24.163  6792  6792 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:44:24.163  6792  6792 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:44:24.163  6792  6792 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-29 13:44:24.213  1017  1493 D SettingsProvider: name = next_alarm_formatted
,08-29 13:44:24.213  1017  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 13:44:24.213  1017  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:44:24.213  1017  1493 D SettingsProvider: selectionArgs: false
,08-29 13:44:24.213  1017  1493 D SettingsProvider: selectionArgs: 10081
08-29 13:44:24.213  1017  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:44:24.213  1017  1493 D SettingsProvider: ret = -1
,08-29 13:44:24.413  1017  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-29 13:44:24.413  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.413  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.413  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.413  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.433  6808  6808 E Zygote  : MountEmulatedStorage()
,08-29 13:44:24.433  6808  6808 E Zygote  : v2
08-29 13:44:24.433  6808  6808 I libpersona: KNOX_SDCARD checking this for 10090
,08-29 13:44:24.433  6808  6808 I libpersona: KNOX_SDCARD not a persona,
08-29 13:44:24.433  6808  6808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:24.433  6808  6808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 13:44:24.433  1017  1487 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6808 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-29 13:44:24.433  1017  1487 I ActivityManager: Killing 6380:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21,
08-29 13:44:24.433  6808  6808 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:24.453  6808  6808 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:24.453  6808  6808 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:24.483  6808  6808 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-29 13:44:24.483  6808  6808 D elm:15121: ELMEngine.ELMEngine( context ).
,08-29 13:44:24.483  6808  6808 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-29 13:44:24.483  1017  1447 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-29 13:44:24.483  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-29 13:44:24.493  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:24.493  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:24.493  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-29 13:44:24.493  6808  6808 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-29 13:44:24.493  1017  3971 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-29 13:44:24.493  1017  3971 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.493  1017  3971 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.493  1017  3971 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.493  1017  3971 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.493  6808  6808 D elm:15121: ElmAgentService : onCreate()
,08-29 13:44:24.503  6808  6823 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-29 13:44:24.503  6824  6824 E Zygote  : MountEmulatedStorage()
08-29 13:44:24.503  6824  6824 E Zygote  : v2
08-29 13:44:24.503  6824  6824 I libpersona: KNOX_SDCARD checking this for 10130
08-29 13:44:24.503  6824  6824 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:24.513  6824  6824 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:24.513  1017  3971 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6824 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,08-29 13:44:24.513  6824  6824 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:24.513  6808  6823 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
08-29 13:44:24.513  6824  6824 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-29 13:44:24.513  6808  6808 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,08-29 13:44:24.513  6808  6808 D elm:15121: ModuleBase.ModifySetAlarm()
08-29 13:44:24.513  6808  6808 D elm:15121: MDMBridge.getInstance()
08-29 13:44:24.513  6808  6808 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-29 13:44:24.523  6808  6808 D elm:15121: ElmAgentService : onDestroy().
,08-29 13:44:24.523  1017  1030 I ActivityManager: Killing 6430:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-29 13:44:24.533  6824  6824 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:24.533  6824  6824 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:24.553  6824  6824 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:44:24.553  6824  6824 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-29 13:44:24.563  6633  6774 W jxcore-log: Initializing JXcore engine
08-29 13:44:24.563  6633  6774 W jxcore-log: JXcore engine is ready
,08-29 13:44:24.563  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-29 13:44:24.573  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.573  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.573  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.573  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.583  6840  6840 E Zygote  : MountEmulatedStorage(),
08-29 13:44:24.583  6840  6840 E Zygote  : v2
08-29 13:44:24.583  6840  6840 I libpersona: KNOX_SDCARD checking this for 10131
08-29 13:44:24.583  6840  6840 I libpersona: KNOX_SDCARD not a persona,
,08-29 13:44:24.583  6840  6840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:24.583  6840  6840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 13:44:24.583  1017  1504 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6840 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-29 13:44:24.583  1017  1504 I ActivityManager: Killing 6400:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-29 13:44:24.593  6840  6840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:24.613  6840  6840 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:24.613  6840  6840 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:24.633  6840  6840 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 13:44:24.633  6840  6840 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:44:24.633  6840  6840 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:44:24.633  2007  2007 E audit   : type=1400 msg=audit(1472471064.633:205): avc:  denied  { ioctl } for  pid=6774 comm="Thread-1240" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 13:44:24.633  2007  2007 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:24.633  2007  2007 E audit   : type=1300 msg=audit(1472471064.633:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9dc868f8 items=0 ppid=304 ppcomm=main pid=6774 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1240" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-29 13:44:24.633  2007  2007 E audit   : type=1320 msg=audit(1472471064.633:205): 
,08-29 13:44:24.643  6633  6774 W jxcore-log: Starting JXcore engine
,08-29 13:44:24.663  1017  1493 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-29 13:44:24.663  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-29 13:44:24.673  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:24.673  1017  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:24.673  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-29 13:44:24.673  2498  2507 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-29 13:44:24.683  1017  1447 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-29 13:44:24.683  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-29 13:44:24.683  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:24.683  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:24.683  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-29 13:44:24.693  1017  1450 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-29 13:44:24.693  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.693  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.693  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.693  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.713  6860  6860 E Zygote  : MountEmulatedStorage(),
08-29 13:44:24.713  1017  1450 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=6860 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:44:24.713  6860  6860 E Zygote  : v2,
08-29 13:44:24.713  6860  6860 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:44:24.713  6860  6860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 13:44:24.713  6860  6860 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:24.723  6860  6860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:24.723  6860  6860 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:24.723  1017  1480 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-29 13:44:24.723  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.723  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.723  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.723  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.743  6872  6872 E Zygote  : MountEmulatedStorage(),
,08-29 13:44:24.743  6872  6872 E Zygote  : v2
,08-29 13:44:24.743  6872  6872 I libpersona: KNOX_SDCARD checking this for 10037
08-29 13:44:24.743  6872  6872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 13:44:24.743  6872  6872 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:24.743  6872  6872 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:24.743  1017  1480 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6872 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:24.743  6872  6872 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 13:44:24.763  6860  6860 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:24.763  6860  6860 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:24.763   304   304 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 648us total 22.302ms
08-29 13:44:24.763  6633  6774 W jxcore-log: Platform android
08-29 13:44:24.763  6633  6774 W jxcore-log: 
08-29 13:44:24.763  6633  6774 W jxcore-log: Process ARCH arm
08-29 13:44:24.763  6633  6774 W jxcore-log: 
,08-29 13:44:24.773  6872  6872 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:24.773  6872  6872 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:24.783   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 17.089ms
,08-29 13:44:24.803   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.840ms
,08-29 13:44:24.823  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:44:24.823  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:44:24.823  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 13:44:24.883   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb766e7c8
08-29 13:44:24.883   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-29 13:44:24.883   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-29 13:44:24.883   273   339 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1217992568)
,08-29 13:44:24.933  1017  1493 I art     : Explicit concurrent mark sweep GC freed 20210(1140KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 3.034ms total 140.347ms
,08-29 13:44:24.933  1017  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-29 13:44:24.933  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.933  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.933  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:24.933  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:24.933   273   339 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
,08-29 13:44:24.933   273   339 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-29 13:44:24.943   273   339 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1217992568) wakelock released: 1, error no: 0
08-29 13:44:24.943   273   339 I rmt_storage: 
08-29 13:44:24.943   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb766e7c8
,08-29 13:44:24.943  6872  6872 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-29 13:44:24.953  6892  6892 E Zygote  : MountEmulatedStorage(),
08-29 13:44:24.953  6892  6892 I libpersona: KNOX_SDCARD checking this for 10153
08-29 13:44:24.953  6892  6892 E Zygote  : v2
08-29 13:44:24.953  6892  6892 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:24.953  6892  6892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:24.953  1017  1487 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6892 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-29 13:44:24.963  6892  6892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:24.963  1017  1487 I ActivityManager: Killing 6475:com.sec.pcw.device/1000 (adj 15): empty #21
08-29 13:44:24.963  6892  6892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:24.973  6892  6892 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:24.983  6892  6892 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:24.993  6872  6872 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-29 13:44:24.993  6892  6892 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:44:25.003  6633  6774 I jxcore-log: JXcore Cordova bridge is ready!
08-29 13:44:25.003  6633  6774 I jxcore-log: 
,08-29 13:44:25.003  6633  6774 W jxcore-log: JXcore engine is started
,08-29 13:44:25.003  1017  3967 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-29 13:44:25.003  6633  6738 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-29 13:44:25.003  1017  3967 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:25.003  1017  3967 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:25.003  1017  3967 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:25.003  1017  3967 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:25.003  6633  6633 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 13:44:25.023  6907  6907 E Zygote  : MountEmulatedStorage(),
08-29 13:44:25.023  6907  6907 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:44:25.023  6907  6907 E Zygote  : v2
08-29 13:44:25.023  6907  6907 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:25.023  6907  6907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 13:44:25.033  6907  6907 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:25.033  1017  3967 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:44:25.033  6907  6907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:44:25.033  1017  3967 I ActivityManager: Killing 5723:com.android.vending/u0a26 (adj 15): empty #21
,08-29 13:44:25.053  6907  6907 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:25.053  6907  6907 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:25.083  6907  6907 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472471065092
,08-29 13:44:25.083  6907  6907 D         : TimeServiceNative: User Time to be set is 1472471065092
08-29 13:44:25.083  6907  6907 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-29 13:44:25.083  6907  6907 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-29 13:44:25.083  6907  6907 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472471065092
,08-29 13:44:25.083   315   556 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-29 13:44:25.083  6907  6907 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-29 13:44:25.083   315  6923 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472471065092
08-29 13:44:25.083   315  6923 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472471065092, operation = 0
08-29 13:44:25.083   315  6923 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/24/71 5:27:13,
,08-29 13:44:25.083   315  6923 D QC-time-services: Daemon:Value read from RTC seconds = 36221233000
08-29 13:44:25.083   315  6923 D QC-time-services: Daemon:new time 1472471065092 
,08-29 13:44:25.083   315  6923 D QC-time-services: Daemon: delta 1436249832092 genoff 1436249832092 
08-29 13:44:25.083   288   288 E SMD     : DCD OFF
08-29 13:44:25.093   315  6923 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249832092 to memory
,08-29 13:44:25.093   315  6923 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-29 13:44:25.093   315  6923 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-29 13:44:25.113   315  6923 D QC-time-services: Updating the TOD offset
08-29 13:44:25.113   315  6923 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249832092 to memory
08-29 13:44:25.113   315  6923 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-29 13:44:25.113   315  6923 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-29 13:44:25.113   315  6923 E QC-time-services: Daemon:Update to modem bit set
08-29 13:44:25.113   315  6923 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-29 13:44:25.113   315  6923 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285032092
,08-29 13:44:25.113  6907  6907 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-29 13:44:25.113   315   553 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-29 13:44:25.113   315   556 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-29 13:44:25.113  1017  1447 I ActivityManager: Killing 6358:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-29 13:44:25.133  2498  2498 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-29 13:44:25.133  2498  2498 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-29 13:44:25.133  2498  2498 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-29 13:44:25.133  2498  2498 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-29 13:44:25.133  1017  1030 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-29 13:44:25.133  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-29 13:44:25.143  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:25.143  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:25.143  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-29 13:44:25.143  2498  2498 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-29 13:44:25.143  2498  2498 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-29 13:44:25.143  2498  2498 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-29 13:44:25.143  2498  2498 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
08-29 13:44:25.143  2498  2498 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-29 13:44:25.143  2498  2498 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-29 13:44:25.153  2498  2498 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-29 13:44:25.153  2498  2498 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-29 13:44:25.153  2498  2498 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-29 13:44:25.153  2498  2498 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-29 13:44:25.153  2498  2498 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-29 13:44:25.153  2498  2498 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-29 13:44:25.163  2498  2498 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-29 13:44:25.163  2498  2498 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-29 13:44:25.173  2498  2498 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-29 13:44:25.173  2498  2498 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-29 13:44:25.173  1017  1504 I ActivityManager: Killing 6502:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-29 13:44:26.143  6872  6872 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-29 13:44:26.143  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:26.143  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:26.143  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-29 13:44:26.153  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-29 13:44:26.153  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:26.153  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:26.153  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-29 13:44:26.153  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:26.153  1017  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:26.153  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-29 13:44:26.163  1017  3971 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-29 13:44:26.163  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-29 13:44:26.163  1017  3971 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:44:26.163  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:26.163  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-29 13:44:26.163  1017  1450 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:26.163  1017  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:26.163  1017  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-29 13:44:26.173  1017  1447 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-29 13:44:26.173  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-29 13:44:26.173  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:26.173  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:26.173  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-29 13:44:26.183  1017  3971 I ActivityManager: Killing 6524:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-29 13:44:26.933  1680  1680 I ConfigService: onDestroy
,08-29 13:44:28.083   288   288 E SMD     : DCD OFF
,08-29 13:44:30.493  1017  2838 D SSRM:n  : SIOP:: AP = 410
,08-29 13:44:31.093   288   288 E SMD     : DCD OFF
,08-29 13:44:32.293  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-29 13:44:32.603  1017  1057 D PackageManager: [MSG] MCS_UNBIND
,08-29 13:44:32.603  1017  1219 I ActivityManager: Killing 6546:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-29 13:44:33.223  1017  1450 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 13:44:33.223  1017  1450 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 13:44:33.223  1017  1450 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 13:44:33.223  1017  1450 D BatteryService: stay LED for charging
,08-29 13:44:33.223  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 13:44:33.223  1017  1017 I MotionRecognitionService: Plugged
,08-29 13:44:33.223  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 13:44:33.223  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 13:44:33.223  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 13:44:33.233  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-29 13:44:33.233  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 13:44:33.243  2758  2758 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 13:44:33.243  2758  2884 D HeadsetStateMachine: Disconnected process message: 10
,08-29 13:44:33.253  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:33.253  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:33.263  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:34.093   288   288 E SMD     : DCD OFF
,08-29 13:44:35.073  1017  1324 E Watchdog: !@Sync 3
,08-29 13:44:35.243  1017  1096 V AlarmManager: waitForAlarm result :4
,08-29 13:44:35.243  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-29 13:44:35.243  1017  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:35.243  1017  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:35.243  1017  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:35.243  1017  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:35.263  6934  6934 E Zygote  : MountEmulatedStorage()
,08-29 13:44:35.263  6934  6934 E Zygote  : v2
08-29 13:44:35.263  6934  6934 I libpersona: KNOX_SDCARD checking this for 10026
08-29 13:44:35.263  6934  6934 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:35.263  6934  6934 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 13:44:35.263  1017  1096 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6934 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:35.263  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{3887bf7 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,08-29 13:44:35.263  6934  6934 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:35.263  6934  6934 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:44:35.283  6934  6934 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:35.283  6934  6934 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:35.353  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.363  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.403  6934  6934 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,08-29 13:44:35.403  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
,08-29 13:44:35.493  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.493  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.,
,08-29 13:44:35.503  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.503  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.503  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.513  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.523  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.523  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.523  6934  6934 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-29 13:44:35.533  6934  6934 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 13:44:35.533  6934  6934 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-29 13:44:35.563  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.573  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.573  6934  6934 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-29 13:44:35.583  6934  6934 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-29 13:44:35.583  1017  3970 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,08-29 13:44:35.583  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-29 13:44:35.583  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:35.583  6934  6970 D Ads     : Skipping gmscore version check
,08-29 13:44:35.583  1017  3970 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 13:44:35.583  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-29 13:44:35.593  1017  1078 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:44:35.603  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:35.603  1017  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-29 13:44:35.603  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-29 13:44:35.603  6934  6934 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-29 13:44:35.633  6934  6934 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-29 13:44:35.833  6934  6967 D Finsky  : [1304] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-29 13:44:35.833  6934  6934 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-29 13:44:35.833  1017  3977 I ActivityManager: Killing 6560:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-29 13:44:36.073   313   313 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 13:44:36.073   313   313 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 13:44:37.093   288   288 E SMD     : DCD OFF,
,08-29 13:44:37.423  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-29 13:44:37.423  6633  6774 I jxcore-log: 
,08-29 13:44:37.423  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-29 13:44:37.423  6633  6774 I jxcore-log: 
,08-29 13:44:37.433  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:37.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:37.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:37.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:37.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:37.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:37.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:37.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:37.433  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:37.433  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 13:44:37.433  6633  6774 I jxcore-log: 
,08-29 13:44:37.443  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 13:44:37.443  6633  6774 I jxcore-log: 
,08-29 13:44:38.113  6633  6774 D executeNativeTests: Running unit tests
,08-29 13:44:38.203  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:44:38.203  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df added. We now have 2 listener(s)
,08-29 13:44:38.203  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 13:44:38.203  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:44:38.203  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:44:38.203  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:38.203  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c added. We now have 2 listener(s)
08-29 13:44:38.203  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:38.203  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-29 13:44:38.203  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:38.213  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:38.213  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:38.213  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:38.213  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:38.213  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:38.213  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:38.213  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:38.213  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:38.213  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:38.213  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:44:38.213  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 13:44:38.213  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:38.213  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:38.213  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.213  6633  6774 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 13:44:38.213  6633  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:44:38.213  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:44:38.213  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:38.213  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 13:44:38.213  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.213  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.223  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.223  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.223  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:44:38.223  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df removed from the list
08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.223  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c removed from the list
,08-29 13:44:38.223  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.223  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.223  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.223  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.223  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.223  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.223  6633  6774 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 13:44:38.223  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.223  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:44:38.223  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.223  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.223  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.223  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
,08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.223  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.223  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.223  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.223  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.223  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:38.223  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.223  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-29 13:44:38.223  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210],
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:44:38.233  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:44:38.233  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.233  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.233  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.233  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:38.233  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.233  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.233  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.233  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.233  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:38.233  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.233  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.233  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:38.233  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.233  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.233  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.233  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.233  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.233  6633  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:44:38.233  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:38.243  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 13:44:38.243  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:38.243  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:38.243  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:38.243  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:38.243  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:38.243  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:38.243  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:38.243  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:38.243  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:38.243  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:44:38.243  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:38.243  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:44:38.243  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:38.243  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:44:38.243  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 13:44:38.253  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.253  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:44:38.253  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:44:38.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:44:38.263  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 13:44:38.263  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 13:44:38.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:44:38.263  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 13:44:38.263  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:44:38.283  2758  2876 D BtGatt.GattService: registerClient() - UUID=e4b111f5-a226-458d-92b4-b35e3487b649
,08-29 13:44:38.323  2758  2818 D BtGatt.GattService: onClientRegistered() - UUID=e4b111f5-a226-458d-92b4-b35e3487b649, clientIf=6
,08-29 13:44:38.333  6633  6641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:44:38.333  2758  2767 D BtGatt.GattService: start scan with filters
,08-29 13:44:38.333  2758  2883 D BtGatt.ScanManager: handling starting scan
,08-29 13:44:38.333  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:44:38.333  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:44:38.333  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:44:38.333  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:44:38.333  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:44:38.333  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:44:38.333  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:44:38.333  2758  2883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:38.343  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:44:38.343  6633  6774 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:44:38.353  2758  2818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 13:44:38.353  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.353  2758  2883 D BtGatt.ScanManager: allow scan with filters
08-29 13:44:38.353  2758  2883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 13:44:38.353  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.353  6633  6774 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:44:38.353  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.353  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:44:38.353  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.353  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:44:38.353  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:44:38.353  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:44:38.353  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:44:38.353  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:44:38.353  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:44:38.353  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:44:38.353  2758  2883 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 13:44:38.353  2758  2770 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:44:38.353  2758  2876 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:44:38.353  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 13:44:38.353  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:44:38.363  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:44:38.363  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:44:38.363  2758  2883 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:44:38.363  2758  2883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:44:38.363  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:44:38.363  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:44:38.363  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:44:38.363  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:38.363  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.363  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:38.363  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.363  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.363  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.363  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.363  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.363  6633  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:44:38.373  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:38.373  2758  2818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 13:44:38.373  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.373  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:38.373  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:38.373  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:38.373  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:38.373  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:38.373  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:38.373  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:38.373  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:44:38.373  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 13:44:38.373  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.383  2758  2883 D BtGatt.ScanManager: filter size is 1
,08-29 13:44:38.383  2758  2883 D BtGatt.ScanManager: delete FilterIndex - 3
,08-29 13:44:38.383  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:38.383  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:44:38.383  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:44:38.383  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:38.383  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:44:38.383  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:38.383  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:44:38.383  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:44:38.383  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:38.383  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 13:44:38.383  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:44:38.383  2758  2883 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:44:38.393  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.393  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:44:38.393  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:44:38.393  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:44:38.393  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:44:38.393  2758  2883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 13:44:38.393  2758  2818 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 13:44:38.393  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:44:38.403  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 13:44:38.403  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:44:38.403  2758  2876 D BtGatt.GattService: registerClient() - UUID=4f7bf129-e598-41eb-a6dc-64170f3cf6cd
,08-29 13:44:38.443  2758  2818 D BtGatt.GattService: onClientRegistered() - UUID=4f7bf129-e598-41eb-a6dc-64170f3cf6cd, clientIf=6
,08-29 13:44:38.443  6633  6641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:44:38.443  2758  2767 D BtGatt.GattService: start scan with filters
,08-29 13:44:38.443  2758  2883 D BtGatt.ScanManager: handling starting scan
,08-29 13:44:38.453  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:44:38.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:44:38.453  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:44:38.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:44:38.453  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:44:38.453  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:44:38.453  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:44:38.453  2758  2818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 13:44:38.453  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:44:38.453  2758  2883 D BtGatt.ScanManager: allow scan with filters
08-29 13:44:38.453  2758  2883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
,08-29 13:44:38.453  2758  2883 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 13:44:38.463  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:44:38.463  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 13:44:38.463  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-29 13:44:38.463  2758  2883 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:44:38.463  2758  2883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-29 13:44:38.463  6633  6774 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:44:38.473  2758  2818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 13:44:38.473  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.473  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:44:38.473  6633  6774 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 13:44:38.473  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.473  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 13:44:38.473  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.473  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:44:38.473  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:44:38.473  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:44:38.473  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:44:38.473  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-29 13:44:38.473  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 13:44:38.473  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-29 13:44:38.473  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:44:38.473  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
,08-29 13:44:38.483  2758  2770 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:44:38.483  2758  2883 D BtGatt.ScanManager: filter size is 1
,08-29 13:44:38.483  2758  2883 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 13:44:38.483  2758  2876 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:44:38.483  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:38.483  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:44:38.493  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:44:38.493  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 13:44:38.493  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:44:38.493  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.493  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:44:38.493  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:44:38.493  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:44:38.493  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:44:38.493  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:44:38.493  2758  2883 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:44:38.493  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:44:38.493  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:44:38.493  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:38.493  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:38.493  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.493  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.493  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:38.493  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.493  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.493  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.493  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.493  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.493  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.493  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.493  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.493  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.493  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.493  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.493  6633  6774 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:44:38.503  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:38.503  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 13:44:38.503  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.503  2758  2883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 13:44:38.503  2758  2818 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 13:44:38.503  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.503  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:38.503  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:38.503  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:38.503  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:38.503  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:38.503  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:38.503  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:38.503  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:38.513  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:38.513  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:44:38.513  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.513  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.513  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:44:38.513  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:44:38.513  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:44:38.513  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:38.513  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:44:38.533  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:44:38.533  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:44:38.533  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:44:38.533  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:44:38.533  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:44:38.533  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:44:38.543  2758  2767 D BtGatt.GattService: registerClient() - UUID=ef630101-9c9e-42f4-b40d-9a31315585f0
,08-29 13:44:38.583  2758  2818 D BtGatt.GattService: onClientRegistered() - UUID=ef630101-9c9e-42f4-b40d-9a31315585f0, clientIf=6
,08-29 13:44:38.583  6633  6642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-29 13:44:38.583  2758  3260 D BtGatt.GattService: start scan with filters
,08-29 13:44:38.583  2758  2883 D BtGatt.ScanManager: handling starting scan,
08-29 13:44:38.583  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:44:38.583  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:44:38.583  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-29 13:44:38.583  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:44:38.583  2758  2818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 13:44:38.593  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:44:38.593  2758  2883 D BtGatt.ScanManager: allow scan with filters
,08-29 13:44:38.593  2758  2883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:44:38.593  2758  2883 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-29 13:44:38.593  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:44:38.593  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:44:38.593  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 13:44:38.593  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:44:38.593  2758  2883 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:44:38.593  2758  2883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:44:38.593  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:44:38.593  2758  2818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 13:44:38.593  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.603  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:44:38.603  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 13:44:38.603  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:44:38.603  6633  6774 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:44:38.603  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:44:38.613  6633  6774 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:44:38.613  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:44:38.613  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:44:38.613  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:38.613  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:44:38.613  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:44:38.613  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:44:38.613  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:44:38.613  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:44:38.613  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:44:38.613  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:44:38.613  2758  2767 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:44:38.613  2758  2883 D BtGatt.ScanManager: filter size is 1
08-29 13:44:38.613  2758  2883 D BtGatt.ScanManager: delete FilterIndex - 5
,08-29 13:44:38.613  2758  3260 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:44:38.613  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:44:38.613  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:44:38.613  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:44:38.613  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:44:38.613  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:44:38.613  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:44:38.623  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 13:44:38.623  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:44:38.623  2758  2883 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:44:38.623  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:44:38.623  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.623  6633  6774 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:44:38.623  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.623  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.623  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:44:38.623  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.623  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.623  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.623  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:38.623  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:44:38.623  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.623  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list,
08-29 13:44:38.623  6633  6774 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 13:44:38.623  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.623  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:44:38.623  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.623  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 13:44:38.623  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.623  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list,
,08-29 13:44:38.623  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.623  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.623  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.623  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.623  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:44:38.623  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:44:38.623  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.623  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.623  2758  2883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 13:44:38.623  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:44:38.633  2758  2818 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 13:44:38.633  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:44:38.633  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:44:38.633  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.633  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.633  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.633  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.633  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.633  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.633  6633  6774 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 13:44:38.633  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.633  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.633  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.633  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.633  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.633  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.633  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.633  6633  6774 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 13:44:38.633  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.633  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.633  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.633  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.633  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.633  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.633  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.633  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.633  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.643  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 13:44:38.643  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:44:38.643  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:44:38.643  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:44:38.643  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.643  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.643  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.643  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:38.643  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.643  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.643  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.643  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:38.643  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.643  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.643  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.643  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.643  6633  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 13:44:38.643  6633  6774 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 13:44:38.643  6633  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:38.643  6633  6774 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:44:38.643  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:44:38.643  6633  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 13:44:38.643  6633  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:38.643  6633  6774 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 13:44:38.643  6633  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 13:44:38.643  6633  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:38.643  6633  6774 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 13:44:38.643  6633  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:38.643  6633  6774 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:44:38.643  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-29 13:44:38.653  6633  6774 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 13:44:38.653  6633  6774 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:44:38.653  6633  6774 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-29 13:44:38.653  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.653  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.653  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 13:44:38.653  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.653  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.653  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.653  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.653  6633  6978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1304
08-29 13:44:38.653  6633  6774 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 13:44:38.653  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.653  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:44:38.653  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.653  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.653  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.653  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.653  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.653  6633  6774 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 13:44:38.653  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.653  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.653  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.653  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.653  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.653  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.653  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.653  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.653  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.663  6633  6977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1304)
08-29 13:44:38.663  6633  6977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1304)
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 13:44:38.663  6633  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-29 13:44:38.663  6633  6774 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:44:38.663  6633  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:38.663  6633  6774 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:44:38.663  6633  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:38.663  6633  6774 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 13:44:38.663  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.663  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:44:38.663  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
,08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.663  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.663  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.663  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.663  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:44:38.663  6633  6633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 13:44:38.663  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
,08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.663  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:44:38.663  6633  6633 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 13:44:38.663  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.663  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.673  6633  6979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 13:44:38.673  6633  6979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-29 13:44:38.673  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:44:38.673  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:38.673  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:44:38.673  6633  6633 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 13:44:38.673  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:44:38.673  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.673  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.673  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.673  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.673  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.673  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.673  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:44:38.673  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.673  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.673  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.673  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.673  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.673  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.673  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.673  6633  6774 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-29 13:44:38.673  6633  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:44:38.673  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:44:38.673  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.673  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.673  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.673  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.673  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.673  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.673  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.673  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.673  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.673  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.673  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.673  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.673  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.673  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.683  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.683  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.683  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.683  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.683  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.683  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.683  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.683  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.683  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.683  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.683  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.683  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.683  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:44:38.683  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:44:38.683  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:44:38.683  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.683  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.683  6633  6774 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecd0df not in the list
08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.683  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:44:38.683  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.683  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:44:38.683  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:44:38.683  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:44:38.683  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:44:38.683  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f3112c not in the list
,08-29 13:44:38.683  6633  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:44:38.683  6633  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:44:38.683  6633  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 13:44:38.683  6633  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:44:38.683  6633  6774 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:44:38.683  6633  6774 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 13:44:38.683  6633  6774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-29 13:44:38.693  6633  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 13:44:38.693  6633  6774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 13:44:38.693  6633  6774 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-29 13:44:38.693  6633  6774 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 13:44:38.693  6633  6774 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 13:44:38.693  6633  6774 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 13:44:38.693  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:38.693  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2eac082e added. We now have 2 listener(s)
08-29 13:44:38.693  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:38.693  6633  6774 D BluetoothAdapter: enable()
,08-29 13:44:38.693  6633  6774 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 13:44:38.693  1017  3967 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 13:44:38.693  1017  3967 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 13:44:38.693  1017  3967 D SecContentProvider2: mCursor = null
,08-29 13:44:38.703  1017  3967 D WifiService: setWifiEnabled: true pid=6633, uid=10170
08-29 13:44:38.703  1017  3967 W ActivityManager: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:44:38.703  1017  3967 W WifiService: Failed getting userId using ActivityManagerNative
08-29 13:44:38.703  1017  3967 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:44:38.703  1017  3967 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:44:38.703  1017  3967 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 13:44:38.703  1017  3967 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 13:44:38.703  1017  3967 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 13:44:38.703  1017  3967 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 13:44:38.703  1017  3967 D SettingsProvider: name = wifi_on
,08-29 13:44:38.703  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:44:38.703  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b51afcf added. We now have 3 listener(s)
08-29 13:44:38.703  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:38.713  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:44:38.713  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e731d5c added. We now have 4 listener(s)
,08-29 13:44:38.713  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:38.713  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:44:38.713  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b1db865 added. We now have 5 listener(s)
,08-29 13:44:38.713  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:38.713  1017  1504 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 13:44:38.713  1017  1504 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 13:44:38.713  1017  1504 D SecContentProvider2: mCursor = null
,08-29 13:44:38.723  1017  1504 D WifiService: setWifiEnabled: false pid=6633, uid=10170
,08-29 13:44:38.723  1017  1504 D SettingsProvider: name = wifi_on
,08-29 13:44:38.723  1017  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 13:44:38.723  1347  1347 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 13:44:38.723  1347  1347 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-29 13:44:38.733  1347  1347 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-29 13:44:38.733  6633  6774 D BluetoothAdapter: disable()
08-29 13:44:38.733  1347  1347 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 13:44:38.733  1017  1219 D SettingsProvider: name = bluetooth_on,
,08-29 13:44:38.733  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:38.743  2758  2815 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-29 13:44:38.743  2758  2815 D BluetoothAdapterProperties: Setting state to 13
,08-29 13:44:38.743  2758  2815 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 13:44:38.743  2758  2815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 13:44:38.743  2758  2815 D BluetoothAdapterService: updateAdapterState state is 13
,08-29 13:44:38.743  1017  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:38.753  1017  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:44:38.753  1017  1127 E WifiNative-wlan0: do suspend true
,08-29 13:44:38.753  1017  1323 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:38.753  1017  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:38.753  1017  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:38.753  2758  2758 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-29 13:44:38.753  2758  2758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25836a78, channel: 19, state: LISTENING
,08-29 13:44:38.753  2758  2758 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25836a78, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e188192, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14351551mSocket: android.net.LocalSocket@14bef1b6 impl:android.net.LocalSocketImpl@2bb68eb7 fd:FileDescriptor[80]
08-29 13:44:38.753  2758  2758 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@14bef1b6 impl:android.net.LocalSocketImpl@2bb68eb7 fd:FileDescriptor[80]
,08-29 13:44:38.753  2758  2815 D BluetoothAdapterService: Autoconnection is available 
,08-29 13:44:38.753  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:44:38.753  2758  2815 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 13:44:38.753  2758  2815 D BluetoothAdapterService: terminating service from this receiver
,08-29 13:44:38.763  4454  4454 D BluetoothPbap: Proxy object disconnected
08-29 13:44:38.763  4454  4454 D PbapServerProfile: Bluetooth service disconnected
,08-29 13:44:38.763  1017  3977 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 13:44:38.763  1017  3977 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:38.763  1017  3977 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:38.763  1017  3977 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:38.763  2758  2815 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:44:38.763  2758  2815 D BluetoothAdapterProperties: mDiscovering is false
,08-29 13:44:38.763  1017  1219 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 13:44:38.763  2758  2815 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 13:44:38.773  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:38.773  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:44:38.773  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:38.773  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:38.773  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:38.773  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:38.773  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:38.773  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:38.773  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:38.773  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:38.773  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:38.773  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:44:38.773  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.773  2758  2818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:44:38.773  2758  2818 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:44:38.783  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:38.783  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:38.783  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-29 13:44:38.783  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-29 13:44:38.783  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:38.783  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-29 13:44:38.783  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
08-29 13:44:38.783  1172  1172 D BluetoothTile:  getBluetoothState : 13
08-29 13:44:38.793  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:38.793  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-29 13:44:38.793  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 13:44:38.793  4454  4454 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:38.793  1017  1480 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:38.803  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:44:38.803  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 13:44:38.803  2758  2815 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 13:44:38.803  2758  2815 E bt-btif : cmd socket is not created
08-29 13:44:38.803  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 13:44:38.803  2758  2819 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-29 13:44:38.803  2758  5257 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 13:44:38.803  2758  2815 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 13:44:38.813  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:38.813  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:38.813  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:44:38.813  4454  4454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:38.813  2758  2758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1164b58d, channel: 5, state: LISTENING
08-29 13:44:38.813  2758  2758 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1164b58d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21c8fc19, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f407342mSocket: android.net.LocalSocket@89b5f53 impl:android.net.LocalSocketImpl@e651090 fd:FileDescriptor[82]
08-29 13:44:38.813  2758  2758 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@89b5f53 impl:android.net.LocalSocketImpl@e651090 fd:FileDescriptor[82]
,08-29 13:44:38.813  1017  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 13:44:38.813  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:44:38.813  2758  2758 I BtOppRfcommListener: stopping Accept Thread
08-29 13:44:38.813  2758  2758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@b741d89, channel: 12, state: LISTENING
08-29 13:44:38.813  2758  2758 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@b741d89, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cc4cfdb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2266818emSocket: android.net.LocalSocket@22f29daf impl:android.net.LocalSocketImpl@31b2a5bc fd:FileDescriptor[86]
08-29 13:44:38.813  2758  2758 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22f29daf impl:android.net.LocalSocketImpl@31b2a5bc fd:FileDescriptor[86]
,08-29 13:44:38.813  2758  5257 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:38.813  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:38.813  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:38.813  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:44:38.813  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.823  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:38.823  2758  2819 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 13:44:38.823  2758  2819 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:38.823  2758  2819 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:38.823  2758  2819 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:38.823  2758  2819 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:38.823  2758  2819 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 13:44:38.823  2758  2758 V BluetoothOppManager: cleanUp...
,08-29 13:44:38.833  1680  1680 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:38.833  4454  4454 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:38.833  4454  4454 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:44:38.833  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:38.833  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 13:44:38.833  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 13:44:38.843  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:38.843  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:38.843  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:38.843  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:38.853  6984  6984 E Zygote  : MountEmulatedStorage()
,08-29 13:44:38.853  6984  6984 E Zygote  : v2
,08-29 13:44:38.853  6984  6984 I libpersona: KNOX_SDCARD checking this for 10055
08-29 13:44:38.853  6984  6984 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:38.853  1017  1029 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6984 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 13:44:38.863  6984  6984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 13:44:38.863  6984  6984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:44:38.863  6984  6984 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 13:44:38.883  6984  6984 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:38.883  6984  6984 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:38.903  6984  6984 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 13:44:38.933  6984  6984 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-29 13:44:38.943  6984  6984 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 13:44:38.943  6984  6984 D UserAnalysis: Create SecureDbHelper
,08-29 13:44:38.943  6984  6984 D IntelligenceServiceApplication: onCreate()
,08-29 13:44:38.953  1017  1029 I ActivityManager: Killing 6577:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-29 13:44:38.953  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 13:44:38.953  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:38.953  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:38.953  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:38.953  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:38.953  6984  6984 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 13:44:38.973  6999  6999 E Zygote  : MountEmulatedStorage(),
08-29 13:44:38.973  6999  6999 E Zygote  : v2
08-29 13:44:38.973  6999  6999 I libpersona: KNOX_SDCARD checking this for 10105
08-29 13:44:38.973  6999  6999 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:38.973  6999  6999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 13:44:38.973  1017  1029 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6999 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 13:44:38.973  6999  6999 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:38.973  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 13:44:38.973  6984  6984 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-29 13:44:38.973  6999  6999 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-29 13:44:38.983  6984  6984 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 13:44:38.993  6999  6999 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:38.993  6999  6999 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:39.003  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 13:44:39.003  2758  2815 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 13:44:39.003  2758  2815 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 13:44:39.003  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-29 13:44:39.003  2758  2815 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-29 13:44:39.003  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 13:44:39.003  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 13:44:39.003  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 13:44:39.003  1017  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:39.013  1017  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 13:44:39.013  1017  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:39.013  1017  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:39.013  1017  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:39.013  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 13:44:39.013  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 13:44:39.013  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-29 13:44:39.013  2758  2758 D HeadsetService: Received stop request...Stopping profile...
08-29 13:44:39.013  1017  3967 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:39.013  1017  3967 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:39.013  1017  3967 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:39.013  1017  3967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:39.013  1017  3967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:39.013  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-29 13:44:39.013  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:44:39.013  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:39.023  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 13:44:39.023  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 13:44:39.023  4454  4454 D HeadsetProfile: Bluetooth service disconnected
,08-29 13:44:39.023  1017  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:39.023  1017  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 13:44:39.023  1017  1323 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:39.023  1017  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:39.023  1017  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:39.033  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-29 13:44:39.033  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 13:44:39.033  2758  2758 D A2dpService: Received stop request...Stopping profile...
,08-29 13:44:39.033  2758  2935 D A2dpStateMachine: Exit Disconnected: -1
,08-29 13:44:39.033  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 13:44:39.033  1017  3977 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:39.033  1017  3977 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 13:44:39.033  1017  3977 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:39.033  1017  3977 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:39.033  1017  3977 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:39.033  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 13:44:39.033  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 13:44:39.033  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 13:44:39.033  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:39.033  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:39.033  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:44:39.033  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:39.033  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:39.033  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:39.043  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 13:44:39.043  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 13:44:39.043  1017  1017 D BluetoothA2dp: Proxy object disconnected
,08-29 13:44:39.043  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 13:44:39.043  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 13:44:39.043  1017  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:39.043  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 13:44:39.043  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:39.043  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:39.043  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:39.043  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 13:44:39.043  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:44:39.043  4454  4454 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:39.043  4454  4454 D A2dpProfile: Bluetooth service disconnected
08-29 13:44:39.043  2758  2815 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-29 13:44:39.043  1017  3971 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:39.043  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:44:39.053  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:39.053  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:39.053  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:39.053  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 13:44:39.053  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 13:44:39.053  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 13:44:39.053  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:39.053  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 13:44:39.053  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:39.053  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-29 13:44:39.053  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 13:44:39.053  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 13:44:39.053  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,08-29 13:44:39.053  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 13:44:39.053  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-29 13:44:39.053  2758  2815 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 13:44:39.053  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 13:44:39.053  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 13:44:39.063  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 13:44:39.063  2758  2758 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:44:39.063  2758  2758 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 13:44:39.063  2758  2758 D HidService: Received stop request...Stopping profile...
08-29 13:44:39.063  2758  2758 D HidService: Stopping Bluetooth HidService
,08-29 13:44:39.063  2758  2758 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:44:39.063  2758  2758 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 13:44:39.063  2758  2758 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 13:44:39.063  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:39.063  2758  2758 D HealthService: Received stop request...Stopping profile...
,08-29 13:44:39.063  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:39.063  4454  4454 D BluetoothInputDevice: Proxy object disconnected
08-29 13:44:39.063  4454  4454 D HidProfile: Bluetooth service disconnected
,08-29 13:44:39.063  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-29 13:44:39.063  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:44:39.063  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 13:44:39.063  2758  2758 D PanService: Received stop request...Stopping profile...
08-29 13:44:39.063  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:39.073  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 13:44:39.073  2758  2758 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:39.073  2758  2758 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-29 13:44:39.073  2758  2936 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 13:44:39.073  2758  2758 I GKI_LINUX: GKI_exit_task 2 done
08-29 13:44:39.073  2758  2758 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-29 13:44:39.073  4454  4454 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 13:44:39.073  4454  4454 D PanProfile: Bluetooth service disconnected
08-29 13:44:39.073  2758  2758 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 13:44:39.073  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:39.073  4454  4454 D BluetoothMap: Proxy object disconnected
08-29 13:44:39.073  4454  4454 D MapProfile: Bluetooth service disconnected
,08-29 13:44:39.073  2758  2758 D SapService: Received stop request...Stopping profile...
08-29 13:44:39.073  2758  2758 D SapService: Stopping Bluetooth SapService
08-29 13:44:39.073  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:39.073  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 13:44:39.073  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 13:44:39.073  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:39.073  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:39.073  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 13:44:39.073  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 13:44:39.073  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:39.073  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:39.073  2758  2758 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:44:39.073  2758  2758 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:44:39.073  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 13:44:39.073  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 13:44:39.073  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:39.083  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:39.083  2758  2758 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:44:39.083  2758  2758 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 13:44:39.083  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 13:44:39.083  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 13:44:39.083  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:44:39.083  2758  2758 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-29 13:44:39.083  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-29 13:44:39.083  4454  4454 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 13:44:39.083  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 13:44:39.083  4454  4454 D SapProfile: Bluetooth service disconnected
08-29 13:44:39.083  2758  2758 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 13:44:39.083  2758  2758 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 13:44:39.083  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 13:44:39.083  2758  2815 D BluetoothAdapterProperties: Setting state to 10
08-29 13:44:39.083  2758  2815 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 13:44:39.083  2758  2815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:44:39.083  2758  2815 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 13:44:39.083  2758  2815 D BluetoothAdapterService: Autoconnection is available 
08-29 13:44:39.083  2758  2815 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 13:44:39.083  2758  2815 I BluetoothAdapterState: Entering OffState
08-29 13:44:39.083  1746  3519 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:39.083  1746  3519 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:39.093  4454  4464 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 13:44:39.093  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:39.093  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:39.093  1172  3170 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:39.093  1172  3170 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:39.093  6633  6641 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:39.093  6633  6641 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:44:39.093  6633  6641 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 13:44:39.093  6633  6641 D BluetoothLeAdvertiser: Exit stop advertising
08-29 13:44:39.093  6633  6641 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 13:44:39.093  6633  6641 D BluetoothLeScanner: Exiting stopAllScan
,08-29 13:44:39.093  2758  2767 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:44:39.093  4454  4462 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:44:39.093  4454  4464 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 13:44:39.093  1463  2018 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:39.093  1463  2018 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:39.093  4454  4462 D Bluetoothsap: onBluetoothStateChange: up=false
,08-29 13:44:39.093  4454  4462 D Bluetoothsap: Unbinding service...
,08-29 13:44:39.103  1680  1775 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:39.103  1680  1775 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:39.103  4454  4462 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 13:44:39.103  1428  1459 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:39.103  1428  1459 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:39.103  2758  3260 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:39.103  2758  3260 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:39.103  4454  4464 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:39.103  4454  4464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:39.103  1443  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:39.103  1443  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:44:39.103  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:44:39.113  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:39.113  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-29 13:44:39.113  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 13:44:39.113  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:44:39.113  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:39.113  1172  1172 D BluetoothTile:  getBluetoothState : 10
,08-29 13:44:39.113  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:44:39.123  4454  4454 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:39.123  1017  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:39.123  1017  1323 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:44:39.123  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:39.123  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:39.123  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:39.133   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 13:44:39.133   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:44:39.133  6999  7018 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 13:44:39.143   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 13:44:39.143   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:44:39.143  6999  7018 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 13:44:39.143  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 13:44:39.173  6633  6633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 13:44:39.283  6999  6999 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:39.283  6999  6999 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:39.283  6999  6999 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:39.283  6999  6999 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:39.283  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:39.293  6999  6999 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:39.293  6999  6999 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:39.293  6999  6999 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:44:39.293  6999  6999 D StrictMode: 	,at java.io.File.exists(File.java:363)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:39.293  6999  6999 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102),
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:39.293  6999  6999 D StrictMode: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:44:39.293  6999  6999 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 13:44:39.293  6999  6999 D StrictMode: ,	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:39.293  6999  6999 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:39.293  1017  1493 I ActivityManager: Killing 6598:com.wsomacp/u0a23 (adj 15): empty #21
,08-29 13:44:39.303  4454  4454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:39.303  1017  3967 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 13:44:39.303  1017  3967 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:44:39.303  1017  3967 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:39.303  1017  3967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:39.303  1017  3967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:44:39.313  1680  1680 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:39.313  1347  1347 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,08-29 13:44:39.313  4454  4454 D DockEventReceiver: finishStartingService: stopping service
08-29 13:44:39.313  1017  1126 D WifiP2pService: InactiveState{ what=147461 }
,08-29 13:44:39.313  1017  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-29 13:44:39.313  1017  1126 D WifiP2pService: DefaultState{ what=147461 }
,08-29 13:44:39.313  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-29 13:44:39.323  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 13:44:39.323   278  1003 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:44:39.323  1680  2543 V NativeCrypto: Read error: ssl=0xb83eaac8: I/O error during system call, Connection timed out
,08-29 13:44:39.323  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:39.323  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 13:44:39.323  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.323  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.323  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.323  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.323  4454  4454 D BluetoothNotiBroadcastReceiver: onReceive,
,08-29 13:44:39.333  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-29 13:44:39.333  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:44:39.333  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:44:39.333  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-29 13:44:39.333  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
08-29 13:44:39.333  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 },
,08-29 13:44:39.333  1680  2543 V NativeCrypto: SSL shutdown failed: ssl=0xb83eaac8: I/O error during system call, Broken pipe,
,08-29 13:44:39.333  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-29 13:44:39.333  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 13:44:39.333  1017  3977 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-29 13:44:39.333  1017  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:39.333  1017  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:39.343  1017  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation,
08-29 13:44:39.343  1017  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:39.343  1017  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-29 13:44:39.343  1017  1781 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 13:44:39.343  1017  1781 I qtaguid : Tagging socket 357 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,08-29 13:44:39.343  1017  1781 I qtaguid : Untagging socket 357
08-29 13:44:39.343  1017  1781 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 13:44:39.353  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
,08-29 13:44:39.353  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:39.353  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-29 13:44:39.363  1017  1152 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:39.363  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:39.363  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:39.363  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:44:39.363  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:39.363  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.363  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.363  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:39.363  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 13:44:39.373  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:39.373  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-29 13:44:39.373  6999  7017 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.,
08-29 13:44:39.373  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 13:44:39.383  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:44:39.383  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 13:44:39.383  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:39.383  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
08-29 13:44:39.383  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 13:44:39.383  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 13:44:39.383  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:44:39.383  1017  1047 D WifiDisplayController: disconnect
08-29 13:44:39.383  1017  1047 D WifiDisplayController: updateConnection
08-29 13:44:39.383  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-29 13:44:39.383  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 13:44:39.383  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 13:44:39.393   278   999 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 13:44:39.393  1017  1126 D WifiP2pService: P2pDisablingState
08-29 13:44:39.393   278   999 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-29 13:44:39.393  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 13:44:39.393  1017  1126 D WifiP2pService: p2p socket connection lost
08-29 13:44:39.393  1017  1126 D WifiP2pService: P2pDisabledState
08-29 13:44:39.393  1017  1127 E WifiNative-wlan0: do suspend true
,08-29 13:44:39.393  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 13:44:39.393  1017  1129 V NetworkStats: updateIfacesLocked()
08-29 13:44:39.393  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.393  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:44:39.393  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:39.393  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:44:39.393  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 13:44:39.393  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-29 13:44:39.393  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:44:39.393  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 13:44:39.393  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-29 13:44:39.393  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-29 13:44:39.403   278  1003 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:44:39.403  1017  1129 V NetworkStats: performPollLocked() took 9ms
08-29 13:44:39.403  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.403  1017  1450 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 13:44:39.403  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 13:44:39.403  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:39.403  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:39.403  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 13:44:39.413  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:39.413  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.413  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.413  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:39.413  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 13:44:39.413  1347  1347 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 13:44:39.423  1017  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
,08-29 13:44:39.423  1017  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 13:44:39.423  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-29 13:44:39.423  1017  1781 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:39.423  1017  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:39.423  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 13:44:39.423  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,08-29 13:44:39.423  1463  1463 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 13:44:39.423  1017  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-29 13:44:39.423  1463  1463 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:44:39.423  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:44:39.423  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.423  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.423  1172  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-29 13:44:39.423  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:44:39.423  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:39.423  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:39.433  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:39.433  4454  4454 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:39.433  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.443  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.443  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:39.443  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:39.443  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-29 13:44:39.443  1017  1447 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 13:44:39.443  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 13:44:39.443  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:39.443  1172  1172 D HotspotTile: onReceive : 0, 0,
08-29 13:44:39.443  1017  1447 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:39.443  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:44:39.443  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-29 13:44:39.443  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:44:39.443  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 13:44:39.443  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:39.443  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:39.443  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:44:39.443  1609  1609 I Hs20UtilService: Starting #8
08-29 13:44:39.443  1609  1651 I Hs20UtilService: Message received 5007
,08-29 13:44:39.443  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 13:44:39.443  1017  1132 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:44:39.443  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 13:44:39.443  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:44:39.443  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 13:44:39.443  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:44:39.443  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-29 13:44:39.453  1017  1124 V NetworkStats: updateIfacesLocked()
08-29 13:44:39.453  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.453  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-29 13:44:39.453  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:39.453  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:44:39.453  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:44:39.453  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:39.453  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:39.453  1017  1124 V NetworkStats: performPollLocked() took 4ms
08-29 13:44:39.453  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:39.453  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 13:44:39.453  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:39.453  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:39.453  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-29 13:44:39.453  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 13:44:39.453  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 13:44:39.453  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-29 13:44:39.453  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.453  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:39.453  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:39.453  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.453  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.453  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.453  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-29 13:44:39.463  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:44:39.463  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 13:44:39.463  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 13:44:39.463  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 13:44:39.463  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-29 13:44:39.463  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-29 13:44:39.463  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-29 13:44:39.473  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:39.473  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.473  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:44:39.473  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:39.473  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:44:39.473  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.473  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.473  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:39.473  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:39.473  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:44:39.473  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:44:39.473  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:44:39.473  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:39.473  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:44:39.483  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:44:39.493  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:44:39.493  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:44:39.493  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:44:39.493  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:44:39.493  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:39.493  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:44:39.493  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:44:39.503  1017  3970 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-29 13:44:39.503  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:39.503  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:39.503  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:39.503  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:39.513  7039  7039 E Zygote  : MountEmulatedStorage(),
08-29 13:44:39.513  7039  7039 E Zygote  : v2
08-29 13:44:39.513  7039  7039 I libpersona: KNOX_SDCARD checking this for 10064
08-29 13:44:39.513  7039  7039 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:39.513  7039  7039 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:39.513  1017  3970 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7039 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:39.523  1347  1347 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 13:44:39.523  7039  7039 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:39.523  7039  7039 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:39.543  7039  7039 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:39.543  7039  7039 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:39.563  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.563  7039  7039 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 13:44:39.563  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:44:39.563  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.563  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:44:39.563  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.573  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-29 13:44:39.573  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.573  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:44:39.573  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.573  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:44:39.573  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.573  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:44:39.573  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 13:44:39.573  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:44:39.573  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:44:39.583  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.583  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:44:39.583  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 13:44:39.583  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 13:44:39.583  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:44:39.583  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.583  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:44:39.583  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.593  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-29 13:44:39.593  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.593  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-29 13:44:39.593  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:44:39.593  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-29 13:44:39.593  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 13:44:39.593  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:44:39.593  1463  1463 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
08-29 13:44:39.593  1463  1463 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:44:39.613  1347  1347 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 13:44:39.613  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:44:39.613  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 13:44:39.613  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:44:39.613  7039  7039 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 13:44:39.613  1017  1323 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 13:44:39.613  1017  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:39.613  1017  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:39.613  1017  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:39.613  1017  1323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:39.633  7070  7070 E Zygote  : MountEmulatedStorage(),
08-29 13:44:39.633  7070  7070 E Zygote  : v2
08-29 13:44:39.633  7070  7070 I libpersona: KNOX_SDCARD checking this for 10065
,08-29 13:44:39.633  7070  7070 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:39.633  1347  1347 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-29 13:44:39.633  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:44:39.633  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:39.633  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:39.633  1347  1347 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 13:44:39.633  1347  1347 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 13:44:39.633  1017  1132 D Tethering: InitialState.processMessage what=4
08-29 13:44:39.633  1347  1347 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 13:44:39.633  1347  1347 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 13:44:39.633  7070  7070 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 13:44:39.633  1017  1132 E Tethering: No numeric data
,08-29 13:44:39.633  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:44:39.633  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:39.633  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:39.633  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:44:39.633  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:39.633  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:39.633  7070  7070 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:39.633  1017  1323 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7070 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:39.633  7070  7070 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:39.643  1017  1323 I ActivityManager: Killing 6616:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-29 13:44:39.643  1017  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:44:39.643  1017  1132 D Tethering: clearTetheredNotification()
,08-29 13:44:39.643  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:44:39.643  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.643  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:39.643  1172  1172 D HotspotTile: updateTetherState():false, false
08-29 13:44:39.643  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:39.643  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:44:39.653  1017  1124 V NetworkStats: performPollLocked() took 4ms
08-29 13:44:39.653  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:39.653  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:39.653  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:39.663  7070  7070 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:39.663  7070  7070 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:39.693  7070  7070 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,08-29 13:44:39.693  1017  1480 I ActivityManager: Killing 6699:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-29 13:44:39.703  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:39.703  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:39.703  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
08-29 13:44:39.703  1017  1480 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-29 13:44:39.703  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:39.703  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:39.703  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:39.703  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:39.723  7085  7085 E Zygote  : MountEmulatedStorage(),
08-29 13:44:39.723  1017  1480 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7085 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-29 13:44:39.723  7085  7085 E Zygote  : v2
08-29 13:44:39.723  7085  7085 I libpersona: KNOX_SDCARD checking this for 10102
08-29 13:44:39.723  7085  7085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:39.723  7085  7085 I libpersona: KNOX_SDCARD not a persona,
,08-29 13:44:39.733  7085  7085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:39.733  7085  7085 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:44:39.753  7085  7085 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:39.753  7085  7085 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:39.773  7085  7085 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 13:44:39.833  1347  1347 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 13:44:39.953  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:39.953  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-29 13:44:39.963  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:39.963  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:39.963  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:39.973  1347  1347 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 13:44:39.973  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:39.973  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:44:39.973  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:40.033  7085  7105 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-29 13:44:40.033  7085  7105 I Babel_SMS: MmsConfig.loadMmsSettings
,08-29 13:44:40.033  7085  7105 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 13:44:40.033  7085  7105 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 13:44:40.063  7085  7105 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-29 13:44:40.063  7085  7105 I Babel_SMS: MmsConfig.loadFromResources
,08-29 13:44:40.063  7085  7105 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 13:44:40.063  7085  7105 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 13:44:40.073  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-29 13:44:40.073  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 13:44:40.083  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:40.083  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:44:40.083  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:44:40.083  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:40.083  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:40.083  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:40.083  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:40.083  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:40.083  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:40.083  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-29 13:44:40.083  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 13:44:40.093  1172  1172 D HotspotTile: onReceive : 1, 0
,08-29 13:44:40.093  4454  4454 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:40.093  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:40.093  1017  1323 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-29 13:44:40.093   288   288 E SMD     : DCD OFF
08-29 13:44:40.093  1017  1323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
08-29 13:44:40.093  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:40.093  1017  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:40.093  1017  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:40.093  1017  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 13:44:40.113  1746  2192 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:40.123  7085  7085 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:40.123  7085  7085 I Babel_Crash: startup - clean
,08-29 13:44:40.153  1017  3970 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:44:40.153  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:44:40.153  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.153  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.153  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:44:40.153  1609  1609 I Hs20UtilService: Starting #9
,08-29 13:44:40.153  1609  1651 I Hs20UtilService: Message received 5007
,08-29 13:44:40.153  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 13:44:40.153  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:44:40.153  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:44:40.163  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:44:40.163  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:40.163  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:44:40.163  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:44:40.163  1017  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:44:40.163  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:44:40.173  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.173  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.173  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:44:40.173  1609  1609 I Hs20UtilService: Starting #10
08-29 13:44:40.173  1609  1651 I Hs20UtilService: Message received 5011
,08-29 13:44:40.173  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:44:40.173  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:44:40.173  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 13:44:40.173  6860  6860 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:44:40.183  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
08-29 13:44:40.183  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-29 13:44:40.183  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 13:44:40.183  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=733)
,08-29 13:44:40.183  7085  7085 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 13:44:40.183  7085  7085 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 13:44:40.183  7085  7085 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 13:44:40.183  1017  1450 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.183  1017  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:40.183  1017  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.193  7085  7085 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-29 13:44:40.193  7085  7085 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-29 13:44:40.193  7085  7085 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 13:44:40.193  7085  7085 W AudioCapabilities: Unsupported mime audio/x-ima
,08-29 13:44:40.193  7085  7085 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 13:44:40.193  7085  7085 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 13:44:40.203  7085  7085 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 13:44:40.213  7085  7085 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 13:44:40.213  7085  7085 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-29 13:44:40.223  7085  7085 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 13:44:40.223  7085  7085 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 13:44:40.223  7085  7085 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-29 13:44:40.223  7085  7085 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-29 13:44:40.223  7085  7085 W VideoCapabilities: Unsupported mime video/mp43
,08-29 13:44:40.233  7085  7085 W VideoCapabilities: Unsupported mime video/sorenson
,08-29 13:44:40.233  7085  7085 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-29 13:44:40.243  7085  7085 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 13:44:40.253  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.253  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.253  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.253  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.253  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.253  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.253  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.253  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.253  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.253  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.253  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.253  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.263  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.263  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.263  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.263  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.263  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.263  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.263  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.263  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.263  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.273  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.273  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.273  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.273  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.273  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.273  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.273  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.273  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.273  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.273  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.273  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.273  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.283  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.283  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.283  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.283  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.283  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.283  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.283  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.283  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.283  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:44:40.283  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-29 13:44:40.283  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.283  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.293  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.293  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.303  7108  7108 E Zygote  : MountEmulatedStorage()
,08-29 13:44:40.303  7108  7108 E Zygote  : v2
08-29 13:44:40.303  7108  7108 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:44:40.303  7108  7108 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:40.303  7108  7108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:40.303  7085  7085 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
08-29 13:44:40.303  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7108 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:44:40.303  7085  7085 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-29 13:44:40.303  7108  7108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:40.303  7108  7108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:40.303  7085  7085 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 13:44:40.313  7085  7085 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 13:44:40.313  1017  3971 I ActivityManager: Killing 6730:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 13:44:40.313  7085  7085 I vclib   : onServiceConnected
,08-29 13:44:40.323  7108  7108 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:40.323  7108  7108 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:40.353  7108  7108 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-29 13:44:40.353  7108  7108 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 13:44:40.353  7108  7108 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 13:44:40.363  7108  7108 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-29 13:44:40.363  7108  7108 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 13:44:40.363  7108  7108 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-29 13:44:40.363  7108  7108 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:40.363  1017  1480 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
08-29 13:44:40.373  1017  1480 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-29 13:44:40.373  1017  1480 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-29 13:44:40.373  1017  1480 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-29 13:44:40.373  7108  7123 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-29 13:44:40.373  1017  1480 I ActivityManager: Killing 6752:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-29 13:44:40.373  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 13:44:40.383  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.383  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.383  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.383  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.393  7125  7125 E Zygote  : MountEmulatedStorage()
,08-29 13:44:40.393  7125  7125 E Zygote  : v2
08-29 13:44:40.393  7125  7125 I libpersona: KNOX_SDCARD checking this for 10001
08-29 13:44:40.393  7125  7125 I libpersona: KNOX_SDCARD not a persona,
08-29 13:44:40.393  7125  7125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:40.393  7125  7125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:40.393  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7125 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:40.393  7125  7125 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:40.413  7125  7125 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:40.413  7125  7125 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:40.463  1017  3970 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-29 13:44:40.463  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.463  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.463  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.463  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.483  7142  7142 E Zygote  : MountEmulatedStorage(),
08-29 13:44:40.483  7142  7142 E Zygote  : v2
08-29 13:44:40.483  7142  7142 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:44:40.483  7142  7142 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:40.483  7142  7142 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:40.483  1017  3970 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:44:40.483  1017  3970 I ActivityManager: Killing 6340:com.android.mms/u0a41 (adj 15): empty #21
,08-29 13:44:40.483  7142  7142 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:40.483  7142  7142 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:40.503  7142  7142 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:40.503  7142  7142 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:40.513   304   304 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 26.140ms
08-29 13:44:40.513  1017  2838 D SSRM:n  : SIOP:: AP = 400
,08-29 13:44:40.523   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.484ms
,08-29 13:44:40.543  7142  7142 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 13:44:40.543   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.221ms
,08-29 13:44:40.573  1017  1030 D CountryDetector: No listener is left
,08-29 13:44:40.663  7142  7142 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-29 13:44:40.673  7142  7142 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-29 13:44:40.673  7142  7142 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:40.673  7142  7142 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 13:44:40.673  7142  7142 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-29 13:44:40.673  7142  7142 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-29 13:44:40.673  1017  1078 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-29 13:44:40.673  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.673  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.673  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.673  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.693  7157  7157 E Zygote  : MountEmulatedStorage()
08-29 13:44:40.693  7157  7157 E Zygote  : v2
08-29 13:44:40.693  7157  7157 I libpersona: KNOX_SDCARD checking this for 10008
08-29 13:44:40.693  7157  7157 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:40.693  1017  1078 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7157 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:40.693  7157  7157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:40.693  1017  1078 I ActivityManager: Killing 6776:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-29 13:44:40.693  1017  1044 D Tethering: interfaceRemoved wlan0,
08-29 13:44:40.693  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
08-29 13:44:40.693  7157  7157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:40.693  7157  7157 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 13:44:40.713  7157  7157 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:40.713  7157  7157 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:40.783  1017  3971 I ActivityManager: Killing 6156:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 13:44:40.783  1017  1219 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-29 13:44:40.783  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 13:44:40.783  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.783  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:40.783  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 13:44:40.793  1937  1937 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 13:44:40.803  1937  4748 I iu.UploadsManager: num queued entries: 0
08-29 13:44:40.803  1017  1219 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:44:40.803  1937  4748 I iu.UploadsManager: num updated entries: 0
08-29 13:44:40.803  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-29 13:44:40.803  1937  4748 I iu.SyncManager: NEXT; no task
,08-29 13:44:40.803  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:40.803  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:40.803  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:44:40.803  1937  1937 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 13:44:40.813  1937  1937 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,08-29 13:44:40.823  2899  2899 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 13:44:40 GMT+02:00 2016
,08-29 13:44:40.823  1017  1493 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 13:44:40.823  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 13:44:40.823  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:40.823  1017  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:40.823  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 13:44:40.823  2899  2899 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 13:44:40.833  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 13:44:40.833  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.833  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.833  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.833  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.833  2899  2899 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 13:44:40.843  2899  2899 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 13:44:40.843  1017  1044 D Tethering: interfaceRemoved p2p0
08-29 13:44:40.843  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 13:44:40.843  2899  2899 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,08-29 13:44:40.843  2899  7173 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 13:44:40.843  7174  7174 E Zygote  : MountEmulatedStorage()
,08-29 13:44:40.843  7174  7174 E Zygote  : v2
08-29 13:44:40.853  7174  7174 I libpersona: KNOX_SDCARD checking this for 10031
08-29 13:44:40.853  7174  7174 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:40.853  7174  7174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 13:44:40.853  1017  1030 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7174 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,08-29 13:44:40.853  2899  7173 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 13:44:40.853  7174  7174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:40.853  7174  7174 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:40.863  2899  7173 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-29 13:44:40.863  2899  7173 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 13:44:40.863  2899  2899 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 13:44:40.883  7174  7174 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:40.883  7174  7174 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:40.913  7174  7174 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-29 13:44:40.923  1017  3967 I ActivityManager: Killing 6792:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-29 13:44:40.933  1017  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 13:44:40.933  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.933  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.933  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:40.933  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:40.933  3475  7189 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-29 13:44:40.953  3475  7189 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-29 13:44:40.953  3475  7189 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-29 13:44:40.953  7190  7190 E Zygote  : MountEmulatedStorage()
08-29 13:44:40.953  7190  7190 E Zygote  : v2
08-29 13:44:40.953  7190  7190 I libpersona: KNOX_SDCARD checking this for 10032
,08-29 13:44:40.953  7190  7190 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:40.953  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:40.953  3475  7189 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-29 13:44:40.953  3475  7189 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-29 13:44:40.953  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:40.963  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-29 13:44:40.963  1017  1480 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7190 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:40.983  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:40.983  7190  7190 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:41.043  7190  7205 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-29 13:44:41.043  7190  7205 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 13:44:41.043  7190  7190 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-29 13:44:41.053  7190  7205 D SPPClientService: PushLog.txt file is not deleted.
08-29 13:44:41.053  7190  7205 D SPPClientService: PushLog.txt file is not deleted.
,08-29 13:44:41.053  1017  1450 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-29 13:44:41.053  7190  7205 D SPPClientService: ============PushLog. stop!
,08-29 13:44:41.053  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:41.053  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:41.053  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:41.053  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:41.073  7207  7207 E Zygote  : MountEmulatedStorage(),
,08-29 13:44:41.073  7207  7207 E Zygote  : v2
08-29 13:44:41.073  7207  7207 I libpersona: KNOX_SDCARD checking this for 10036
,08-29 13:44:41.073  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:41.073  7207  7207 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:41.073   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:44:41.073  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:41.073  1017  1450 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7207 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:44:41.083  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 13:44:41.083  1017  1450 I ActivityManager: Killing 6808:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-29 13:44:41.083  1017  1504 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-29 13:44:41.083  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-29 13:44:41.083  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:41.083  1017  1504 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 13:44:41.083  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-29 13:44:41.093  7190  7216 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-29 13:44:41.103  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:41.103  7207  7207 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:41.143  7207  7207 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3df0ce59
,08-29 13:44:41.153  7207  7207 I SA      : [SSP] onCreated
,08-29 13:44:41.163  7207  7207 I SA      : [TPM] There is no property file
,08-29 13:44:41.173  7207  7207 I SA      : [SCU] isHaveSA() - false
,08-29 13:44:41.173  7207  7207 I SA      : [TPM] getModelProperty : null
,08-29 13:44:41.173  7207  7207 I SA      : [TPM] getCSCProperty : null
,08-29 13:44:41.173  7207  7207 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-29 13:44:41.173  7207  7207 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 13:44:41.173  7207  7207 I SA      : [DM] TFT FEATURE: false
,08-29 13:44:41.183  7207  7207 I SA      : [DM] init START
,08-29 13:44:41.193  7207  7207 I SA      : [DM] This device is not a Vodafone
,08-29 13:44:41.203  7207  7207 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-29 13:44:41.203  7207  7207 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 13:44:41.203  7207  7207 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-29 13:44:41.203  7207  7207 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-29 13:44:41.203  7207  7207 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-29 13:44:41.203  7207  7207 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-29 13:44:41.203  7207  7207 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-29 13:44:41.213  7207  7207 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-29 13:44:41.223  7207  7207 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-29 13:44:41.223  7207  7207 I SA      : [SCU] isHaveSA() - false
08-29 13:44:41.223  7207  7207 I SA      : support phone number id : false
08-29 13:44:41.223  7207  7207 I SA      : [DM] Supports Ref Jpn : true
,08-29 13:44:41.233  7207  7207 I SA      : [DM] init END
,08-29 13:44:41.233  7207  7207 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 13:44:41.233  7207  7207 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-29 13:44:41.233  7207  7207 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 13:44:41.233  7207  7207 I SA      : [SLFUCHKMGR] constructor called
,08-29 13:44:41.243  7207  7207 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 13:44:41.243  7207  7207 I SA      : [OR] == isSIMCardReady false ==
,08-29 13:44:41.243  7207  7207 I SA      : [SCU] == networkStateCheck == false
,08-29 13:44:41.253  7207  7207 I SA      : [OR] onReceive END,
,08-29 13:44:41.253  1017  1504 I ActivityManager: Killing 6892:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-29 13:44:41.263  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:41.263  1783  1783 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 13:44:41.273  2498  2507 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-29 13:44:41.273  1783  1783 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 13:44:41.273  1783  1783 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-29 13:44:41.273  1783  1783 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-29 13:44:41.273  1783  1783 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-29 13:44:41.283  1783  1783 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 13:44:41.283  1783  1783 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 13:44:41.283  1017  1493 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-29 13:44:41.283  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:41.283  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:41.293  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:41.293  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:41.303  1017  1493 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7229 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-29 13:44:41.303  7229  7229 E Zygote  : MountEmulatedStorage()
08-29 13:44:41.303  7229  7229 E Zygote  : v2
,08-29 13:44:41.303  7229  7229 I libpersona: KNOX_SDCARD checking this for 10077
08-29 13:44:41.303  7229  7229 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:41.303  7229  7229 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:41.303  7229  7229 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:44:41.313  7229  7229 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-29 13:44:41.323  7229  7229 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-29 13:44:41.323  7229  7229 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:41.443  1017  3967 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-29 13:44:41.443  1017  3967 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 13:44:41.443  1017  3967 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:41.443  1017  3967 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:41.443  1017  3967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 13:44:41.443  1017  1487 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-29 13:44:41.443  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:41.443  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:41.443  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:41.443  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:41.463  7247  7247 E Zygote  : MountEmulatedStorage()
08-29 13:44:41.463  7247  7247 I libpersona: KNOX_SDCARD checking this for 10110
08-29 13:44:41.463  7247  7247 E Zygote  : v2
08-29 13:44:41.463  7247  7247 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:41.463  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:41.463  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 13:44:41.463  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:44:41.473  1017  1487 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7247 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:41.483  1017  3977 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 13:44:41.483  1017  3977 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 13:44:41.483  1017  3977 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:41.483  1017  3977 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:41.483  1017  3977 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 13:44:41.483  7085  7246 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 13:44:41.493  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:41.493  7247  7247 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:41.493  1017  3971 I ActivityManager: Killing 6907:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-29 13:44:41.553  1017  1219 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 13:44:41.623  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 13:44:41.633   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 13:44:41.633   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:44:41.633  7247  7265 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 13:44:41.643   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 13:44:41.643   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:44:41.643  7247  7265 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
08-29 13:44:41.643  7247  7247 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 13:44:41.643  7247  7247 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 13:44:41.643  7247  7247 I GAv4    :   adb logcat -s GAv4
,08-29 13:44:41.663   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 13:44:41.663   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:44:41.663  7247  7267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 13:44:41.663  7247  7247 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:44:41.663  1017  3977 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 13:44:41.663   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 13:44:41.663   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:44:41.663  7247  7267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 13:44:41.683  7247  7247 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:44:41.703  7247  7268 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:44:41.773  1017  3967 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 13:44:41.773  1017  3967 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 13:44:41.773  1017  3967 D SecContentProvider2: mCursor = null
,08-29 13:44:41.773  1017  3967 D WifiService: setWifiEnabled: true pid=6633, uid=10170
08-29 13:44:41.773  1017  3967 W ActivityManager: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:44:41.773  1017  3967 W WifiService: Failed getting userId using ActivityManagerNative
08-29 13:44:41.773  1017  3967 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:44:41.773  1017  3967 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:44:41.773  1017  3967 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 13:44:41.773  1017  3967 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 13:44:41.773  1017  3967 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 13:44:41.773  1017  3967 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 13:44:41.773  1017  3967 D SettingsProvider: name = wifi_on
,08-29 13:44:41.783  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 13:44:41.893  1017  1078 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:44:41.903  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:41.903  1017  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:41.903  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-29 13:44:41.923  7247  7247 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-29 13:44:41.933  7247  7247 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 4675-4677)
08-29 13:44:41.933  7247  7247 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 13:44:41.943  7247  7247 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25836a78}
,08-29 13:44:41.943  7247  7247 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 13:44:41.943  7247  7247 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 13:44:41.963  7247  7247 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 13:44:41.963  7247  7247 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:44:41.973  7247  7247 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 13:44:41.983  7247  7247 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 13:44:41.983  7247  7247 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 13:44:41.983  7247  7247 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 13:44:41.983  7247  7247 I Adreno-EGL: Local Branch: 
08-29 13:44:41.983  7247  7247 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 13:44:41.983  7247  7247 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 13:44:41.983  7247  7247 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 13:44:42.053  7247  7247 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 13:44:42.053  7247  7303 W cr.media: Requires BLUETOOTH permission
,08-29 13:44:42.063  7247  7247 I NSApplication: Starting up...
,08-29 13:44:42.063  1017  1078 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 13:44:42.063  1017  1447 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 13:44:42.073  1017  1487 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-29 13:44:42.073  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.073  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.073  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.073  1017  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.073   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:44:42.083  1017  1487 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7308 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-29 13:44:42.093  7308  7308 E Zygote  : MountEmulatedStorage()
08-29 13:44:42.093  7308  7308 I libpersona: KNOX_SDCARD checking this for 10117
08-29 13:44:42.093  7308  7308 E Zygote  : v2
08-29 13:44:42.093  7308  7308 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:42.093  7308  7308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:42.093  1017  1487 I ActivityManager: Killing 6872:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-29 13:44:42.093  7308  7308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:42.103  7308  7308 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:44:42.143  7308  7308 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:42.143  7308  7308 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:42.143  1017  1044 D Tethering: interfaceAdded wlan0
,08-29 13:44:42.163  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:44:42.163  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:42.163  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:42.173  1017  1132 E Tethering: No numeric data
,08-29 13:44:42.173  1017  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 13:44:42.173  1017  1132 D Tethering: clearTetheredNotification()
08-29 13:44:42.173  7308  7308 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:44:42.173  1017  1132 D Tethering: InitialState.processMessage what=4
08-29 13:44:42.173  1017  1044 D Tethering: interfaceAdded p2p0,
08-29 13:44:42.173  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:42.173  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-29 13:44:42.173  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:42.173  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:44:42.183   278  1003 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-29 13:44:42.183   278  1003 D SoftapController: Softap fwReload - Ok
,08-29 13:44:42.183  1017  1132 E Tethering: No numeric data
08-29 13:44:42.183  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-29 13:44:42.183  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring,
,08-29 13:44:42.183  1172  1172 D HotspotTile: updateTetherState():false, false
08-29 13:44:42.183  1017  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:44:42.183  1017  1124 V NetworkStats: performPollLocked() took 10ms
08-29 13:44:42.183  1017  1132 D Tethering: clearTetheredNotification()
08-29 13:44:42.183  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-29 13:44:42.183  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:42.183  1172  1172 D HotspotTile: updateTetherState():false, false
08-29 13:44:42.183   278  1003 D CommandListener: Setting iface cfg
08-29 13:44:42.183  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 13:44:42.183   278  1003 D CommandListener: Trying to bring down wlan0
08-29 13:44:42.183  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 13:44:42.183  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-29 13:44:42.183   278  1003 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:44:42.193  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:44:42.183  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:42.183  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:42.193  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:42.193  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
08-29 13:44:42.193  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:42.193  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:44:42.193  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 13:44:42.193  1017  1124 V NetworkStats: performPollLocked() took 4ms
,08-29 13:44:42.203  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:42.203  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-29 13:44:42.233  7324  7324 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-29 13:44:42.233  7324  7324 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 13:44:42.233  7324  7324 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 13:44:42.253  7324  7324 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-29 13:44:42.253   349   349 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7324,
08-29 13:44:42.253   349   349 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-29 13:44:42.253  7324  7324 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 13:44:42.253  7324  7324 I wpa_supplicant: ssSupport state is = 1,
08-29 13:44:42.253  7324  7324 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-29 13:44:42.253  7324  7324 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 13:44:42.253   349   349 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7324
08-29 13:44:42.253   349   349 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106,
,08-29 13:44:42.293  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-29 13:44:42.303  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:42.313  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:44:42.313  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:44:42.313  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:42.313  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:42.313  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:42.313  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 13:44:42.313  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:42.313  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-29 13:44:42.313  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:42.313  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2),
08-29 13:44:42.313  1172  1172 D HotspotTile: onReceive : 2, 0,
08-29 13:44:42.313  4454  4454 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:42.313  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 13:44:42.323  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 13:44:42.423   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-29 13:44:42.433  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-29 13:44:42.483  7324  7324 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 13:44:42.483  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 13:44:42.483  1017  1450 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 13:44:42.483  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.483  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.483  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:44:42.483  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.493  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 13:44:42.493   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7324
08-29 13:44:42.493   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 13:44:42.493  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 13:44:42.493  7324  7324 I wpa_supplicant: ssSupport state is = 1
,08-29 13:44:42.493  7324  7324 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 13:44:42.493  7324  7324 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:44:42.493  7324  7324 E wpa_supplicant: SIM READ ERROR
08-29 13:44:42.493  7324  7324 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:42.493  7324  7324 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 13:44:42.493  7324  7324 E wpa_supplicant: SIM READ ERROR
08-29 13:44:42.493  7324  7324 I wpa_supplicant: Blacklist: Clear (all) 
08-29 13:44:42.493  7324  7324 I wpa_supplicant: wpa_default_ap_write_once
08-29 13:44:42.493  7324  7324 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-29 13:44:42.493  7324  7324 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:42.493  7324  7324 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 13:44:42.493  7324  7324 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:42.493  7324  7324 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 13:44:42.503  7324  7324 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-29 13:44:42.503  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 13:44:42.503  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:44:42.503  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:42.513  7335  7335 E Zygote  : MountEmulatedStorage(),
08-29 13:44:42.513  7335  7335 E Zygote  : v2
08-29 13:44:42.513  7335  7335 I libpersona: KNOX_SDCARD checking this for 10121
,08-29 13:44:42.513  7335  7335 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:42.513  1017  1450 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7335 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 13:44:42.513  1017  1450 I ActivityManager: Killing 6824:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21,
,08-29 13:44:42.523  7335  7335 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:42.523  7335  7335 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:42.523  7335  7335 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:42.543  7335  7335 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:42.543  7335  7335 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:42.563  7335  7335 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:44:42.563  7335  7335 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 13:44:42.563  7335  7335 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:44:42.573  7335  7335 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:44:42.573  7335  7335 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 13:44:42.583  7335  7335 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-29 13:44:42.583  7324  7324 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-29 13:44:42.583  1017  1078 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-29 13:44:42.583  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.583  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.583  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.583  1017  1078 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.593  7350  7350 E Zygote  : MountEmulatedStorage()
,08-29 13:44:42.593  7350  7350 E Zygote  : v2,
08-29 13:44:42.593  7350  7350 I libpersona: KNOX_SDCARD checking this for 10141
08-29 13:44:42.593  7350  7350 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:42.603  7350  7350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:42.603  7350  7350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:44:42.603  7350  7350 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:44:42.603  1017  1078 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7350 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-29 13:44:42.603  1017  1078 I ActivityManager: Killing 6840:com.android.calendar/u0a131 (adj 15): empty #21
,08-29 13:44:42.623  7350  7350 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:42.623  7350  7350 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:42.643  7350  7350 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-29 13:44:42.643  7350  7350 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:44:42.643  7350  7350 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:44:42.643  7350  7350 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 13:44:42.703  1017  1078 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:44:42.723  1017  3977 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:44:42.753  1017  1323 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:44:42.763  1017  1450 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:44:42.803  1017  3970 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-29 13:44:42.803  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.803  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.803  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.803  1017  3970 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.813  7324  7324 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 13:44:42.813  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
08-29 13:44:42.823  1017  1447 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:44:42.823  7374  7374 E Zygote  : MountEmulatedStorage()
,08-29 13:44:42.823  7374  7374 E Zygote  : v2
08-29 13:44:42.823  7374  7374 I libpersona: KNOX_SDCARD checking this for 10068
08-29 13:44:42.823  7374  7374 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:42.823  7374  7374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:44:42.833  7374  7374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:44:42.833  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-29 13:44:42.833  1017  1450 D RCPManagerService: exchangeData() failure , invalid userId
08-29 13:44:42.833   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7324
08-29 13:44:42.833   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 13:44:42.833  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 13:44:42.833  7324  7324 I wpa_supplicant: ssSupport state is = 1
08-29 13:44:42.833  1017  3970 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7374 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-29 13:44:42.833  7374  7374 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 13:44:42.853  7374  7374 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:42.853  7374  7374 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:42.863  7324  7324 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-29 13:44:42.863  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 13:44:42.873  7374  7374 D BadgeProvider: onCreate
08-29 13:44:42.873  7374  7374 D BadgeProvider: DatabaseHelper
,08-29 13:44:42.873  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 13:44:42.883   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7324
08-29 13:44:42.883   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 13:44:42.883  7324  7324 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 13:44:42.883  7324  7324 I wpa_supplicant: ssSupport state is = 1
08-29 13:44:42.883  7324  7324 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:42.883  7324  7324 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:44:42.883  7324  7324 E wpa_supplicant: SIM READ ERROR
08-29 13:44:42.883  7324  7324 I wpa_supplicant: wpa_default_ap_write_once
08-29 13:44:42.883  7324  7324 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 13:44:42.883  7324  7324 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:44:42.883  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 13:44:42.883  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 13:44:42.883  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:44:42.883  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 13:44:42.883  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:44:42.883  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:44:42.893  1017  3977 D RCPManagerService: exchangeData() failure , invalid userId
08-29 13:44:42.893  7374  7384 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
08-29 13:44:42.893  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-29 13:44:42.903  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.903  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.903  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:42.903  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:42.913  7324  7324 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 13:44:42.913  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 13:44:42.913  7390  7390 E Zygote  : MountEmulatedStorage(),
08-29 13:44:42.913  1017  1030 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7390 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-29 13:44:42.913  7390  7390 E Zygote  : v2
08-29 13:44:42.913  7390  7390 I libpersona: KNOX_SDCARD checking this for 10009
08-29 13:44:42.913  7390  7390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:42.913  7390  7390 I libpersona: KNOX_SDCARD not a persona
08-29 13:44:42.913  1017  1030 I ActivityManager: Killing 6934:com.android.vending/u0a26 (adj 15): empty #21
08-29 13:44:42.913  1017  1030 I ActivityManager: Killing 6648:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-29 13:44:42.913  7390  7390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:44:42.923  7390  7390 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 13:44:42.923  7374  7386 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-29 13:44:42.923  7374  7386 D BadgeProvider: sendNotify, [notify] : null
08-29 13:44:42.923  7374  7386 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-29 13:44:42.923  7374  7386 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-29 13:44:42.923  7374  7386 D BadgeProvider: update, [UpdateCount] : 1
08-29 13:44:42.923  1488  1488 D Launcher.Model: reloadBadges entered.
,08-29 13:44:42.953  7390  7390 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:44:42.953  7390  7390 D ActivityThread: Added TimaKeyStore provider
08-29 13:44:42.953   304   304 I art     : Explicit concurrent mark sweep GC freed 8667(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 43.339ms
,08-29 13:44:42.973   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.961ms,
,08-29 13:44:42.993   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 17.062ms
08-29 13:44:42.993  7324  7324 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-29 13:44:42.993  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 13:44:42.993  7324  7324 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 13:44:43.003  1017  2857 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 13:44:43.003  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-29 13:44:43.003  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 13:44:43.003  7324  7324 I wpa_supplicant: HOTSPOT20_ENABLE called
08-29 13:44:43.003  7324  7324 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:43.003  7324  7324 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:44:43.003  7324  7324 E wpa_supplicant: SIM READ ERROR
08-29 13:44:43.003  7324  7324 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 13:44:43.033  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:44:43.033  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:44:43.033  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:43.033  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:43.033  7324  7324 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 13:44:43.043  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
08-29 13:44:43.043  1609  1609 I Hs20UtilService: Starting #11
,08-29 13:44:43.043  1609  1651 I Hs20UtilService: Message received 5011
,08-29 13:44:43.043  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:44:43.043  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:44:43.043  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 13:44:43.043  6860  6860 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:44:43.053  7324  7324 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 13:44:43.073  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-29 13:44:43.073   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:44:43.083  4454  4454 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:43.083  1017  1127 E WifiConfigStore: Not a HS20
,08-29 13:44:43.083  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:43.083  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:43.083  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:44:43.083  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:43.083  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:43.083  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:43.083  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:43.083  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:43.083  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 13:44:43.083  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:43.083  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 13:44:43.083  1017  3970 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:44:43.083  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:44:43.083  1172  1172 D HotspotTile: onReceive : 3, 0
,08-29 13:44:43.083  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:43.083  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:43.083  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:44:43.083  1609  1609 I Hs20UtilService: Starting #12
,08-29 13:44:43.093  1609  1651 I Hs20UtilService: Message received 5011
,08-29 13:44:43.093  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:43.093  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:43.093  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:43.093  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:43.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:43.093  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-29 13:44:43.093  1017  3971 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
08-29 13:44:43.093   288   288 E SMD     : DCD OFF
,08-29 13:44:43.093  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:43.093  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:43.093  1017  1493 I art     : Explicit concurrent mark sweep GC freed 61793(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 23MB/34MB, paused 2.751ms total 168.272ms
,08-29 13:44:43.103  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 13:44:43.103  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:44:43.103  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 13:44:43.103  7324  7324 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 13:44:43.103  7324  7324 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 13:44:43.103  7324  7324 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 13:44:43.103  7324  7324 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 13:44:43.103  7324  7324 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 13:44:43.103  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 13:44:43.103  7324  7324 I wpa_supplicant: First Scan Start
,08-29 13:44:43.103  7324  7324 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-29 13:44:43.103  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-29 13:44:43.103  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:44:43.103  1017  1127 I WifiNative-HAL: startHal
08-29 13:44:43.103  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9e97488c
08-29 13:44:43.103  1017  1127 I WifiNative-HAL: Could not start hal
,08-29 13:44:43.103  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:44:43.103  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:44:43.103  6860  6860 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:44:43.103  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-29 13:44:43.103  1017  1127 E WifiNative-wlan0: do suspend true
08-29 13:44:43.103  7085  7085 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:43.113  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 13:44:43.113   278  1003 D CommandListener: Setting iface cfg
08-29 13:44:43.113   278  1003 D CommandListener: Trying to bring up p2p0
,08-29 13:44:43.113  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 13:44:43.113  1017  1126 D WifiP2pService: P2pEnablingState
,08-29 13:44:43.113  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 13:44:43.113  1017  1126 D WifiP2pService: P2p socket connection successful
,08-29 13:44:43.113  1017  1126 D WifiP2pService: P2pEnabledState
,08-29 13:44:43.113  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-29 13:44:43.113  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 13:44:43.123  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-29 13:44:43.123  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-29 13:44:43.123  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 13:44:43.123  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 13:44:43.123  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 13:44:43.123  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 13:44:43.123  1017  1127 E WifiNative-wlan0: invaild command id : 215
,08-29 13:44:43.123  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:44:43.123  1017  1047 D WifiDisplayController: disconnect
,08-29 13:44:43.123  1017  1047 D WifiDisplayController: updateConnection
08-29 13:44:43.123  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:44:43.123  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 13:44:43.123  1017  1017 D RttService: SCAN_AVAILABLE : 3
,08-29 13:44:43.123  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:43.123  1017  1151 I WifiNative-HAL: startHal
08-29 13:44:43.123  1017  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:44:43.123  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x990199bc
08-29 13:44:43.123  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:44:43.123  1017  1151 I WifiNative-HAL: Could not start hal
08-29 13:44:43.123  1017  1151 E WifiScanningService: could not start HAL
08-29 13:44:43.123  1017  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:43.123  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:43.123  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:43.123  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:44:43.123  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 13:44:43.123  7324  7324 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:44:43.123  7324  7324 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:44:43.123  1609  1609 I Hs20UtilService: Starting #13
08-29 13:44:43.123  1609  1651 I Hs20UtilService: Message received 5011
08-29 13:44:43.133  7324  7324 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-29 13:44:43.133  1017  1127 E WifiStateMachine: Failed to set frequency band 0
,08-29 13:44:43.133  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:44:43.133  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:43.133  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 13:44:43.133  1017  1450 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 13:44:43.133  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 13:44:43.133  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 13:44:43.133  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 13:44:43.133  1017  1127 E WifiNative-wlan0: invaild command id : 215
,08-29 13:44:43.133  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:44:43.133  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:43.133  1017  3971 I ActivityManager: Killing 6984:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-29 13:44:43.133  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:43.133  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:44:43.133  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:44:43.133  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 13:44:43.143  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-29 13:44:43.143  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-29 13:44:43.143  1017  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,08-29 13:44:43.143  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  secondary type: null
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  wps: 0
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  grpcapab: 0
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  devcapab: 0
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  status: 3
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  wfdInfo: null
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-29 13:44:43.143  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-29 13:44:43.143  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 13:44:43.143  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:44:43.143  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:44:43.143  6860  6860 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:44:43.153  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 13:44:43.153  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 13:44:43.153  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:44:43.153  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:44:43.153  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:44:43.153  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:44:43.163  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 13:44:43.163  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:43.163  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
08-29 13:44:43.163  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:44:43.163  1017  1126 D WifiP2pService: InactiveState
08-29 13:44:43.163  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 13:44:43.163  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
08-29 13:44:43.163  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 13:44:43.163  7324  7324 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 13:44:43.163  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 13:44:43.163  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
08-29 13:44:43.163  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
08-29 13:44:43.163  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 13:44:43.163  7039  7039 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 13:44:43.173  7070  7070 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:44:43.273  1017  3967 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-29 13:44:43.273  1017  3967 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4215, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 13:44:43.273  1017  3967 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 13:44:43.273  1017  3967 D BatteryService: stay LED for charging,
08-29 13:44:43.273  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-29 13:44:43.273  1017  1017 I MotionRecognitionService: Plugged
08-29 13:44:43.273  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 13:44:43.283  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-29 13:44:43.283  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 13:44:43.283  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 13:44:43.283  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 13:44:43.303  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:43.303  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:43.303  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:43.443  5868  5868 D FactoryTest: Not factory mode
,08-29 13:44:43.443  5868  5868 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-29 13:44:43.443  5868  5868 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-29 13:44:43.443  5868  5868 D MTPRx   : still no open session command from host, so toast
,08-29 13:44:43.443  5868  5868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
,08-29 13:44:43.443  5868  5868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-29 13:44:43.443  5868  5868 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116189
,08-29 13:44:43.453  1017  3977 E PersonaManagerService: inState():  stateMachine is null !!
08-29 13:44:43.453  1017  3977 I PersonaManagerService: PersonaId don't exist
08-29 13:44:43.453  1017  3977 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-29 13:44:43.453  1017  3977 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-29 13:44:43.453  1017  3977 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:43.453  1017  3977 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:43.453  1017  3977 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-29 13:44:43.463  1017  3977 W ActivityManager: mDVFSHelper.acquire()
,08-29 13:44:43.473  1017  3977 D PersonaManager: isKioskContainerExistOnDevice
,08-29 13:44:43.493  1017  3977 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 13:44:43.493  1017  3977 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 13:44:43.493  1017  3977 D InputDispatcher: Focused application set to: xxxx
,08-29 13:44:43.493  1017  3977 D InputDispatcher: Focus left window: 6633
,08-29 13:44:43.493  5868  5868 E MTPRx   : started activity for popup
,08-29 13:44:43.493  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 13:44:43.493  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 13:44:43.523  5868  5868 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-29 13:44:43.523  5868  5868 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 13:44:43.523  5868  5868 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 13:44:43.523  5868  5868 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:44:43.523  5868  5868 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:44:43.523  5868  5868 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:44:43.543  5868  5868 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-29 13:44:43.553  1017  1504 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 13:44:43.553  1017  1504 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 13:44:43.553  1017  1504 D InputDispatcher: Focused application set to: xxxx
,08-29 13:44:43.553  1017  1504 D InputDispatcher: Focus entered window: 6633
,08-29 13:44:43.553  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 13:44:43.553  1017  1487 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 13:44:43.553  1017  1487 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2675823d attribute=null, token = android.os.BinderProxy@287b7c11
,08-29 13:44:43.553  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 13:44:43.593  5868  5868 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-29 13:44:43.603  5868  5868 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-29 13:44:43.603  5868  5868 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-29 13:44:43.623  6633  6633 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 13:44:43.623  6633  6633 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-29 13:44:43.623  6633  6633 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-29 13:44:43.623  6633  6633 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-29 13:44:43.623  1017  3971 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 13:44:43.623  1017  3971 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 13:44:43.623  1017  3971 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 13:44:43.623  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-29 13:44:43.623  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 13:44:43.643  6633  6633 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-29 13:44:43.643  6633  6633 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 13:44:43.643  6633  6633 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@22f271a6 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2de379eb, 16908290=android.view.AbsSavedState$1@2de379eb}, android:focusedViewId=100}]}]
08-29 13:44:43.643  6633  6633 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 13:44:43.643  6633  6633 V ActivityThread: updateVisibility : ActivityRecord{33258a71 token=android.os.BinderProxy@2375a58a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-29 13:44:43.643  6633  6633 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 13:44:43.643  6633  6633 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 13:44:43.643  6633  6633 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2375a58a time:116387
,08-29 13:44:43.643  1017  3970 D PersonaManager: isKioskContainerExistOnDevice
,08-29 13:44:44.073   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:44:44.323  7324  7324 I wpa_supplicant: nl80211: Received scan results (19 BSSes),
08-29 13:44:44.323  7324  7324 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 13:44:44.323  7324  7324 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 13:44:44.323  7324  7324 I wpa_supplicant: Trying to associate with  'G700'
08-29 13:44:44.323  7324  7324 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 13:44:44.323  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-29 13:44:44.323  1017  7405 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 13:44:44.333  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:44:44.333  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:44.433  7324  7324 E wpa_supplicant: Cmd 35605 not handled
,08-29 13:44:44.433  7324  7324 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 13:44:44.433  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 13:44:44.433  7324  7324 I wpa_supplicant: Associated with F4.99.3E
08-29 13:44:44.433  7324  7324 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-29 13:44:44.433  7324  7324 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 13:44:44.433  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-29 13:44:44.433  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:44:44.433  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:44.433  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:44.433  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:44:44.433  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:44.433  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:44.433  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 13:44:44.433  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-29 13:44:44.433  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-29 13:44:44.433  1017  1132 E Tethering: No numeric data
08-29 13:44:44.433  1017  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 13:44:44.433  1017  1132 D Tethering: clearTetheredNotification()
,08-29 13:44:44.443  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-29 13:44:44.443  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:44:44.443  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:44.443  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:44.443  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:44:44.443  1172  1172 D HotspotTile: updateTetherState():false, false,
,08-29 13:44:44.443  7324  7324 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 13:44:44.443  1017  1124 V NetworkStats: performPollLocked() took 3ms
08-29 13:44:44.443  7324  7324 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 13:44:44.443  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 13:44:44.443  7324  7324 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 13:44:44.443  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 13:44:44.443  7324  7324 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 13:44:44.443  7324  7324 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 13:44:44.443  7324  7324 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 13:44:44.443  7324  7324 I wpa_supplicant: Blacklist: Clear (temp) ,
08-29 13:44:44.443  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030,
08-29 13:44:44.443  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:44.443  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,08-29 13:44:44.443  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-29 13:44:44.443  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:44:44.443  1017  1127 D SecContentProvider2: mCursor = null
08-29 13:44:44.443  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 13:44:44.443  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:44.443  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-29 13:44:44.453  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-29 13:44:44.453  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 13:44:44.453  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 13:44:44.453  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:44:44.453  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 13:44:44.463  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:44.463  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:44.463  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:44:44.463  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:44:44.463  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.463  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.463  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.463  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:44.463  1017  3977 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:44:44.463  1017  3977 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,08-29 13:44:44.463  1017  3977 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:44.463  1017  3977 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:44.463  1017  3977 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:44:44.473  1609  1609 I Hs20UtilService: Starting #14
08-29 13:44:44.473  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:44.473  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 13:44:44.473  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:44:44.473  1609  1651 I Hs20UtilService: Message received 5007
,08-29 13:44:44.473  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:44:44.473  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:44:44.473  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:44.473  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:44:44.473  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:44:44.483   278  1003 D CommandListener: Setting iface cfg,
08-29 13:44:44.483  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-29 13:44:44.483  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:44:44.483  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:44.493  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:44:44.493  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:44.493  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:44.503  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:44.503  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 13:44:44.503  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:44.503  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.503  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.503  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:44.503  1017  1127 E WifiNative-wlan0: do suspend false
,08-29 13:44:44.503  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:44:44.503  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:44.503  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-29 13:44:44.503  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 13:44:44.713  7416  7416 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 13:44:44.723  7416  7416 I dhcpcd  : version 5.5.6 starting,
,08-29 13:44:44.723  7416  7416 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 13:44:44.773  7416  7416 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 13:44:44.773  7416  7416 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 13:44:44.773  7416  7416 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-29 13:44:44.783  7416  7416 I dhcpcd  : bssid match
,08-29 13:44:44.783  7416  7416 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-29 13:44:44.783  1017  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-29 13:44:44.783  1017  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 13:44:44.783  1017  1029 D SecContentProvider2: mCursor = null,
08-29 13:44:44.783  1017  1029 D WifiService: setWifiEnabled: false pid=6633, uid=10170
,08-29 13:44:44.783  1017  1029 D SettingsProvider: name = wifi_on
,08-29 13:44:44.793  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:44:44.843  7416  7416 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-29 13:44:44.873  1017  1127 E WifiNative-wlan0: do suspend true
,08-29 13:44:44.883  7416  7416 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
,08-29 13:44:44.913  1017  1126 D WifiP2pService: InactiveState{ what=143375 },
08-29 13:44:44.913  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 13:44:44.913  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-29 13:44:44.913  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:44:44.913  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:44:44.913  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.913  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:44.913  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.913  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.913   278  1003 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:44:44.923  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:44:44.923  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:44:44.923  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:44:44.923  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-29 13:44:44.923   278  1003 E Netd    : no such netId 503
,08-29 13:44:44.923  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 13:44:44.923  1017  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-29 13:44:44.923  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:44.923  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 13:44:44.923  1017  1129 V NetworkStats: updateIfacesLocked()
08-29 13:44:44.923  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-29 13:44:44.933  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:44.933  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:44:44.933  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:44:44.933  1017  1126 D WifiP2pService: InactiveState{ what=131204 },
08-29 13:44:44.933  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 13:44:44.933  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-29 13:44:44.933  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:44:44.933  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-29 13:44:44.933  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:44:44.933  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:44.933  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 13:44:44.933  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:44.933  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.933  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:44:44.933  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:44.933  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:44:44.933  1017  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:44.933  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 13:44:44.933  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-29 13:44:44.933  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:44:44.933  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:44:44.933  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:44:44.933  1017  1152 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:44.933  1017  1129 V NetworkStats: performPollLocked() took 11ms
08-29 13:44:44.933  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:44.943  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-29 13:44:44.933  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:44.943  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 13:44:44.933  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:44:44.943  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 13:44:44.933  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:44.943  1017  7414 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:44.943  1017  7414 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-29 13:44:44.943  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 13:44:44.943  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 13:44:44.943  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:44:44.943  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:44.943  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:44.943  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:44:44.943  1609  1609 I Hs20UtilService: Starting #15
08-29 13:44:44.943  1609  1651 I Hs20UtilService: Message received 5007
,08-29 13:44:44.943  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 13:44:44.943  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:44:44.943  1017  1047 D WifiDisplayController: disconnect
08-29 13:44:44.943  1017  1047 D WifiDisplayController: updateConnection
08-29 13:44:44.943  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:44:44.943  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 13:44:44.943  1017  1126 D WifiP2pService: P2pDisablingState
08-29 13:44:44.943  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-29 13:44:44.943  1017  1126 D WifiP2pService: p2p socket connection lost
,08-29 13:44:44.943  1017  1126 D WifiP2pService: P2pDisabledState
08-29 13:44:44.943  1017  1127 E WifiNative-wlan0: do suspend true
08-29 13:44:44.943  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 13:44:44.953  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 13:44:44.953  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:44:44.953  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:44:44.953  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 13:44:44.953  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 13:44:44.953  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:44:44.953  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:44:44.953  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 13:44:44.953  1017  1078 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 13:44:44.963  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:44:44.953  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-29 13:44:44.963  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:44.963  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:44:44.963  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:44:44.973  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:44:44.973  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 13:44:44.973  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 13:44:44.973  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:44:44.973  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:44.973  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:44:44.973  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:44:44.973  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
08-29 13:44:44.973  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 13:44:44.973  7039  7039 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 13:44:44.983  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-29 13:44:44.983  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-29 13:44:44.983  7070  7070 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
08-29 13:44:44.983   278  1003 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:44:44.993  7324  7324 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 13:44:44.993  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 13:44:44.993  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-29 13:44:44.993  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:44.993  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:44:44.993  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.993  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.993  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:44.993  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:45.003  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:44:45.003  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:45.013  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:45.013  4454  4454 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:45.013  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.013  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.013  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:45.013  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-29 13:44:45.023  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:45.023  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 13:44:45.023  1172  1172 D HotspotTile: onReceive : 0, 0
,08-29 13:44:45.023  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:45.023  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:45.023  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:45.023  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-29 13:44:45.023  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:45.023  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:45.023  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:45.023  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:45.023  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:45.023  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:45.023  1017  3971 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:44:45.023  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:45.023  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:44:45.023  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:45.023  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:45.023  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:44:45.023  1609  1609 I Hs20UtilService: Starting #16
08-29 13:44:45.023  1609  1651 I Hs20UtilService: Message received 5007
,08-29 13:44:45.033  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:45.033  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:45.033  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:45.033  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:45.033  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:45.033  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:45.033  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:45.033  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:45.033  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:45.033  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 13:44:45.033  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:45.033  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:45.033  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 13:44:45.033  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:44:45.033  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:44:45.033  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:45.033  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:44:45.033  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:44:45.053  1017  3971 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:44:45.053  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:45.053  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:44:45.053  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:45.053  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:44:45.053  1609  1609 I Hs20UtilService: Starting #17
08-29 13:44:45.053  1609  1651 I Hs20UtilService: Message received 5011
,08-29 13:44:45.063  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:44:45.063  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:44:45.063  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:44:45.063  6860  6860 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:44:45.073   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:44:45.103  7324  7324 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 13:44:45.153  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-29 13:44:45.153  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:44:45.153  1017  1044 D Tethering: interfaceStatusChanged p2p0, false,
08-29 13:44:45.153  7324  7324 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 13:44:45.183  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 13:44:45.183  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 13:44:45.183  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:44:45.183  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-29 13:44:45.183  1017  1132 D Tethering: InitialState.processMessage what=4,
08-29 13:44:45.183  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:45.183  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:44:45.183  7324  7324 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-29 13:44:45.183  7324  7324 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED,
08-29 13:44:45.183  7324  7324 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 13:44:45.183  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:44:45.183  7324  7324 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030,
08-29 13:44:45.183  7324  7324 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 13:44:45.183  1017  1132 E Tethering: No numeric data
08-29 13:44:45.183  1017  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-29 13:44:45.183  1017  1132 D Tethering: clearTetheredNotification()
08-29 13:44:45.183  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:45.183  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:45.183  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:44:45.183  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:45.183  1017  1124 V NetworkStats: performPollLocked() took 3ms
08-29 13:44:45.183  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:45.183  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:45.183  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:44:45.183  1172  1172 D HotspotTile: updateTetherState():false, false
08-29 13:44:45.183  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:44:45.193  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:45.193  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:45.433  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:44:45.433  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 13:44:45.433  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,08-29 13:44:45.493  7324  7324 I wpa_supplicant: Blacklist: Clear (all) ,
,08-29 13:44:45.613  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 13:44:45.613  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 13:44:45.613  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
08-29 13:44:45.613  7324  7324 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-29 13:44:45.723  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-29 13:44:45.723  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 13:44:45.723  7085  7085 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:45.733  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:45.733  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:45.733  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:44:45.733  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:45.733  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.733  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.733  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.733  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:45.733  1746  2192 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:44:45.733  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 13:44:45.733  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:45.733  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-29 13:44:45.733  1172  1172 D HotspotTile: onReceive : 1, 0
,08-29 13:44:45.743  4454  4454 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:45.743  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:45.743  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:45.743  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-29 13:44:45.743  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:44:45.753  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:45.753  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:45.753  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:44:45.753  1609  1609 I Hs20UtilService: Starting #18
08-29 13:44:45.753  1609  1651 I Hs20UtilService: Message received 5011
,08-29 13:44:45.753  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:44:45.753  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 13:44:45.753  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:44:45.753  6860  6860 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:44:46.083   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-29 13:44:46.093   288   288 E SMD     : DCD OFF,
,08-29 13:44:46.383  1017  1044 D Tethering: interfaceRemoved wlan0
,08-29 13:44:46.383  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 13:44:46.463  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-29 13:44:46.683  1017  1044 D Tethering: interfaceRemoved p2p0
,08-29 13:44:46.683  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring,
,08-29 13:44:47.323  1017  1096 V AlarmManager: waitForAlarm result :4
,08-29 13:44:47.333   278   999 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 13:44:47.333   278   999 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-29 13:44:47.353  1017  1042 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:44:47.353  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:47.353  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-29 13:44:47.473  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 13:44:47.793  6633  6774 D BluetoothAdapter: enable()
,08-29 13:44:47.803  1017  3970 W ActivityManager: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:44:47.803  1017  3970 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 13:44:47.803  1017  3970 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:44:47.803  1017  3970 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:44:47.803  1017  3970 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 13:44:47.803  1017  3970 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 13:44:47.803  1017  3970 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 13:44:47.803  1017  3970 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 13:44:47.803  1017  3970 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:44:47.803  1017  3970 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:44:47.803  1017  3970 D SettingsProvider: name = bluetooth_on,
,08-29 13:44:47.813  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:44:47.813  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:44:47.813  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 13:44:47.823  2758  2815 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
08-29 13:44:47.823  2758  2815 D BluetoothAdapterProperties: Setting state to 11
08-29 13:44:47.823  2758  2815 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 13:44:47.823  2758  2815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 13:44:47.823  2758  2815 D BluetoothAdapterService: updateAdapterState state is 11
08-29 13:44:47.823  2758  2815 D BluetoothAdapterService: Autoconnection is available 
08-29 13:44:47.823  2758  2815 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11,
08-29 13:44:47.823  2758  2815 D BtConfig.SecureMode: isSecureModeOn:false
08-29 13:44:47.823  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 13:44:47.823  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10,
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 13:44:47.823  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 13:44:47.823  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 13:44:47.843  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-29 13:44:47.843  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 13:44:47.843  1172  1172 D BluetoothTile:  getBluetoothState : 11
08-29 13:44:47.843  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
08-29 13:44:47.843  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 13:44:47.843  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:44:47.853  4454  4454 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:47.853  1017  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:47.853  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 13:44:47.853  1017  3970 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:47.863  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:47.863  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:47.863  1017  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.863  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:47.863  1017  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:44:47.863  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:47.863  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 13:44:47.863  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:44:47.863  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 13:44:47.863  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:47.863  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:47.863  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 13:44:47.873  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:47.873  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.873  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:47.873  2758  2758 D HeadsetService: Received start request. Starting profile...
08-29 13:44:47.873  2758  2758 D HeadsetService: start()
08-29 13:44:47.873  2758  2758 D HeadsetStateMachine: make
,08-29 13:44:47.873  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-29 13:44:47.873  1017  3977 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:47.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 13:44:47.873  1017  3977 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 13:44:47.873  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-29 13:44:47.873  1017  3977 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:47.873  1017  3977 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.873  1017  3977 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:47.883  2758  2758 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 13:44:47.883  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-29 13:44:47.883  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 13:44:47.883  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 13:44:47.883  1680  1680 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:47.893  1017  3971 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-29 13:44:47.893  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 13:44:47.893  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:47.893  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.893  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 13:44:47.893  4454  4454 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:44:47.903  1017  1447 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:47.903  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 13:44:47.903  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:47.903  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.903  1017  1450 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-29 13:44:47.903  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:47.903  1017  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 13:44:47.903  1017  1450 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:47.903  1017  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.903  1017  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-29 13:44:47.903  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 13:44:47.903  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 13:44:47.903  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 13:44:47.903  2758  2758 I bluedroid: get_profile_interface handsfree
,08-29 13:44:47.903  1017  1450 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:47.903  1017  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:44:47.913  1017  1450 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:47.913  1017  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.913  1017  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:47.913  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 13:44:47.913  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:47.913  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 13:44:47.923  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-29 13:44:47.923  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:47.923  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11,
08-29 13:44:47.923  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 13:44:47.923  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:47.923  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.923  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:47.923  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 13:44:47.923  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:44:47.923  2758  2815 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-29 13:44:47.923  2758  2758 E DualScoManager: Dual Sco Manager already instantiated
,08-29 13:44:47.923  2758  2758 I DualScoManager: Set HeadsetServiceHelper
08-29 13:44:47.923  2758  2758 D BluetoothAtMessage: createCMTIContentObservers
,08-29 13:44:47.923  1017  3967 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-29 13:44:47.923  1017  3967 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:44:47.923  1017  3967 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:44:47.923  1017  3967 D SettingsProvider: selectionArgs: false
08-29 13:44:47.923  1017  3967 D SettingsProvider: selectionArgs: 1002
,08-29 13:44:47.923  1017  3967 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 13:44:47.923  1017  3967 D SettingsProvider: ret = -1
,08-29 13:44:47.933  2758  7448 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 13:44:47.933  1017  1480 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 13:44:47.933  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:47.933  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:47.933  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:47.933  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:47.943  1017  1480 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7449 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 13:44:47.943  7449  7449 E Zygote  : MountEmulatedStorage()
08-29 13:44:47.943  1017  3971 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:47.943  7449  7449 E Zygote  : v2
08-29 13:44:47.943  7449  7449 I libpersona: KNOX_SDCARD checking this for 10055
08-29 13:44:47.943  7449  7449 I libpersona: KNOX_SDCARD not a persona,
,08-29 13:44:47.953  7449  7449 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:47.953  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0,
,08-29 13:44:47.953  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:47.953  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:47.953  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:47.953  7449  7449 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:44:47.953  7449  7449 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:44:47.953  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:47.953  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:47.953  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:47.953  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:47.953  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:47.953  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:47.953  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 13:44:47.953  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:44:47.953  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 13:44:47.953  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 13:44:47.953  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 13:44:47.953  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 13:44:47.953  2758  2815 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 13:44:47.963  2758  2758 D HeadsetService: mStartError = false
08-29 13:44:47.963  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:47.963  2758  2758 D A2dpService: Received start request. Starting profile...
08-29 13:44:47.963  2758  2758 D A2dpService: start()
08-29 13:44:47.963  2758  2758 I bluedroid: get_profile_interface avrcp
,08-29 13:44:47.963  2758  7448 D HeadsetStateMachine: Clear mHeadsetBrsf
08-29 13:44:47.963  2758  7448 D HeadsetStateMachine: map size, before remove : 0
08-29 13:44:47.963  2758  7448 D HeadsetStateMachine: map size, after remove: 0
,08-29 13:44:47.963  2758  2758 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-29 13:44:47.963  2758  2758 D Avrcp   : Initialize Media Controller
08-29 13:44:47.963  2758  2758 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-29 13:44:47.963  2758  2758 E Avrcp   : getActiveSessions
08-29 13:44:47.963  2758  2758 D Avrcp   : pick active media Controller
08-29 13:44:47.963  2758  2758 D Avrcp   : Get the active Media Controller 
,08-29 13:44:47.973  2758  2758 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 13:44:47.973  2758  7457 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 13:44:47.973  2758  2758 D A2dpStateMachine: make
,08-29 13:44:47.983  2758  2758 I bluedroid: get_profile_interface a2dp
,08-29 13:44:47.983  2758  7462 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-29 13:44:47.983  2758  2758 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 13:44:47.983  2758  2758 D A2dpService: mStartError = false
08-29 13:44:47.983  2758  7460 D A2dpStateMachine: Enter Disconnected: -2
08-29 13:44:47.983  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:47.983  2758  2758 D HidService: Received start request. Starting profile...
08-29 13:44:47.983  2758  2758 D HidService: start()
08-29 13:44:47.983  2758  2758 I bluedroid: get_profile_interface hidhost
08-29 13:44:47.983  2758  2758 D HidService: setHidService(): set to: null
08-29 13:44:47.983  2758  2758 D HidService: mStartError = false
08-29 13:44:47.983  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:47.983  2758  2758 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 13:44:47.993  1428  1459 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 13:44:47.993  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-29 13:44:47.993  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 13:44:47.993  1428  1459 I Telecom : BluetoothPhoneService: Result of Message : true
08-29 13:44:47.993  2758  2758 D HeadsetStateMachine: Proxy object connected
,08-29 13:44:47.993  2758  2758 D HealthService: Received start request. Starting profile...
08-29 13:44:47.993  2758  2758 D HealthService: start()
08-29 13:44:47.993  2758  7457 D BluetoothMediaBrowser: no now playing list
08-29 13:44:47.993  2758  7457 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 13:44:48.003  2758  2758 I bluedroid: get_profile_interface health
08-29 13:44:48.003  2758  2758 D HealthService: mStartError = false
08-29 13:44:48.003  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:48.003  2758  2758 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-29 13:44:48.003  2758  7448 D HeadsetStateMachine: Disconnected process message: 11
,08-29 13:44:48.003  2758  2758 D PanService: Received start request. Starting profile...
08-29 13:44:48.003  2758  2758 D PanService: start()
08-29 13:44:48.003  2758  2758 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:44:48.003  2758  2758 I bluedroid: get_profile_interface pan
08-29 13:44:48.003  2758  2758 D PanService: mStartError = false
08-29 13:44:48.003  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:48.003  2758  2758 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 13:44:48.003  2758  2758 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-29 13:44:48.003  2758  7448 D HeadsetStateMachine: Disconnected process message: 18
08-29 13:44:48.003  2758  2758 D BluetoothMapService: Received start request. Starting profile...
08-29 13:44:48.003  2758  2758 D BluetoothMapService: start()
,08-29 13:44:48.003  2758  2758 D BluetoothMapService: mStartError = false
,08-29 13:44:48.003  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:48.003  2758  2758 D SapService: Received start request. Starting profile...
08-29 13:44:48.003  2758  2758 D SapService: start()
08-29 13:44:48.003  2758  2758 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 13:44:48.003  2758  2758 I bluedroid: get_profile_interface sap
08-29 13:44:48.003  2758  2758 D SapService: mStartError = false
08-29 13:44:48.003  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:48.003  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 13:44:48.003  2758  2758 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 13:44:48.003  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 13:44:48.003  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-29 13:44:48.003  2758  7448 D HeadsetStateMachine: Disconnected process message: 10
08-29 13:44:48.003  2758  7448 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:44:48.003  2758  7448 D HeadsetStateMachine: Disconnected process message: 11
,08-29 13:44:48.013  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true,
,08-29 13:44:48.013  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 13:44:48.023  7449  7449 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:48.023  7449  7449 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:48.033  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-29 13:44:48.033  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 13:44:48.043  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 13:44:48.043  2758  2815 I bluedroid: enable
,08-29 13:44:48.043  2758  2818 E bt-btif : Calling BTA_HhEnable
,08-29 13:44:48.043  2758  2818 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 13:44:48.043  2758  2818 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 13:44:48.043  2758  2818 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 13:44:48.043  2758  2818 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-29 13:44:48.043  2758  2818 E BluetoothServiceJni: populateRssiValuesNative
08-29 13:44:48.043  2758  2818 I bluedroid: getModelRssiValues
08-29 13:44:48.043  2758  2818 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 13:44:48.043  2758  2818 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 13:44:48.053  2758  2818 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-29 13:44:48.053  1017  1017 D SettingsProvider: name = bluetooth_name
,08-29 13:44:48.053  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 13:44:48.053  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-29 13:44:48.053  2758  2818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:44:48.053  2758  2818 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:44:48.053  2758  2818 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:44:48.053  2758  2818 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
,08-29 13:44:48.053  2758  2818 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-29 13:44:48.053  2758  2818 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-29 13:44:48.053  2758  2818 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 13:44:48.053  2758  2818 E bt-btif : JVenable fails
08-29 13:44:48.053  2758  2818 D bte_conf: Device ID record 1 : primary
08-29 13:44:48.053  2758  2818 D bte_conf:   vendorId            = 0075
08-29 13:44:48.053  2758  2818 D bte_conf:   vendorIdSource      = 0001
,08-29 13:44:48.053  2758  2818 D bte_conf:   product             = 0100
08-29 13:44:48.053  2758  2818 D bte_conf:   version             = 0200
08-29 13:44:48.053  2758  2818 D bte_conf:   clientExecutableURL = 
08-29 13:44:48.053  2758  2818 D bte_conf:   serviceDescription  = 
,08-29 13:44:48.053  2758  2818 D bte_conf:   documentationURL    = 
08-29 13:44:48.053  2758  2818 D bte_conf: bte_load_did_conf no section named DID2.
08-29 13:44:48.053  2758  2818 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 13:44:48.053  2758  2818 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 13:44:48.053  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 13:44:48.053  2758  2815 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:44:48.053  2758  2815 D BluetoothAdapterProperties: State =  11
08-29 13:44:48.063  1017  1450 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 13:44:48.063  2758  2815 D BluetoothAdapterProperties: Setting state to 12
08-29 13:44:48.063  2758  2815 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12,
08-29 13:44:48.063  2758  2818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:44:48.063  2758  2818 D BluetoothAdapterProperties: Scan Mode:21
,08-29 13:44:48.063  1017  1480 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 13:44:48.063  1017  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:44:48.063  1017  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:44:48.063  1017  1480 D SettingsProvider: selectionArgs: false
,08-29 13:44:48.063  1017  1480 D SettingsProvider: selectionArgs: 1002,
08-29 13:44:48.063  1017  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:44:48.063  1017  1447 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:48.063  1017  1480 D SettingsProvider: ret = -1
08-29 13:44:48.063  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-29 13:44:48.063  2758  2815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:44:48.063  2758  2815 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 13:44:48.063  2758  2818 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:44:48.063  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.063  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.063  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:48.073  2758  2758 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 13:44:48.073  2758  2758 I BluetoothPbapService: Handler(): got msg=1
,08-29 13:44:48.073  7449  7449 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 13:44:48.073  1017  1504 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 13:44:48.073  2758  2815 D BluetoothAdapterService: Autoconnection is available 
08-29 13:44:48.073  2758  2815 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 13:44:48.073  2758  2815 D BluetoothAdapterService: starting service from this receiver
08-29 13:44:48.073  6999  7008 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.073  1017  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:48.073  6999  7008 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:48.073  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.073  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.073  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.073  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:48.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:48.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:48.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:48.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:48.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:48.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:48.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:44:48.073  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:48.083  1746  3519 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.083  1746  3519 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:48.083  2758  2815 I BluetoothAdapterState: Entering On State from state = 11
,08-29 13:44:48.083  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:48.083  4454  4462 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:48.083  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:48.083  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 13:44:48.083  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.083  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.083  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 13:44:48.083  4454  4462 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:44:48.083  1017  1046 D BluetoothPan: Binding service...
08-29 13:44:48.083  2758  7472 V BluetoothPbapService: PBAP Service initSocket try: 0
08-29 13:44:48.083  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 13:44:48.083  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-29 13:44:48.093  4454  4464 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 13:44:48.093  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:48.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:48.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:48.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:48.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:48.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:48.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:48.093  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:48.093  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:48.093  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 13:44:48.093  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.093  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.093  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.093  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 13:44:48.093  2758  7472 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:44:48.093  2758  7472 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:48.093  4454  4454 D HeadsetProfile: Bluetooth service connected
08-29 13:44:48.093  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:44:48.093  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.093  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:48.093  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:48.093  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:48.093  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 13:44:48.093  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:44:48.093  1172  3170 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.093  1172  3170 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:48.093  6633  6642 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.093  6633  6642 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:48.103  2758  7472 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-29 13:44:48.103  2758  7472 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:44:48.103  2758  7472 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:44:48.103  2758  7472 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@111a5cdd
08-29 13:44:48.103  2758  7472 D BluetoothSocket: channel: 19
08-29 13:44:48.103  2758  7472 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-29 13:44:48.103  2758  2770 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:44:48.103  2758  2770 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:48.103  4454  4454 D BluetoothPbap: Proxy object connected
08-29 13:44:48.103  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:44:48.103  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.103  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.103  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.103  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:48.103  4454  4454 D PbapServerProfile: Bluetooth service connected
,08-29 13:44:48.103  2758  2758 D BluetoothA2dp: Proxy object connected
,08-29 13:44:48.103  2758  2758 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-29 13:44:48.103  1428  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 13:44:48.103  7449  7449 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-29 13:44:48.113  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:48.113  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:44:48.113  7449  7449 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 13:44:48.113  7449  7449 D UserAnalysis: Create SecureDbHelper
,08-29 13:44:48.113  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.113  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.113  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 13:44:48.113  1428  1454 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:44:48.113  4454  4464 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:44:48.113  4454  4464 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:48.113  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:44:48.113  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.113  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.113  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.113  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:48.113  4454  4464 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:44:48.113  4454  4454 D BluetoothA2dp: Proxy object connected
08-29 13:44:48.113  4454  4454 D A2dpProfile: Bluetooth service connected
,08-29 13:44:48.113  7449  7449 D IntelligenceServiceApplication: onCreate()
,08-29 13:44:48.113  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 13:44:48.113  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 13:44:48.123  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.123  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.123  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:48.123  1463  1482 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.123  1463  1482 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:48.123  4454  4462 D Bluetoothsap: onBluetoothStateChange: up=true
08-29 13:44:48.123  4454  4462 D Bluetoothsap: Binding service...
,08-29 13:44:48.123  1017  3977 I ActivityManager: Killing 6999:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-29 13:44:48.123  4454  4454 D BluetoothInputDevice: Proxy object connected
08-29 13:44:48.123  4454  4454 D HidProfile: Bluetooth service connected
,08-29 13:44:48.123  4454  4462 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-29 13:44:48.123  7449  7449 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 13:44:48.133  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 13:44:48.133  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-29 13:44:48.133  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.133  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.133  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.133  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 13:44:48.133  4454  4462 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 13:44:48.133  7449  7449 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-29 13:44:48.133  1680  1690 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.133  1680  1690 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:48.133  4454  4454 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 13:44:48.133  1428  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:48.133  4454  4454 D SapProfile: Bluetooth service connected
08-29 13:44:48.133  4454  4454 D Bluetoothsap: getConnectedDevices()
08-29 13:44:48.133  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:48.133  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:44:48.133  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.133  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.133  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:48.133  1428  1454 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:44:48.143  1463  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:48.143  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:48.143  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:44:48.143  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.143  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.143  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:48.143  1463  1475 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:44:48.143  4454  7473 D BluetoothPan: Binding service...
,08-29 13:44:48.143  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 13:44:48.143  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.143  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.143  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.143  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 13:44:48.143  4454  4464 D BluetoothMap: onBluetoothStateChange: up=true
08-29 13:44:48.143  4454  4454 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:44:48.143  4454  4454 D PanProfile: Bluetooth service connected
,08-29 13:44:48.143  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 13:44:48.143  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.143  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.143  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.143  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:48.143  1428  7474 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.143  1428  7474 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:48.143  4454  4454 D BluetoothMap: Proxy object connected
08-29 13:44:48.153  1428  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 13:44:48.153  4454  4454 D MapProfile: Bluetooth service connected
08-29 13:44:48.153  4454  4454 D BluetoothMap: getConnectedDevices()
,08-29 13:44:48.153  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:48.153  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 13:44:48.153  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.153  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.153  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:48.153  1428  1459 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:44:48.153  2758  2767 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.153  2758  2767 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:48.153  4454  4462 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.153  4454  4462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:48.153  1443  1461 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:48.153  7449  7449 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-29 13:44:48.153  1443  1461 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:48.153  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:44:48.153  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:48.153  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:44:48.153  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-29 13:44:48.153  1017  1017 D BluetoothA2dp: Proxy object connected
08-29 13:44:48.153  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 13:44:48.153  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 13:44:48.163  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2c230bcf, true
08-29 13:44:48.163  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-29 13:44:48.163  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:44:48.163  1428  1428 D BluetoothHeadset: registerMessageListener
08-29 13:44:48.163  1172  1172 D BluetoothTile:  getBluetoothState : 12
08-29 13:44:48.163  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:48.163  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:44:48.163  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:48.163  4454  4454 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:48.173  2758  3260 D HeadsetService: registerMessageListener
08-29 13:44:48.173  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
08-29 13:44:48.173  2758  3260 D HeadsetService: registerMessageListener
08-29 13:44:48.173  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:48.173  2758  7448 D HeadsetStateMachine: Disconnected process message: 70
08-29 13:44:48.173  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-29 13:44:48.173  2758  7448 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@731052
08-29 13:44:48.173  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-29 13:44:48.173  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 13:44:48.173  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 13:44:48.173  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:48.173  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 13:44:48.173  4454  4454 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-29 13:44:48.173  4454  4454 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 13:44:48.173  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:44:48.173  4454  4454 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 13:44:48.173  4454  4454 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-29 13:44:48.173  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-29 13:44:48.173  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 13:44:48.183  2758  7478 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 13:44:48.183  1017  1480 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:48.183  2758  7448 D HeadsetStateMachine: Disconnected process message: 9
08-29 13:44:48.183  2758  7448 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-29 13:44:48.183  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:48.183  1017  3970 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 13:44:48.183  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:48.183   283   680 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-29 13:44:48.183   283   680 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-29 13:44:48.193   283   680 V voice   : voice_set_parameters: exit with code(-2)
08-29 13:44:48.193   283   680 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 13:44:48.193   283   680 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 13:44:48.193   283   680 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 13:44:48.193  2758  7478 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:44:48.193  2758  7478 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:44:48.193   283   680 V audio_hw_primary: adev_set_parameters: exit
08-29 13:44:48.193  2758  7448 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 13:44:48.193  2758  7478 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
08-29 13:44:48.193  2758  7478 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:44:48.193  2758  7478 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:44:48.193  2758  7478 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31631f23
,08-29 13:44:48.193  2758  7478 D BluetoothSocket: channel: 5
,08-29 13:44:48.263  4454  4454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:48.263  1017  1447 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 13:44:48.263  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.263  1017  1447 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:44:48.263  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.263  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:44:48.273  1680  1680 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:48.273  4454  4454 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:48.283  4454  4454 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:44:48.283  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:48.283  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 13:44:48.293  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:48.293  2758  2758 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 13:44:48.293  1017  3970 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:48.303  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 13:44:48.303  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:48.303  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:48.303  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:48.303  1017  1493 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast,
08-29 13:44:48.303  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:48.303  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:48.303  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:44:48.303  1017  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:44:48.323  7481  7481 E Zygote  : MountEmulatedStorage()
08-29 13:44:48.323  7481  7481 E Zygote  : v2
08-29 13:44:48.323  7481  7481 I libpersona: KNOX_SDCARD checking this for 10105
08-29 13:44:48.323  7481  7481 I libpersona: KNOX_SDCARD not a persona
,08-29 13:44:48.333  7481  7481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:44:48.333  1017  1493 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7481 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 13:44:48.333  1017  1487 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 13:44:48.333  7481  7481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 13:44:48.343  7481  7481 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:44:48.353  2758  7491 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:44:48.353  2758  7491 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:44:48.353  2758  7491 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-29 13:44:48.353  2758  7491 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:44:48.353  2758  7491 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:44:48.353  2758  7491 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f3e8a7f
08-29 13:44:48.353  2758  7491 D BluetoothSocket: channel: 12
08-29 13:44:48.353  2758  7491 I BtOppRfcommListener: Accept thread started.
,08-29 13:44:48.373  7481  7481 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:44:48.383  7481  7481 D ActivityThread: Added TimaKeyStore provider
,08-29 13:44:48.523   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 13:44:48.523   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:44:48.523  7481  7501 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 13:44:48.533   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 13:44:48.533   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:44:48.533  7481  7501 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 13:44:48.693  7481  7481 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:48.693  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:48.703  7481  7481 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:44:48.703  7481  7481 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:44:48.703  7481  7481 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:44:48.703  7481  7481 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:44:48.703  7481  7481 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:44:48.703  7481  7481 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:44:48.703  1017  1219 I ActivityManager: Killing 7108:com.sec.pcw.device/1000 (adj 15): empty #21
08-29 13:44:48.703  7481  7481 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:44:48.703  7481  7481 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:44:48.763  7481  7502 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 13:44:48.793  1017  1323 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:44:48.793  1017  1323 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:44:48.793  1017  1323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:44:48.793  1017  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 13:44:49.103   288   288 E SMD     : DCD OFF
,08-29 13:44:50.523  1017  2838 D SSRM:n  : SIOP:: AP = 380
,08-29 13:44:50.823  6633  6774 D BluetoothAdapter: disable(),
08-29 13:44:50.823  1017  1493 D SettingsProvider: name = bluetooth_on
,08-29 13:44:50.833  2758  2815 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-29 13:44:50.833  2758  2815 D BluetoothAdapterProperties: Setting state to 13
08-29 13:44:50.833  1017  3971 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:50.833  2758  2815 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:44:50.833  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-29 13:44:50.833  2758  2815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:44:50.833  2758  2815 D BluetoothAdapterService: updateAdapterState state is 13
08-29 13:44:50.833  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:50.833  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:50.833  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:50.833  2758  2758 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-29 13:44:50.843  2758  2758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@290dda4c, channel: 19, state: LISTENING
08-29 13:44:50.843  2758  2758 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@290dda4c, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@111a5cdd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16314a95mSocket: android.net.LocalSocket@3bf457aa impl:android.net.LocalSocketImpl@313b4f9b fd:FileDescriptor[80]
,08-29 13:44:50.843  2758  2758 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3bf457aa impl:android.net.LocalSocketImpl@313b4f9b fd:FileDescriptor[80]
08-29 13:44:50.843  2758  2815 D BluetoothAdapterService: Autoconnection is available 
08-29 13:44:50.843  2758  2815 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-29 13:44:50.843  2758  2815 D BluetoothAdapterService: terminating service from this receiver
08-29 13:44:50.843  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:50.843  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-29 13:44:50.843  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-29 13:44:50.853  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:44:50.853  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:44:50.853  1172  1172 D BluetoothTile:  getBluetoothState : 13
,08-29 13:44:50.853  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:50.853  1872  1872 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:44:50.853  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:50.853  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 13:44:50.853  4454  4454 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:50.863  1017  1504 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:50.863  1017  1487 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:44:50.863  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 13:44:50.863  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:50.863  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:50.863  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:50.863  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:50.863  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:50.863  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:50.863  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:50.863  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:50.863  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:50.873  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 13:44:50.873  2758  2758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35644f38, channel: 5, state: LISTENING
08-29 13:44:50.873  2758  2758 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35644f38, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31631f23, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@928fb11mSocket: android.net.LocalSocket@23184476 impl:android.net.LocalSocketImpl@3f754a77 fd:FileDescriptor[82]
08-29 13:44:50.873  2758  2758 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@23184476 impl:android.net.LocalSocketImpl@3f754a77 fd:FileDescriptor[82]
,08-29 13:44:50.873  2758  2758 I BtOppRfcommListener: stopping Accept Thread
08-29 13:44:50.873  2758  2758 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10ab26e4, channel: 12, state: LISTENING
08-29 13:44:50.873  2758  2758 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10ab26e4, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f3e8a7f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3711374dmSocket: android.net.LocalSocket@3bc3202 impl:android.net.LocalSocketImpl@1dea1713 fd:FileDescriptor[85]
08-29 13:44:50.873  2758  2758 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3bc3202 impl:android.net.LocalSocketImpl@1dea1713 fd:FileDescriptor[85]
08-29 13:44:50.873  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:50.873  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:50.873  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:50.873  2758  7491 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:44:50.873  2758  7491 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 13:44:50.873  2758  2815 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:44:50.873  2758  2815 D BluetoothAdapterProperties: mDiscovering is false
,08-29 13:44:50.873  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:50.873  1017  3971 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 13:44:50.873  2758  2815 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-29 13:44:50.883  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:50.883  4454  4454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:50.883  1017  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 13:44:50.883  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:44:50.883  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:44:50.883  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:50.883  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:50.883  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:50.883  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:50.883  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:44:50.883  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:50.883  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:50.883  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:50.883  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:50.893  6633  6633 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:44:50.893  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:44:50.893  2758  2818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:44:50.893  2758  2818 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:44:50.893  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:50.893  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:44:50.893  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:50.893  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:50.903  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-29 13:44:50.903  2758  2815 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 13:44:50.903  2758  2815 E bt-btif : cmd socket is not created
,08-29 13:44:50.903  2758  2815 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 13:44:50.903  2758  2819 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-29 13:44:50.903  4454  4454 D BluetoothPbap: Proxy object disconnected
,08-29 13:44:50.903  4454  4454 D PbapServerProfile: Bluetooth service disconnected
,08-29 13:44:50.913  1680  1680 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 13:44:50.913  2758  2819 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:50.913  2758  2819 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:50.913  2758  2819 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:44:50.913  2758  2819 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:44:50.913  2758  2819 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:44:50.913  2758  2819 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 13:44:50.923  2758  2758 V BluetoothOppManager: cleanUp...
,08-29 13:44:50.923  4454  4454 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:50.923  4454  4454 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:44:50.923  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:50.923  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 13:44:51.083   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:44:51.113  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 13:44:51.113  2758  2815 D BtConfig.SecureMode: isSecureModeOn:false
08-29 13:44:51.113  2758  2815 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 13:44:51.113  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-29 13:44:51.113  2758  2815 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-29 13:44:51.113  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 13:44:51.113  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 13:44:51.113  1017  1078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:51.113  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 13:44:51.113  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 13:44:51.113  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:51.113  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:51.113  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:51.113  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 13:44:51.113  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:44:51.113  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 13:44:51.113  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:51.113  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:51.113  2758  2758 D HeadsetService: Received stop request...Stopping profile...,
,08-29 13:44:51.113  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:51.113  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:51.113  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:51.123  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8,
,08-29 13:44:51.123  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-29 13:44:51.123  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:44:51.123  1017  3971 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:51.123  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-29 13:44:51.123  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 13:44:51.123  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-29 13:44:51.123  2758  2758 D A2dpService: Received stop request...Stopping profile...
08-29 13:44:51.123  4454  4454 D HeadsetProfile: Bluetooth service disconnected
08-29 13:44:51.123  2758  7460 D A2dpStateMachine: Exit Disconnected: -1
08-29 13:44:51.123  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:51.123  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:51.123  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:51.123  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-29 13:44:51.123  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 13:44:51.123  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 13:44:51.123  1017  1447 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:51.123  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 13:44:51.123  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:51.123  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:51.123  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:51.123  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:51.133  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-29 13:44:51.133  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 13:44:51.133  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 13:44:51.133  1017  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:51.133  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:44:51.133  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:51.133  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:51.133  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:51.133  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:51.133  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.133  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.133  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.133  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 13:44:51.133  1017  1078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:51.133  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 13:44:51.133  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:51.133  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:51.143  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:51.143  4454  4454 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:51.143  4454  4454 D A2dpProfile: Bluetooth service disconnected
,08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-29 13:44:51.143  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 13:44:51.143  1017  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:51.143  1017  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:44:51.143  1017  1323 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:51.143  1017  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:51.143  1017  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:51.143  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:51.143  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 13:44:51.143  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 13:44:51.143  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 13:44:51.143  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 13:44:51.143  2758  2815 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 13:44:51.143  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 13:44:51.143  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:44:51.143  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 13:44:51.153  2758  2758 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:44:51.153  2758  2758 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 13:44:51.153  2758  2758 D HidService: Received stop request...Stopping profile...
,08-29 13:44:51.153  2758  2758 D HidService: Stopping Bluetooth HidService
08-29 13:44:51.153  2758  2758 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:44:51.153  2758  2758 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-29 13:44:51.153  2758  2758 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:44:51.153  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:51.153  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
08-29 13:44:51.153  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:44:51.153  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService,
08-29 13:44:51.153  2758  2758 D HealthService: Received stop request...Stopping profile...
08-29 13:44:51.153  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:51.153  2758  2758 D BluetoothA2dp: Proxy object disconnected
08-29 13:44:51.153  2758  2758 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-29 13:44:51.153  2758  7462 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 13:44:51.153  2758  2758 I GKI_LINUX: GKI_exit_task 2 done
08-29 13:44:51.153  2758  2758 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-29 13:44:51.153  4454  4454 D BluetoothInputDevice: Proxy object disconnected
08-29 13:44:51.153  4454  4454 D HidProfile: Bluetooth service disconnected
08-29 13:44:51.153  2758  2758 D PanService: Received stop request...Stopping profile...
08-29 13:44:51.153  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:51.153  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 13:44:51.163  2758  2758 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 13:44:51.163  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:51.163  4454  4454 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:44:51.163  2758  2758 D SapService: Received stop request...Stopping profile...
08-29 13:44:51.163  2758  2758 D SapService: Stopping Bluetooth SapService
08-29 13:44:51.163  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:51.163  4454  4454 D PanProfile: Bluetooth service disconnected
,08-29 13:44:51.163  4454  4454 D BluetoothMap: Proxy object disconnected
08-29 13:44:51.163  4454  4454 D MapProfile: Bluetooth service disconnected
08-29 13:44:51.163  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 13:44:51.163  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 13:44:51.163  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.163  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 13:44:51.163  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 13:44:51.163  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-29 13:44:51.163  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.163  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.163  2758  2758 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-29 13:44:51.163  2758  2758 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:44:51.163  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 13:44:51.163  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 13:44:51.173  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.173  2758  2758 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:51.173  2758  2758 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:44:51.173  2758  2758 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 13:44:51.173  4454  4454 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,08-29 13:44:51.173  4454  4454 D SapProfile: Bluetooth service disconnected
,08-29 13:44:51.173  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-29 13:44:51.173  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-29 13:44:51.173  2758  2758 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 13:44:51.173  2758  2758 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-29 13:44:51.173  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-29 13:44:51.173  2758  2758 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. ,
08-29 13:44:51.173  2758  2758 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 13:44:51.173  2758  2758 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-29 13:44:51.173  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-29 13:44:51.173  2758  2815 D BluetoothAdapterProperties: Setting state to 10
08-29 13:44:51.173  2758  2815 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 13:44:51.173  2758  2815 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
08-29 13:44:51.173  2758  2815 D BluetoothAdapterService: updateAdapterState state is 10
08-29 13:44:51.173  2758  2815 D BluetoothAdapterService: Autoconnection is available 
08-29 13:44:51.173  2758  2815 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 13:44:51.173  2758  2815 I BluetoothAdapterState: Entering OffState
,08-29 13:44:51.173  1746  1989 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:51.173  1746  1989 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:51.173  4454  4462 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 13:44:51.173  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:51.183  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:51.183  1172  1189 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:51.183  1172  1189 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:51.183  6633  6642 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:51.183  6633  6642 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:51.183  6633  6642 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 13:44:51.183  6633  6642 D BluetoothLeAdvertiser: Exit stop advertising
,08-29 13:44:51.183  6633  6642 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 13:44:51.183  6633  6642 D BluetoothLeScanner: Exiting stopAllScan
,08-29 13:44:51.183  2758  2770 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:44:51.183  4454  4464 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:44:51.183  4454  7473 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 13:44:51.183  1463  1482 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:51.183  1463  1482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:51.183  4454  4462 D Bluetoothsap: onBluetoothStateChange: up=false
08-29 13:44:51.183  4454  4462 D Bluetoothsap: Unbinding service...
,08-29 13:44:51.193  1680  1775 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:51.193  1680  1775 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:51.193  4454  7473 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 13:44:51.193  1428  7474 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:51.193  1428  7474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:51.193  7481  7494 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:51.193  7481  7494 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:44:51.193  2758  2767 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:44:51.193  2758  2767 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:44:51.193  4454  4462 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:51.193  4454  4462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:44:51.193  1443  1461 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:44:51.193  1443  1461 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:44:51.193  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:44:51.203  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:51.203  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-29 13:44:51.203  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0),
,08-29 13:44:51.203  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:44:51.203  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:51.213  1172  1172 D BluetoothTile:  getBluetoothState : 10
,08-29 13:44:51.213  1872  1872 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:44:51.213  1017  3967 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:51.213  1017  1493 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:44:51.213  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:51.213  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 13:44:51.213  4454  4454 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:51.213  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:51.223  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:51.223  4454  4454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:51.223  1017  1493 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 13:44:51.223  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-29 13:44:51.223  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:51.223  1017  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:51.223  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:44:51.223  1680  1680 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:51.233  4454  4454 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:51.233  4454  4454 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:44:51.233  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:51.233  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 13:44:52.083   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:44:52.103   288   288 E SMD     : DCD OFF,
,08-29 13:44:53.083   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:44:53.323  1017  1219 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 13:44:53.323  1017  1219 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 13:44:53.323  1017  1219 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 13:44:53.323  1017  1219 D BatteryService: stay LED for charging
,08-29 13:44:53.323  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-29 13:44:53.333  1172  1172 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-29 13:44:53.333  1017  1017 I MotionRecognitionService: Plugged
,08-29 13:44:53.333  1172  1172 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-29 13:44:53.333  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-29 13:44:53.333  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-29 13:44:53.333  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 13:44:53.363  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:53.363  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:53.363  1172  1172 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-29 13:44:53.833  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:44:53.833  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:44:54.083   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:44:55.083   313   313 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:44:55.103   288   288 E SMD     : DCD OFF
,08-29 13:44:56.083   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-29 13:44:56.843  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 13:44:56.843  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc2b348 added. We now have 6 listener(s)
08-29 13:44:56.843  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:56.843  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:44:56.843  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a3675e1 added. We now have 7 listener(s),
08-29 13:44:56.843  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:44:56.843  6633  6774 I System.out: IsBluetoothEnabled
08-29 13:44:56.843  6633  6774 D BluetoothAdapter: disable()
08-29 13:44:56.843  1017  1030 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-29 13:44:56.853  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:56.853  6633  6774 D BluetoothAdapter: enable()
,08-29 13:44:56.853  1017  1493 W ActivityManager: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:44:56.853  1017  1493 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 13:44:56.853  1017  1493 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:44:56.853  1017  1493 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:44:56.853  1017  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 13:44:56.853  1017  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 13:44:56.853  1017  1493 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 13:44:56.853  1017  1493 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 13:44:56.853  1017  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 13:44:56.853  1017  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:44:56.853  1017  1493 D SettingsProvider: name = bluetooth_on
,08-29 13:44:56.863  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 13:44:56.863  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:44:56.863  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 13:44:56.863  2758  2815 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 13:44:56.863  2758  2815 D BluetoothAdapterProperties: Setting state to 11
08-29 13:44:56.863  2758  2815 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 13:44:56.863  2758  2815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:44:56.863  2758  2815 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 13:44:56.873  2758  2815 D BluetoothAdapterService: Autoconnection is available 
08-29 13:44:56.873  2758  2815 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-29 13:44:56.873  2758  2815 D BtConfig.SecureMode: isSecureModeOn:false
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 13:44:56.873  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 13:44:56.873  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 13:44:56.873  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:56.873  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-29 13:44:56.873  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:44:56.883  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:56.883  1172  1172 D BluetoothTile:  getBluetoothState : 11
,08-29 13:44:56.883  1872  1872 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:44:56.883  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
08-29 13:44:56.883  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 13:44:56.883  4454  4454 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:56.883  1017  3971 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:56.893  1017  1078 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:44:56.893  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 13:44:56.893  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:56.893  1017  1447 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:56.893  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.893  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:56.893  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:56.893  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:56.893  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 13:44:56.893  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:44:56.893  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 13:44:56.903  2758  2758 D HeadsetService: Received start request. Starting profile...
,08-29 13:44:56.903  2758  2758 D HeadsetService: start()
08-29 13:44:56.903  2758  2758 D HeadsetStateMachine: make
,08-29 13:44:56.903  1680  1680 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:56.903  1017  3970 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:56.903  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.903  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:56.903  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:56.903  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:56.903  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,08-29 13:44:56.913  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:44:56.913  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 13:44:56.913  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:56.913  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.913  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:56.913  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:56.913  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:56.913  2758  2758 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 13:44:56.913  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-29 13:44:56.913  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 13:44:56.913  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 13:44:56.923  1017  1030 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-29 13:44:56.923  4454  4454 D BluetoothNotiBroadcastReceiver: onReceive
08-29 13:44:56.923  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.923  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:56.923  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:56.923  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 13:44:56.923  1017  3967 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:56.923  1017  3967 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.923  1017  3967 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:56.923  1017  3967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:56.923  1017  3967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:56.933  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-29 13:44:56.933  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 13:44:56.933  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 13:44:56.933  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:56.933  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 13:44:56.933  1017  1450 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-29 13:44:56.933  1017  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.933  1017  1450 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:56.933  1017  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:56.933  1017  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 13:44:56.933  1017  3970 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:56.933  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.933  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:56.933  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:56.933  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:56.933  2758  2758 I bluedroid: get_profile_interface handsfree
,08-29 13:44:56.943  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 13:44:56.943  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:44:56.943  2758  2815 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 13:44:56.943  1017  1323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:56.943  1017  1323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.943  1017  1323 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:56.943  1017  1323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:56.943  1017  1323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:56.943  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-29 13:44:56.943  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:44:56.943  2758  2815 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 13:44:56.953  1017  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:56.953  1017  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:44:56.953  1017  1487 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:56.953  1017  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:56.953  1017  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:56.953  2758  2758 E DualScoManager: Dual Sco Manager already instantiated
,08-29 13:44:56.953  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:56.953  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:56.953  2758  2758 I DualScoManager: Set HeadsetServiceHelper
08-29 13:44:56.953  2758  2758 D BluetoothAtMessage: createCMTIContentObservers
08-29 13:44:56.953  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:44:56.953  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:56.953  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:56.953  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:44:56.953  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 13:44:56.953  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:44:56.953  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 13:44:56.953  2758  2815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-29 13:44:56.953  2758  2815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 13:44:56.953  2758  2815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 13:44:56.953  2758  2815 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 13:44:56.953  1017  1030 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-29 13:44:56.953  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:44:56.953  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:44:56.953  1017  1030 D SettingsProvider: selectionArgs: false
08-29 13:44:56.953  1017  1030 D SettingsProvider: selectionArgs: 1002
08-29 13:44:56.953  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:44:56.953  1017  1030 D SettingsProvider: ret = -1
,08-29 13:44:56.963  2758  7527 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 13:44:56.963  2758  2758 D HeadsetService: mStartError = false
08-29 13:44:56.963  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:56.963  2758  2758 D A2dpService: Received start request. Starting profile...
08-29 13:44:56.963  2758  2758 D A2dpService: start()
08-29 13:44:56.963  2758  2758 I bluedroid: get_profile_interface avrcp
,08-29 13:44:56.963  2758  7527 D HeadsetStateMachine: Clear mHeadsetBrsf
08-29 13:44:56.963  2758  7527 D HeadsetStateMachine: map size, before remove : 0
08-29 13:44:56.963  2758  7527 D HeadsetStateMachine: map size, after remove: 0
,08-29 13:44:56.963  2758  2758 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:44:56.963  2758  2758 D Avrcp   : Initialize Media Controller
08-29 13:44:56.963  2758  2758 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 13:44:56.963  2758  2758 E Avrcp   : getActiveSessions
,08-29 13:44:56.963  2758  2758 D Avrcp   : pick active media Controller
08-29 13:44:56.963  2758  2758 D Avrcp   : Get the active Media Controller 
,08-29 13:44:56.973  2758  2758 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 13:44:56.973  2758  2758 D A2dpStateMachine: make
,08-29 13:44:56.973  2758  7528 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 13:44:56.973  2758  2758 I bluedroid: get_profile_interface a2dp
,08-29 13:44:56.973  2758  7530 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-29 13:44:56.983  2758  2758 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 13:44:56.983  2758  2758 D A2dpService: mStartError = false
08-29 13:44:56.983  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:56.983  2758  2758 D HidService: Received start request. Starting profile...
08-29 13:44:56.983  2758  2758 D HidService: start()
08-29 13:44:56.983  2758  2758 I bluedroid: get_profile_interface hidhost
08-29 13:44:56.983  2758  2758 D HidService: setHidService(): set to: null
08-29 13:44:56.983  2758  2758 D HidService: mStartError = false
08-29 13:44:56.983  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:56.983  2758  7529 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:44:56.983  2758  2758 D HealthService: Received start request. Starting profile...
08-29 13:44:56.983  2758  2758 D HealthService: start()
,08-29 13:44:56.983  2758  2758 I bluedroid: get_profile_interface health
08-29 13:44:56.983  2758  2758 D HealthService: mStartError = false
08-29 13:44:56.983  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:56.983  2758  2758 D HeadsetStateMachine: Try to query the phonestate on bind
08-29 13:44:56.983  1428  1454 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 13:44:56.983  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-29 13:44:56.983  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-29 13:44:56.983  1428  1454 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 13:44:56.983  2758  2758 D HeadsetStateMachine: Proxy object connected
08-29 13:44:56.983  2758  2758 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 13:44:56.983  2758  7527 D HeadsetStateMachine: Disconnected process message: 11
08-29 13:44:56.983  2758  2758 D PanService: Received start request. Starting profile...
08-29 13:44:56.983  2758  2758 D PanService: start()
08-29 13:44:56.983  2758  2758 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:44:56.983  2758  2758 I bluedroid: get_profile_interface pan
08-29 13:44:56.983  2758  2758 D PanService: mStartError = false
08-29 13:44:56.983  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:56.983  2758  2758 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 13:44:56.983  2758  2758 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-29 13:44:56.983  2758  7527 D HeadsetStateMachine: Disconnected process message: 18
,08-29 13:44:56.983  2758  2758 D BluetoothMapService: Received start request. Starting profile...
08-29 13:44:56.993  2758  2758 D BluetoothMapService: start()
,08-29 13:44:56.993  2758  2758 D BluetoothMapService: mStartError = false
08-29 13:44:56.993  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:56.993  2758  2758 D SapService: Received start request. Starting profile...
08-29 13:44:56.993  2758  2758 D SapService: start()
08-29 13:44:56.993  2758  7528 D BluetoothMediaBrowser: no now playing list
08-29 13:44:56.993  2758  2758 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 13:44:56.993  2758  2758 I bluedroid: get_profile_interface sap
08-29 13:44:56.993  2758  7528 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-29 13:44:56.993  2758  2758 D SapService: mStartError = false
08-29 13:44:56.993  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
08-29 13:44:56.993  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 13:44:56.993  2758  2758 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 13:44:56.993  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 13:44:56.993  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-29 13:44:56.993  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 13:44:56.993  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-29 13:44:56.993  2758  7527 D HeadsetStateMachine: Disconnected process message: 10
08-29 13:44:56.993  2758  7527 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:44:56.993  2758  7527 D HeadsetStateMachine: Disconnected process message: 11
,08-29 13:44:57.003  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-29 13:44:57.013  2758  2758 E BluetoothAdapterService(582305208): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 13:44:57.013  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 13:44:57.013  2758  2815 I bluedroid: enable
,08-29 13:44:57.013  2758  2818 E bt-btif : Calling BTA_HhEnable
,08-29 13:44:57.013  2758  2818 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,08-29 13:44:57.023  2758  2818 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 13:44:57.023  2758  2818 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-29 13:44:57.023  2758  2818 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,08-29 13:44:57.023  2758  2818 E BluetoothServiceJni: populateRssiValuesNative
,08-29 13:44:57.023  2758  2818 I bluedroid: getModelRssiValues
08-29 13:44:57.023  2758  2818 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 13:44:57.023  2758  2818 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 13:44:57.023  1017  1017 D SettingsProvider: name = bluetooth_name
,08-29 13:44:57.023  2758  2818 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-29 13:44:57.033  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:57.033  2758  2818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 13:44:57.033  2758  2818 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:44:57.033  2758  2818 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:44:57.033  2758  2818 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-29 13:44:57.033  2758  2818 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-29 13:44:57.033  2758  2818 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-29 13:44:57.033  2758  2818 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 13:44:57.033  2758  2818 E bt-btif : JVenable fails
,08-29 13:44:57.033  2758  2818 D bte_conf: Device ID record 1 : primary
,08-29 13:44:57.033  2758  2818 D bte_conf:   vendorId            = 0075
08-29 13:44:57.033  2758  2818 D bte_conf:   vendorIdSource      = 0001
08-29 13:44:57.033  2758  2818 D bte_conf:   product             = 0100
08-29 13:44:57.033  2758  2818 D bte_conf:   version             = 0200
,08-29 13:44:57.033  2758  2818 D bte_conf:   clientExecutableURL = 
,08-29 13:44:57.033  2758  2818 D bte_conf:   serviceDescription  = 
08-29 13:44:57.033  2758  2818 D bte_conf:   documentationURL    = 
08-29 13:44:57.033  2758  2818 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 13:44:57.033  2758  2815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 13:44:57.033  2758  2815 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:44:57.033  2758  2815 D BluetoothAdapterProperties: State =  11
,08-29 13:44:57.033  2758  2818 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-29 13:44:57.033  2758  2818 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 13:44:57.033  1017  1323 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 13:44:57.043  2758  2815 D BluetoothAdapterProperties: Setting state to 12
08-29 13:44:57.043  2758  2815 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 13:44:57.043  1017  1504 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 13:44:57.043  1017  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:44:57.043  1017  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:44:57.043  1017  1504 D SettingsProvider: selectionArgs: false
08-29 13:44:57.043  1017  1504 D SettingsProvider: selectionArgs: 1002
08-29 13:44:57.043  1017  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:44:57.043  1017  1504 D SettingsProvider: ret = -1
,08-29 13:44:57.043  2758  2815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:44:57.043  2758  2815 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 13:44:57.043  1017  1078 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:57.043  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.043  2758  2818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:44:57.043  2758  2818 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:44:57.043  2758  2818 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:44:57.043  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.043  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.043  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.043  2758  2815 D BluetoothAdapterService: Autoconnection is available 
,08-29 13:44:57.043  2758  2815 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 13:44:57.043  2758  2815 D BluetoothAdapterService: starting service from this receiver
08-29 13:44:57.043  1746  1761 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:57.043  1746  1761 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:57.043  1017  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:44:57.043  4454  4464 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:57.053  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.053  2758  2758 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-29 13:44:57.053  2758  2758 I BluetoothPbapService: Handler(): got msg=1
08-29 13:44:57.053  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.053  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.053  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:44:57.053  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:57.053  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:57.053  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:57.053  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:57.053  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:57.053  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:57.053  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:57.053  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:57.053  1017  1078 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-29 13:44:57.053  2758  2815 I BluetoothAdapterState: Entering On State from state = 11
08-29 13:44:57.053  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:57.053  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 13:44:57.053  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.053  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.053  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.053  4454  4464 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:44:57.053  1017  1046 D BluetoothPan: Binding service...
,08-29 13:44:57.053  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 13:44:57.053  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.053  4454  7473 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 13:44:57.053  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:57.063  2758  7535 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 13:44:57.063  2758  7535 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 13:44:57.063  2758  7535 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:44:57.083  2758  7535 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-29 13:44:57.083  2758  7535 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:44:57.083  2758  7535 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:44:57.083  2758  7535 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f4a756b
08-29 13:44:57.083  2758  7535 D BluetoothSocket: channel: 19
,08-29 13:44:57.083  2758  7535 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-29 13:44:57.203  1017  1046 I art     : Explicit concurrent mark sweep GC freed 63413(3MB) AllocSpace objects, 6(97KB) LOS objects, 33% free, 22MB/34MB, paused 2.339ms total 142.564ms
08-29 13:44:57.203  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 13:44:57.203  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.203  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.203  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.203  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.203  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:57.203  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:57.203  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:57.203  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:57.203  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 13:44:57.203  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:44:57.203  1172  2008 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:44:57.203  1172  2008 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:57.213  6633  6641 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:57.213  6633  6641 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:57.213  2758  2876 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:44:57.213  2758  2876 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:57.213  4454  4454 D HeadsetProfile: Bluetooth service connected
08-29 13:44:57.213  1017  1046 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:44:57.213  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.213  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.213  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.213  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.213  1428  1459 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:57.213  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:57.213  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:44:57.213  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.213  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.213  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.223  1428  1459 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:44:57.223  4454  7473 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:44:57.223  2758  2758 D BluetoothA2dp: Proxy object connected
,08-29 13:44:57.223  2758  2758 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 13:44:57.223  4454  4454 D BluetoothPbap: Proxy object connected
08-29 13:44:57.223  4454  4454 D PbapServerProfile: Bluetooth service connected
,08-29 13:44:57.223  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:44:57.223  4454  7473 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:57.223  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:44:57.223  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.223  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.223  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.223  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-29 13:44:57.223  4454  4462 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 13:44:57.223  4454  4454 D BluetoothA2dp: Proxy object connected
08-29 13:44:57.223  4454  4454 D A2dpProfile: Bluetooth service connected
,08-29 13:44:57.223  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 13:44:57.223  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.223  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.223  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.223  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.223  1463  1482 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:44:57.223  1463  1482 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:57.223  4454  4464 D Bluetoothsap: onBluetoothStateChange: up=true
08-29 13:44:57.223  4454  4464 D Bluetoothsap: Binding service...
,08-29 13:44:57.223  4454  4454 D BluetoothInputDevice: Proxy object connected
08-29 13:44:57.223  4454  4454 D HidProfile: Bluetooth service connected
,08-29 13:44:57.223  4454  4464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 13:44:57.233  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-29 13:44:57.233  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.233  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.233  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.233  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.233  4454  4464 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 13:44:57.233  1680  2079 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:44:57.233  1680  2079 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:57.233  4454  4454 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 13:44:57.233  4454  4454 D SapProfile: Bluetooth service connected
08-29 13:44:57.233  4454  4454 D Bluetoothsap: getConnectedDevices()
08-29 13:44:57.233  1428  7474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:57.233  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:57.233  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:44:57.233  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.233  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.233  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.233  1428  7474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:44:57.233  1463  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:44:57.233  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 13:44:57.243  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:44:57.243  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.243  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.243  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.243  1463  1475 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:44:57.243  4454  7473 D BluetoothPan: Binding service...
,08-29 13:44:57.243  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 13:44:57.243  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.243  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.243  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.243  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.243  4454  4454 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:44:57.243  4454  4454 D PanProfile: Bluetooth service connected
08-29 13:44:57.243  4454  4464 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 13:44:57.243  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-29 13:44:57.243  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.253  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.253  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.253  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.253  1428  1459 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-29 13:44:57.253  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:44:57.253  1428  1459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:57.253  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3,
08-29 13:44:57.253  1428  1454 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-29 13:44:57.253  4454  4454 D BluetoothMap: Proxy object connected
08-29 13:44:57.253  4454  4454 D MapProfile: Bluetooth service connected
08-29 13:44:57.253  4454  4454 D BluetoothMap: getConnectedDevices()
08-29 13:44:57.253  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.253  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.253  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.253  1428  1454 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:44:57.253  7481  7496 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:57.253  7481  7496 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:57.253  2758  7477 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:44:57.253  2758  7477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:57.253  4454  7473 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:57.253  4454  7473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:44:57.253  1443  1477 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:44:57.253  1443  1477 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:44:57.253  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:44:57.253  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 13:44:57.253  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 13:44:57.253  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.263  1017  1017 D BluetoothA2dp: Proxy object connected
,08-29 13:44:57.263  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt,
08-29 13:44:57.263  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 13:44:57.263  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:57.263  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-29 13:44:57.263  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 13:44:57.273  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@299f495c, true
,08-29 13:44:57.273  1172  1172 D BluetoothTile:  onBluetoothStateChange:
,08-29 13:44:57.273  1172  1172 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:44:57.273  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:57.273  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:57.273  1172  1172 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:57.273  1172  1172 D BluetoothTile:  getBluetoothState : 12
,08-29 13:44:57.273  1172  1774 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:44:57.283  1428  1428 D BluetoothHeadset: registerMessageListener
,08-29 13:44:57.283  1017  1504 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:57.283  1872  1872 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:44:57.283  1017  1450 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-29 13:44:57.283  4454  4454 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:57.283  1172  1172 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:44:57.283  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:57.293  2758  2876 D HeadsetService: registerMessageListener
,08-29 13:44:57.293  2758  2876 D HeadsetService: registerMessageListener
,08-29 13:44:57.293  2758  7527 D HeadsetStateMachine: Disconnected process message: 70
08-29 13:44:57.293  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 13:44:57.293  2758  7527 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@17be9d61
08-29 13:44:57.293  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 13:44:57.293  2758  7536 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-29 13:44:57.293  4454  4454 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-29 13:44:57.293  4454  4454 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 13:44:57.293  4454  4454 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-29 13:44:57.293  4454  4454 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 13:44:57.293  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-29 13:44:57.293  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-29 13:44:57.293  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 13:44:57.293  2758  7527 D HeadsetStateMachine: Disconnected process message: 9
,08-29 13:44:57.293  2758  7527 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 13:44:57.303   283   705 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 13:44:57.303   283   705 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 13:44:57.303   283   705 V voice   : voice_set_parameters: exit with code(-2)
08-29 13:44:57.303   283   705 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 13:44:57.303   283   705 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 13:44:57.303   283   705 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 13:44:57.303   283   705 V audio_hw_primary: adev_set_parameters: exit
08-29 13:44:57.303  2758  7527 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 13:44:57.303  2758  7536 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:44:57.303  2758  7536 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:44:57.303  2758  7536 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-29 13:44:57.303  2758  7536 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:44:57.303  2758  7536 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:44:57.303  2758  7536 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a22c086
08-29 13:44:57.303  2758  7536 D BluetoothSocket: channel: 5
,08-29 13:44:57.303  4454  4454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:44:57.303  1017  3971 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 13:44:57.303  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.303  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.303  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:57.303  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:44:57.313  1680  1680 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 13:44:57.313  4454  4454 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:44:57.323  4454  4454 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:44:57.323  1172  1172 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:44:57.323  1172  1172 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 13:44:57.333  2758  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22b545b8
,08-29 13:44:57.333  2758  2758 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 13:44:57.333  1017  1447 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:44:57.333  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 13:44:57.333  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:44:57.333  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:57.333  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:44:57.343  1017  1504 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 13:44:57.363  2758  7541 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:44:57.363  2758  7541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:44:57.363  2758  7541 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[87]}
,08-29 13:44:57.363  2758  7541 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:44:57.363  2758  7541 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:44:57.363  2758  7541 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@175a5f12
,08-29 13:44:57.363  2758  7541 D BluetoothSocket: channel: 12
08-29 13:44:57.363  2758  7541 I BtOppRfcommListener: Accept thread started.
,08-29 13:44:57.873  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:57.873  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:57.873  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:57.873  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:44:57.873  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:57.873  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:57.873  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:57.873  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:57.873  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:57.873  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:44:57.883  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e20ef06 added. We now have 8 listener(s)
,08-29 13:44:57.883  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:44:57.883  1017  3970 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 13:44:57.883  1017  3970 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 13:44:57.883  1017  3970 D SecContentProvider2: mCursor = null
,08-29 13:44:57.883  1017  3970 D WifiService: setWifiEnabled: false pid=6633, uid=10170
,08-29 13:44:57.883  1017  3970 D SettingsProvider: name = wifi_on
,08-29 13:44:57.893  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:57.893  1017  1447 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 13:44:57.893  1017  1447 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 13:44:57.893  1017  1447 D SecContentProvider2: mCursor = null
,08-29 13:44:57.893  1017  1447 D WifiService: setWifiEnabled: true pid=6633, uid=10170
,08-29 13:44:57.893  1017  1447 W ActivityManager: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:44:57.903  1017  1447 W WifiService: Failed getting userId using ActivityManagerNative
08-29 13:44:57.903  1017  1447 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6633, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:44:57.903  1017  1447 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:44:57.903  1017  1447 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 13:44:57.903  1017  1447 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 13:44:57.903  1017  1447 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 13:44:57.903  1017  1447 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 13:44:57.903  1017  1447 D SettingsProvider: name = wifi_on
,08-29 13:44:57.903  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 13:44:58.103   288   288 E SMD     : DCD OFF
,08-29 13:44:58.243  1017  1044 D Tethering: interfaceAdded wlan0
,08-29 13:44:58.243  1017  1132 E Tethering: No numeric data
,08-29 13:44:58.253  1017  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-29 13:44:58.253  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:44:58.253  1017  1132 D Tethering: clearTetheredNotification()
08-29 13:44:58.253  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:58.253  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 13:44:58.253  1172  1172 D HotspotTile: updateTetherState():false, false,
08-29 13:44:58.253  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:58.253  1017  1124 V NetworkStats: performPollLocked() took 8ms
08-29 13:44:58.253  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-29 13:44:58.253  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:58.263  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:58.263  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:58.263  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:44:58.263  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:58.263  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:58.263  1017  1132 D Tethering: InitialState.processMessage what=4,
,08-29 13:44:58.263  1017  1132 E Tethering: No numeric data,
08-29 13:44:58.263  1017  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:44:58.263  1017  1132 D Tethering: clearTetheredNotification()
08-29 13:44:58.273  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-29 13:44:58.273  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:58.273  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:44:58.273  1172  1172 D HotspotTile: updateTetherState():false, false
,08-29 13:44:58.273  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:44:58.273  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:44:58.273  1017  1044 D Tethering: interfaceAdded p2p0
,08-29 13:44:58.283  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring,
,08-29 13:44:58.283  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:44:58.283  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 13:44:58.283  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-29 13:44:58.283   278  1003 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-29 13:44:58.293  1017  1124 V NetworkStats: performPollLocked() took 16ms,
08-29 13:44:58.293   278  1003 D SoftapController: Softap fwReload - Ok
08-29 13:44:58.293  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:58.293  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:44:58.293  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:44:58.293   278  1003 D CommandListener: Setting iface cfg,
08-29 13:44:58.293   278  1003 D CommandListener: Trying to bring down wlan0
08-29 13:44:58.293   278  1003 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:44:58.303  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 13:44:58.343  7554  7554 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-29 13:44:58.343  7554  7554 I wpa_supplicant: Successfully initialized wpa_supplicant,
08-29 13:44:58.343  7554  7554 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 13:44:58.353  7554  7554 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-29 13:44:58.363   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7554,
08-29 13:44:58.363   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 13:44:58.363  7554  7554 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 13:44:58.363  7554  7554 I wpa_supplicant: ssSupport state is = 1
08-29 13:44:58.363  7554  7554 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-29 13:44:58.363  7554  7554 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 13:44:58.363   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7554
08-29 13:44:58.363   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-29 13:44:58.403  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-29 13:44:58.423  4454  4454 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:58.423  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:44:58.433  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:58.433  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:44:58.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:58.433  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:58.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:58.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:58.433  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:58.433  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:58.433  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-29 13:44:58.433  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 13:44:58.433  1172  1172 D HotspotTile: onReceive : 2, 0
,08-29 13:44:58.433  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:44:58.433  1017  3970 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:44:58.433  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:44:58.443  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:58.443  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:44:58.443  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:44:58.443  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:44:58.443  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:44:58.443  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 13:44:58.443  6860  6860 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:44:58.453  1609  1609 I Hs20UtilService: Starting #19
,08-29 13:44:58.453  1609  1651 I Hs20UtilService: Message received 5011
,08-29 13:44:58.543   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-29 13:44:58.553  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-29 13:44:58.593  7554  7554 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-29 13:44:58.593  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 13:44:58.603  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-29 13:44:58.603   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7554
08-29 13:44:58.603   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 13:44:58.603  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-29 13:44:58.603  7554  7554 I wpa_supplicant: ssSupport state is = 1
08-29 13:44:58.603  7554  7554 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:58.603  7554  7554 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:44:58.603  7554  7554 E wpa_supplicant: SIM READ ERROR
08-29 13:44:58.603  7554  7554 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 13:44:58.603  7554  7554 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:44:58.603  7554  7554 E wpa_supplicant: SIM READ ERROR
08-29 13:44:58.603  7554  7554 I wpa_supplicant: Blacklist: Clear (all) 
08-29 13:44:58.603  7554  7554 I wpa_supplicant: wpa_default_ap_write_once
,08-29 13:44:58.603  7554  7554 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 13:44:58.603  7554  7554 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:58.603  7554  7554 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 13:44:58.603  7554  7554 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:58.603  7554  7554 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-29 13:44:58.613  7554  7554 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:44:58.613  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:44:58.613  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:44:58.613  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:44:58.663  7554  7554 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 13:44:58.773  7554  7554 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-29 13:44:58.773  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-29 13:44:58.783  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 13:44:58.783   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7554
08-29 13:44:58.783   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-29 13:44:58.783  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 13:44:58.793  7554  7554 I wpa_supplicant: ssSupport state is = 1,
08-29 13:44:58.793  7554  7554 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 13:44:58.793  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 13:44:58.803  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 13:44:58.803   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7554
08-29 13:44:58.803   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-29 13:44:58.803  7554  7554 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 13:44:58.803  7554  7554 I wpa_supplicant: ssSupport state is = 1,
08-29 13:44:58.803  7554  7554 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:58.803  7554  7554 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 13:44:58.803  7554  7554 E wpa_supplicant: SIM READ ERROR
08-29 13:44:58.803  7554  7554 I wpa_supplicant: wpa_default_ap_write_once
08-29 13:44:58.803  7554  7554 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-29 13:44:58.803  7554  7554 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:44:58.813  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:44:58.813  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 13:44:58.813  1017  1044 D Tethering: interfaceStatusChanged p2p0, false,
,08-29 13:44:58.813  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:44:58.813  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-29 13:44:58.813  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:44:58.883  7554  7554 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 13:44:58.883  7554  7554 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 13:44:59.013  7554  7554 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-29 13:44:59.013  7554  7554 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 13:44:59.013  7554  7554 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 13:44:59.023  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-29 13:44:59.023  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 13:44:59.023  7554  7554 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-29 13:44:59.023  7554  7554 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:44:59.023  7554  7554 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:44:59.023  7554  7554 E wpa_supplicant: SIM READ ERROR
08-29 13:44:59.023  7554  7554 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 13:44:59.043  7554  7554 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 13:44:59.053  7554  7554 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-29 13:44:59.063  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-29 13:44:59.063  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:44:59.063  1172  1172 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:59.063  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:44:59.063  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:44:59.063  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:59.063  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:44:59.063  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:59.063  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:44:59.063  1172  1172 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:44:59.063  1172  1172 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-29 13:44:59.073  1172  1774 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 13:44:59.073  1172  1172 D HotspotTile: onReceive : 3, 0
08-29 13:44:59.073  4454  4454 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:44:59.073  1017  1447 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:44:59.073  1017  1447 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:44:59.073  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:59.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:59.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:59.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:59.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:59.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:59.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:59.073  6633  6633 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:59.083  1017  1127 E WifiConfigStore: Not a HS20
,08-29 13:44:59.083  1017  1447 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:44:59.083  1017  1447 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:44:59.083  1017  1447 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:44:59.083  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 13:44:59.083  6633  6633 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:59.083  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 13:44:59.083  7554  7554 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 13:44:59.083  7554  7554 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 13:44:59.093  7554  7554 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 13:44:59.093  7554  7554 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 13:44:59.093  7554  7554 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 13:44:59.093  7554  7554 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 13:44:59.093  7554  7554 I wpa_supplicant: First Scan Start
08-29 13:44:59.093  7554  7554 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-29 13:44:59.093  1609  1609 I Hs20UtilService: Starting #20
,08-29 13:44:59.093  1609  1651 I Hs20UtilService: Message received 5011
,08-29 13:44:59.093  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-29 13:44:59.093  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:44:59.093  1017  1127 I WifiNative-HAL: startHal
08-29 13:44:59.093  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9e97488c
08-29 13:44:59.093  1017  1127 I WifiNative-HAL: Could not start hal
,08-29 13:44:59.093  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 13:44:59.093  6860  6860 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:44:59.093  6860  6860 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:44:59.103  6860  6860 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:44:59.103  7085  7085 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:44:59.103  1017  1127 E WifiNative-wlan0: do suspend true
,08-29 13:44:59.103  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 13:44:59.103   278  1003 D CommandListener: Setting iface cfg
08-29 13:44:59.103   278  1003 D CommandListener: Trying to bring up p2p0
,08-29 13:44:59.103  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 13:44:59.103  1017  1126 D WifiP2pService: P2pEnablingState
08-29 13:44:59.103  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 13:44:59.103  1017  1126 D WifiP2pService: P2p socket connection successful
08-29 13:44:59.103  1017  1126 D WifiP2pService: P2pEnabledState
,08-29 13:44:59.113  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-29 13:44:59.113  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-29 13:44:59.113  1017  1151 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:44:59.113  1017  1151 I WifiNative-HAL: startHal
,08-29 13:44:59.113  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x990199bc
08-29 13:44:59.113  1017  1151 I WifiNative-HAL: Could not start hal
08-29 13:44:59.113  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-29 13:44:59.113  1017  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:44:59.113  1017  1151 E WifiScanningService: could not start HAL
,08-29 13:44:59.113  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 13:44:59.113  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 13:44:59.113  1017  1127 E WifiNative-wlan0: invaild command id : 215
,08-29 13:44:59.113  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 13:44:59.113  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 13:44:59.113  1017  1127 E WifiNative-wlan0: invaild command id : 215
,08-29 13:44:59.113  7554  7554 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-29 13:44:59.113  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 13:44:59.113  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-29 13:44:59.123  7554  7554 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:44:59.123  7554  7554 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 13:44:59.123  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 13:44:59.123  1017  1127 E WifiStateMachine: Failed to set frequency band 0
,08-29 13:44:59.123  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 13:44:59.123  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:44:59.123  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:44:59.123  1017  1047 D WifiDisplayController: disconnect
,08-29 13:44:59.123  1017  1127 D SecContentProvider2: mCursor = null
08-29 13:44:59.123  1017  1047 D WifiDisplayController: updateConnection
08-29 13:44:59.123  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:44:59.123  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 13:44:59.123  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:44:59.123  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:44:59.123  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:44:59.123  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:44:59.123  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:44:59.123  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 13:44:59.123  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-29 13:44:59.133  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,08-29 13:44:59.133  1172  1172 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 13:44:59.133  1017  1504 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 13:44:59.133  1172  1172 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 13:44:59.133  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:44:59.133  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:44:59.133  1017  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,08-29 13:44:59.133  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  secondary type: null
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  wps: 0
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  grpcapab: 0
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  devcapab: 0
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  status: 3
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  wfdInfo: null
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-29 13:44:59.133  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-29 13:44:59.143  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:44:59.143  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 13:44:59.143  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:44:59.143  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:44:59.143  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:44:59.143  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:44:59.143  7039  7039 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 13:44:59.143  7039  7039 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 13:44:59.153  7070  7070 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:44:59.163  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 13:44:59.163  1017  1126 D WifiP2pService: InactiveState
,08-29 13:44:59.163  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-29 13:44:59.163  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 13:44:59.163  7554  7554 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:44:59.163  1017  1126 D WifiP2pService: InactiveState{ what=143376 },
,08-29 13:44:59.163  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 13:44:59.263  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-29 13:44:59.263  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 13:44:59.263  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:44:59.923  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:44:59.923  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:44:59.923  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:44:59.923  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:44:59.923  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:44:59.923  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:44:59.923  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:44:59.923  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:44:59.923  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:44:59.933  6633  6774 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 13:44:59.933  6633  6774 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 13:44:59.933  6633  6774 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@22f271a6 Bundle[{}]
,08-29 13:44:59.933  6633  6774 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 13:44:59.933  6633  6774 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 13:44:59.933  6633  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 13:44:59.933  6633  6774 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 13:44:59.943  6633  6774 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 13:44:59.943  6633  6774 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:44:59.943  6633  6774 I System.out: Running OutgoingSocketThread
,08-29 13:44:59.943  6633  7563 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1334)
,08-29 13:44:59.953  6633  7563 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37498
,08-29 13:44:59.953  6633  7563 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 13:44:59.993  1017  1096 V AlarmManager: waitForAlarm result :8
,08-29 13:45:00.403  7554  7554 I wpa_supplicant: nl80211: Received scan results (21 BSSes),
08-29 13:45:00.403  7554  7554 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 13:45:00.403  7554  7554 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 13:45:00.403  7554  7554 I wpa_supplicant: Trying to associate with  'G700'
08-29 13:45:00.403  7554  7554 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 13:45:00.403  7554  7554 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-29 13:45:00.403  1017  7560 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 13:45:00.423  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-29 13:45:00.423  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:45:00.533  7554  7554 E wpa_supplicant: Cmd 35605 not handled
,08-29 13:45:00.533  7554  7554 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-29 13:45:00.533  7554  7554 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-29 13:45:00.533  7554  7554 I wpa_supplicant: Associated with F4.99.3E
08-29 13:45:00.533  7554  7554 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 13:45:00.533  7554  7554 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 13:45:00.533  7554  7554 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-29 13:45:00.533  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:45:00.533  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:45:00.533  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:45:00.533  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:45:00.533  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:45:00.533  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:45:00.543  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:45:00.543  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:45:00.543  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:45:00.543  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 13:45:00.543  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 13:45:00.543  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-29 13:45:00.543  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:45:00.543  1017  1127 D SecContentProvider2: mCursor = null
08-29 13:45:00.543  7554  7554 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-29 13:45:00.543  7554  7554 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 13:45:00.543  1017  1132 E Tethering: No numeric data
,08-29 13:45:00.543  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:45:00.543  1017  1127 D SecContentProvider2: mCursor = null
08-29 13:45:00.543  1017  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 13:45:00.543  1017  1132 D Tethering: clearTetheredNotification()
,08-29 13:45:00.543  7554  7554 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-29 13:45:00.543  7554  7554 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 13:45:00.543  7554  7554 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-29 13:45:00.543  7554  7554 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 13:45:00.543  7554  7554 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 13:45:00.553  7554  7554 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 13:45:00.553  7554  7554 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 13:45:00.553  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:45:00.553  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:00.553  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 13:45:00.553  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 13:45:00.553  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-29 13:45:00.553  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:45:00.553  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:45:00.553  1172  1172 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:45:00.553  1172  1172 D HotspotTile: updateTetherState():false, false
,08-29 13:45:00.553  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:00.553  1017  1124 V NetworkStats: performPollLocked() took 5ms
,08-29 13:45:00.553  1017  2838 D SSRM:n  : SIOP:: AP = 350
,08-29 13:45:00.553  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:00.553  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:00.553  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-29 13:45:00.563  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-29 13:45:00.563  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:45:00.563  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:45:00.563  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-29 13:45:00.573  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:00.573  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:00.573  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:45:00.573  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:45:00.573  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 13:45:00.573  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:00.573  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:45:00.573  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 13:45:00.573  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:45:00.573  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:45:00.573  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:00.573  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:45:00.573  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:45:00.573  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:45:00.573  1609  1609 I Hs20UtilService: Starting #21
,08-29 13:45:00.573  1609  1651 I Hs20UtilService: Message received 5007
,08-29 13:45:00.573  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-29 13:45:00.583  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:45:00.583  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:45:00.583  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 13:45:00.583  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 13:45:00.583  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:45:00.583  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:45:00.593  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:45:00.603   278  1003 D CommandListener: Setting iface cfg
,08-29 13:45:00.603  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-29 13:45:00.603  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:45:00.603  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:45:00.613  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:45:00.613  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:45:00.613  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 13:45:00.623  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 13:45:00.623  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:00.623  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:00.623  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:45:00.623  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:45:00.623  1017  1127 D SecContentProvider2: mCursor = null
,08-29 13:45:00.633  1017  1127 E WifiNative-wlan0: do suspend false
,08-29 13:45:00.633  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-29 13:45:00.633  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 13:45:00.843  7566  7566 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 13:45:00.853  7566  7566 I dhcpcd  : version 5.5.6 starting,
,08-29 13:45:00.853  7566  7566 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 13:45:00.913  7566  7566 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 13:45:00.913  7566  7566 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 13:45:00.913  7566  7566 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-29 13:45:00.913  7566  7566 I dhcpcd  : bssid match,
08-29 13:45:00.913  7566  7566 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-29 13:45:00.953  6633  6774 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1335),
08-29 13:45:00.953  6633  6774 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1335)
,08-29 13:45:00.953  6633  6774 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1340)
08-29 13:45:00.953  6633  6774 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 13:45:00.953  6633  6774 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1341),
08-29 13:45:00.953  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:00.953  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@117dc9c7 added. We now have 2 listener(s)
,08-29 13:45:00.963  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:45:00.963  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:00.963  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:00.963  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:00.963  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf3bbf4 added. We now have 9 listener(s)
,08-29 13:45:00.963  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:00.963  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:00.973  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:00.973  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:00.973  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:00.973  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:00.973  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:00.973  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:00.973  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:00.973  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:00.973  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:00.973  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:45:00.973  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:45:00.983  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:00.983  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b4cf592 added. We now have 3 listener(s)
,08-29 13:45:00.983  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:00.983  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:00.983  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:45:00.983  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:00.983  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:00.983  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:00.983  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23833b63 added. We now have 10 listener(s)
,08-29 13:45:00.983  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:00.993  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:00.993  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:45:00.993  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:45:00.993  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:45:00.993  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:00.993  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:45:00.993  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:00.993  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@117dc9c7 removed from the list
,08-29 13:45:00.993  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:00.993  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf3bbf4 removed from the list
08-29 13:45:00.993  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:45:00.993  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:45:00.993  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:00.993  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:45:00.993  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:45:00.993  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:45:00.993  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:00.993  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cf3bbf4 not in the list
,08-29 13:45:00.993  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:00.993  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.003  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:45:01.003  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:01.003  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:01.003  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23833b63 removed from the list
08-29 13:45:01.003  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.003  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:45:01.003  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.003  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:01.003  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b4cf592 removed from the list
,08-29 13:45:01.003  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:01.003  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8aa360 added. We now have 2 listener(s)
,08-29 13:45:01.003  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:45:01.003  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:01.003  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:01.003  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:01.003  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@310f0019 added. We now have 9 listener(s)
,08-29 13:45:01.003  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:01.003  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:01.013  7566  7566 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
08-29 13:45:01.013  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:01.013  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-29 13:45:01.013  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:01.013  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:01.013  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:01.013  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:01.013  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:01.013  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-29 13:45:01.013  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:01.013  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:45:01.013  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:45:01.013  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:01.013  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ae42abf added. We now have 3 listener(s)
08-29 13:45:01.023  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:01.023  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 13:45:01.023  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 13:45:01.023  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:01.023  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:01.023  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:01.023  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26e6958c added. We now have 10 listener(s)
08-29 13:45:01.023  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:01.023  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:45:01.023  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:45:01.023  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:45:01.023  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:01.023  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:45:01.023  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-29 13:45:01.033  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:45:01.033  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:45:01.033  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:45:01.033  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:45:01.033  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:45:01.033  2758  3260 D BtGatt.GattService: registerClient() - UUID=7c862072-1e47-411d-ad30-faf4db5a3ff3,
,08-29 13:45:01.083  2758  2818 D BtGatt.GattService: onClientRegistered() - UUID=7c862072-1e47-411d-ad30-faf4db5a3ff3, clientIf=6
,08-29 13:45:01.083  6633  6641 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:45:01.083  2758  2770 D BtGatt.GattService: start scan with filters
,08-29 13:45:01.083  2758  2883 D BtGatt.ScanManager: handling starting scan
08-29 13:45:01.083  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:45:01.083  2758  2818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 13:45:01.083  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.083  2758  2883 D BtGatt.ScanManager: allow scan with filters
08-29 13:45:01.093  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:45:01.093  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:45:01.093  7566  7566 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
08-29 13:45:01.093  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 13:45:01.093  2758  2883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:45:01.093  2758  2883 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
08-29 13:45:01.093  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 13:45:01.093  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.093  2758  2883 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:45:01.093  2758  2883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-29 13:45:01.103  2758  2818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 13:45:01.103  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.103  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:45:01.103  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:45:01.103  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:45:01.103  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 13:45:01.103  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.103   288   288 E SMD     : DCD OFF
08-29 13:45:01.103  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 13:45:01.113  6633  6774 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:45:01.113  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:01.113  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:45:01.113  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.113  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:45:01.113  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:45:01.113  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:45:01.113  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:45:01.113  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:45:01.113  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:45:01.113  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:45:01.113  2758  2876 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:45:01.113  2758  2883 D BtGatt.ScanManager: filter size is 1
08-29 13:45:01.113  2758  2883 D BtGatt.ScanManager: delete FilterIndex - 6
08-29 13:45:01.113  2758  7476 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 13:45:01.113  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:45:01.113  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:45:01.113  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:45:01.113  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:45:01.113  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:45:01.123  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 13:45:01.123  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.123  2758  2883 D BtGatt.ScanManager: stopping BLe Batch
08-29 13:45:01.123  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:45:01.123  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:45:01.123  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.123  2758  2883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 13:45:01.123  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:45:01.123  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:45:01.123  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:45:01.123  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:01.133  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:01.133  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:01.133  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:45:01.133  2758  2818 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 13:45:01.133  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.143  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:01.143  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:01.143  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.143  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.143  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:01.143  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8aa360 removed from the list
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.143  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@310f0019 removed from the list
08-29 13:45:01.143  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:01.143  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 13:45:01.143  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.143  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.143  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@310f0019 not in the list
08-29 13:45:01.143  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.143  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.143  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26e6958c removed from the list
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.143  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.143  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.143  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:01.143  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ae42abf removed from the list
,08-29 13:45:01.143  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:01.143  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392d7e78 added. We now have 2 listener(s)
,08-29 13:45:01.153  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:45:01.153  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:01.153  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:01.153  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:01.153  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3db79951 added. We now have 9 listener(s)
08-29 13:45:01.153  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:01.153  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:01.163  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:01.163  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:01.163  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:01.163  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:01.163  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:01.163  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:01.163  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:01.163  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-29 13:45:01.163  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:01.163  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:45:01.163  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:01.163  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:01.163  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3da6b2b7 added. We now have 3 listener(s)
,08-29 13:45:01.163  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:01.173  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:45:01.173  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:01.173  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:01.173  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:01.173  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af80a24 added. We now have 10 listener(s)
08-29 13:45:01.173  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:01.173  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:01.173  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-29 13:45:01.173  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:45:01.173  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:45:01.173  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:01.173  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:45:01.173  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:01.173  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-29 13:45:01.173  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:45:01.183  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:45:01.183  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:45:01.183  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:45:01.183  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:45:01.193  2758  2876 D BtGatt.GattService: registerClient() - UUID=d1bdf37b-d376-4b01-b85b-fba218e79fed
,08-29 13:45:01.233  2758  2818 D BtGatt.GattService: onClientRegistered() - UUID=d1bdf37b-d376-4b01-b85b-fba218e79fed, clientIf=6
08-29 13:45:01.233  6633  6642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:45:01.243  2758  2770 D BtGatt.GattService: start scan with filters,
08-29 13:45:01.243  2758  2883 D BtGatt.ScanManager: handling starting scan
08-29 13:45:01.243  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:45:01.243  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:45:01.243  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:45:01.243  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:45:01.243  2758  2818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-29 13:45:01.243  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.243  2758  2883 D BtGatt.ScanManager: allow scan with filters
08-29 13:45:01.243  2758  2883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:45:01.243  2758  2883 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6,
,08-29 13:45:01.253  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 13:45:01.253  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-29 13:45:01.253  2758  2883 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:45:01.253  2758  2883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:45:01.253  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:45:01.253  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:45:01.253  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:01.253  2758  2818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 13:45:01.253  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.253  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:45:01.253  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 13:45:01.253  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.263  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
08-29 13:45:01.263  6633  6774 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 13:45:01.263  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:01.263  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:01.263  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.263  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.263  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:01.263  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@392d7e78 removed from the list
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.263  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3db79951 removed from the list
,08-29 13:45:01.263  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:01.263  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:01.263  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.263  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 13:45:01.263  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.263  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:01.263  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3db79951 not in the list
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:45:01.263  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:45:01.263  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:45:01.263  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:45:01.273  2758  7476 D BtGatt.GattService: stopScan() - queue size =1,
,08-29 13:45:01.273  2758  3260 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:45:01.273  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-29 13:45:01.273  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:45:01.273  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:45:01.273  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-29 13:45:01.273  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:45:01.273  2758  2883 D BtGatt.ScanManager: filter size is 1
08-29 13:45:01.273  2758  2883 D BtGatt.ScanManager: delete FilterIndex - 7
,08-29 13:45:01.283  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:45:01.283  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 13:45:01.283  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:45:01.283  2758  2883 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:45:01.283  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-29 13:45:01.283  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:45:01.283  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:45:01.283  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-29 13:45:01.283  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 13:45:01.283  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.283  2758  2883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 13:45:01.283  2758  2818 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 13:45:01.283  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.293  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:01.293  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:01.293  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.293  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af80a24 removed from the list
08-29 13:45:01.293  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.293  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.293  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.293  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:01.293  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3da6b2b7 removed from the list
08-29 13:45:01.293  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:01.293  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bda490 added. We now have 2 listener(s)
,08-29 13:45:01.293  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:01.293  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:01.293  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:45:01.293  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:45:01.293  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:01.293  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:01.293  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:01.293  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a432189 added. We now have 9 listener(s)
08-29 13:45:01.293  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:01.293  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:01.303  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:01.303  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:01.303  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:01.303  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:01.303  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:01.303  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:01.303  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:01.303  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:01.303  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:01.303  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:45:01.303  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:45:01.313  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:01.313  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:01.313  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:45:01.313  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@364341af added. We now have 3 listener(s)
,08-29 13:45:01.313  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:45:01.313  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:01.313  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:01.313  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:01.313  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@150079bc added. We now have 10 listener(s)
08-29 13:45:01.313  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:01.313  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:01.313  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:45:01.313  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:45:01.313  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:45:01.313  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:45:01.323  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:45:01.323  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:45:01.323  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:45:01.333  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:45:01.333  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:45:01.333  6633  6774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:45:01.333  2758  2767 D BtGatt.GattService: registerClient() - UUID=978f63f9-d4ff-48c6-a1c5-aec3ecbd5c85
,08-29 13:45:01.373  2758  2818 D BtGatt.GattService: onClientRegistered() - UUID=978f63f9-d4ff-48c6-a1c5-aec3ecbd5c85, clientIf=6
,08-29 13:45:01.373  6633  6642 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:45:01.373  2758  2876 D BtGatt.GattService: start scan with filters
,08-29 13:45:01.373  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:45:01.373  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:45:01.373  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:45:01.373  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:45:01.383  2758  2883 D BtGatt.ScanManager: handling starting scan
,08-29 13:45:01.383  2758  2818 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 13:45:01.383  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.383  2758  2883 D BtGatt.ScanManager: allow scan with filters
,08-29 13:45:01.383  2758  2883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:45:01.383  2758  2883 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-29 13:45:01.383  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 13:45:01.383  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.383  2758  2883 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:45:01.383  2758  2883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:45:01.383  2758  2818 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 13:45:01.393  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.393  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:01.393  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:45:01.393  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:45:01.393  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 13:45:01.393  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.393  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:45:01.403  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:45:01.403  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:01.403  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.403  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.403  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:01.403  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bda490 removed from the list
08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.403  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a432189 removed from the list
08-29 13:45:01.403  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:01.403  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:01.403  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.403  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 13:45:01.403  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.403  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:01.403  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a432189 not in the list
,08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:45:01.403  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:45:01.403  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 13:45:01.403  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:45:01.403  2758  2767 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:45:01.413  2758  2883 D BtGatt.ScanManager: filter size is 1
08-29 13:45:01.413  2758  2883 D BtGatt.ScanManager: delete FilterIndex - 8
,08-29 13:45:01.413  2758  2818 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 13:45:01.413  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.413  2758  2876 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:45:01.413  2758  2883 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:45:01.413  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:45:01.413  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:45:01.413  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:45:01.413  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:45:01.413  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:45:01.413  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:45:01.413  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 13:45:01.413  2758  2818 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-29 13:45:01.413  6633  6774 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:45:01.413  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:45:01.413  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.413  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.423  2758  2883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 13:45:01.423  2758  2818 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 13:45:01.423  2758  2818 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:45:01.423  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:01.423  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:01.423  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.423  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@150079bc removed from the list
,08-29 13:45:01.423  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.423  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.423  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.423  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:01.423  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@364341af removed from the list
08-29 13:45:01.423  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:45:01.423  6633  6633 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:45:01.423  6633  6633 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:45:01.423  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:01.423  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3975a8 added. We now have 2 listener(s)
,08-29 13:45:01.423  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-29 13:45:01.423  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:45:01.423  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:45:01.423  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:45:01.423  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144078c1 added. We now have 9 listener(s)
,08-29 13:45:01.433  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:45:01.433  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:45:01.433  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:45:01.433  6633  6774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:45:01.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:45:01.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:45:01.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:45:01.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:45:01.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:45:01.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:45:01.433  6633  6774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:45:01.443  1017  1127 E WifiNative-wlan0: do suspend true
,08-29 13:45:01.443  6633  6774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:45:01.443  6633  6774 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:45:01.443  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:45:01.443  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1713b7a7 added. We now have 3 listener(s)
,08-29 13:45:01.443  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:01.443  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-29 13:45:01.443  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:45:01.443  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:45:01.443  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:45:01.443  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7844454 added. We now have 10 listener(s)
08-29 13:45:01.443  6633  6774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:45:01.443  6633  6774 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:45:01.443  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:45:01.443  6633  6774 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:45:01.443  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.443  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.443  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:45:01.443  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:45:01.443  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3975a8 removed from the list
08-29 13:45:01.443  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.443  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144078c1 removed from the list
,08-29 13:45:01.443  6633  6633 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:45:01.443  6633  6774 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:45:01.443  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:45:01.453  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.453  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:45:01.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:01.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:45:01.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:45:01.453  6633  6774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144078c1 not in the list
,08-29 13:45:01.453  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:45:01.453  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:45:01.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:45:01.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:45:01.453  6633  6774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7844454 removed from the list
08-29 13:45:01.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:45:01.453  6633  6774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 13:45:01.453  6633  6774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:45:01.453  6633  6774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:45:01.453  6633  6774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1713b7a7 removed from the list
08-29 13:45:01.453  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-29 13:45:01.453  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 13:45:01.453  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-29 13:45:01.453  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:45:01.453  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 13:45:01.453  6633  6774 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:45:01.463  6633  7597 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1348, name: My test thread name)
,08-29 13:45:01.463  6633  7597 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1348, thread name: My test thread name)
08-29 13:45:01.463  6633  7597 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1348, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 13:45:01.463  6633  7598 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1350, name: My test thread name)
,08-29 13:45:01.463  6633  7598 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1350, thread name: My test thread name)
08-29 13:45:01.463  6633  7598 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1350, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 13:45:01.463  6633  6774 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 13:45:01.463  6633  6774 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 13:45:01.463  6633  6774 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 13:45:01.463  6633  6774 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 13:45:01.463  6633  6774 D com.test.thalitest.ThaliTestRunner: Total duration: 23266 ms
08-29 13:45:01.463  6633  6774 I jxcore-log: *Native tests were executed*
08-29 13:45:01.463  6633  6774 I jxcore-log: 
08-29 13:45:01.473  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-29 13:45:01.463  6633  6774 I jxcore-log: Total number of executed tests:  80
08-29 13:45:01.463  6633  6774 I jxcore-log: 
08-29 13:45:01.463  6633  6774 I jxcore-log: Number of passed tests:  80
08-29 13:45:01.463  6633  6774 I jxcore-log: 
08-29 13:45:01.473  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 13:45:01.463  6633  6774 I jxcore-log: Number of failed tests:  0
08-29 13:45:01.463  6633  6774 I jxcore-log: 
08-29 13:45:01.463  6633  6774 I jxcore-log: Number of ignored tests:  0
08-29 13:45:01.463  6633  6774 I jxcore-log: 
08-29 13:45:01.463  6633  6774 I jxcore-log: Total duration:  23266
08-29 13:45:01.463  6633  6774 I jxcore-log: 
08-29 13:45:01.463  6633  6774 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 13:45:01.463  6633  6774 I jxcore-log: 
,08-29 13:45:01.473  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:01.473  6633  6774 I jxcore-log: 
08-29 13:45:01.473  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:01.473  6633  6774 I jxcore-log: 
08-29 13:45:01.473  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:01.473  6633  6774 I jxcore-log: 
08-29 13:45:01.473  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:01.473  6633  6774 I jxcore-log: 
08-29 13:45:01.473  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:01.473  6633  6774 I jxcore-log: 
08-29 13:45:01.483  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:01.483  6633  6774 I jxcore-log: 
08-29 13:45:01.483  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:45:01.483  6633  6774 I jxcore-log: 
08-29 13:45:01.483  1017  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 13:45:01.483  1017  1127 E WifiStateMachine: VerifyingLinkState enter
08-29 13:45:01.483  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:45:01.483  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:45:01.483  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:45:01.483  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.483  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.483  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.483  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.483  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:01.483  6633  6774 I jxcore-log: 
08-29 13:45:01.493  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.493  6633  6774 I jxcore-log: 
08-29 13:45:01.493  6633  6633 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 13:45:01.493  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.493  6633  6774 I jxcore-log: 
,08-29 13:45:01.493  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-29 13:45:01.493  6633  6774 I jxcore-log: 
08-29 13:45:01.493  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-29 13:45:01.493  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:45:01.493  6633  6774 I jxcore-log: 
,08-29 13:45:01.493  1017  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-29 13:45:01.493  1017  1129 D ConnectivityService: Adding iface wlan0 to network 504
08-29 13:45:01.493  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.493  6633  6774 I jxcore-log: 
,08-29 13:45:01.493  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.493  6633  6774 I jxcore-log: 
,08-29 13:45:01.503  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.503  6633  6774 I jxcore-log: 
,08-29 13:45:01.503  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-29 13:45:01.503  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.503  6633  6774 I jxcore-log: 
08-29 13:45:01.503  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 13:45:01.503  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 13:45:01.503  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 13:45:01.503  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 13:45:01.503  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.503  6633  6774 I jxcore-log: 
08-29 13:45:01.503  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.503  6633  6774 I jxcore-log: 
,08-29 13:45:01.503  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.503  6633  6774 I jxcore-log: 
,08-29 13:45:01.503  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:45:01.503  6633  6774 I jxcore-log: 
,08-29 13:45:01.503  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:01.503  6633  6774 I jxcore-log: 
,08-29 13:45:01.513  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:01.513  6633  6774 I jxcore-log: 
,08-29 13:45:01.513  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-29 13:45:01.513  6633  6774 I jxcore-log: 
08-29 13:45:01.513  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:01.513  6633  6774 I jxcore-log: 
08-29 13:45:01.513  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:01.513  6633  6774 I jxcore-log: 
,08-29 13:45:01.523  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:01.523  6633  6774 I jxcore-log: 
,08-29 13:45:01.523  1017  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-29 13:45:01.523  1017  3971 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:45:01.523  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:45:01.523  6633  6774 I jxcore-log: 
08-29 13:45:01.523  1017  3971 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:45:01.523  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:45:01.523  1017  3971 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:01.523  1017  3971 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:45:01.523  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:45:01.523  1017  3971 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:45:01.523  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:45:01.523  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.523  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.523  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.523  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.523  1609  1609 I Hs20UtilService: Starting #22
08-29 13:45:01.523  1609  1651 I Hs20UtilService: Message received 5007
08-29 13:45:01.523  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 13:45:01.533  4454  4454 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-29 13:45:01.533  1017  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-29 13:45:01.533  1017  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-29 13:45:01.543  1017  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-29 13:45:01.543  1017  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 13:45:01.543  1017  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-29 13:45:01.543  1017  1129 D ConnectivityService: LTETest block dns file not exists
,08-29 13:45:01.543  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 13:45:01.553  1017  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 13:45:01.553  1017  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 13:45:01.553  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 13:45:01.553  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-29 13:45:01.553  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-29 13:45:01.553  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:45:01.563  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:45:01.563  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.563  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:45:01.573  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:45:01.573  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:45:01.573  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:01.573  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:45:01.573  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:45:01.573  1609  1609 I Hs20UtilService: Starting #23
,08-29 13:45:01.573  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.573  1017  1129 V NetworkStats: updateIfacesLocked()
08-29 13:45:01.573  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated,
,08-29 13:45:01.573  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:45:01.573  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:45:01.583  1017  1129 V NetworkStats: performPollLocked() took 8ms
08-29 13:45:01.583  1609  1651 I Hs20UtilService: Message received 5007
08-29 13:45:01.583  1017  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-29 13:45:01.583  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.583  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:45:01.583  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 13:45:01.583  1017  1129 V NetworkStats: updateIfacesLocked()
08-29 13:45:01.583  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:45:01.583  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:45:01.583  1017  1129 E ConnectivityService: updateNetworkInfo()
08-29 13:45:01.583  4454  4454 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 13:45:01.583  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.583  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:45:01.583  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:45:01.583  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.583  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:01.583  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 13:45:01.583  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.583  1017  1129 V NetworkStats: performPollLocked() took 4ms
,08-29 13:45:01.593  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.593  1017  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-29 13:45:01.593  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.593  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 13:45:01.593  1017  7564 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:01.593  1017  7564 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-29 13:45:01.593  1017  7564 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:45:01.593  1017  7564 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-29 13:45:01.593  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:45:01.593  4454  4454 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:45:01.593  4454  4454 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:45:01.593  4454  4521 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:45:01.593  1017  7564 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 13:45:01.593  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 13:45:01.593  1017  1129 D ConnectivityService:    accepting network in place of null
08-29 13:45:01.593  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 13:45:01.593  1463  1463 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 13:45:01.593  1463  1463 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 13:45:01.593  1017  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 13:45:01.593  1017  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-29 13:45:01.593   278   999 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 13:45:01.593  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:45:01.593   278   999 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-29 13:45:01.603  1017  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
08-29 13:45:01.603  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 13:45:01.603  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-29 13:45:01.603  1017  1132 D Tethering: MasterInitialState.processMessage what=3
08-29 13:45:01.603  1017  1124 V NetworkStats: updateIfacesLocked()
08-29 13:45:01.603  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.603  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:45:01.603  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:45:01.603  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:45:01.603  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-29 13:45:01.603  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-29 13:45:01.603  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 13:45:01.603  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 13:45:01.603  1172  1172 D StatusBar.NetworkController: updateDataNetType()
08-29 13:45:01.603  1172  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 13:45:01.613  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.613  1017  1124 V NetworkStats: performPollLocked() took 6ms
,08-29 13:45:01.613  1017  1078 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:45:01.613  1017  1078 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:45:01.613  1017  1078 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:01.613  1017  1078 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:45:01.613  1017  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:45:01.613  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.613  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-29 13:45:01.613  1609  1609 I Hs20UtilService: Starting #24
08-29 13:45:01.613  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 13:45:01.613  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.613  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.613  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.613  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.613  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:01.613  1609  1651 I Hs20UtilService: Message received 5007
,08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 13:45:01.613  4454  4454 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-29 13:45:01.613  4454  4454 I NearbySettings: MountReceiver.onReceive - Keep current state
08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:45:01.613  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.613  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:45:01.623  1017  3977 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-29 13:45:01.623  1017  1447 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-29 13:45:01.623  1017  1447 D SecContentProvider2: mCursor = null
08-29 13:45:01.623  1017  1487 D SecContentProvider2: uri = 15 selection = getToastGravity
08-29 13:45:01.623  1017  1487 D SecContentProvider2: mCursor = null
,08-29 13:45:01.623  1017  1480 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-29 13:45:01.623  1017  1480 D SecContentProvider2: mCursor = null
08-29 13:45:01.623  1017  1219 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-29 13:45:01.623  1017  1219 D SecContentProvider2: mCursor = null
,08-29 13:45:01.633  1017  1078 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-29 13:45:01.633  1017  1078 D SecContentProvider2: mCursor = null
08-29 13:45:01.633  6633  6633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 13:45:01.633  1017  1504 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-29 13:45:01.633  1017  1504 D SecContentProvider2: mCursor = null
,08-29 13:45:01.633  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:01.633  6633  6774 I jxcore-log: 
,08-29 13:45:01.653   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-29 13:45:01.673  1017  3971 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017,
,08-29 13:45:01.683  1172  1172 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 13:45:01.713  1017  7564 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-29 13:45:01.753  7601  7601 D AndroidRuntime: 
08-29 13:45:01.753  7601  7601 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 13:45:01.753  7601  7601 D AndroidRuntime: CheckJNI is OFF
,08-29 13:45:01.753  7601  7601 D AndroidRuntime: readGMSProperty: start
08-29 13:45:01.753  7601  7601 D AndroidRuntime: readGMSProperty: already setted!!
08-29 13:45:01.753  7601  7601 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 13:45:01.753  7601  7601 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 13:45:01.753  7601  7601 D AndroidRuntime: readGMSProperty: end
08-29 13:45:01.753  7601  7601 D AndroidRuntime: addProductProperty: start
,08-29 13:45:01.793  1017  7564 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 11:45:01 GMT], X-Android-Received-Millis=[1472471101802], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472471101760]}
,08-29 13:45:01.793  1017  7564 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-29 13:45:01.793  1017  7564 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 13:45:01.793  1017  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504],
08-29 13:45:01.793  6633  6633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 13:45:01.793  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 13:45:01.793  1017  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-29 13:45:01.793  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-29 13:45:01.793  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 13:45:01.793  1172  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 13:45:01.793  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:01.793  6633  6774 I jxcore-log: 
,08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: EthernetConnected: false
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: updateDataNetType()
,08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-29 13:45:01.803  1172  1172 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:45:01.803  1172  1172 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:45:01.803  1172  1172 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:45:01.903  7601  7601 E AffinityControl: AffinityControl: registerfunction enter
,08-29 13:45:01.923  6633  6633 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-29 13:45:01.923  6633  6774 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:45:01.923  6633  6774 I jxcore-log: 
,08-29 13:45:01.933  7601  7601 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-29 13:45:01.943  1017  1030 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-29 13:45:01.943  1017  1030 D PackageManager: START PACKAGE DELETE: observer{112022147}
08-29 13:45:01.943  1017  1030 D PackageManager: pkg{<packageName>}
08-29 13:45:01.943  1017  1030 D PackageManager: user{0}
08-29 13:45:01.943  1017  1030 D PackageManager: caller{2000}
08-29 13:45:01.943  1017  1030 D PackageManager: flags{2}
08-29 13:45:01.943  1017  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-29 13:45:01.943  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-29 13:45:01.943  1017  1030 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-29 13:45:01.943  1017  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 13:45:01.943  1017  1030 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 13:45:01.943  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-29 13:45:01.943  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-29 13:45:01.943  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-29 13:45:01.943  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-29 13:45:01.943  1017  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-29 13:45:01.943  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-29 13:45:01.943  1017  1042 I ActivityManager: Killing 6633:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-29 13:45:01.953  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{d07c43 u0 com.test.thalitest/.MainActivity t163}
,08-29 13:45:01.963  1017  1042 D InputDispatcher: Focus left window: 6633
,08-29 13:45:01.963   258   437 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-29 13:45:01.963   258  1098 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-29 13:45:01.983  1017  1042 D InputDispatcher: Focused application released,
08-29 13:45:01.983  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 13:45:01.983  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 13:45:02.093  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-29 13:45:02.103  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-29 13:45:02.113  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:45:02.123  6053  6053 I art     : Explicit concurrent mark sweep GC freed 2083(119KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 657us total 25.284ms
,08-29 13:45:02.143  1872  1872 E SamsungIME: mOCRHelper is null
,08-29 13:45:02.143  1746  1995 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 13:45:02.143  1017  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 13:45:02.163  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-29 13:45:02.163  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:45:02.163  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-29 13:45:02.163  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:45:02.163  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:45:02.173  1017  1124 V NetworkStats: performPollLocked() took 9ms
08-29 13:45:02.173  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:02.183  2899  2899 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 13:45:02 GMT+02:00 2016
,08-29 13:45:02.203  1017  3970 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 13:45:02.203  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 13:45:02.203  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:02.203  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:45:02.203  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-29 13:45:02.213  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,08-29 13:45:02.213  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:02.223  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:02.223  1443  1443 D RegisteredServicesCache: empty dynamic service
,08-29 13:45:02.223  2899  2899 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 13:45:02.223  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-29 13:45:02.233  1017  3971 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-29 13:45:02.233  1017  3971 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-29 13:45:02.233  1017  3971 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-29 13:45:02.233  1017  3971 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.233  1017  3971 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.233  1017  3971 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.233  1017  3971 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.243  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-29 13:45:02.243  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 13:45:02.243  1017  1030 D SecContentProvider2: mCursor = null
,08-29 13:45:02.243  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-29 13:45:02.243  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-29 13:45:02.243  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-29 13:45:02.253  7617  7617 E Zygote  : MountEmulatedStorage()
08-29 13:45:02.253  7617  7617 I libpersona: KNOX_SDCARD checking this for 10090
08-29 13:45:02.253  7617  7617 E Zygote  : v2
08-29 13:45:02.253  7617  7617 I libpersona: KNOX_SDCARD not a persona
,08-29 13:45:02.253  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-29 13:45:02.253  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-29 13:45:02.253  7617  7617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.263  7617  7617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:45:02.263  1017  3971 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7617 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-29 13:45:02.263  7617  7617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.273  2899  2899 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 13:45:02.283  2899  2899 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 13:45:02.283  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-29 13:45:02.283  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.283  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.283  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.283  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.293  2899  2899 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 13:45:02.293  2899  7616 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 13:45:02.303  7617  7617 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:45:02.303  7617  7617 D ActivityThread: Added TimaKeyStore provider
,08-29 13:45:02.303  1017  1057 I art     : Explicit concurrent mark sweep GC freed 65792(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/34MB, paused 6.107ms total 198.996ms
,08-29 13:45:02.313  2899  7616 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-29 13:45:02.313  7632  7632 E Zygote  : MountEmulatedStorage()
08-29 13:45:02.313  7632  7632 I libpersona: KNOX_SDCARD checking this for 10052
08-29 13:45:02.313  7632  7632 E Zygote  : v2
08-29 13:45:02.313  7632  7632 I libpersona: KNOX_SDCARD not a persona
08-29 13:45:02.313  1017  1042 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7632 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-29 13:45:02.313  7632  7632 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.313  7632  7632 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:45:02.313  7632  7632 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.313  1017  1027 I art     : WaitForGcToComplete blocked for 104.564ms for cause HeapTrim
,08-29 13:45:02.323  2899  7616 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-29 13:45:02.323  2899  7616 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-29 13:45:02.333  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,08-29 13:45:02.333  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.333  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.333  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.333  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.333  1017  1057 D PackageManager: delete codoeFile: 
,08-29 13:45:02.343  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-29 13:45:02.343  1017  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-29 13:45:02.343  1017  1057 D PackageManager: result of delete: 1{112022147}
,08-29 13:45:02.353  7642  7642 E Zygote  : MountEmulatedStorage()
08-29 13:45:02.353  7642  7642 I libpersona: KNOX_SDCARD checking this for 10098
08-29 13:45:02.353  7642  7642 E Zygote  : v2
08-29 13:45:02.353  7642  7642 I libpersona: KNOX_SDCARD not a persona
08-29 13:45:02.353  7642  7642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.353  7642  7642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:45:02.353  7642  7642 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.353  7632  7632 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:45:02.363  7632  7632 D ActivityThread: Added TimaKeyStore provider
,08-29 13:45:02.373  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 13:45:02.373  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-29 13:45:02.373  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 13:45:02.383  7601  7601 D AndroidRuntime: Shutting down VM
,08-29 13:45:02.383  1017  1042 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7642 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-29 13:45:02.383  1017  1450 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 13:45:02.383  1443  1443 D RegisteredComponentCache: Collect Tech packages for Knox
,08-29 13:45:02.383  7642  7642 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:45:02.383  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.383  7642  7642 D ActivityThread: Added TimaKeyStore provider
08-29 13:45:02.383  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.383  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.383  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.393  2899  7616 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-29 13:45:02.393  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-29 13:45:02.393  1017  1057 D PackageManager: userId{-1}
08-29 13:45:02.393  1017  1057 D PackageManager: andCode{true}
,08-29 13:45:02.403  7662  7662 E Zygote  : MountEmulatedStorage()
,08-29 13:45:02.403  7662  7662 E Zygote  : v2
08-29 13:45:02.403  7662  7662 I libpersona: KNOX_SDCARD checking this for 10032
08-29 13:45:02.403  7662  7662 I libpersona: KNOX_SDCARD not a persona
08-29 13:45:02.403  2899  7616 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-29 13:45:02.403  7662  7662 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.403  1017  1450 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7662 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:45:02.403  7662  7662 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:45:02.403  2899  7616 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-29 13:45:02.403  7662  7662 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.413  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
08-29 13:45:02.413  1017  1041 W TextServicesManagerService: no available spell checker services found
08-29 13:45:02.413  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-29 13:45:02.413  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.423  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,08-29 13:45:02.423  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.423  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-29 13:45:02.433  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.433  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.433  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:45:02.433  1017  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.443  7662  7662 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:45:02.443  7662  7662 D ActivityThread: Added TimaKeyStore provider
,08-29 13:45:02.443  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.453  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.453  7677  7677 E Zygote  : MountEmulatedStorage()
08-29 13:45:02.453  7677  7677 E Zygote  : v2
08-29 13:45:02.453  7677  7677 I libpersona: KNOX_SDCARD checking this for 10003
08-29 13:45:02.453  7677  7677 I libpersona: KNOX_SDCARD not a persona
,08-29 13:45:02.453  7677  7677 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.453  7677  7677 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:45:02.453  7677  7677 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.473  7617  7617 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-29 13:45:02.473  7617  7617 D elm:15121: ELMEngine.ELMEngine( context ).
,08-29 13:45:02.473  7617  7617 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-29 13:45:02.473  1017  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7677 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-29 13:45:02.473  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicy: uID is 10170
08-29 13:45:02.483  1017  2838 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 13:45:02.483  7677  7677 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:45:02.483  7677  7677 D ActivityThread: Added TimaKeyStore provider
,08-29 13:45:02.483  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 13:45:02.493  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-29 13:45:02.493  1017  3970 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-29 13:45:02.493  1017  3970 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-29 13:45:02.493  1017  3970 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:45:02.493  1017  3970 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:45:02.493  1017  3970 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-29 13:45:02.503  7617  7617 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-29 13:45:02.503  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-29 13:45:02.503  2899  2899 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 13:45:02.513  1017  1450 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-29 13:45:02.513  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.513  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.513  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.513  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.513  7617  7617 D elm:15121: ElmAgentService : onCreate()
,08-29 13:45:02.523  7617  7692 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-29 13:45:02.523  7617  7692 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-29 13:45:02.523  7617  7692 D elm:15121: MDMBridge.getInstance()
08-29 13:45:02.523  7617  7692 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-29 13:45:02.533  7693  7693 E Zygote  : MountEmulatedStorage(),
08-29 13:45:02.533  7693  7693 E Zygote  : v2,
08-29 13:45:02.533  7693  7693 I libpersona: KNOX_SDCARD checking this for 1000
,08-29 13:45:02.533  7693  7693 I libpersona: KNOX_SDCARD not a persona
,08-29 13:45:02.533  7693  7693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.533  7617  7692 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-29 13:45:02.533  1017  1450 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 13:45:02.543  1017  1450 I ActivityManager: Killing 7125:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-29 13:45:02.543  7693  7693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:45:02.543  7693  7693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.573  7617  7617 D elm:15121: ElmAgentService : onDestroy().
,08-29 13:45:02.573  1017  3967 I ActivityManager: Killing 7142:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-29 13:45:02.593  7601  7601 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-29 13:45:02.603  7662  7709 E SPPClientService: ============PushLog. commonIsShipBuild. stop!,
08-29 13:45:02.603  1017  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-29 13:45:02.603  7662  7709 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version,
08-29 13:45:02.603  1017  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 13:45:02.603  1017  1129 V NetworkStats: updateIfacesLocked()
08-29 13:45:02.603  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:02.603  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:45:02.603  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:45:02.603  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:45:02.613  1017  3977 I ActivityManager: Killing 7157:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-29 13:45:02.613  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-29 13:45:02.613  1017  1129 V NetworkStats: performPollLocked() took 5ms
08-29 13:45:02.613  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:02.613  7693  7693 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:45:02.613  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.613  7693  7693 D ActivityThread: Added TimaKeyStore provider
08-29 13:45:02.613  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.623  1017  3977 I ActivityManager: Killing 7174:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-29 13:45:02.623  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 13:45:02.623  1017  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-29 13:45:02.623  1017  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-29 13:45:02.623  1172  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 13:45:02.633  1172  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-29 13:45:02.633  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:02.633  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:45:02.633  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 13:45:02.633  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:45:02.633  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:45:02.643  1017  1450 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-29 13:45:02.643  1017  1450 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-29 13:45:02.643  7662  7709 D SPPClientService: PushLog.txt file is not deleted.
08-29 13:45:02.643  7662  7709 D SPPClientService: PushLog.txt file is not deleted.
08-29 13:45:02.643  7662  7709 D SPPClientService: ============PushLog. stop!
,08-29 13:45:02.643  1017  1450 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:02.643  1017  1450 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:45:02.643  1017  1450 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-29 13:45:02.643  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.643  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.653  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.653  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 13:45:02.653  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 13:45:02.653  1017  1480 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-29 13:45:02.653  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-29 13:45:02.653  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.653  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:02.663  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:45:02.663  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-29 13:45:02.663  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.663  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 13:45:02.663  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-29 13:45:02.663  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.663  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.663  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.663  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.673  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 13:45:02.673  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 13:45:02.673  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:45:02.683  7715  7715 E Zygote  : MountEmulatedStorage()
08-29 13:45:02.683  7715  7715 E Zygote  : v2
08-29 13:45:02.683  7715  7715 I libpersona: KNOX_SDCARD checking this for 10039
08-29 13:45:02.683  7715  7715 I libpersona: KNOX_SDCARD not a persona
,08-29 13:45:02.683  1017  1504 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7715 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-29 13:45:02.683  7715  7715 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.683  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-29 13:45:02.683  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-29 13:45:02.683  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:02.683  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:45:02.683  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-29 13:45:02.693  7715  7715 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:45:02.693  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-29 13:45:02.693  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-29 13:45:02.693  7715  7715 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.693  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:45:02.703  1680  1680 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-29 13:45:02.703  1680  1680 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-29 13:45:02.723  1017  1450 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-29 13:45:02.723  7449  7449 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
08-29 13:45:02.723  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:45:02.723  7449  7449 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
08-29 13:45:02.723  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.723  7715  7715 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:45:02.723  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.723  7715  7715 D ActivityThread: Added TimaKeyStore provider
08-29 13:45:02.723  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.733  7731  7731 E Zygote  : MountEmulatedStorage()
08-29 13:45:02.733  7731  7731 E Zygote  : v2
08-29 13:45:02.733  7731  7731 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:45:02.733  7731  7731 I libpersona: KNOX_SDCARD not a persona
,08-29 13:45:02.743  1017  1450 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7731 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-29 13:45:02.743  7731  7731 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.743  1017  1450 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
08-29 13:45:02.743  1546  1554 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-29 13:45:02.743  1546  1554 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-29 13:45:02.743  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.743  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:45:02.743  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:45:02.743  1017  1450 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:45:02.743  7731  7731 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:45:02.743  7731  7731 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.753  7449  7449 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:45:02.753  7449  7449 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:45:02.753  7449  7449 D AndroidRuntime: Shutting down VM
08-29 13:45:02.753  7741  7741 E Zygote  : MountEmulatedStorage()
08-29 13:45:02.753  7741  7741 E Zygote  : v2
08-29 13:45:02.753  7741  7741 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:45:02.753  7741  7741 I libpersona: KNOX_SDCARD not a persona
08-29 13:45:02.763  7741  7741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:45:02.763  1546  1554 E DatabaseUtils: Writing exception to parcel,
08-29 13:45:02.763  1546  1554 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510),
08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at com.sec.android.provider.logsprovider.LogsProvider.delete(LogsProvider.java:3550)
08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
,08-29 13:45:02.763  1546  1554 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: FATAL EXCEPTION: main
08-29 13:45:02.763  7449  7449 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 7449
08-29 13:45:02.763  7449  7449 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,08-29 13:45:02.763  7449  7449 E AndroidRuntime: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	,at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:45:02.763  7449  7449 E AndroidRuntime: 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:45:02.763  7741  7741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:45:02.763  7741  7741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:45:02.773  1017  1450 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:45:02.773  1017  1450 I ActivityManager: Killing 7207:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-29 13:45:02.773  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-29 13:45:02.773  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-29 13:45:02.783  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:45:02.783  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:45:02.783  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-29 13:45:02.793  7741  7741 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:45:02.793  7741  7741 D ActivityThread: Added TimaKeyStore provider
,08-29 13:45:02.793  1017  1447 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
,08-29 13:45:02.793  1937  7758 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-29 13:45:02.793  1937  7758 D AccountUtils: Clearing selected account for com.test.thalitest
08-29 13:45:02.793   304   304 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 3.317ms total 22.662ms
,08-29 13:45:02.813  7731  7731 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: Can't write: system_app_crash
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 13:45:02.813  1017  7763 E DropBoxManagerService: 	... 5 more
08-29 13:45:02.813  7731  7731 D ActivityThread: Added TimaKeyStore provider
08-29 13:45:02.813   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 17.295ms

```
