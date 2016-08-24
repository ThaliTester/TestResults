#### Test 8251899684424f3_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-24 17:07:37.301  1454  1471 D TP/MmsSmsProvider: query,matched:13, calling pid = 6596
08-24 17:07:37.301  1454  1471 D TP/MmsSmsProvider: match 13:Elapsed time : 1.146 ms
--------- beginning of system
08-24 17:07:37.301  1018  4327 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-24 17:07:37.301  1018  4327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.301  1018  4327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.301  1018  4327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.301  1018  4327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.311  6596  6596 D Mms/Contact: [end]    init consume time = 43.165833
08-24 17:07:37.321  6770  6770 E Zygote  : MountEmulatedStorage()
08-24 17:07:37.321  6770  6770 E Zygote  : v2
08-24 17:07:37.321  6770  6770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:37.321  6596  6769 D Mms/DraftCache: [start]    rebuildCache consume time = 13.204375
08-24 17:07:37.321  6770  6770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:37.321  6770  6770 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:37.321  6770  6770 I libpersona: KNOX_SDCARD checking this for 10152
08-24 17:07:37.321  6770  6770 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:37.321  1018  4327 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6770 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-24 17:07:37.321  1018  4327 I ActivityManager: Killing 6361:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-24 17:07:37.331  6756  6756 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:37.331  6756  6756 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:37.331  1018  4334 I ActivityManager: Killing 6025:com.google.android.gm/u0a99 (adj 15): empty #21
08-24 17:07:37.351  6770  6770 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:37.351  3824  6679 I qtaguid : Tagging socket 98 with tag 1000040b00000000{268436491,0} for uid -1, pid: 3824, getuid(): 10011
08-24 17:07:37.351  6770  6770 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:37.351  6596  6596 D Mms/MethodReflector: getSubId is called
08-24 17:07:37.351  6596  6596 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-24 17:07:37.351  6596  6596 D Mms/MethodReflector: getTelephonyProperty is called
08-24 17:07:37.361  6596  6596 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-24 17:07:37.361  6596  6596 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 17:07:37.361  6596  6596 D Mms/DownloadManager: auto download without roaming -> true
08-24 17:07:37.361  6596  6596 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-24 17:07:37.361  6596  6596 D Mms/MethodReflector: getSubId is called
08-24 17:07:37.371  6596  6596 D Mms/MethodReflector: getDefaultSmsSubId is called
08-24 17:07:37.371  6596  6596 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-24 17:07:37.371  6596  6596 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-24 17:07:37.371  1454  1474 D TP/MmsSmsProvider: query,matched:12, calling pid = 6596
08-24 17:07:37.371  6596  6596 D Mms/MethodReflector: getTelephonyProperty is called
08-24 17:07:37.371  6596  6596 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-24 17:07:37.371  6596  6596 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-24 17:07:37.371  6596  6596 D Mms/DownloadManager: auto download without roaming -> true
08-24 17:07:37.371  6596  6596 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-24 17:07:37.371  6596  6596 D Mms/DownloadManager: auto download during roaming secondary -> false
08-24 17:07:37.371  6596  6596 D Mms/DownloadManager: mAutoDownload ------> true
08-24 17:07:37.371  1454  1474 D TP/MmsSmsProvider: match 12:Elapsed time : 1.417 ms
08-24 17:07:37.381  6596  6769 D Mms/DraftCache: [end]    rebuildCache consume time = 56.016354
08-24 17:07:37.391  6756  6756 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-24 17:07:37.391  6756  6756 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 17:07:37.391  6756  6756 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-24 17:07:37.401  3824  6683 W BaseAppContext: Using Auth Proxy for data requests.
08-24 17:07:37.401  3824  6683 W BaseAppContext: Using Auth Proxy for data requests.
08-24 17:07:37.411  6756  6756 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-24 17:07:37.411  6756  6756 I PCWCLIENTTRACE_PushUtil: sales region : global
08-24 17:07:37.411  6756  6756 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 17:07:37.411  6756  6756 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
08-24 17:07:37.411  6770  6770 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-24 17:07:37.411  6770  6770 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
08-24 17:07:37.421  6596  6596 D ComposerPerformance: 1472051257432 ms / [DONE] Composer constructor
08-24 17:07:37.421  6596  6596 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-24 17:07:37.421  6596  6596 I Mms/ReservationManager: ReservationManager()
08-24 17:07:37.421  6596  6596 I Mms/ReservationManager: resetAfterConnected()
08-24 17:07:37.421  6596  6793 D Mms/Conversation: [start]    init() consume time = 43.891406
08-24 17:07:37.421  6770  6770 I TapandpayWidget:Utils: Clear T&P info.
08-24 17:07:37.431  1454  1471 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-24 17:07:37.431  1454  3328 D TP/MmsSmsProvider: query,matched:7, calling pid = 6596
08-24 17:07:37.431  1454  1471 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-24 17:07:37.431  1454  1471 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-24 17:07:37.431  1454  1471 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-24 17:07:37.431  1454  3328 D TP/MmsSmsProvider: match 7:Elapsed time : 3.413 ms
08-24 17:07:37.441  1454  1471 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-24 17:07:37.441  1454  1471 D TP/MmsSmsProvider: need read changed broadcast:false
08-24 17:07:37.441  6596  6596 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-24 17:07:37.441  6596  6793 D Mms/Conversation: [end]    init consume time = 19.304948
08-24 17:07:37.441  6596  6596 D Mms/MmsApp: [end]    onCreate() consume time = 2.228073
08-24 17:07:37.451  6596  6793 D Mms/MessagingNotification: [start]    init() consume time = 4.743594
08-24 17:07:37.451  6770  6770 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-24 17:07:37.451  1018  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-24 17:07:37.451  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.451  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.451  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.451  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.471  6596  6596 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-24 17:07:37.471  6795  6795 E Zygote  : MountEmulatedStorage()
08-24 17:07:37.471  6795  6795 I libpersona: KNOX_SDCARD checking this for 10009
08-24 17:07:37.471  6795  6795 E Zygote  : v2
08-24 17:07:37.471  6795  6795 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:37.471  6795  6795 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:37.471  6596  6596 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-24 17:07:37.471  6596  6596 D Mms/MethodReflector: getSubId is called
08-24 17:07:37.481  6596  6596 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-24 17:07:37.481  1018  1488 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6795 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-24 17:07:37.481  1018  1488 I ActivityManager: Killing 6424:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
08-24 17:07:37.481  6795  6795 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:37.481  1018  1488 I ActivityManager: Killing 6277:com.google.android.music:main/u0a108 (adj 15): empty #21
08-24 17:07:37.481  6795  6795 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-24 17:07:37.491  6596  6596 D Mms/MethodReflector: getTelephonyProperty is called
08-24 17:07:37.491  6596  6596 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-24 17:07:37.491  6596  6596 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-24 17:07:37.491  6596  6596 D Mms/DownloadManager: auto download without roaming -> true
08-24 17:07:37.491  6596  6596 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-24 17:07:37.491  6596  6596 D Mms/DownloadManager: mAutoDownload ------> true
08-24 17:07:37.491  6596  6793 D Mms/MessagingNotification: [end]    init consume time = 41.992239
08-24 17:07:37.511  6795  6795 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:37.521  6795  6795 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:37.521  6596  6596 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-24 17:07:37.521  3824  6683 W BaseAppContext: Using Auth Proxy for data requests.
08-24 17:07:37.521  6596  6806 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 28.585938
08-24 17:07:37.531  1018  4334 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-24 17:07:37.531  1018  4334 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-24 17:07:37.531  1018  4334 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:37.531  1018  4334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:37.531  1018  4334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-24 17:07:37.531  1454  1471 D TP/MmsSmsProvider: query,matched:400, calling pid = 6596
08-24 17:07:37.531  1018  1137 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-24 17:07:37.541  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.541  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.541  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.541  1018  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.541  6596  6811 D Mms/Synchronizer: [start]    doSync consume time = 20.719427
08-24 17:07:37.551  6813  6813 E Zygote  : MountEmulatedStorage()
08-24 17:07:37.551  6813  6813 E Zygote  : v2
08-24 17:07:37.561  6813  6813 I libpersona: KNOX_SDCARD checking this for 10042
08-24 17:07:37.561  1018  1137 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6813 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-24 17:07:37.561  6813  6813 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:37.561  6596  6812 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-24 17:07:37.561  6596  6812 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-24 17:07:37.561  6813  6813 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:37.561  1018  1137 I ActivityManager: Killing 6099:com.google.android.talk/u0a102 (adj 15): empty #21
08-24 17:07:37.571  6813  6813 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:37.571  1454  1474 D TP/MmsSmsProvider: query,matched:0, calling pid = 6596
08-24 17:07:37.571  1454  1474 V TP/MmsSmsProvider: getSimpleConversations entered.
08-24 17:07:37.571  1454  1474 D TP/MmsSmsProvider: match 0:Elapsed time : 0.986 ms
08-24 17:07:37.571  6813  6813 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-24 17:07:37.571  6596  6806 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 34.493281
08-24 17:07:37.571  1454  1646 D TP/MmsSmsProvider: update, matched:300, calling pid = 6596
08-24 17:07:37.571  1454  1646 V TP/MmsSmsProvider: syncDBData start
08-24 17:07:37.571  1454  1646 V TP/MmsSmsProvider: syncDBData sms end
08-24 17:07:37.571  1454  1646 V TP/MmsSmsProvider: syncDBData mms end
08-24 17:07:37.581  1454  1646 V TP/MmsSmsProvider: syncDBData end
08-24 17:07:37.581  6596  6811 D Mms/Synchronizer: [end]    doSync consume time = 6.83474
08-24 17:07:37.581  3824  6683 W BaseAppContext: Using Auth Proxy for data requests.
08-24 17:07:37.591  1018  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-24 17:07:37.591  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.591  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.591  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.591  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.611  6825  6825 E Zygote  : MountEmulatedStorage()
08-24 17:07:37.611  6825  6825 E Zygote  : v2
08-24 17:07:37.611  6813  6813 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:37.611  6813  6813 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:37.611  6825  6825 I libpersona: KNOX_SDCARD checking this for 10068
08-24 17:07:37.621  6825  6825 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:37.621  6825  6825 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:37.621  1018  1031 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6825 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-24 17:07:37.621  6825  6825 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:37.621  6825  6825 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-24 17:07:37.631  3824  6683 W BaseAppContext: Using Auth Proxy for data requests.
08-24 17:07:37.641  6825  6825 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:37.641  6825  6825 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:37.651  1018  1488 I ActivityManager: Killing 6379:com.android.calendar/u0a131 (adj 15): empty #21
08-24 17:07:37.661  1018  1562 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-24 17:07:37.681  3824  6683 W BaseAppContext: Using Auth Proxy for data requests.
08-24 17:07:37.681  6813  6813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 17:07:37.681  6813  6813 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-24 17:07:37.681  6813  6813 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-24 17:07:37.691  6825  6825 D BadgeProvider: onCreate
08-24 17:07:37.691  6825  6825 D BadgeProvider: DatabaseHelper
08-24 17:07:37.701  1018  1327 I ActivityManager: Killing 6476:com.android.defcontainer/u0a3 (adj 15): empty #21
08-24 17:07:37.731  6596  6793 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-24 17:07:37.741  1454  3328 D TP/SmsProvider: query,matched:26, calling pid = 6596
08-24 17:07:37.741  1454  3328 D TP/SmsProvider: match 26:Elapsed time : 1.707 ms
08-24 17:07:37.751  1454  1474 D TP/MmsSmsProvider: query,matched:6, calling pid = 6596
08-24 17:07:37.751  1454  1474 D TP/MmsSmsProvider: match 6:Elapsed time : 2.767 ms
08-24 17:07:37.791  3824  6679 I qtaguid : Untagging socket 89
08-24 17:07:37.791  3824  3824 I ConfigFetchService: fetch service done; releasing wakelock
08-24 17:07:37.791  6813  6813 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-24 17:07:37.851  3824  3840 W art     : Suspending all threads took: 15.355ms
08-24 17:07:37.851  6653  6692 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-24 17:07:37.851  6653  6692 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 17:07:37.851  6653  6692 I GAv4    :   adb logcat -s GAv4
08-24 17:07:37.871  6653  6692 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-24 17:07:37.871  1018  1501 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-24 17:07:37.901  6653  6692 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-24 17:07:37.921  6653  6692 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-24 17:07:37.921  6653  6848 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-24 17:07:37.941  1018  1563 I art     : Explicit concurrent mark sweep GC freed 145802(8MB) AllocSpace objects, 3(1840KB) LOS objects, 33% free, 23MB/34MB, paused 2.558ms total 165.241ms
08-24 17:07:37.941  3824  3824 I ConfigFetchService: stopping self
08-24 17:07:37.941  1018  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-24 17:07:37.941  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-24 17:07:37.941  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.941  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.941  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.941  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.961  6850  6850 E Zygote  : MountEmulatedStorage()
08-24 17:07:37.961  6850  6850 E Zygote  : v2
08-24 17:07:37.961  6850  6850 I libpersona: KNOX_SDCARD checking this for 10003
08-24 17:07:37.961  6850  6850 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:37.961  6850  6850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:37.961  6850  6850 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:37.961  6850  6850 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:37.971  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6850 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-24 17:07:37.971  1018  4327 I ActivityManager: Killing 6234:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-24 17:07:37.971  1018  4333 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-24 17:07:37.971  1018  4333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.971  1018  4333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.971  1018  4333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.971  1018  4333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:37.991  6850  6850 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:37.991  6850  6850 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:37.991  6866  6866 E Zygote  : MountEmulatedStorage()
08-24 17:07:37.991  6866  6866 E Zygote  : v2
08-24 17:07:37.991  6866  6866 I libpersona: KNOX_SDCARD checking this for 10023
08-24 17:07:37.991  6866  6866 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:37.991  6866  6866 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:37.991  1018  4333 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6866 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-24 17:07:38.001  6866  6866 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:38.001  6866  6866 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:38.031  6866  6866 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:38.031  6866  6866 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:38.041  1018  1494 I ActivityManager: Killing 6523:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-24 17:07:38.051   286   286 E installd: system dir 0 : /system/app/
08-24 17:07:38.051   286   286 E installd: system dir 1 : /system/priv-app/
08-24 17:07:38.051   286   286 E installd: system dir 2 : /vendor/app/
08-24 17:07:38.051   286   286 E installd: system dir 3 : /oem/app/
08-24 17:07:38.061  3824  4337 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-24 17:07:38.091  6866  6866 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-24 17:07:38.091  1018  1058 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-24 17:07:38.101  6596  6793 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-24 17:07:38.121  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-24 17:07:38.131  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-24 17:07:38.131  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-24 17:07:38.131  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-24 17:07:38.131  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-24 17:07:38.131  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-24 17:07:38.131  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-24 17:07:38.141  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-24 17:07:38.141  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-24 17:07:38.141  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-24 17:07:38.141  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-24 17:07:38.141  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-24 17:07:38.141  6866  6866 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-24 17:07:38.151  3824  4337 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-24 17:07:38.211  1018  1488 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-24 17:07:38.221  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.221  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.221  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.221  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.221  3824  4337 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-24 17:07:38.231  6889  6889 E Zygote  : MountEmulatedStorage()
08-24 17:07:38.231  6889  6889 E Zygote  : v2
08-24 17:07:38.231  6889  6889 I libpersona: KNOX_SDCARD checking this for 1000
08-24 17:07:38.231  6889  6889 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:38.231  6889  6889 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:38.241  1018  1488 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6889 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 17:07:38.241  6889  6889 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:38.241  6889  6889 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:38.251   311   311 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 20.552ms
08-24 17:07:38.251  1018  1486 I ActivityManager: Killing 6548:com.sec.spp.push/u0a32 (adj 15): empty #21
08-24 17:07:38.271   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 651us total 16.863ms
08-24 17:07:38.281  6889  6889 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:38.281  6889  6889 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:38.291   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 17.210ms
08-24 17:07:38.301  1018  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-24 17:07:38.301  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:38.301  1018  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:38.301  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 17:07:38.321  6889  6889 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-24 17:07:38.321  6889  6889 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-24 17:07:38.321  1018  1222 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-24 17:07:38.321  1018  1222 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-24 17:07:38.321  1018  1222 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:38.321  1018  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:38.321  1018  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-24 17:07:38.331  1018  1488 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-24 17:07:38.331  1018  1018 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-24 17:07:38.331  1018  1018 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-24 17:07:38.331  1018  1018 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-24 17:07:38.331  1018  1018 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
08-24 17:07:38.341  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-24 17:07:38.341  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.341  3824  6683 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 125.137ms
08-24 17:07:38.341  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.341  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.341  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.341  6889  6889 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-24 17:07:38.351  6907  6907 E Zygote  : MountEmulatedStorage()
08-24 17:07:38.351  6907  6907 E Zygote  : v2
08-24 17:07:38.351  6907  6907 I libpersona: KNOX_SDCARD checking this for 10008
08-24 17:07:38.351  6907  6907 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:38.361  6907  6907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:38.361  6907  6907 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:38.361  1018  1018 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6907 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:38.381  6653  6887 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-24 17:07:38.381  6907  6907 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-24 17:07:38.381  6653  6887 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-24 17:07:38.381   291   291 E SMD     : DCD OFF
08-24 17:07:38.381  6884  6884 D AndroidRuntime: 
08-24 17:07:38.381  6884  6884 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 17:07:38.391  6884  6884 D AndroidRuntime: CheckJNI is OFF
08-24 17:07:38.391  6884  6884 D AndroidRuntime: readGMSProperty: start
08-24 17:07:38.391  6884  6884 D AndroidRuntime: readGMSProperty: already setted!!
08-24 17:07:38.391  6884  6884 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 17:07:38.391  6884  6884 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-24 17:07:38.391  6884  6884 D AndroidRuntime: readGMSProperty: end
08-24 17:07:38.391  6884  6884 D AndroidRuntime: addProductProperty: start
08-24 17:07:38.391  6638  6677 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-24 17:07:38.401  6907  6907 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:38.401  6907  6907 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:38.411  6638  6677 I AcmsKeyStoreHelper: Key Store exist
08-24 17:07:38.411  6638  6677 I AcmsKeyStoreHelper: Hence loading the keystore file
08-24 17:07:38.421  6889  6906 E FilterInstaller: installFilters
08-24 17:07:38.431  6889  6906 E FilterInstaller: There is no requred permission
08-24 17:07:38.441  1018  1487 I ActivityManager: Killing 6539:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
08-24 17:07:38.451  6653  6887 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-24 17:07:38.481  6638  6677 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-24 17:07:38.481  6638  6677 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-24 17:07:38.481  6638  6677 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-24 17:07:38.481  6638  6677 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 17:07:38.481  6638  6677 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-24 17:07:38.481  6638  6677 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-24 17:07:38.481  6638  6677 D AcmsCore: This is NOT a valid MirrorLink app
08-24 17:07:38.481  6638  6677 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-24 17:07:38.481  6638  6677 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-24 17:07:38.481  6638  6677 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-24 17:07:38.481  6638  6677 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-24 17:07:38.481  6638  6638 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-24 17:07:38.481  6638  6638 D AcmsService: Enter onDestroy
08-24 17:07:38.481  6638  6638 I AcmsService: cleanUp(): inside service clean up
08-24 17:07:38.481  6638  6638 D AcmsCore: AcmsCore: inside DeInit
08-24 17:07:38.481  6638  6638 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-24 17:07:38.481  6638  6638 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-24 17:07:38.481  6638  6638 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-24 17:07:38.481  6638  6638 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-24 17:07:38.481  6638  6638 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-24 17:07:38.481  6638  6638 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-24 17:07:38.481  6638  6638 D AcmsService: killing acms process
08-24 17:07:38.481  6638  6638 I Process : Sending signal. PID: 6638 SIG: 9
08-24 17:07:38.521  6653  6887 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-24 17:07:38.521  6653  6887 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21b4eb50: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-24 17:07:38.521  6653  6887 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-24 17:07:38.531  6907  6907 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
08-24 17:07:38.541  6907  6907 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
08-24 17:07:38.541  1018  1488 I ActivityManager: Killing 6571:com.samsung.helphub/1000 (adj 15): empty #21
08-24 17:07:38.551  1018  1487 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:07:38.551  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
08-24 17:07:38.561  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:38.561  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:38.561  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 17:07:38.561  6884  6884 E AffinityControl: AffinityControl: registerfunction enter
08-24 17:07:38.571  1018  4327 I ActivityManager: Process ACMS.Process (pid 6638)(adj 0) has died(48,760)
08-24 17:07:38.591  6884  6884 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-24 17:07:38.601  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
08-24 17:07:38.611  1018  1030 I PersonaManagerService: PersonaId don't exist
08-24 17:07:38.611  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-24 17:07:38.611  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 17:07:38.631  1018  1030 W ActivityManager: mDVFSHelper.acquire()
08-24 17:07:38.631  1018  1030 D FocusedStackFrame: Set to : 0
08-24 17:07:38.641  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.641  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.641  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.641  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.651  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 17:07:38.651  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-24 17:07:38.651  6932  6932 E Zygote  : MountEmulatedStorage()
08-24 17:07:38.651  6932  6932 I libpersona: KNOX_SDCARD checking this for 10170
08-24 17:07:38.651  6932  6932 E Zygote  : v2
08-24 17:07:38.651  6932  6932 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:38.651  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-24 17:07:38.651  1018  1030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6932 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 17:07:38.651  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 17:07:38.651  1018  1030 D InputDispatcher: Focused application set to: xxxx
08-24 17:07:38.651  6932  6932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:38.651  1018  1030 D InputDispatcher: Focus left window: 1490
08-24 17:07:38.661  6884  6884 D AndroidRuntime: Shutting down VM
08-24 17:07:38.661  6932  6932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:38.661  6932  6932 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 17:07:38.661  1018  1222 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:07:38.661  1018  1222 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
08-24 17:07:38.661  1018  1222 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:38.661  1018  1222 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:38.661  1018  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-24 17:07:38.671  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 17:07:38.671  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-24 17:07:38.671   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-24 17:07:38.681  2845  2845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Wed Aug 24 17:07:38 GMT+02:00 2016
08-24 17:07:38.681  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-24 17:07:38.681  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-24 17:07:38.681  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:38.681  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:38.681  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-24 17:07:38.681  6932  6932 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:38.691  6932  6932 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:38.691  1018  1486 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-24 17:07:38.701  2845  2845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-24 17:07:38.701  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 17:07:38.701  2845  2845 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-24 17:07:38.701  2845  2845 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-24 17:07:38.711  2845  2845 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-24 17:07:38.711  2845  6948 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
08-24 17:07:38.711  1018  1486 D PersonaManager: isKioskContainerExistOnDevice
08-24 17:07:38.711  2845  6948 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
08-24 17:07:38.721  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 17:07:38.721  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-24 17:07:38.721  1018  1018 V ActivityManager: Display changed displayId=0
08-24 17:07:38.721  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
08-24 17:07:38.731  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.731  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.731  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.731  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.731  2845  6948 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Wed Aug 24 17:07:38 GMT+02:00 2016
08-24 17:07:38.741  2845  6948 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
08-24 17:07:38.741  6950  6950 E Zygote  : MountEmulatedStorage()
08-24 17:07:38.741  6950  6950 E Zygote  : v2
08-24 17:07:38.741  6950  6950 I libpersona: KNOX_SDCARD checking this for 10036
08-24 17:07:38.741  6950  6950 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:38.741  6950  6950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:38.751  1018  1494 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6950 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:38.751  6950  6950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:38.751  6950  6950 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-24 17:07:38.761  2845  2845 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-24 17:07:38.771   257   450 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-24 17:07:38.771  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-24 17:07:38.771   257   452 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-24 17:07:38.781  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{2a023843 token=android.os.BinderProxy@2a5826e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-24 17:07:38.781  1490  1490 D Launcher: onTrimMemory. Level: 20
08-24 17:07:38.781  6950  6950 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:38.781  6950  6950 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:38.821  6950  6950 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3485f032
08-24 17:07:38.831  6950  6950 I SA      : [SSP] onCreated
08-24 17:07:38.851  6950  6950 I SA      : [TPM] There is no property file
08-24 17:07:38.851  6950  6950 I SA      : [SCU] isHaveSA() - false
08-24 17:07:38.861  6950  6950 I SA      : [TPM] getModelProperty : null
08-24 17:07:38.861  6950  6950 I SA      : [TPM] getCSCProperty : null
08-24 17:07:38.861  6950  6950 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-24 17:07:38.861  6950  6950 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-24 17:07:38.861  6950  6950 I SA      : [DM] TFT FEATURE: false
08-24 17:07:38.861  6884  6884 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-24 17:07:38.861  6950  6950 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
08-24 17:07:38.861  6950  6950 I SA      : [DM] init START
08-24 17:07:38.871  6950  6950 I SA      : [DM] This device is not a Vodafone
,08-24 17:07:38.871  6950  6950 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-24 17:07:38.871  6950  6950 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-24 17:07:38.871  6950  6950 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-24 17:07:38.881  6950  6950 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-24 17:07:38.891  6932  6932 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-24 17:07:38.891  6950  6950 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-24 17:07:38.891  6950  6950 I SA      : [SCU] isHaveSA() - false
08-24 17:07:38.891  6950  6950 I SA      : support phone number id : false
08-24 17:07:38.891  6950  6950 I SA      : [DM] Supports Ref Jpn : true
,08-24 17:07:38.901  6950  6950 I SA      : [DM] init END
,08-24 17:07:38.931  1018  1563 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-24 17:07:38.931  1018  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:38.931  1018  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.931  1018  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:38.931  1018  1563 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:38.941  6970  6970 E Zygote  : MountEmulatedStorage(),
08-24 17:07:38.941  6970  6970 E Zygote  : v2
08-24 17:07:38.941  6970  6970 I libpersona: KNOX_SDCARD checking this for 10058
,08-24 17:07:38.941  6970  6970 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:38.951  6970  6970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:38.951  6970  6970 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:38.951  1018  1563 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6970 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:38.951  6970  6970 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:38.951  1018  1563 I ActivityManager: Killing 6253:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
08-24 17:07:38.951  6932  6932 I cr.library_loader: Time to load native libraries: 13 ms (timestamps 5471-5484)
08-24 17:07:38.951  6932  6932 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 17:07:38.971  6970  6970 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:38.971  6970  6970 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:38.981  6932  6932 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7c7538a}
,08-24 17:07:38.981  6932  6932 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-24 17:07:38.981  6932  6932 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 17:07:39.021  6970  6970 I ExternalOEMControlProvider: onCreate
,08-24 17:07:39.021  6932  6932 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 17:07:39.031  6932  6932 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:07:39.031  1018  1327 I ActivityManager: Killing 5101:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-24 17:07:39.031  6970  6987 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-24 17:07:39.031  1793  1793 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-24 17:07:39.041  1793  1793 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-24 17:07:39.041  6932  6932 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 17:07:39.041  1018  1507 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-24 17:07:39.041  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.041  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.041  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.041  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.051  6988  6988 E Zygote  : MountEmulatedStorage()
,08-24 17:07:39.051  6988  6988 E Zygote  : v2
08-24 17:07:39.051  6988  6988 I libpersona: KNOX_SDCARD checking this for 10081
08-24 17:07:39.051  6988  6988 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:39.061  6988  6988 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:39.061  1018  1507 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6988 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:39.061  6988  6988 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:39.061  6988  6988 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:39.071  6988  6988 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:39.081  6988  6988 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:39.091  6988  6988 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
08-24 17:07:39.091  6988  6988 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 17:07:39.091  6988  6988 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:07:39.091  6988  6988 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 17:07:39.091  6988  6988 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-24 17:07:39.101  6932  6932 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 17:07:39.101  6932  6932 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 17:07:39.101  6932  6932 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 17:07:39.101  6932  6932 I Adreno-EGL: Local Branch: 
08-24 17:07:39.101  6932  6932 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 17:07:39.101  6932  6932 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 17:07:39.101  6932  6932 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 17:07:39.141  1018  1563 D SettingsProvider: name = next_alarm_formatted
,08-24 17:07:39.141  1018  1563 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:07:39.141  1018  1563 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:07:39.141  1018  1563 D SettingsProvider: selectionArgs: false
08-24 17:07:39.141  1018  1563 D SettingsProvider: selectionArgs: 10081
08-24 17:07:39.141  1018  1563 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:07:39.141  1018  1563 D SettingsProvider: ret = -1
,08-24 17:07:39.171  6932  6932 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 17:07:39.181  6932  6932 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 17:07:39.181  6932  6932 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-24 17:07:39.191  6932  6932 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 17:07:39.191  6932  6932 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-24 17:07:39.211  1018  4334 I ActivityManager: Killing 6062:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-24 17:07:39.221  1018  1043 W ActivityManager: Activity pause timeout for ActivityRecord{37f1eb3a u0 com.test.thalitest/.MainActivity t163}
,08-24 17:07:39.261  6988  6988 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 114.226ms
,08-24 17:07:39.311  6932  6932 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:07:39.321  6932  6932 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 17:07:39.341  6932  6932 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-24 17:07:39.341  6932  6932 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-24 17:07:39.341  6932  6932 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-24 17:07:39.351  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 17:07:39.351  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4195, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 17:07:39.351  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 17:07:39.351  1018  1031 D BatteryService: stay LED for charging
08-24 17:07:39.351  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 17:07:39.351  6932  6932 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 17:07:39.351  6932  6932 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:07:39.351  1018  1018 I MotionRecognitionService: Plugged
,08-24 17:07:39.351  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 17:07:39.361  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-24 17:07:39.361  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 17:07:39.361  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 17:07:39.361  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 17:07:39.371  3221  3221 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 17:07:39.371  3221  3360 D HeadsetStateMachine: Disconnected process message: 10
,08-24 17:07:39.371  1018  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-24 17:07:39.371  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.371  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.371  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.371  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.381  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:07:39.381  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:07:39.381  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:07:39.391  7024  7024 E Zygote  : MountEmulatedStorage()
08-24 17:07:39.391  7024  7024 E Zygote  : v2
08-24 17:07:39.391  7024  7024 I libpersona: KNOX_SDCARD checking this for 10090
08-24 17:07:39.391  7024  7024 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:39.391  7024  7024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:39.391  7024  7024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:39.391  7024  7024 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-24 17:07:39.401  1018  1501 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7024 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-24 17:07:39.401  1018  1501 I ActivityManager: Killing 6611:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-24 17:07:39.411  6932  7035 D OpenGLRenderer: Render dirty regions requested: true
,08-24 17:07:39.411  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-24 17:07:39.411  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 17:07:39.411  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 17:07:39.411  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 17:07:39.411  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 17:07:39.421  6932  7012 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-24 17:07:39.421  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:39.421  6932  6932 V ActivityThread: updateVisibility : ActivityRecord{1422e6d5 token=android.os.BinderProxy@1bfd3cbf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-24 17:07:39.421  7024  7024 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:39.431  6932  6932 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-24 17:07:39.431  6932  6932 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-24 17:07:39.441   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-24 17:07:39.441  6596  6596 I Mms/MmsApp:  start initViewCache mms
,08-24 17:07:39.441  6596  6596 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1863.569478
08-24 17:07:39.441  6596  6596 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-24 17:07:39.451  1018  1030 D InputDispatcher: Focus entered window: 6932
,08-24 17:07:39.451  7024  7024 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-24 17:07:39.451  7024  7024 D elm:15121: ELMEngine.ELMEngine( context ).
,08-24 17:07:39.461  7024  7024 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-24 17:07:39.461  1018  4327 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-24 17:07:39.461  1018  4327 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-24 17:07:39.461  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 17:07:39.461  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 17:07:39.461  6932  6932 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-24 17:07:39.461  1018  4327 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:39.461  1018  4327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:39.461  1018  4327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-24 17:07:39.461  6932  7035 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 17:07:39.461  7024  7024 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-24 17:07:39.471  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-24 17:07:39.471  6932  7035 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-24 17:07:39.471  6932  7035 D OpenGLRenderer: Enabling debug mode 0
,08-24 17:07:39.471  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.471  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.471  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.471  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.471  7024  7024 D elm:15121: ElmAgentService : onCreate()
,08-24 17:07:39.471  7024  7043 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-24 17:07:39.481  7045  7045 E Zygote  : MountEmulatedStorage()
08-24 17:07:39.481  7045  7045 E Zygote  : v2
08-24 17:07:39.481  7045  7045 I libpersona: KNOX_SDCARD checking this for 10130
08-24 17:07:39.481  7045  7045 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:39.481  7045  7045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:39.491  7045  7045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:39.491  7045  7045 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-24 17:07:39.491  7024  7043 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
08-24 17:07:39.491  1018  1031 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7045 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-24 17:07:39.491  7024  7024 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
08-24 17:07:39.491  7024  7024 D elm:15121: ModuleBase.ModifySetAlarm()
08-24 17:07:39.491  7024  7024 D elm:15121: MDMBridge.getInstance()
08-24 17:07:39.491  7024  7024 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-24 17:07:39.501  1018  4334 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 17:07:39.501  7024  7024 D elm:15121: ElmAgentService : onDestroy().
08-24 17:07:39.501  1018  7059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 17:07:39.511  1176  1176 D PanelView: There is/are notification(s) 
,08-24 17:07:39.511  1018  4327 I ActivityManager: Killing 6653:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-24 17:07:39.531  7045  7045 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:39.531  1018  1048 W ActivityManager: mDVFSHelper.release()
08-24 17:07:39.531  1018  1048 I ActivityManager: Displayed Component not be shown by security: +820ms (total +898ms)
08-24 17:07:39.531  7045  7045 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:39.531  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37f1eb3a u0 com.test.thalitest/.MainActivity t163} time:96069
,08-24 17:07:39.541  6932  6932 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 17:07:39.541  6932  6932 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bfd3cbf time:96078
,08-24 17:07:39.551   257   452 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-24 17:07:39.551   257  1098 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-24 17:07:39.561  7045  7045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-24 17:07:39.561  7045  7045 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-24 17:07:39.571  1869  1869 I SamsungIME: getCurrentCandidateView,
,08-24 17:07:39.581  1018  1222 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-24 17:07:39.581  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.581  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-24 17:07:39.581  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.581  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.591  7065  7065 E Zygote  : MountEmulatedStorage()
,08-24 17:07:39.591  7065  7065 I libpersona: KNOX_SDCARD checking this for 10131
08-24 17:07:39.591  7065  7065 E Zygote  : v2
08-24 17:07:39.591  7065  7065 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:39.591  7065  7065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:39.601  7065  7065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:39.601  7065  7065 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:39.611  1018  1222 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7065 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-24 17:07:39.611  1018  1222 I ActivityManager: Killing 6179:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-24 17:07:39.621  7065  7065 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:39.631  7065  7065 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:39.641  6596  6596 D AbsListView: Get MotionRecognitionManager
,08-24 17:07:39.641  1018  1222 D MotionRecognitionService:  ssp status : false
,08-24 17:07:39.641  7065  7065 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 17:07:39.641  7065  7065 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:07:39.641  7065  7065 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 17:07:39.651  6596  6596 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 202.537917
,08-24 17:07:39.691  2632  2697 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 17:07:39.691  1018  1501 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-24 17:07:39.691  1018  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-24 17:07:39.691  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:39.691  1018  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:39.691  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-24 17:07:39.711  1018  1327 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-24 17:07:39.711  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-24 17:07:39.711  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:39.711  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:39.711  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-24 17:07:39.721  1018  4333 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-24 17:07:39.721  1018  4333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.721  1018  4333 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.721  1018  4333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.721  1018  4333 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.741  7088  7088 E Zygote  : MountEmulatedStorage()
08-24 17:07:39.741  7088  7088 E Zygote  : v2
08-24 17:07:39.741  7088  7088 I libpersona: KNOX_SDCARD checking this for 1000
08-24 17:07:39.741  7088  7088 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:39.741  7088  7088 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:39.741  1869  1869 D SamsungIME: Dismiss ExpandCandiate
,08-24 17:07:39.741  1018  4333 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=7088 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 17:07:39.741  7088  7088 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:39.741  7088  7088 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:39.741  1018  1222 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-24 17:07:39.751  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.751  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.751  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.751  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.751  6932  6932 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6932
,08-24 17:07:39.751  6596  6596 D Mms/BubbleViewCache: fillCache bubble = 1
,08-24 17:07:39.761  7097  7097 E Zygote  : MountEmulatedStorage()
,08-24 17:07:39.761  7097  7097 E Zygote  : v2
08-24 17:07:39.761  7097  7097 I libpersona: KNOX_SDCARD checking this for 10037
08-24 17:07:39.761  7097  7097 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:39.771  1018  1222 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7097 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:39.771  7097  7097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:39.771  7088  7088 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:39.771  7097  7097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:39.771  7088  7088 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:39.771  7097  7097 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 17:07:39.801  7097  7097 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:39.801  7097  7097 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:39.821  7097  7097 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-24 17:07:39.821  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 17:07:39.821  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:39.821  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
,08-24 17:07:39.841  1018  1327 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-24 17:07:39.841  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.841  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.841  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.841  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:39.851  7097  7097 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-24 17:07:39.861  7123  7123 E Zygote  : MountEmulatedStorage()
08-24 17:07:39.861  7123  7123 E Zygote  : v2
08-24 17:07:39.861  7123  7123 I libpersona: KNOX_SDCARD checking this for 10153
08-24 17:07:39.861  7123  7123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:39.861  7123  7123 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:39.861  7123  7123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:39.861  1018  1327 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7123 uid=10153 gids={50153, 9997} abi=armeabi-v7a
08-24 17:07:39.861  7123  7123 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:39.861  1018  1327 I ActivityManager: Killing 6684:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-24 17:07:39.891  7123  7123 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:39.891   311   311 I art     : Explicit concurrent mark sweep GC freed 8666(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 636us total 28.117ms
08-24 17:07:39.891  7123  7123 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:39.901  7123  7123 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 17:07:39.911   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 17.825ms
,08-24 17:07:39.921  1018  1562 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
08-24 17:07:39.921  1018  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.921  1018  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.921  1018  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.921  1018  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:39.921   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 17.020ms
,08-24 17:07:39.931  6932  6932 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,08-24 17:07:39.941  7140  7140 E Zygote  : MountEmulatedStorage(),
,08-24 17:07:39.941  7140  7140 E Zygote  : v2
,08-24 17:07:39.941  7140  7140 I libpersona: KNOX_SDCARD checking this for 1000
08-24 17:07:39.941  7140  7140 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:39.941  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:39.941  1018  1562 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7140 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 17:07:39.941  1018  1562 I ActivityManager: Killing 6719:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21,
08-24 17:07:39.951  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:39.951  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:39.961  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:39.961  7140  7140 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:39.991  7140  7140 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472051260003
,08-24 17:07:39.991  7140  7140 D         : TimeServiceNative: User Time to be set is 1472051260003
08-24 17:07:39.991  7140  7140 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,08-24 17:07:39.991  7140  7140 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-24 17:07:39.991  7140  7140 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472051260003
,08-24 17:07:39.991   324   430 D QC-time-services: Daemon: Connection accepted:time_genoff
08-24 17:07:39.991  7140  7140 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-24 17:07:39.991   324  7156 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472051260003
08-24 17:07:39.991   324  7156 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472051260003, operation = 0
,08-24 17:07:39.991   324  7156 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/19/71 8:50:32
08-24 17:07:39.991   324  7156 D QC-time-services: Daemon:Value read from RTC seconds = 35801432000
08-24 17:07:39.991   324  7156 D QC-time-services: Daemon:new time 1472051260003 
,08-24 17:07:39.991   324  7156 D QC-time-services: Daemon: delta 1436249828003 genoff 1436249828003 
,08-24 17:07:39.991   324  7156 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249828003 to memory
08-24 17:07:39.991   324  7156 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-24 17:07:39.991   324  7156 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-24 17:07:40.011  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 17:07:40.011  1018  1031 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-24 17:07:40.011  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-24 17:07:40.021  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:40.021  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:40.021  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-24 17:07:40.041   324  7156 D QC-time-services: Updating the TOD offset
08-24 17:07:40.041   324  7156 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249828003 to memory
08-24 17:07:40.041   324  7156 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-24 17:07:40.041   324  7156 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-24 17:07:40.051   324  7156 E QC-time-services: Daemon:Update to modem bit set
08-24 17:07:40.051   324  7156 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-24 17:07:40.051   324  7156 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285028003
08-24 17:07:40.051  7140  7140 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-24 17:07:40.051   324   425 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-24 17:07:40.051   324   430 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-24 17:07:40.051  1018  4327 I ActivityManager: Killing 6702:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-24 17:07:40.061  2632  2632 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-24 17:07:40.061  2632  2632 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-24 17:07:40.061  2632  2632 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 17:07:40.071  2632  2632 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-24 17:07:40.071  2632  2632 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-24 17:07:40.081  2632  2632 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-24 17:07:40.081  2632  2632 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 17:07:40.081  2632  2632 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,08-24 17:07:40.081  2632  2632 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-24 17:07:40.081  2632  2632 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-24 17:07:40.081  2632  2632 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-24 17:07:40.081  2632  2632 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-24 17:07:40.081  1018  1030 I ActivityManager: Killing 6756:com.sec.pcw.device/1000 (adj 15): empty #21
,08-24 17:07:40.091  2632  2632 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-24 17:07:40.091  1869  1869 I SamsungIME: getDebugLevel  : 0x4f4c
,08-24 17:07:40.091  2632  2632 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-24 17:07:40.091  2632  2632 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-24 17:07:40.091  2632  2632 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-24 17:07:40.091  2632  2632 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-24 17:07:40.101  1869  1869 I SamsungIME: KeybaordView init() : load resources
,08-24 17:07:40.101  2632  2632 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-24 17:07:40.111  2632  2632 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-24 17:07:40.111  2632  2632 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-24 17:07:40.131  1869  1869 I SamsungIME: getCurrentKeyboard
08-24 17:07:40.131  1869  1869 I SamsungIME: getTextKeyboard
,08-24 17:07:40.141  6932  7080 D jxcore_app_log: JniHelper::setJavaVM(0xb7f8e2b0), pthread_self() = -1202602680
,08-24 17:07:40.151  6932  7080 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 17:07:40.151  6932  7080 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 17:07:40.151  6932  7080 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 17:07:40.151  6932  7080 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 17:07:40.151  6932  7080 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 17:07:40.151  6932  7080 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f662e90 added. We now have 1 listener(s)
,08-24 17:07:40.151  1869  1869 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-24 17:07:40.161  6932  7080 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-24 17:07:40.161  6932  7080 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 17:07:40.161  6932  7080 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 17:07:40.161  6932  7080 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 17:07:40.161  6932  7080 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4d3af added. We now have 1 listener(s)
,08-24 17:07:40.161  6932  7080 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:40.171  6932  7080 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:07:40.171  6932  7080 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 17:07:40.171  6932  7080 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 17:07:40.171  6932  7080 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 17:07:40.171  6932  7080 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 17:07:40.171  6932  7080 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:40.181  6932  7080 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-24 17:07:40.191  6932  7080 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 17:07:40.191  6932  7080 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:40.191  6932  7080 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:40.191  6932  7080 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:40.191  6932  7080 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:40.191  6932  7080 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:40.191  6932  7080 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:40.191  6932  7080 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:40.191  6932  7080 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:07:40.191  6932  7080 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 17:07:40.191  6932  7080 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:40.191  6932  7080 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 17:07:40.191  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:40.201  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:40.221  6932  6932 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 17:07:40.711   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb789f7c8
08-24 17:07:40.711   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-24 17:07:40.711   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-24 17:07:40.711   272   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1215694712)
,08-24 17:07:40.751   272   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-24 17:07:40.751   272   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-24 17:07:40.751   272   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1215694712) wakelock released: 1, error no: 0
08-24 17:07:40.751   272   340 I rmt_storage: 
,08-24 17:07:40.751  6932  7162 W jxcore-log: Initializing JXcore engine,
08-24 17:07:40.751  6932  7162 W jxcore-log: JXcore engine is ready
08-24 17:07:40.751   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb789f7c8,
,08-24 17:07:40.831  2012  2012 E audit   : type=1400 msg=audit(1472051260.831:205): avc:  denied  { ioctl } for  pid=7162 comm="Thread-1306" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-24 17:07:40.831  2012  2012 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:40.831  2012  2012 E audit   : type=1300 msg=audit(1472051260.831:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d3c48f8 items=0 ppid=311 ppcomm=main pid=7162 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1306" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-24 17:07:40.831  2012  2012 E audit   : type=1320 msg=audit(1472051260.831:205): 
,08-24 17:07:40.841  6932  7162 W jxcore-log: Starting JXcore engine,
,08-24 17:07:40.951  6932  7162 W jxcore-log: Platform android
08-24 17:07:40.951  6932  7162 W jxcore-log: 
08-24 17:07:40.951  6932  7162 W jxcore-log: Process ARCH arm
08-24 17:07:40.951  6932  7162 W jxcore-log: 
,08-24 17:07:41.021  7097  7097 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-24 17:07:41.031  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:41.031  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:41.031  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-24 17:07:41.031  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-24 17:07:41.031  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:41.031  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:41.031  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-24 17:07:41.031  1018  4333 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:41.031  1018  4333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:41.031  1018  4333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-24 17:07:41.041  1018  1031 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-24 17:07:41.041  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-24 17:07:41.041  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:41.041  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:07:41.041  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-24 17:07:41.051  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:41.051  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:41.051  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-24 17:07:41.061  1018  4334 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-24 17:07:41.061  1018  4334 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-24 17:07:41.061  1018  4334 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:41.061  1018  4334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:41.061  1018  4334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-24 17:07:41.071  1018  1486 I ActivityManager: Killing 6770:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-24 17:07:41.161  6932  7162 I jxcore-log: JXcore Cordova bridge is ready!
08-24 17:07:41.161  6932  7162 I jxcore-log: 
,08-24 17:07:41.161  6932  7162 W jxcore-log: JXcore engine is started
,08-24 17:07:41.171  6932  7080 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 17:07:41.171  6932  6932 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 17:07:41.381   291   291 E SMD     : DCD OFF,
,08-24 17:07:41.401  1018  3414 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 17:07:43.001  2650  2650 I ConfigService: onDestroy
,08-24 17:07:44.381   291   291 E SMD     : DCD OFF,
,08-24 17:07:45.681  1018  3386 D SSRM:n  : SIOP:: AP = 400
,08-24 17:07:46.401  1018  3414 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 17:07:47.381   291   291 E SMD     : DCD OFF
,08-24 17:07:48.141  1018  1058 D PackageManager: [MSG] MCS_UNBIND
,08-24 17:07:48.151  1018  1494 I ActivityManager: Killing 6110:com.android.vending/u0a26 (adj 15): empty #21
,08-24 17:07:48.641  1018  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-24 17:07:49.391  1018  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 17:07:49.391  1018  1137 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4257, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 17:07:49.391  1018  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 17:07:49.391  1018  1137 D BatteryService: stay LED for charging
08-24 17:07:49.391  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 17:07:49.401  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 17:07:49.401  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 17:07:49.401  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 17:07:49.401  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 17:07:49.401  1018  1018 I MotionRecognitionService: Plugged
,08-24 17:07:49.401  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 17:07:49.421  3221  3221 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-24 17:07:49.421  3221  3360 D HeadsetStateMachine: Disconnected process message: 10
,08-24 17:07:49.431  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:07:49.431  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:07:49.431  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:07:50.391   291   291 E SMD     : DCD OFF,
,08-24 17:07:51.301  1018  1317 E Watchdog: !@Sync 3
,08-24 17:07:52.421  1018  1096 V AlarmManager: waitForAlarm result :4,
08-24 17:07:52.421  1018  1096 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-24 17:07:52.421  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:52.421  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:52.421  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:52.421  1018  1096 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:52.441  7171  7171 E Zygote  : MountEmulatedStorage()
08-24 17:07:52.441  7171  7171 I libpersona: KNOX_SDCARD checking this for 10026
08-24 17:07:52.441   322   322 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-24 17:07:52.441  7171  7171 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:52.441  7171  7171 E Zygote  : v2
08-24 17:07:52.441   322   322 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-24 17:07:52.441  7171  7171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:52.441  1018  1096 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7171 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:52.441  7171  7171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:52.441  7171  7171 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:07:52.461  7171  7171 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:52.461  7171  7171 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:52.541  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.551  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.591  7171  7171 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-24 17:07:52.591  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.681  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.681  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.691  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.691  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.701  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.701  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.701  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.701  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.701  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.701  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.711  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.711  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.711  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.711  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.711  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.711  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.721  7171  7171 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-24 17:07:52.731  7171  7171 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 17:07:52.731  7171  7171 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-24 17:07:52.751  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.751  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:52.751  7171  7171 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-24 17:07:52.911  1018  1137 I art     : Explicit concurrent mark sweep GC freed 23483(1351KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/34MB, paused 2.604ms total 149.465ms
,08-24 17:07:52.931  7171  7171 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-24 17:07:52.931  7171  7207 D Ads     : Skipping gmscore version check
,08-24 17:07:52.931  1018  1031 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,08-24 17:07:52.941  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,08-24 17:07:52.941  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:52.941  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:07:52.941  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,08-24 17:07:52.951  1018  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:52.961  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:52.961  1018  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:52.961  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,08-24 17:07:52.961  7171  7171 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-24 17:07:52.971  7171  7171 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-24 17:07:53.041  7171  7204 D Finsky  : [1354] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-24 17:07:53.041  7171  7171 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-24 17:07:53.041  1018  1507 I ActivityManager: Killing 6795:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-24 17:07:53.391   291   291 E SMD     : DCD OFF
,08-24 17:07:53.911  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-24 17:07:53.911  6932  7162 I jxcore-log: 
,08-24 17:07:53.911  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-24 17:07:53.911  6932  7162 I jxcore-log: 
,08-24 17:07:53.921  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:53.921  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:53.921  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:53.921  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:53.921  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:53.921  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:53.921  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:53.921  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:53.921  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:53.931  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 17:07:53.931  6932  7162 I jxcore-log: 
,08-24 17:07:53.931  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 17:07:53.931  6932  7162 I jxcore-log: 
,08-24 17:07:54.601  6932  7162 D executeNativeTests: Running unit tests,
,08-24 17:07:54.681  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:07:54.681  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 added. We now have 2 listener(s)
,08-24 17:07:54.691  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 17:07:54.691  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:07:54.691  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:07:54.691  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:07:54.691  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 added. We now have 2 listener(s)
08-24 17:07:54.691  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:54.691  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:07:54.691  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:54.691  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:54.691  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:54.691  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:54.691  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:54.691  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:54.691  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:54.691  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:54.691  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:54.701  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:54.701  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:54.701  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:54.701  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:54.701  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 17:07:54.711  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:07:54.711  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 17:07:54.711  6932  7162 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-24 17:07:54.711  6932  7162 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 17:07:54.711  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:07:54.711  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:07:54.711  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:07:54.711  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:54.711  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:54.711  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:54.711  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:54.711  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:54.711  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:07:54.711  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:07:54.711  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 removed from the list
08-24 17:07:54.711  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:54.711  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 removed from the list
08-24 17:07:54.711  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:54.711  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:54.721  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:54.721  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:54.721  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:54.721  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:54.721  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:54.721  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:54.721  6932  7162 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-24 17:07:54.721  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:54.721  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:54.721  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:54.721  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:54.721  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:54.721  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:54.721  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:54.721  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:54.721  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:54.721  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:54.721  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:54.721  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:54.721  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:54.721  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:54.731  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 17:07:54.731  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:54.731  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:07:54.731  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:54.731  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:54.731  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:54.731  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
,08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:54.731  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:54.731  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop,
08-24 17:07:54.731  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:54.731  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:54.731  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:54.731  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:54.731  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:54.731  6932  7162 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-24 17:07:54.731  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:54.741  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:54.741  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:54.741  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:54.741  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:54.741  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:54.741  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:54.741  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:54.741  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:54.741  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:54.741  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:54.741  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:07:54.741  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:07:54.741  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:07:54.741  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:54.741  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:07:54.751  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:54.751  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:07:54.751  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:54.751  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:07:54.761  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:07:54.761  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-24 17:07:54.761  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-24 17:07:54.761  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 17:07:54.761  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:07:54.761  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:07:54.771  3221  3355 D BtGatt.GattService: registerClient() - UUID=7bda057b-80c5-4a0a-996b-439d094a1fce
,08-24 17:07:54.821  3221  3295 D BtGatt.GattService: onClientRegistered() - UUID=7bda057b-80c5-4a0a-996b-439d094a1fce, clientIf=6
,08-24 17:07:54.821  6932  6944 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 17:07:54.821  3221  3231 D BtGatt.GattService: start scan with filters
,08-24 17:07:54.821  3221  3358 D BtGatt.ScanManager: handling starting scan
,08-24 17:07:54.831  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:07:54.831  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 17:07:54.831  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 17:07:54.831  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:07:54.831  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:54.831  3221  3358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:07:54.841  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:07:54.841  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:54.841  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:07:54.851  3221  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-24 17:07:54.851  6932  7162 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:07:54.851  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.851  3221  3358 D BtGatt.ScanManager: allow scan with filters
08-24 17:07:54.851  3221  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 17:07:54.851  3221  3358 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-24 17:07:54.851  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:54.851  6932  7162 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:07:54.861  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:07:54.861  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 17:07:54.861  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:54.861  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 17:07:54.861  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.861  3221  3358 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:07:54.861  3221  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:07:54.861  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:07:54.861  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:07:54.861  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:07:54.861  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:07:54.861  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:07:54.861  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:07:54.861  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:07:54.861  3221  5337 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:07:54.871  3221  3355 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:07:54.871  3221  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-24 17:07:54.871  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 17:07:54.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:07:54.871  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:07:54.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 17:07:54.871  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:07:54.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:54.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 17:07:54.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:07:54.871  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:07:54.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:07:54.881  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
,08-24 17:07:54.881  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:54.881  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:54.881  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:54.881  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:07:54.881  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:54.881  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:54.881  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:54.881  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:54.881  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:07:54.881  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:54.881  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:54.881  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:54.881  6932  7162 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 17:07:54.881  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:54.891  3221  3358 D BtGatt.ScanManager: filter size is 1
,08-24 17:07:54.891  3221  3358 D BtGatt.ScanManager: delete FilterIndex - 3
,08-24 17:07:54.891  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:54.891  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:54.891  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:54.891  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:54.891  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:54.891  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:54.891  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:54.891  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:54.891  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-24 17:07:54.901  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.901  3221  3358 D BtGatt.ScanManager: stopping BLe Batch
08-24 17:07:54.901  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:54.901  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:07:54.901  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:07:54.901  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:07:54.901  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:07:54.901  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:54.901  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:07:54.901  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:54.901  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:07:54.911  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:07:54.911  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.911  3221  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:07:54.911  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:54.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:07:54.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:07:54.911  3221  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-24 17:07:54.911  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.921  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:07:54.921  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:07:54.921  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:07:54.921  3221  3355 D BtGatt.GattService: registerClient() - UUID=604f6f9b-ecd8-4e54-b6c5-a38c13d14d69
,08-24 17:07:54.971  3221  3295 D BtGatt.GattService: onClientRegistered() - UUID=604f6f9b-ecd8-4e54-b6c5-a38c13d14d69, clientIf=6
,08-24 17:07:54.971  6932  6940 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 17:07:54.971  3221  3231 D BtGatt.GattService: start scan with filters
,08-24 17:07:54.971  3221  3358 D BtGatt.ScanManager: handling starting scan
08-24 17:07:54.971  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:07:54.971  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:07:54.971  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:07:54.971  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:07:54.971  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:54.971  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:54.971  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:07:54.971  3221  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-24 17:07:54.971  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.971  3221  3358 D BtGatt.ScanManager: allow scan with filters
,08-24 17:07:54.971  3221  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 17:07:54.981  3221  3358 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-24 17:07:54.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:07:54.981  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 17:07:54.981  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.981  3221  3358 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:07:54.981  3221  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:07:54.991  6932  7162 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:07:54.991  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:54.991  3221  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 17:07:54.991  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:54.991  6932  7162 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:07:54.991  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:07:54.991  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 17:07:55.001  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.001  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:07:55.001  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:07:55.001  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:07:55.001  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:07:55.001  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:07:55.001  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:07:55.001  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:07:55.001  3221  5337 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:07:55.001  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 17:07:55.001  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.001  3221  3358 D BtGatt.ScanManager: filter size is 1
,08-24 17:07:55.001  3221  3358 D BtGatt.ScanManager: delete FilterIndex - 4
,08-24 17:07:55.011  3221  3355 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:07:55.011  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 17:07:55.011  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 17:07:55.011  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 17:07:55.011  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 17:07:55.011  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:07:55.011  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-24 17:07:55.011  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.011  3221  3358 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:07:55.011  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:55.011  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 17:07:55.011  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 17:07:55.011  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:07:55.021  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-24 17:07:55.021  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:07:55.021  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:55.021  3221  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:07:55.021  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.021  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.021  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:07:55.021  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.021  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:07:55.021  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.021  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.021  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.021  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:55.021  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:55.021  3221  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 17:07:55.021  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:55.021  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.021  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.021  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.021  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:07:55.021  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.021  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.021  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.021  6932  7162 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 17:07:55.031  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:55.031  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:55.031  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:55.031  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:55.031  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:55.031  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:07:55.031  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:55.031  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:55.031  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:55.031  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:55.031  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:55.031  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:55.041  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:07:55.041  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:07:55.041  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:07:55.041  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:07:55.041  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:07:55.041  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:55.041  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:07:55.051  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:07:55.051  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:07:55.051  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:07:55.051  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 17:07:55.051  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:07:55.051  3221  3231 D BtGatt.GattService: registerClient() - UUID=63c8f0a2-4c00-4555-b542-6125ba9a2a7d
,08-24 17:07:55.101  3221  3295 D BtGatt.GattService: onClientRegistered() - UUID=63c8f0a2-4c00-4555-b542-6125ba9a2a7d, clientIf=6
,08-24 17:07:55.101  6932  6940 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 17:07:55.101  3221  3230 D BtGatt.GattService: start scan with filters
,08-24 17:07:55.101  3221  3358 D BtGatt.ScanManager: handling starting scan
,08-24 17:07:55.101  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 17:07:55.101  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:07:55.101  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:07:55.101  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:07:55.101  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:55.101  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:07:55.101  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:07:55.101  3221  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-24 17:07:55.111  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.111  3221  3358 D BtGatt.ScanManager: allow scan with filters
,08-24 17:07:55.111  3221  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 17:07:55.111  3221  3358 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-24 17:07:55.111  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:07:55.111  6932  7162 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 17:07:55.111  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:55.111  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 17:07:55.111  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.111  3221  3358 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:07:55.111  3221  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:07:55.121  6932  7162 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 17:07:55.121  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.121  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 17:07:55.121  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:07:55.121  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:07:55.121  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:07:55.121  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:07:55.121  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:07:55.121  3221  3231 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:07:55.121  3221  3230 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 17:07:55.121  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:07:55.121  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:07:55.121  3221  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-24 17:07:55.121  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 17:07:55.121  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 17:07:55.121  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:07:55.131  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:07:55.131  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:07:55.131  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:07:55.131  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.131  6932  7162 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 17:07:55.131  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.131  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.131  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.131  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.131  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.131  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-24 17:07:55.131  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.131  6932  7162 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-24 17:07:55.131  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.131  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.131  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.131  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.131  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.131  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.131  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.131  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 17:07:55.131  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.131  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.131  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.131  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.131  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.131  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.131  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.131  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.131  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.131  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.141  6932  7162 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-24 17:07:55.141  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.141  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:07:55.141  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.141  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.141  6932  7162 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 17:07:55.141  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.141  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.141  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.141  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.141  3221  3358 D BtGatt.ScanManager: filter size is 1
,08-24 17:07:55.141  3221  3358 D BtGatt.ScanManager: delete FilterIndex - 5
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-24 17:07:55.141  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:07:55.141  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 17:07:55.141  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-24 17:07:55.141  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:55.141  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:07:55.141  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.141  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.141  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.141  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-24 17:07:55.141  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-24 17:07:55.141  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list,
08-24 17:07:55.141  6932  7162 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:07:55.141  6932  7162 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-24 17:07:55.141  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-24 17:07:55.141  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 17:07:55.141  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.141  3221  3358 D BtGatt.ScanManager: stopping BLe Batch
08-24 17:07:55.151  6932  7162 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 17:07:55.151  6932  7162 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510],
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 17:07:55.151  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-24 17:07:55.151  6932  7162 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 17:07:55.151  6932  7162 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:07:55.151  6932  7162 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-24 17:07:55.151  6932  7162 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 17:07:55.151  6932  7162 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:07:55.151  6932  7162 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 17:07:55.151  6932  7162 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:07:55.151  6932  7162 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 17:07:55.151  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-24 17:07:55.151  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:07:55.151  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.151  3221  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-24 17:07:55.161  3221  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 17:07:55.161  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 17:07:55.161  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 17:07:55.161  6932  7162 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-24 17:07:55.161  6932  7162 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 17:07:55.161  6932  7162 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-24 17:07:55.161  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.161  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.161  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.161  6932  7214 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1370)
08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.161  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.161  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.161  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-24 17:07:55.161  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.161  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.161  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.161  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.161  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.161  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.161  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.161  6932  7215 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1370
08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.161  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.161  6932  7162 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 17:07:55.161  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.161  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.161  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.161  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.161  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.161  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.161  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.161  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.161  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.161  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.161  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.161  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.161  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.171  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.171  6932  7162 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-24 17:07:55.171  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.171  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.171  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.171  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.171  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.171  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.171  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.171  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.171  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.171  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.171  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.171  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.171  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.171  6932  7162 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 17:07:55.171  6932  7162 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 17:07:55.171  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-24 17:07:55.171  6932  7162 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 17:07:55.171  6932  7214 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-24 17:07:55.171  6932  7214 D BluetoothSocket: connect(): myUserId = 0,
08-24 17:07:55.171  6932  7214 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 17:07:55.171  6932  7162 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 17:07:55.171  6932  7162 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-24 17:07:55.171  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:07:55.171  6932  7162 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 17:07:55.171  6932  7162 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 17:07:55.171  6932  7162 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 17:07:55.171  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:07:55.171  6932  7162 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 17:07:55.171  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:55.171  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.171  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.171  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.171  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.171  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.171  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.171  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.171  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:07:55.171  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.171  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.171  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.171  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.171  3221  3355 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.181  6932  7214 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.181  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.181  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.181  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.181  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.181  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.181  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.181  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.181  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.181  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.181  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:5,5.181  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:07:55.181  6932  6932 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 17:07:55.181  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.181  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:07:55.181  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.181  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.191  6932  6932 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.191  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.191  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.191  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.191  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.191  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.191  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:07:55.191  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:07:55.191  6932  7216 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 17:07:55.191  6932  7216 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-24 17:07:55.191  6932  7162 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 17:07:55.191  6932  7162 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 17:07:55.191  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 17:07:55.191  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.191  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.191  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.191  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.191  6932  6932 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.191  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:07:55.191  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.191  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list
08-24 17:07:55.191  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.191  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.191  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.191  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.191  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.201  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-24 17:07:55.201  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.201  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.201  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
,08-24 17:07:55.201  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:07:55.201  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:07:55.201  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:07:55.201  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:07:55.201  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.201  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.201  6932  7162 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e084160 not in the list,
08-24 17:07:55.201  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.201  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:07:55.201  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.201  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:07:55.201  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:07:55.201  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:07:55.201  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:07:55.201  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:07:55.201  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:07:55.201  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3daf4619 not in the list,
08-24 17:07:55.201  6932  7162 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:07:55.201  6932  7162 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 17:07:55.201  6932  7162 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 17:07:55.201  6932  7162 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 17:07:55.201  6932  7162 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 17:07:55.201  6932  7162 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 17:07:55.201  6932  7162 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 17:07:55.201  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:07:55.201  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34049953 added. We now have 2 listener(s)
08-24 17:07:55.201  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:55.211  6932  7162 D BluetoothAdapter: enable()
,08-24 17:07:55.211  6932  7162 D BluetoothAdapter: enable(): BT is already enabled..!
,08-24 17:07:55.211  1018  4327 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-24 17:07:55.211  1018  4327 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-24 17:07:55.211  1018  4327 D SecContentProvider2: mCursor = null
,08-24 17:07:55.211  1018  4327 D WifiService: setWifiEnabled: true pid=6932, uid=10170
08-24 17:07:55.211  1018  4327 W ActivityManager: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 17:07:55.221  1018  4327 W WifiService: Failed getting userId using ActivityManagerNative,
08-24 17:07:55.221  1018  4327 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:07:55.221  1018  4327 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:07:55.221  1018  4327 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 17:07:55.221  1018  4327 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 17:07:55.221  1018  4327 W WifiService: ,	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 17:07:55.221  1018  4327 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 17:07:55.221  1018  4327 D SettingsProvider: name = wifi_on
08-24 17:07:55.221  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:07:55.221  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35dec290 added. We now have 3 listener(s)
08-24 17:07:55.221  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:55.221  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:07:55.221  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a80e789 added. We now have 4 listener(s)
08-24 17:07:55.221  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:55.231  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:07:55.231  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c64838e added. We now have 5 listener(s)
,08-24 17:07:55.231  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:07:55.231  1018  1494 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 17:07:55.231  1018  1494 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-24 17:07:55.231  1018  1494 D SecContentProvider2: mCursor = null
,08-24 17:07:55.231  1018  1494 D WifiService: setWifiEnabled: false pid=6932, uid=10170
,08-24 17:07:55.231  1018  1494 D SettingsProvider: name = wifi_on
,08-24 17:07:55.241  1018  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-24 17:07:55.241  1383  1383 I wpa_supplicant: reset timer : RESET_TIMER 0
08-24 17:07:55.241  1383  1383 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-24 17:07:55.241  1383  1383 I wpa_supplicant: P2P: Current p2p state = IDLE
08-24 17:07:55.241  1383  1383 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 17:07:55.241  6932  7162 D BluetoothAdapter: disable()
,08-24 17:07:55.251  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:07:55.251  1018  1030 D SettingsProvider: name = bluetooth_on
,08-24 17:07:55.261  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-24 17:07:55.261  3221  3292 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-24 17:07:55.261  3221  3292 D BluetoothAdapterProperties: Setting state to 13
,08-24 17:07:55.261  1018  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:55.261  3221  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 17:07:55.261  1018  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-24 17:07:55.261  3221  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:07:55.261  3221  3292 D BluetoothAdapterService: updateAdapterState state is 13
08-24 17:07:55.271  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.271  1018  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.271  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:55.271  3221  3221 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-24 17:07:55.271  3221  3292 D BluetoothAdapterService: Autoconnection is available 
08-24 17:07:55.271  3221  3292 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-24 17:07:55.271  3221  3292 D BluetoothAdapterService: terminating service from this receiver
,08-24 17:07:55.271  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@251073b5, channel: 19, state: LISTENING
08-24 17:07:55.271  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@251073b5, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9401ef2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e409a4amSocket: android.net.LocalSocket@fc06dbb impl:android.net.LocalSocketImpl@2fffe2d8 fd:FileDescriptor[82]
08-24 17:07:55.271  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fc06dbb impl:android.net.LocalSocketImpl@2fffe2d8 fd:FileDescriptor[82]
,08-24 17:07:55.271  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:55.271  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:55.271  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:07:55.271  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:55.271  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-24 17:07:55.271  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:55.271  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:55.271  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:55.271  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:55.271  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 17:07:55.271  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
08-24 17:07:55.271  1383  1383 I wpa_supplicant: Scan aborted because the firmware maybe busy.
08-24 17:07:55.271  1383  1383 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
08-24 17:07:55.271  1383  1383 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,08-24 17:07:55.271  1018  1127 E WifiNative-wlan0: do suspend true
,08-24 17:07:55.271  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:55.271  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:55.271  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:07:55.281  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-24 17:07:55.281  1176  1176 D BluetoothTile:  onBluetoothStateChange:,
,08-24 17:07:55.281  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:55.281  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:07:55.281  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:07:55.291  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:55.291  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-24 17:07:55.291  1869  1869 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:07:55.291  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:07:55.291  1018  4334 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:07:55.291  1018  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:07:55.291  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:07:55.291  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 17:07:55.301  4768  4768 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:07:55.301  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.301  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.301  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.301  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:07:55.301  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32219631, channel: 5, state: LISTENING
,08-24 17:07:55.301  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32219631, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@180e01fd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ef61116mSocket: android.net.LocalSocket@4fe2a97 impl:android.net.LocalSocketImpl@18fc5484 fd:FileDescriptor[80]
08-24 17:07:55.301  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@4fe2a97 impl:android.net.LocalSocketImpl@18fc5484 fd:FileDescriptor[80]
,08-24 17:07:55.301  3221  3292 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 17:07:55.301  3221  3292 D BluetoothAdapterProperties: mDiscovering is false
08-24 17:07:55.301  3221  3221 I BtOppRfcommListener: stopping Accept Thread
08-24 17:07:55.301  1018  1501 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-24 17:07:55.301  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2748646d, channel: 12, state: LISTENING
,08-24 17:07:55.301  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2748646d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19f973ec, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21ba28a2mSocket: android.net.LocalSocket@23f0d933 impl:android.net.LocalSocketImpl@202c34f0 fd:FileDescriptor[87]
08-24 17:07:55.301  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@23f0d933 impl:android.net.LocalSocketImpl@202c34f0 fd:FileDescriptor[87]
08-24 17:07:55.301  3221  3292 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-24 17:07:55.311  3221  5341 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 17:07:55.311  3221  5341 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 17:07:55.311  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:07:55.311  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:55.311  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:55.311  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:55.311  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:55.311  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:55.311  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 17:07:55.311  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 17:07:55.311  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:55.311  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:55.311  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 17:07:55.311  3221  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 17:07:55.311  3221  3295 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:07:55.311  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-24 17:07:55.311  3221  3292 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-24 17:07:55.321  3221  3292 E bt-btif : cmd socket is not created
08-24 17:07:55.321  6932  7214 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c1577bc, channel: -1, state: INIT
08-24 17:07:55.321  6932  7214 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c1577bc, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17077345, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3fa94a9amSocket: android.net.LocalSocket@3cebdfcb impl:android.net.LocalSocketImpl@30a053a8 fd:FileDescriptor[105]
08-24 17:07:55.321  6932  7214 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3cebdfcb impl:android.net.LocalSocketImpl@30a053a8 fd:FileDescriptor[105]
08-24 17:07:55.321  6932  7214 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1370)
,08-24 17:07:55.321  3221  3296 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-24 17:07:55.321  3221  3292 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-24 17:07:55.321  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:55.321  3221  3221 V BluetoothOppManager: cleanUp...
,08-24 17:07:55.321  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:55.331  4768  4768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:07:55.331  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 17:07:55.331  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.331  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:55.331  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.331  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:07:55.331  3221  3296 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
08-24 17:07:55.331  3221  3296 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
08-24 17:07:55.331  3221  3296 W bt-btif : invalid rfc slot id: 4
,08-24 17:07:55.331  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:55.331  4768  4768 D BluetoothPbap: Proxy object disconnected
08-24 17:07:55.331  4768  4768 D PbapServerProfile: Bluetooth service disconnected
,08-24 17:07:55.331  2650  2650 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:07:55.341  4768  4768 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:07:55.341  3221  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 17:07:55.341  3221  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 17:07:55.341  3221  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:07:55.341  3221  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 17:07:55.341  3221  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-24 17:07:55.341  3221  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-24 17:07:55.341  4768  4768 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:07:55.351  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-24 17:07:55.351  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 17:07:55.351  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:07:55.351  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-24 17:07:55.351   277  1004 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:07:55.361  2650  2704 V NativeCrypto: Read error: ssl=0xb83e80e8: I/O error during system call, Connection timed out,
,08-24 17:07:55.361  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:07:55.361  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:07:55.361  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:07:55.361  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
08-24 17:07:55.361  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-24 17:07:55.361  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:55.361  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 17:07:55.361  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.361  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.361  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.361  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:55.361  2650  2704 V NativeCrypto: SSL shutdown failed: ssl=0xb83e80e8: I/O error during system call, Broken pipe
,08-24 17:07:55.361  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.361  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.361  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.361  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.371  1018  1486 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-24 17:07:55.371  1018  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:55.371  1018  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:55.371  1018  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-24 17:07:55.371  1018  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:55.371  1018  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-24 17:07:55.371  1018  1746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-24 17:07:55.371  1018  1746 I qtaguid : Tagging socket 330 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,08-24 17:07:55.381  7223  7223 E Zygote  : MountEmulatedStorage()
08-24 17:07:55.381  7223  7223 E Zygote  : v2
08-24 17:07:55.381  7223  7223 I libpersona: KNOX_SDCARD checking this for 10055
08-24 17:07:55.381  7223  7223 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.381  7223  7223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.381  1018  1030 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7223 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-24 17:07:55.381  7223  7223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.381  7223  7223 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:55.381  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
08-24 17:07:55.381  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-24 17:07:55.381  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-24 17:07:55.391  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-24 17:07:55.391  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 17:07:55.391  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
,08-24 17:07:55.401  1018  1152 D WifiScanningService: DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:07:55.401  1018  1746 I qtaguid : Untagging socket 330
08-24 17:07:55.401  1018  1746 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 17:07:55.401  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-24 17:07:55.401  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:55.401  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:07:55.401  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
,08-24 17:07:55.411  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
08-24 17:07:55.411  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:55.411  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:55.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:55.411  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-24 17:07:55.411  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-24 17:07:55.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:55.411  1018  1126 D WifiP2pService: P2pDisablingState
08-24 17:07:55.411  1018  1127 E WifiNative-wlan0: do suspend true
08-24 17:07:55.411  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-24 17:07:55.411  1018  1126 D WifiP2pService: p2p socket connection lost
08-24 17:07:55.411  1018  1126 D WifiP2pService: P2pDisabledState
,08-24 17:07:55.421  7223  7223 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:55.421  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:07:55.421  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 17:07:55.421  7223  7223 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:55.421  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-24 17:07:55.421  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:55.421  1018  1048 D WifiDisplayController: disconnect
08-24 17:07:55.421  1018  1048 D WifiDisplayController: updateConnection
08-24 17:07:55.421  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:55.421  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 17:07:55.421  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:07:55.421  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:07:55.421  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 17:07:55.421  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:07:55.431  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-24 17:07:55.431  1018  1486 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-24 17:07:55.431  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 17:07:55.441  7223  7223 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-24 17:07:55.451  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-24 17:07:55.451  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-24 17:07:55.461   277  1000 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
08-24 17:07:55.461   277  1000 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-24 17:07:55.461  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-24 17:07:55.461   277  1004 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:07:55.461  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.461  1018  1129 V NetworkStats: updateIfacesLocked()
08-24 17:07:55.461  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:07:55.461  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:55.461  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:07:55.461  1018  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,08-24 17:07:55.461  1018  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-24 17:07:55.461  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:07:55.461  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:55.461  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 17:07:55.461  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-24 17:07:55.461  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.461  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:55.471  1018  1129 V NetworkStats: performPollLocked() took 6ms
,08-24 17:07:55.471  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:55.471  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-24 17:07:55.471  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.471  1383  1383 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:07:55.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:55.471  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-24 17:07:55.471  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:55.481  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:07:55.481  1018  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:07:55.481  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:55.481  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-24 17:07:55.481  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:07:55.481  1018  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-24 17:07:55.481  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.481  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 17:07:55.481  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.481  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.481  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.481  1176  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-24 17:07:55.481  1018  1746 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:55.481  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-24 17:07:55.481  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-24 17:07:55.481  1454  1454 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 17:07:55.481  7223  7223 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-24 17:07:55.481  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-24 17:07:55.481  7223,  7223 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-24 17:07:55.481  7223  7223 D UserAnalysis: Create SecureDbHelper
08-24 17:07:55.481  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:55.481  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:07:55.491  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:07:55.491  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:55.491  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-24 17:07:55.491  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.491  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.491  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.491  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:55.491  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.491  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:07:55.491  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-24 17:07:55.491  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-24 17:07:55.491  1176  1176 D HotspotTile: onReceive : 0, 0
08-24 17:07:55.491  4768  4768 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:55.491  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-24 17:07:55.491  7223  7223 D IntelligenceServiceApplication: onCreate()
,08-24 17:07:55.491  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-24 17:07:55.491  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-24 17:07:55.491  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:07:55.491  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:07:55.491  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-24 17:07:55.501  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-24 17:07:55.501  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,08-24 17:07:55.501  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 17:07:55.501  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-24 17:07:55.501  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:55.501  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:07:55.501  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.501  1018  1124 V NetworkStats: updateIfacesLocked()
08-24 17:07:55.501  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:55.501  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:07:55.501  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:07:55.501  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:55.501  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:07:55.501  1018  1124 V NetworkStats: performPollLocked() took 4ms
08-24 17:07:55.501  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.501  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:55.501  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-24 17:07:55.511  7223  7223 D IntelligenceServiceApplication: no applications having user consent for prediction
08-24 17:07:55.511  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.511  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-24 17:07:55.511  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.511  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.511  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:07:55.511  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-24 17:07:55.511  1018  1050 I PowerManagerService: [PWL] Off : 50s ago
08-24 17:07:55.511  1018  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-24 17:07:55.511  1018  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-24 17:07:55.511  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=3221, ws=null) (elapsedTime=671)
08-24 17:07:55.511  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=18)
08-24 17:07:55.511  1018  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'NetworkStats' (uid=1000, pid=1018, ws=null) (elapsedTime=13)
,08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-24 17:07:55.511  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-24 17:07:55.511  1018  4334 I ActivityManager: Killing 6813:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-24 17:07:55.521  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-24 17:07:55.521  7223  7223 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-24 17:07:55.521  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-24 17:07:55.521  3221  3292 D BtConfig.SecureMode: isSecureModeOn:false
08-24 17:07:55.521  3221  3292 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-24 17:07:55.521  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-24 17:07:55.521  3221  3292 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
08-24 17:07:55.521  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 17:07:55.521  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:07:55.521  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:07:55.521  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:55.521  1018  4334 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-24 17:07:55.521  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:07:55.521  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.521  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.521  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.521  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:55.521  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 17:07:55.521  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.521  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.521  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.521  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.521  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.521  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.531  7223  7223 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,08-24 17:07:55.541  7243  7243 E Zygote  : MountEmulatedStorage()
08-24 17:07:55.541  7243  7243 E Zygote  : v2
08-24 17:07:55.541  7243  7243 I libpersona: KNOX_SDCARD checking this for 10105
08-24 17:07:55.541  7243  7243 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:55.541  1018  4334 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7243 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-24 17:07:55.541  7243  7243 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:55.541  7243  7243 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:55.541  1018  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:55.541  1018  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-24 17:07:55.541  7243  7243 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 17:07:55.541  1018  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:55.541  1018  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.541  1018  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:55.551  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
08-24 17:07:55.551  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 17:07:55.551  3221  3221 D HeadsetService: Received stop request...Stopping profile...
,08-24 17:07:55.551  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 17:07:55.551  1018  1222 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:55.551  1018  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.551  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:07:55.551  1018  1222 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.551  1018  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.551  1018  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:55.561  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-24 17:07:55.561  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-24 17:07:55.561  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-24 17:07:55.561  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-24 17:07:55.561  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:55.561  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-24 17:07:55.561  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.561  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.561  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:55.561  4768  4768 D HeadsetProfile: Bluetooth service disconnected
08-24 17:07:55.561  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
08-24 17:07:55.561  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-24 17:07:55.561  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 17:07:55.561  1018  1563 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:55.561  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-24 17:07:55.561  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.561  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.561  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:55.571  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-24 17:07:55.571  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-24 17:07:55.571  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 17:07:55.571  1018  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:55.571  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.571  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.571  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.571  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:55.571  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-24 17:07:55.571  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-24 17:07:55.571  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 17:07:55.571  1018  4334 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:55.571  1018  4334 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-24 17:07:55.571  1018  4334 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.571  1018  4334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.571  1018  4334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:07:55.571  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-24 17:07:55.571  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:07:55.571  3221  3292 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 17:07:55.581  7243  7243 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:55.581  1018  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:07:55.581  7243  7243 D ActivityThread: Added TimaKeyStore provider
08-24 17:07:55.581  1018  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:07:55.581  1018  1562 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.581  1018  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.581  1018  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:07:55.581  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:07:55.581  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:07:55.581  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:07:55.581  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:07:55.581  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-24 17:07:55.581  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:07:55.581  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 17:07:55.581  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:07:55.581  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 17:07:55.581  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-24 17:07:55.581  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 17:07:55.581  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 17:07:55.581  3221  3292 D BluetoothAdapterState: Stopping profile services that were post enabled
08-24 17:07:55.581  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-24 17:07:55.581  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:07:55.581  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-24 17:07:55.581  3221  3221 D A2dpService: Received stop request...Stopping profile...
,08-24 17:07:55.591  3221  3372 D A2dpStateMachine: Exit Disconnected: -1
,08-24 17:07:55.591  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:07:55.591  1383  1383 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:07:55.591  1018  1018 D BluetoothA2dp: Proxy object disconnected
,08-24 17:07:55.591  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-24 17:07:55.591  4768  4768 D BluetoothA2dp: Proxy object disconnected
08-24 17:07:55.591  4768  4768 D A2dpProfile: Bluetooth service disconnected
,08-24 17:07:55.591  3221  3221 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 17:07:55.591  3221  3221 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 17:07:55.601  3221  3221 D HidService: Received stop request...Stopping profile...
08-24 17:07:55.601  3221  3221 D HidService: Stopping Bluetooth HidService
08-24 17:07:55.601  3221  3221 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-24 17:07:55.601  3221  3221 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-24 17:07:55.601  3221  3221 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 17:07:55.601  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:07:55.601  3221  3221 D HealthService: Received stop request...Stopping profile...,
08-24 17:07:55.601  4768  4768 D BluetoothInputDevice: Proxy object disconnected
08-24 17:07:55.601  4768  4768 D HidProfile: Bluetooth service disconnected,
08-24 17:07:55.601  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:07:55.601  3221  3221 D PanService: Received stop request...Stopping profile...
08-24 17:07:55.601  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:07:55.601  4768  4768 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 17:07:55.601  4768  4768 D PanProfile: Bluetooth service disconnected
,08-24 17:07:55.601  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 17:07:55.601  3221  3221 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 17:07:55.611  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
08-24 17:07:55.611  4768  4768 D BluetoothMap: Proxy object disconnected
08-24 17:07:55.611  4768  4768 D MapProfile: Bluetooth service disconnected
,08-24 17:07:55.611  3221  3221 D SapService: Received stop request...Stopping profile...
08-24 17:07:55.611  3221  3221 D SapService: Stopping Bluetooth SapService
08-24 17:07:55.611  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:07:55.621  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-24 17:07:55.621  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-24 17:07:55.621  3221  3221 D BluetoothA2dp: Proxy object disconnected
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-24 17:07:55.621  3221  3378 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-24 17:07:55.621  3221  3221 I GKI_LINUX: GKI_exit_task 2 done
08-24 17:07:55.621  3221  3221 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 17:07:55.621  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:07:55.621  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:55.621  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:07:55.621  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:55.621  3221  3221 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 17:07:55.621  3221  3221 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 17:07:55.621  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:07:55.621  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:07:55.621  3221  3221 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 17:07:55.621  3221  3221 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-24 17:07:55.621  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:07:55.621  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-24 17:07:55.621  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-24 17:07:55.621  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,08-24 17:07:55.621  3221  3221 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-24 17:07:55.621  3221  3221 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-24 17:07:55.621  4768  4768 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-24 17:07:55.621  4768  4768 D SapProfile: Bluetooth service disconnected
,08-24 17:07:55.621  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-24 17:07:55.621  3221  3292 D BluetoothAdapterProperties: Setting state to 10
08-24 17:07:55.621  3221  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 17:07:55.621  3221  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:07:55.621  3221  3292 D BluetoothAdapterService: updateAdapterState state is 10
08-24 17:07:55.621  3221  3292 D BluetoothAdapterService: Autoconnection is available 
08-24 17:07:55.621  3221  3292 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-24 17:07:55.621  3221  3292 I BluetoothAdapterState: Entering OffState
08-24 17:07:55.621  3221  5337 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:07:55.631  1440  1484 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:55.631  1440  1484 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.631  4768  4777 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 17:07:55.631  4768  4776 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:55.631  4768  4776 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.631  3221  3230 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:55.631  3221  3230 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.631  1176  5261 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:07:55.631  1176  5261 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.631  6932  6940 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:07:55.641  6932  6940 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.641  6932  6940 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-24 17:07:55.641  6932  6940 D BluetoothLeAdvertiser: Exit stop advertising
08-24 17:07:55.641  6932  6940 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-24 17:07:55.641  6932  6940 D BluetoothLeScanner: Exiting stopAllScan
,08-24 17:07:55.641  4768  4776 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 17:07:55.651  4768  4777 D Bluetoothsap: onBluetoothStateChange: up=false
08-24 17:07:55.651  4768  4777 D Bluetoothsap: Unbinding service...
,08-24 17:07:55.651  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:07:55.651  4768  4776 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 17:07:55.651  2650  4336 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:55.651  2650  4336 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.651  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:07:55.661  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.661  1454  1474 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:07:55.661  1454  1474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.661  1425  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:55.661  1425  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.661  1771  1784 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:07:55.661  1771  1784 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:07:55.661  4768  4776 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:07:55.661  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.661  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.671  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:55.671  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
08-24 17:07:55.671  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-24 17:07:55.671  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.671  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.671  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.671  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.671  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.671  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:55.671  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-24 17:07:55.671  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:07:55.671  1176  1176 D BluetoothTile:  getBluetoothState : 10
,08-24 17:07:55.671  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.681  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.681  1869  1869 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:07:55.681  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.681  4768  4768 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:07:55.681  1383  1383 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-24 17:07:55.681  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:07:55.681  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-24 17:07:55.681  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:07:55.681  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.681  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.681  1018  4334 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-24 17:07:55.681  1018  1486 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:07:55.691  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:07:55.691  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:07:55.691  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.691  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:55.691  6932  6932 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-24 17:07:55.691  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:55.691  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.691  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:55.691  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.691  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:55.691  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.691  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:55.691  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.701  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.701  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.701  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-24 17:07:55.701  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.701  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.701  1454  1454 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-24 17:07:55.701  1018  3386 D SSRM:n  : SIOP:: AP = 390
08-24 17:07:55.701  1454  1454 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-24 17:07:55.711  1383  1383 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-24 17:07:55.711  1383  1383 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-24 17:07:55.711  1383  1383 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-24 17:07:55.711  1383  1383 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-24 17:07:55.711  1383  1383 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:07:55.711  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:55.711  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:07:55.711  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:07:55.711  1018  1132 D Tethering: InitialState.processMessage what=4
,08-24 17:07:55.711  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:55.711  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:07:55.711  1018  1132 E Tethering: No numeric data
08-24 17:07:55.711  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:07:55.711  1018  1132 D Tethering: clearTetheredNotification()
08-24 17:07:55.711  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:55.711  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.711  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-24 17:07:55.711  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:55.711  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:07:55.711  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:55.711  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:07:55.711  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:55.711  1176  1176 D HotspotTile: updateTetherState():false, false
08-24 17:07:55.711  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:07:55.711  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:07:55.721  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:55.721  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:07:55.721  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-24 17:07:55.721  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:55.721  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:55.721  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:55.731   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 17:07:55.731   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:55.731  7243  7279 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 17:07:55.741   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 17:07:55.741   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:55.741  7243  7279 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 17:07:55.831  1383  1383 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:07:55.881  7243  7243 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:55.881  7243  7243 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:55.881  7243  7243 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:55.881  7243  7243 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:55.881  7243  7243 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.k.d(PG:583)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:55.881  7243  7243 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:55.881  7243  7243 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:55.881  7243  7243 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:07:55.881  7243  7243 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:07:55.881  1018  1486 I ActivityManager: Killing 6825:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-24 17:07:55.881  1018  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:07:55.881  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 17:07:55.891  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.891  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:55.891  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:07:55.891  1636  1636 I Hs20UtilService: Starting #8
08-24 17:07:55.891  1636  1665 I Hs20UtilService: Message received 5007
08-24 17:07:55.891  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 17:07:55.891  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 17:07:55.901  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 17:07:55.901  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:07:55.901  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:55.901  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:07:55.901  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-24 17:07:55.901  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:55.901  1018  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:55.901  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-24 17:07:55.901  1018  1507 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-24 17:07:55.901  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.901  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.901  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:55.901  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:55.921  7289  7289 E Zygote  : MountEmulatedStorage()
08-24 17:07:55.921  7289  7289 I libpersona: KNOX_SDCARD checking this for 10102
08-24 17:07:55.921  7289  7289 E Zygote  : v2
08-24 17:07:55.921  7289  7289 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:55.921  7289  7289 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:55.921  1018  1507 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7289 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-24 17:07:55.921  7289  7289 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:55.921  7289  7289 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-24 17:07:55.931  7289  7289 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:55.941  7289  7289 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:55.951  7289  7289 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-24 17:07:55.961  7243  7276 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-24 17:07:55.971  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 17:07:55.971  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:55.971  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:55.971  1383  1383 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-24 17:07:55.991  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:55.991  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:55.991  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:07:55.991  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-24 17:07:56.001  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:56.001  1018  1018 I ApplicationPolicy: updateDataUsageMap
,08-24 17:07:56.011  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:56.021  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:56.081  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-24 17:07:56.081  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 17:07:56.091  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:07:56.091  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:56.091  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:07:56.091  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:56.091  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:56.091  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:56.091  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:56.091  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:56.091  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:56.091  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-24 17:07:56.091  1176  1176 D HotspotTile: onReceive : 1, 0
,08-24 17:07:56.091  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-24 17:07:56.091  4768  4768 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:56.091  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:56.091  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:56.091  1771  2207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:07:56.101  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:56.181  7289  7311 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-24 17:07:56.181  7289  7311 I Babel_SMS: MmsConfig.loadMmsSettings
,08-24 17:07:56.181  7289  7311 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-24 17:07:56.181  7289  7311 I Babel_SMS: MmsConfig.loadFromDatabase
,08-24 17:07:56.201  7289  7311 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-24 17:07:56.201  7289  7311 I Babel_SMS: MmsConfig.loadFromResources
,08-24 17:07:56.201  7289  7311 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-24 17:07:56.201  7289  7311 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-24 17:07:56.231  1018  1222 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-24 17:07:56.231  1018  1222 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-24 17:07:56.231  1018  1222 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:56.231  1018  1222 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:56.231  1018  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-24 17:07:56.251  7289  7289 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-24 17:07:56.251  7289  7289 I Babel_Crash: startup - clean,
,08-24 17:07:56.281  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 17:07:56.291  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:07:56.291  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:07:56.291  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 17:07:56.291  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:56.291  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:07:56.291  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:56.291  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-24 17:07:56.291  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.291  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.291  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.291  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.301  7314  7314 E Zygote  : MountEmulatedStorage(),
08-24 17:07:56.301  7314  7314 E Zygote  : v2
,08-24 17:07:56.311  7314  7314 I libpersona: KNOX_SDCARD checking this for 10064
08-24 17:07:56.311  7314  7314 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:56.311  7314  7314 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:56.311  7314  7314 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:07:56.311  1018  1494 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7314 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:56.311  7314  7314 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:56.321  7289  7289 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:56.321  7289  7289 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 17:07:56.321  7289  7289 W AudioCapabilities: Unsupported mime audio/qcelp
,08-24 17:07:56.331  7289  7289 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-24 17:07:56.331  7289  7289 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-24 17:07:56.331  7289  7289 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-24 17:07:56.331  7289  7289 W AudioCapabilities: Unsupported mime audio/x-ima
,08-24 17:07:56.331  7289  7289 W AudioCapabilities: Unsupported mime audio/qcelp
,08-24 17:07:56.341  7314  7314 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:56.341  7289  7289 W AudioCapabilities: Unsupported mime audio/evrc
,08-24 17:07:56.341  7314  7314 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:56.351  7289  7289 W VideoCapabilities: Unsupported mime video/wvc1
,08-24 17:07:56.351  7289  7289 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-24 17:07:56.351  7314  7314 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-24 17:07:56.361  7289  7289 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-24 17:07:56.361  7289  7289 W VideoCapabilities: Unsupported mime video/wvc1
,08-24 17:07:56.361  7289  7289 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-24 17:07:56.361  7289  7289 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-24 17:07:56.371  7289  7289 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-24 17:07:56.371  7289  7289 W VideoCapabilities: Unsupported mime video/mp43
,08-24 17:07:56.371  7289  7289 W VideoCapabilities: Unsupported mime video/sorenson
,08-24 17:07:56.381  7314  7314 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:07:56.381  7314  7314 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-24 17:07:56.381  7289  7289 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-24 17:07:56.391   291   291 E SMD     : DCD OFF
,08-24 17:07:56.401  7289  7289 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 17:07:56.411  7314  7314 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 17:07:56.411  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-24 17:07:56.421  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.421  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.421  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.421  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.421  7289  7289 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-24 17:07:56.421  7289  7289 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:56.431  7289  7289 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:56.431  7329  7329 E Zygote  : MountEmulatedStorage()
08-24 17:07:56.431  7329  7329 E Zygote  : v2
08-24 17:07:56.431  7329  7329 I libpersona: KNOX_SDCARD checking this for 10065
08-24 17:07:56.431  7329  7329 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:56.431  7329  7329 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:56.431  7329  7329 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:56.431  1018  1494 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7329 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:56.431  1018  1494 I ActivityManager: Killing 6866:com.wsomacp/u0a23 (adj 15): empty #21
,08-24 17:07:56.431  7329  7329 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:56.441  7289  7289 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 17:07:56.441  1018  4334 I ActivityManager: Killing 6889:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-24 17:07:56.451  7289  7289 I vclib   : onServiceConnected
,08-24 17:07:56.461  7329  7329 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:56.461  7329  7329 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:56.481  7329  7329 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:07:56.491  1018  4334 I ActivityManager: Killing 6907:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-24 17:07:56.491  1018  1327 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:07:56.491  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:56.491  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.491  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.491  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:56.501  1636  1636 I Hs20UtilService: Starting #9
,08-24 17:07:56.501  1636  1665 I Hs20UtilService: Message received 5007
,08-24 17:07:56.501  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-24 17:07:56.501  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:07:56.501  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:07:56.501  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 17:07:56.501  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:56.501  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:07:56.501  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:56.511  1018  4333 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:07:56.511  1018  4333 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:56.511  1018  4333 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:56.511  1018  4333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.511  1018  4333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:56.511  1636  1636 I Hs20UtilService: Starting #10
08-24 17:07:56.511  1636  1665 I Hs20UtilService: Message received 5011
,08-24 17:07:56.511  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 17:07:56.521  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:56.521  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
,08-24 17:07:56.521  7088  7088 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:07:56.531  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.531  1018  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:07:56.531  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.531  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.531  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.531  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.531  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.531  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:07:56.531  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.541  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.541  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:07:56.541  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.551  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.551  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:07:56.551  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.551  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.551  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.551  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.551  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.561  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.561  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.561  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.561  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.561  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.561  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:56.561  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.561  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.561  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:56.561  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.561  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.571  1018  1018 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:07:56.571  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.571  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.571  1018  1018 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:07:56.571  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.571  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.571  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:56.571  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.571  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.571  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:56.571  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.571  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.581  1018  1045 D Tethering: interfaceRemoved wlan0
08-24 17:07:56.581  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:56.581  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
08-24 17:07:56.581  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.581  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-24 17:07:56.581  4768  4768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:07:56.591  1018  1501 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-24 17:07:56.591  1018  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:07:56.591  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:56.591  1018  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:56.591  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:07:56.591  2650  2650 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:07:56.601  4768  4768 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:07:56.601  4768  4768 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:07:56.601  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:07:56.601  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-24 17:07:56.621  1018  1562 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-24 17:07:56.621  1018  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.621  1018  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.621  1018  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.621  1018  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.631  7347  7347 E Zygote  : MountEmulatedStorage(),
08-24 17:07:56.631  7347  7347 I libpersona: KNOX_SDCARD checking this for 1000
08-24 17:07:56.631  7347  7347 E Zygote  : v2
08-24 17:07:56.631  7347  7347 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:56.631  7347  7347 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:56.631  7347  7347 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:56.631  1018  1562 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7347 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-24 17:07:56.641  7347  7347 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:56.661  7347  7347 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:56.661  7347  7347 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:56.681  7347  7347 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-24 17:07:56.681  7347  7347 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 17:07:56.681  7347  7347 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-24 17:07:56.691  7347  7347 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-24 17:07:56.691  7347  7347 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-24 17:07:56.701  7347  7347 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 17:07:56.701  7347  7347 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:56.701  1018  1486 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-24 17:07:56.701  1018  1486 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-24 17:07:56.701  1018  1486 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-24 17:07:56.701  1018  1486 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-24 17:07:56.701  7347  7362 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-24 17:07:56.701  1018  1486 I ActivityManager: Killing 6950:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-24 17:07:56.701  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-24 17:07:56.711  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.711  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.711  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.711  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.721  7364  7364 E Zygote  : MountEmulatedStorage(),
08-24 17:07:56.721  7364  7364 E Zygote  : v2
08-24 17:07:56.721  7364  7364 I libpersona: KNOX_SDCARD checking this for 10001
08-24 17:07:56.721  7364  7364 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:56.721  7364  7364 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:56.721  7364  7364 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:07:56.721  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7364 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:56.721  7364  7364 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:56.731  7364  7364 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:56.731  7364  7364 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:56.781  1018  1045 D Tethering: interfaceRemoved p2p0
08-24 17:07:56.781  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-24 17:07:56.801  1018  4327 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-24 17:07:56.801  1018  4327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.801  1018  4327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.801  1018  4327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:56.801  1018  4327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:56.811  7381  7381 E Zygote  : MountEmulatedStorage(),
08-24 17:07:56.811  7381  7381 E Zygote  : v2
08-24 17:07:56.811  7381  7381 I libpersona: KNOX_SDCARD checking this for 1000
08-24 17:07:56.811  7381  7381 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:56.821  1018  4327 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7381 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 17:07:56.821  7381  7381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:56.821  1018  4327 I ActivityManager: Killing 6596:com.android.mms/u0a41 (adj 15): empty #21
,08-24 17:07:56.821  7381  7381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:56.821  7381  7381 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:56.841  7381  7381 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:56.841  7381  7381 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:56.871  7381  7381 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-24 17:07:56.921  1018  1494 D CountryDetector: No listener is left
,08-24 17:07:56.991  7381  7381 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-24 17:07:57.001  7381  7381 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-24 17:07:57.001  7381  7381 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:57.001  7381  7381 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-24 17:07:57.001  7381  7381 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-24 17:07:57.011  7381  7381 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-24 17:07:57.011  1018  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-24 17:07:57.011  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.011  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.011  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.011  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.021  7397  7397 E Zygote  : MountEmulatedStorage()
08-24 17:07:57.021  7397  7397 E Zygote  : v2
08-24 17:07:57.021  7397  7397 I libpersona: KNOX_SDCARD checking this for 10008
08-24 17:07:57.021  7397  7397 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:57.021  7397  7397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:57.021  7397  7397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:07:57.021  1018  1488 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7397 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:57.021  1018  1488 I ActivityManager: Killing 6970:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-24 17:07:57.031  7397  7397 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 17:07:57.041  7397  7397 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:57.041  7397  7397 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:57.051   311   311 I art     : Explicit concurrent mark sweep GC freed 8706(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 26.326ms,
,08-24 17:07:57.061   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 16.322ms
,08-24 17:07:57.081   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.557ms
,08-24 17:07:57.111  1018  1507 I ActivityManager: Killing 6399:com.samsung.android.sm/1000 (adj 15): empty #21
,08-24 17:07:57.121  1018  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-24 17:07:57.121  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-24 17:07:57.121  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:57.121  1018  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:57.121  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:57.131  3824  7412 I iu.SyncManager: SYNC; picasa accounts
,08-24 17:07:57.141  3824  3824 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-24 17:07:57.151  1018  1222 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-24 17:07:57.151  1018  1222 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,08-24 17:07:57.151  1018  1222 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:57.151  1018  1222 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:57.151  1018  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-24 17:07:57.161  3824  3824 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 17:07:57.161  3824  3824 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000,
,08-24 17:07:57.171  2845  2845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 24 17:07:57 GMT+02:00 2016
,08-24 17:07:57.171  1018  1137 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-24 17:07:57.171  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-24 17:07:57.171  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:57.171  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:57.171  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-24 17:07:57.171  2845  2845 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-24 17:07:57.181  2845  2845 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-24 17:07:57.181  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-24 17:07:57.181  2845  2845 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-24 17:07:57.181  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.181  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.181  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.181  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.181  2845  2845 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-24 17:07:57.181  2845  7414 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-24 17:07:57.181  2845  7414 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-24 17:07:57.191  2845  7414 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-24 17:07:57.191  7415  7415 E Zygote  : MountEmulatedStorage()
,08-24 17:07:57.191  7415  7415 E Zygote  : v2
08-24 17:07:57.191  7415  7415 I libpersona: KNOX_SDCARD checking this for 10031,
08-24 17:07:57.191  7415  7415 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:57.191  7415  7415 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:57.191  7415  7415 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:07:57.191  1018  1030 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7415 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-24 17:07:57.201  2845  7414 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-24 17:07:57.201  7415  7415 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-24 17:07:57.201  2845  2845 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-24 17:07:57.211  7415  7415 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:57.211  7415  7415 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:57.241  7415  7415 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-24 17:07:57.241  1018  1486 I ActivityManager: Killing 6988:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-24 17:07:57.271  1018  4334 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-24 17:07:57.271  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.271  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.271  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.271  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.291  2783  7430 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false,
08-24 17:07:57.291  7431  7431 E Zygote  : MountEmulatedStorage(),
08-24 17:07:57.291  7431  7431 E Zygote  : v2
08-24 17:07:57.291  7431  7431 I libpersona: KNOX_SDCARD checking this for 10032,
08-24 17:07:57.291  7431  7431 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:57.291  7431  7431 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:57.301  1018  4334 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7431 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:57.301  7431  7431 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:57.301  2783  7430 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-24 17:07:57.301  2783  7430 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-24 17:07:57.301  7431  7431 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-24 17:07:57.301  2783  7430 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-24 17:07:57.311  2783  7430 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-24 17:07:57.341  7431  7431 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:57.341  7431  7431 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:57.341  1018  1096 V AlarmManager: waitForAlarm result :4
,08-24 17:07:57.411  7431  7446 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-24 17:07:57.411  7431  7446 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-24 17:07:57.411  7431  7431 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-24 17:07:57.421  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-24 17:07:57.421  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.421  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.421  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.421  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.421  7431  7446 D SPPClientService: PushLog.txt file is not deleted.
08-24 17:07:57.421  7431  7446 D SPPClientService: PushLog.txt file is not deleted.
08-24 17:07:57.421  7431  7446 D SPPClientService: ============PushLog. stop!
,08-24 17:07:57.441  7448  7448 E Zygote  : MountEmulatedStorage(),
08-24 17:07:57.441  7448  7448 E Zygote  : v2
08-24 17:07:57.441  7448  7448 I libpersona: KNOX_SDCARD checking this for 10036
,08-24 17:07:57.441  1018  1030 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7448 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:57.441  1018  1030 I ActivityManager: Killing 7024:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-24 17:07:57.441  1018  1327 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-24 17:07:57.441  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-24 17:07:57.441  7448  7448 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:57.441  7448  7448 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:57.441   322   322 I ServiceManager: Waiting for service AtCmdFwd...
08-24 17:07:57.441  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:57.441  1018  1327 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-24 17:07:57.441  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-24 17:07:57.451  7448  7448 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:57.451  7448  7448 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-24 17:07:57.471  7448  7448 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:57.471  7448  7448 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:57.481  7431  7454 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-24 17:07:57.531  7448  7448 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3485f032
,08-24 17:07:57.551  7448  7448 I SA      : [SSP] onCreated
,08-24 17:07:57.561  7448  7448 I SA      : [TPM] There is no property file
,08-24 17:07:57.561  7448  7448 I SA      : [SCU] isHaveSA() - false
,08-24 17:07:57.561  7448  7448 I SA      : [TPM] getModelProperty : null
,08-24 17:07:57.561  7448  7448 I SA      : [TPM] getCSCProperty : null
,08-24 17:07:57.561  7448  7448 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-24 17:07:57.571  7448  7448 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-24 17:07:57.571  7448  7448 I SA      : [DM] TFT FEATURE: false
,08-24 17:07:57.571  7448  7448 I SA      : [DM] init START
,08-24 17:07:57.571  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-24 17:07:57.571  7448  7448 I SA      : [DM] This device is not a Vodafone
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-24 17:07:57.581  7448  7448 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-24 17:07:57.581  7448  7448 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-24 17:07:57.591  7448  7448 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,08-24 17:07:57.601  7448  7448 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-24 17:07:57.601  7448  7448 I SA      : [SCU] isHaveSA() - false
08-24 17:07:57.601  7448  7448 I SA      : support phone number id : false
08-24 17:07:57.601  7448  7448 I SA      : [DM] Supports Ref Jpn : true
,08-24 17:07:57.601  7448  7448 I SA      : [DM] init END
08-24 17:07:57.601  7448  7448 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-24 17:07:57.601  7448  7448 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-24 17:07:57.601  7448  7448 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-24 17:07:57.611  7448  7448 I SA      : [SLFUCHKMGR] constructor called,
,08-24 17:07:57.611  7448  7448 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-24 17:07:57.611  7448  7448 I SA      : [OR] == isSIMCardReady false ==
,08-24 17:07:57.621  7448  7448 I SA      : [SCU] == networkStateCheck == false
,08-24 17:07:57.621  7448  7448 I SA      : [OR] onReceive END
,08-24 17:07:57.621  1018  1487 I ActivityManager: Killing 7123:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-24 17:07:57.621  1233  1233 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:57.631  1793  1793 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-24 17:07:57.641  2632  2697 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-24 17:07:57.641  1793  1793 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-24 17:07:57.641  1793  1793 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1,
08-24 17:07:57.641  1793  1793 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-24 17:07:57.641  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-24 17:07:57.641  1793  1793 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-24 17:07:57.641  1793  1793 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-24 17:07:57.641  1018  1494 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-24 17:07:57.651  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.651  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.651  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.651  1018  1494 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.661  7470  7470 E Zygote  : MountEmulatedStorage()
,08-24 17:07:57.661  7470  7470 E Zygote  : v2
08-24 17:07:57.661  7470  7470 I libpersona: KNOX_SDCARD checking this for 10077
,08-24 17:07:57.661  7470  7470 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:57.661  1018  1494 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7470 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:57.661  7470  7470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:07:57.671  7470  7470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 17:07:57.671  7470  7470 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-24 17:07:57.681  7470  7470 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:57.681  7470  7470 D ActivityThread: Added TimaKeyStore provider,
,08-24 17:07:57.851  1018  1137 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-24 17:07:57.851  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-24 17:07:57.851  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:57.851  1018  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:57.851  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-24 17:07:57.851  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-24 17:07:57.861  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.861  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.861  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:57.861  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:57.871  7488  7488 E Zygote  : MountEmulatedStorage(),
08-24 17:07:57.871  1018  1030 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7488 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:07:57.871  7488  7488 E Zygote  : v2
08-24 17:07:57.871  7488  7488 I libpersona: KNOX_SDCARD checking this for 10110
08-24 17:07:57.871  7488  7488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:57.871  7488  7488 I libpersona: KNOX_SDCARD not a persona,
08-24 17:07:57.871  1018  1327 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-24 17:07:57.871  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-24 17:07:57.871  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:57.871  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:57.871  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-24 17:07:57.871  7488  7488 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:07:57.871  7488  7488 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:07:57.881  7289  7487 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-24 17:07:57.881  1018  4334 I ActivityManager: Killing 7140:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-24 17:07:57.901  7488  7488 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:57.901  7488  7488 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:58.011  1018  1563 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 17:07:58.141   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-24 17:07:58.141   256   525 W Vold    : Returning OperationFailed - no handler for errno 0,
08-24 17:07:58.141  7488  7506 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-24 17:07:58.141   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
,08-24 17:07:58.141   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-24 17:07:58.141  7488  7506 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-24 17:07:58.151  7488  7488 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 17:07:58.151  7488  7488 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 17:07:58.151  7488  7488 I GAv4    :   adb logcat -s GAv4
,08-24 17:07:58.161   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-24 17:07:58.161   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:58.161  7488  7507 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-24 17:07:58.161   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-24 17:07:58.161   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:07:58.161  7488  7507 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-24 17:07:58.181  7488  7488 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:07:58.181  1018  1030 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 17:07:58.191  7488  7488 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:07:58.201  7488  7509 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 17:07:58.281  1018  1222 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 17:07:58.281  1018  1222 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-24 17:07:58.281  1018  1222 D SecContentProvider2: mCursor = null
,08-24 17:07:58.281  1018  1222 D WifiService: setWifiEnabled: true pid=6932, uid=10170
,08-24 17:07:58.281  1018  1222 W ActivityManager: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 17:07:58.281  1018  1222 W WifiService: Failed getting userId using ActivityManagerNative
08-24 17:07:58.281  1018  1222 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:07:58.281  1018  1222 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:07:58.281  1018  1222 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 17:07:58.281  1018  1222 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 17:07:58.281  1018  1222 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 17:07:58.281  1018  1222 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 17:07:58.281  1018  1222 D SettingsProvider: name = wifi_on
,08-24 17:07:58.291  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-24 17:07:58.441   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:07:58.461  1018  1222 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:07:58.471  1018  1222 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:58.471  1018  1222 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:58.471  1018  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-24 17:07:58.501  7488  7488 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-24 17:07:58.521  7488  7488 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5056-5058)
,08-24 17:07:58.531  7488  7488 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-24 17:07:58.531  7488  7488 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {251073b5}
,08-24 17:07:58.531  7488  7488 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-24 17:07:58.531  7488  7488 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 17:07:58.551  7488  7488 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-24 17:07:58.561  7488  7488 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 17:07:58.561  7488  7488 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 17:07:58.581  7488  7488 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-24 17:07:58.581  7488  7488 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-24 17:07:58.581  7488  7488 I Adreno-EGL: Build Date: 04/06/15 Mon
08-24 17:07:58.581  7488  7488 I Adreno-EGL: Local Branch: 
08-24 17:07:58.581  7488  7488 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-24 17:07:58.581  7488  7488 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-24 17:07:58.581  7488  7488 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-24 17:07:58.641  7488  7488 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 17:07:58.641  7488  7544 W cr.media: Requires BLUETOOTH permission
,08-24 17:07:58.651  7488  7488 I NSApplication: Starting up...
,08-24 17:07:58.651  1018  1494 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 17:07:58.651  1018  4333 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-24 17:07:58.661  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-24 17:07:58.661  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:58.661  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:58.661  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:58.661  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:58.671  7549  7549 E Zygote  : MountEmulatedStorage()
,08-24 17:07:58.671  7549  7549 E Zygote  : v2
08-24 17:07:58.671  7549  7549 I libpersona: KNOX_SDCARD checking this for 10117
08-24 17:07:58.671  7549  7549 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:58.671  7549  7549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 17:07:58.671  1018  1030 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7549 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:58.681  1018  1030 I ActivityManager: Killing 7097:com.android.providers.calendar/u0a37 (adj 15): empty #21,
,08-24 17:07:58.681  7549  7549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:07:58.681  7549  7549 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-24 17:07:58.681  1018  1045 D Tethering: interfaceAdded wlan0
,08-24 17:07:58.691  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:58.691  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:07:58.691  1018  1132 E Tethering: No numeric data
,08-24 17:07:58.691  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 17:07:58.691  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:07:58.691  1018  1132 D Tethering: clearTetheredNotification()
08-24 17:07:58.691  1018  1132 D Tethering: InitialState.processMessage what=4
08-24 17:07:58.691  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.691  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-24 17:07:58.691  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:58.701  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:07:58.691  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:07:58.701  1176  1176 D HotspotTile: updateTetherState():false, false,
08-24 17:07:58.701  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.701  1018  1124 V NetworkStats: performPollLocked() took 4ms
,08-24 17:07:58.701  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:58.701  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:58.701  1018  1045 D Tethering: interfaceAdded p2p0,
,08-24 17:07:58.711   277  1004 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-24 17:07:58.711   277  1004 D SoftapController: Softap fwReload - Ok
08-24 17:07:58.711  1018  1132 E Tethering: No numeric data
,08-24 17:07:58.711  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:07:58.711  1018  1132 D Tethering: clearTetheredNotification()
08-24 17:07:58.711  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-24 17:07:58.711  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:07:58.711  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-24 17:07:58.711  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:07:58.711  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.711  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:07:58.711  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:07:58.711  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:07:58.711  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:07:58.711  1176  1176 D HotspotTile: updateTetherState():false, false
,08-24 17:07:58.711  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.711  1018  1124 V NetworkStats: performPollLocked() took 6ms
,08-24 17:07:58.721  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:07:58.721  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:07:58.721   277  1004 D CommandListener: Setting iface cfg
08-24 17:07:58.721   277  1004 D CommandListener: Trying to bring down wlan0
,08-24 17:07:58.721   277  1004 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:07:58.721  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-24 17:07:58.731  7549  7549 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-24 17:07:58.731  7549  7549 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:58.751  7549  7549 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 17:07:58.781  7562  7562 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-24 17:07:58.781  7562  7562 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 17:07:58.781  7562  7562 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-24 17:07:58.811  7562  7562 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-24 17:07:58.811   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7562
,08-24 17:07:58.811   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-24 17:07:58.811  7562  7562 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-24 17:07:58.811  7562  7562 I wpa_supplicant: ssSupport state is = 1
08-24 17:07:58.811  7562  7562 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-24 17:07:58.811  7562  7562 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-24 17:07:58.811   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7562
08-24 17:07:58.811   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-24 17:07:58.821  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-24 17:07:58.841  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:07:58.841  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:07:58.841  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:07:58.841  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.841  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.841  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.841  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:58.841  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:58.841  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:07:58.841  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:58.841  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-24 17:07:58.841  1176  1176 D HotspotTile: onReceive : 2, 0
,08-24 17:07:58.841  4768  4768 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:58.851  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:58.851  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:07:58.991   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-24 17:07:58.991  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,08-24 17:07:59.051  7562  7562 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-24 17:07:59.051  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 17:07:59.061  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-24 17:07:59.061   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7562
08-24 17:07:59.061   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 17:07:59.061  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-24 17:07:59.061  7562  7562 I wpa_supplicant: ssSupport state is = 1
,08-24 17:07:59.101  7562  7562 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-24 17:07:59.101  7562  7562 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-24 17:07:59.101  7562  7562 E wpa_supplicant: SIM READ ERROR
08-24 17:07:59.101  7562  7562 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:07:59.101  7562  7562 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:07:59.101  7562  7562 E wpa_supplicant: SIM READ ERROR,
08-24 17:07:59.101  7562  7562 I wpa_supplicant: Blacklist: Clear (all) 
08-24 17:07:59.101  7562  7562 I wpa_supplicant: wpa_default_ap_write_once
08-24 17:07:59.101  7562  7562 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 17:07:59.101  7562  7562 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-24 17:07:59.101  7562  7562 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-24 17:07:59.101  7562  7562 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:07:59.101  7562  7562 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:07:59.101  7562  7562 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 17:07:59.101  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:07:59.101  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:07:59.101  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:07:59.141  1018  1507 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-24 17:07:59.141  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.141  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.141  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.141  1018  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:59.151  7574  7574 E Zygote  : MountEmulatedStorage()
,08-24 17:07:59.151  7574  7574 E Zygote  : v2
,08-24 17:07:59.151  7574  7574 I libpersona: KNOX_SDCARD checking this for 10121
08-24 17:07:59.151  7574  7574 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:59.161  1018  1507 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7574 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-24 17:07:59.161  1018  1507 I ActivityManager: Killing 7045:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-24 17:07:59.161  7574  7574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 17:07:59.161  7574  7574 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:59.161  7574  7574 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:59.191  7562  7562 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-24 17:07:59.191  7574  7574 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:59.191  7574  7574 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:59.201  7574  7574 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 17:07:59.201  7574  7574 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-24 17:07:59.201  7574  7574 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 17:07:59.221  7574  7574 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:07:59.231  7574  7574 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-24 17:07:59.231  7574  7574 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-24 17:07:59.231  1018  1501 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
,08-24 17:07:59.231  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 17:07:59.231  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.231  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 17:07:59.231  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:59.251  7591  7591 E Zygote  : MountEmulatedStorage()
,08-24 17:07:59.251  7591  7591 E Zygote  : v2
08-24 17:07:59.251  7591  7591 I libpersona: KNOX_SDCARD checking this for 10141
08-24 17:07:59.251  7591  7591 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:59.251  1018  1501 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7591 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-24 17:07:59.251  7591  7591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:59.251  1018  1501 I ActivityManager: Killing 7065:com.android.calendar/u0a131 (adj 15): empty #21
,08-24 17:07:59.251  7591  7591 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-24 17:07:59.251  7591  7591 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:59.271  7591  7591 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:59.271  7591  7591 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:59.291  7591  7591 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-24 17:07:59.291  7591  7591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 17:07:59.291  7591  7591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 17:07:59.291  7591  7591 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-24 17:07:59.351  1018  1488 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:59.371  1018  1563 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:59.391   291   291 E SMD     : DCD OFF,
,08-24 17:07:59.401  7562  7562 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:07:59.411  1018  1222 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:59.411  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 17:07:59.421  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-24 17:07:59.421   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7562
08-24 17:07:59.421   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 17:07:59.421  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-24 17:07:59.421  7562  7562 I wpa_supplicant: ssSupport state is = 1
,08-24 17:07:59.421  7562  7562 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-24 17:07:59.421  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-24 17:07:59.431  1018  4334 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:59.431  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-24 17:07:59.441   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7562
08-24 17:07:59.441   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 17:07:59.441  7562  7562 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-24 17:07:59.441  7562  7562 I wpa_supplicant: ssSupport state is = 1
08-24 17:07:59.441  7562  7562 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:07:59.441  7562  7562 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:07:59.441  7562  7562 E wpa_supplicant: SIM READ ERROR
08-24 17:07:59.441  7562  7562 I wpa_supplicant: wpa_default_ap_write_once
08-24 17:07:59.441  7562  7562 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-24 17:07:59.441  7562  7562 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 17:07:59.441  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-24 17:07:59.441  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 17:07:59.441  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-24 17:07:59.441  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:07:59.441  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:07:59.441  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:07:59.441   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:07:59.451  1018  1507 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 17:07:59.451  1018  1507 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-24 17:07:59.451  1018  1507 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-24 17:07:59.451  1018  1507 D BatteryService: stay LED for charging
,08-24 17:07:59.451  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 17:07:59.461  1018  1018 I MotionRecognitionService: Plugged
08-24 17:07:59.461  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-24 17:07:59.461  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 17:07:59.461  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-24 17:07:59.461  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 17:07:59.461  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 17:07:59.481  1018  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-24 17:07:59.481  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.481  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.481  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.481  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:59.491  1018  4327 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:59.491  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:07:59.491  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 17:07:59.491  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:07:59.501  7562  7562 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-24 17:07:59.501  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-24 17:07:59.501  7616  7616 E Zygote  : MountEmulatedStorage()
08-24 17:07:59.501  7616  7616 E Zygote  : v2
08-24 17:07:59.501  7616  7616 I libpersona: KNOX_SDCARD checking this for 10068
08-24 17:07:59.501  7616  7616 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:59.501  7616  7616 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 17:07:59.501  1018  4334 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:59.501  7616  7616 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 17:07:59.501  7616  7616 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-24 17:07:59.501  1018  1031 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7616 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-24 17:07:59.521  7562  7562 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-24 17:07:59.521  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-24 17:07:59.521  7562  7562 I wpa_supplicant: Skip scan - bUseNetwork false
,08-24 17:07:59.521  7616  7616 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:07:59.521  7616  7616 D ActivityThread: Added TimaKeyStore provider,
,08-24 17:07:59.531  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-24 17:07:59.531  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-24 17:07:59.531  7562  7562 I wpa_supplicant: HOTSPOT20_ENABLE called
08-24 17:07:59.531  7562  7562 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:07:59.531  7562  7562 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:07:59.531  7562  7562 E wpa_supplicant: SIM READ ERROR
08-24 17:07:59.531  7562  7562 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:07:59.541  1018  1562 D RCPManagerService: exchangeData() failure , invalid userId
,08-24 17:07:59.541  1018  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-24 17:07:59.541  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.541  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.541  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.541  1018  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:59.551  7616  7616 D BadgeProvider: onCreate
08-24 17:07:59.551  7616  7616 D BadgeProvider: DatabaseHelper
,08-24 17:07:59.551  7632  7632 E Zygote  : MountEmulatedStorage()
08-24 17:07:59.551  1018  1501 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7632 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-24 17:07:59.551  7632  7632 E Zygote  : v2
08-24 17:07:59.551  7632  7632 I libpersona: KNOX_SDCARD checking this for 10009
08-24 17:07:59.551  7632  7632 I libpersona: KNOX_SDCARD not a persona
08-24 17:07:59.561  7632  7632 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-24 17:07:59.561  1018  1501 I ActivityManager: Killing 7171:com.android.vending/u0a26 (adj 15): empty #21
,08-24 17:07:59.561  1018  1501 I ActivityManager: Killing 6850:com.android.defcontainer/u0a3 (adj 15): empty #22
,08-24 17:07:59.561  7632  7632 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:07:59.561  7632  7632 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-24 17:07:59.591  7562  7562 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-24 17:07:59.591  7632  7632 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:07:59.591  7632  7632 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:59.601  7562  7562 I wpa_supplicant: Skip scan - bUseNetwork false
,08-24 17:07:59.611  1018  1127 D WifiConfigStore: Loading config and enabling all networks ,
,08-24 17:07:59.621  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:07:59.621  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:07:59.621  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 17:07:59.621  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:59.621  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:59.621  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:07:59.621  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:07:59.621  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:59.621  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:07:59.621  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-24 17:07:59.621  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:59.621  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:59.621  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:59.621  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:59.621  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:59.621  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:59.621  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:59.621  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:07:59.621  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:07:59.621  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:07:59.621  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:59.621  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:07:59.631  4768  4768 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:07:59.631  1176  1176 D HotspotTile: onReceive : 3, 0
,08-24 17:07:59.631  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:07:59.631  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:07:59.631  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:07:59.631  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:07:59.631  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:07:59.631  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:07:59.631  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:07:59.631  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:07:59.631  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:07:59.631  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:07:59.631  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:07:59.641  1018  1127 E WifiConfigStore: Not a HS20
,08-24 17:07:59.641  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-24 17:07:59.651  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-24 17:07:59.651  7562  7562 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-24 17:07:59.651  7562  7562 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-24 17:07:59.651  7562  7562 I wpa_supplicant: reset timer : RESET_TIMER 0
08-24 17:07:59.651  7562  7562 I wpa_supplicant: P2P: Current p2p state = IDLE
08-24 17:07:59.651  7562  7562 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-24 17:07:59.651  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-24 17:07:59.651  7562  7562 I wpa_supplicant: First Scan Start
,08-24 17:07:59.651  7562  7562 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 17:07:59.651  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-24 17:07:59.651  7289  7289 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 17:07:59.651  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-24 17:07:59.651  1018  1127 I WifiNative-HAL: startHal
,08-24 17:07:59.651  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9ecb388c
08-24 17:07:59.651  1018  1127 I WifiNative-HAL: Could not start hal
,08-24 17:07:59.661  1018  1127 E WifiNative-wlan0: do suspend true
,08-24 17:07:59.661  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-24 17:07:59.661  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-24 17:07:59.661   277  1004 D CommandListener: Setting iface cfg
08-24 17:07:59.661   277  1004 D CommandListener: Trying to bring up p2p0
,08-24 17:07:59.661  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 17:07:59.661  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 17:07:59.661  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:59.661  1018  1126 D WifiP2pService: P2pEnablingState
08-24 17:07:59.661  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-24 17:07:59.661  1018  1018 D RttService: SCAN_AVAILABLE : 3
,08-24 17:07:59.661  1018  1126 D WifiP2pService: P2p socket connection successful
08-24 17:07:59.661  1018  1152 I WifiNative-HAL: startHal
08-24 17:07:59.661  1018  1126 D WifiP2pService: P2pEnabledState
08-24 17:07:59.661  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x993469bc
,08-24 17:07:59.671  1018  1152 I WifiNative-HAL: Could not start hal
08-24 17:07:59.671  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-24 17:07:59.671  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-24 17:07:59.671  1018  1153 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:07:59.671  1018  1152 E WifiScanningService: could not start HAL
,08-24 17:07:59.671  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-24 17:07:59.671  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-24 17:07:59.671  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:59.671  1018  1048 D WifiDisplayController: disconnect
,08-24 17:07:59.671  1018  1048 D WifiDisplayController: updateConnection
08-24 17:07:59.671  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:07:59.671  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:07:59.671  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:07:59.671  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:07:59.671  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:07:59.671  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-24 17:07:59.681  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 17:07:59.681  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 17:07:59.681  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-24 17:07:59.681  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-24 17:07:59.681  7562  7562 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-24 17:07:59.681  7562  7562 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-24 17:07:59.681  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-24 17:07:59.681  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-24 17:07:59.681  1018  4327 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:07:59.681  7562  7562 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-24 17:07:59.681  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 17:07:59.681  1018  1126 D WifiP2pService: DeviceAddress: 0a:75:42
,08-24 17:07:59.681  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  secondary type: null
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  wps: 0
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  grpcapab: 0
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  devcapab: 0
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  status: 3
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  wfdInfo: null
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-24 17:07:59.681  1018  1048 D WifiDisplayController:  SConnectInfo : null
08-24 17:07:59.681  1018  1127 E WifiStateMachine: Failed to set frequency band 0
,08-24 17:07:59.691  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,08-24 17:07:59.691  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-24 17:07:59.691  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:59.691  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:07:59.691  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:07:59.691  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:07:59.691  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:07:59.701  1018  1030 I ActivityManager: Killing 7314:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-24 17:07:59.721  1018  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:07:59.721  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:59.721  1018  1486 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:07:59.721  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:07:59.721  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:59.721  1636  1636 I Hs20UtilService: Starting #11
,08-24 17:07:59.721  1636  1665 I Hs20UtilService: Message received 5011
,08-24 17:07:59.731  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-24 17:07:59.731  1018  1126 D WifiP2pService: InactiveState
,08-24 17:07:59.731  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
08-24 17:07:59.731  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 17:07:59.731  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-24 17:07:59.731  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:59.731  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:07:59.731  7088  7088 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:07:59.741  7562  7562 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-24 17:07:59.741  1018  1031 I art     : Explicit concurrent mark sweep GC freed 62005(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 22MB/34MB, paused 2.919ms total 179.131ms
,08-24 17:07:59.741  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
08-24 17:07:59.741  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
08-24 17:07:59.751  1018  4334 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:07:59.751  1018  4334 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:59.751  1018  4334 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:59.751  1018  4334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:59.751  1018  4334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:07:59.751   277  1000 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:07:59.751   277  1000 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-24 17:07:59.751  1636  1636 I Hs20UtilService: Starting #12
,08-24 17:07:59.761  1636  1665 I Hs20UtilService: Message received 5011
08-24 17:07:59.761  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:07:59.761  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:59.761  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:07:59.761  7088  7088 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:07:59.771  7616  7624 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-24 17:07:59.771  1018  1507 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:07:59.771  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:07:59.771  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:07:59.771  1018  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:07:59.771  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:07:59.781  1636  1636 I Hs20UtilService: Starting #13
,08-24 17:07:59.781  1636  1665 I Hs20UtilService: Message received 5011
,08-24 17:07:59.781  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 17:07:59.781  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 17:07:59.781  1018  1127 E WifiNative-wlan0: invaild command id : 215
,08-24 17:07:59.781  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:07:59.781  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:07:59.781  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:07:59.781  7088  7088 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:07:59.791  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-24 17:07:59.791  1018  1507 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-24 17:07:59.791  7616  7624 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-24 17:07:59.791  7616  7624 D BadgeProvider: sendNotify, [notify] : null
08-24 17:07:59.791  7616  7624 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-24 17:07:59.791  7616  7624 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-24 17:07:59.791  7616  7624 D BadgeProvider: update, [UpdateCount] : 1
,08-24 17:07:59.791  1490  1490 D Launcher.Model: reloadBadges entered.
,08-24 17:07:59.801  1018  4333 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-24 17:07:59.801  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-24 17:07:59.801  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 17:07:59.801  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:07:59.801  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:07:59.811  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:07:59.811  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:07:59.811  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:07:59.811  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:07:59.811  1018  4334 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-24 17:07:59.811  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.811  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.811  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:07:59.811  1018  4334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:07:59.821  1018  4334 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7656 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 17:07:59.821  7656  7656 E Zygote  : MountEmulatedStorage()
08-24 17:07:59.821  7656  7656 I libpersona: KNOX_SDCARD checking this for 10064
08-24 17:07:59.821  7656  7656 E Zygote  : v2
08-24 17:07:59.821  7656  7656 I libpersona: KNOX_SDCARD not a persona
,08-24 17:07:59.831  7656  7656 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-24 17:07:59.831  7656  7656 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 17:07:59.831  7656  7656 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:07:59.851  7656  7656 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-24 17:07:59.851  7656  7656 D ActivityThread: Added TimaKeyStore provider
,08-24 17:07:59.851   311   311 I art     : Explicit concurrent mark sweep GC freed 8663(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 701us total 27.537ms
,08-24 17:07:59.861  7656  7656 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-24 17:07:59.871  7656  7656 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-24 17:07:59.871   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.465ms
,08-24 17:07:59.871  7656  7656 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-24 17:07:59.891   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 16.205ms,
,08-24 17:07:59.901  7656  7656 D FileShare-Client: Outbound.stopDelayTimer - ,
,08-24 17:07:59.901  7329  7329 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:07:59.911  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:07:59.911  1018  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:07:59.911  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-24 17:07:59.911  1018  4327 I ActivityManager: Killing 7223:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-24 17:07:59.991  1018  1096 V AlarmManager: waitForAlarm result :8
,08-24 17:08:00.451   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:08:00.821  7562  7562 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
08-24 17:08:00.821  7562  7562 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-24 17:08:00.821  7562  7562 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-24 17:08:00.821  7562  7562 I wpa_supplicant: Trying to associate with  'G700'
,08-24 17:08:00.821  7562  7562 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-24 17:08:00.821  1018  7631 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-24 17:08:00.821  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-24 17:08:00.841  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 17:08:00.841  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:00.941  7562  7562 E wpa_supplicant: Cmd 35605 not handled
,08-24 17:08:00.941  7562  7562 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-24 17:08:00.941  7562  7562 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-24 17:08:00.941  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-24 17:08:00.941  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:00.941  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:00.941  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:00.941  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:00.941  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:00.941  7562  7562 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-24 17:08:00.941  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:00.941  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:08:00.941  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:08:00.941  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,08-24 17:08:00.941  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-24 17:08:00.941  1018  1045 D Tethering: interfaceStatusChanged wlan0, true,
08-24 17:08:00.941  1018  1132 E Tethering: No numeric data,
08-24 17:08:00.941  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-24 17:08:00.941  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-24 17:08:00.941  1018  1124 V NetworkStats: performPollLocked(flags=0x1),
08-24 17:08:00.941  1018  1132 D Tethering: clearTetheredNotification()
08-24 17:08:00.941  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-24 17:08:00.941  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:00.941  1176  1176 D HotspotTile: updateTetherState():false, false
,08-24 17:08:00.941  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:00.941  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:00.941  7562  7562 I wpa_supplicant: Associated with F4.99.3E
08-24 17:08:00.941  7562  7562 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-24 17:08:00.941  7562  7562 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-24 17:08:00.951  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-24 17:08:00.951  1018  1124 V NetworkStats: performPollLocked() took 6ms
08-24 17:08:00.951  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:00.951  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:00.951  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-24 17:08:00.961  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 17:08:00.961  1018  1127 D SecContentProvider2: mCursor = null
08-24 17:08:00.961  7562  7562 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-24 17:08:00.961  7562  7562 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-24 17:08:00.961  7562  7562 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-24 17:08:00.961  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-24 17:08:00.961  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-24 17:08:00.961  7562  7562 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:08:00.961  7562  7562 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-24 17:08:00.961  7562  7562 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-24 17:08:00.961  7562  7562 I wpa_supplicant: Blacklist: Clear (temp) 
08-24 17:08:00.961  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-24 17:08:00.961  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-24 17:08:00.961  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-24 17:08:00.961  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:00.961  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:00.971  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-24 17:08:00.981  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-24 17:08:00.981  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} },
08-24 17:08:00.981  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-24 17:08:00.981  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:08:00.981  1018  1129 E ConnectivityService: updateNetworkInfo(),
08-24 17:08:00.981  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:08:00.981  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:00.981  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:00.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:00.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:00.991  1018  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:00.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:00.991  1018  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 17:08:00.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:00.991  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:00.991  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:00.991  1018  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:00.991  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:00.991  1636  1636 I Hs20UtilService: Starting #14
,08-24 17:08:00.991  1636  1665 I Hs20UtilService: Message received 5007
,08-24 17:08:00.991  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:08:01.001  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 17:08:01.001  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:01.001  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-24 17:08:01.001  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:08:01.001  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:08:01.001  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:08:01.001  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:08:01.011   277  1004 D CommandListener: Setting iface cfg
,08-24 17:08:01.011  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-24 17:08:01.021  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 17:08:01.021  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:01.031  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:01.031  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:01.031  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 17:08:01.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:01.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:01.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:01.031  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:01.041  1018  1127 E WifiNative-wlan0: do suspend false
,08-24 17:08:01.041  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:01.041  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:01.041  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-24 17:08:01.051  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 17:08:01.261  7673  7673 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-24 17:08:01.271  7673  7673 I dhcpcd  : version 5.5.6 starting,
,08-24 17:08:01.271  7673  7673 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-24 17:08:01.291  1018  1137 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-24 17:08:01.291  1018  1137 D WifiService: setWifiEnabled: false pid=6932, uid=10170,
08-24 17:08:01.291  1018  1137 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-24 17:08:01.291  1018  1137 D SecContentProvider2: mCursor = null,
,08-24 17:08:01.291  1018  1137 D SettingsProvider: name = wifi_on
,08-24 17:08:01.301  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:01.311  1018  1127 E WifiNative-wlan0: do suspend true
,08-24 17:08:01.331  1018  1126 D WifiP2pService: InactiveState{ what=143375 },
08-24 17:08:01.331  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 17:08:01.331   277  1004 D CommandListener: Clearing all IP addresses on wlan0,
,08-24 17:08:01.341  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:01.341  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:01.341  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:01.341  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.341  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.341  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.341  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:01.341  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:08:01.341  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:08:01.341  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:08:01.341  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-24 17:08:01.341   277  1004 E Netd    : no such netId 503
08-24 17:08:01.341  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 17:08:01.351  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:01.351  1018  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-24 17:08:01.351  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:01.351  1018  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-24 17:08:01.351  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:01.351  1018  1129 V NetworkStats: updateIfacesLocked()
08-24 17:08:01.351  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-24 17:08:01.351  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:01.351  1018  1129 V NetworkStats: performPollLocked() took 4ms
,08-24 17:08:01.351  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:08:01.351  1018  1126 D WifiP2pService: InactiveState{ what=131204 }
,08-24 17:08:01.361  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:01.361  1018  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-24 17:08:01.361  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:01.361  1018  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-24 17:08:01.361  7673  7673 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-24 17:08:01.361  1018  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-24 17:08:01.361  7673  7673 E dhcpcd  : wlan0: sendmsg: Network is unreachable
08-24 17:08:01.361  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-24 17:08:01.361  7673  7673 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-24 17:08:01.361  1018  7671 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:08:01.361  1018  7671 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-24 17:08:01.361  1018  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-24 17:08:01.361  1018  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-24 17:08:01.361  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-24 17:08:01.361  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.361  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.361  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.361  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:08:01.361  7673  7673 I dhcpcd  : bssid match
08-24 17:08:01.361  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 1
08-24 17:08:01.361  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:08:01.361  7673  7673 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
08-24 17:08:01.361  1018  4334 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:01.361  1018  1018 D RttService: SCAN_AVAILABLE : 1
08-24 17:08:01.361  1018  4334 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 17:08:01.361  1018  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-24 17:08:01.361  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:08:01.361  1018  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 17:08:01.361  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:08:01.361  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:01.361  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:08:01.361  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:01.361  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 17:08:01.361  1018  4334 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:01.361  1018  4334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:01.361  1018  4334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:08:01.361  1636  1636 I Hs20UtilService: Starting #15
08-24 17:08:01.361  1636  1665 I Hs20UtilService: Message received 5007
08-24 17:08:01.361  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-24 17:08:01.361  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-24 17:08:01.361  1018  1126 D WifiP2pService: P2pDisablingState
,08-24 17:08:01.361  1018  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-24 17:08:01.371  1018  1126 D WifiP2pService: p2p socket connection lost,
08-24 17:08:01.371  1018  1126 D WifiP2pService: P2pDisabledState
08-24 17:08:01.371  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-24 17:08:01.371  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-24 17:08:01.371  1018  1127 E WifiNative-wlan0: do suspend true
08-24 17:08:01.371  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-24 17:08:01.371  1018  1048 D WifiDisplayController: disconnect
08-24 17:08:01.371  1018  1048 D WifiDisplayController: updateConnection
08-24 17:08:01.371  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:08:01.371  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:08:01.371  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:08:01.371  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 17:08:01.371  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-24 17:08:01.371  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-24 17:08:01.371  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:08:01.371  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:08:01.371  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-24 17:08:01.371  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:08:01.371  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:08:01.371  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:08:01.371  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:08:01.371  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-24 17:08:01.371  1018  1488 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:08:01.381  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 17:08:01.381  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-24 17:08:01.381  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:08:01.381  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:08:01.381  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 17:08:01.381  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:08:01.381  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:08:01.381  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:08:01.391  7656  7656 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:08:01.391  7656  7656 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-24 17:08:01.391  7656  7656 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 17:08:01.391  7329  7329 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:08:01.401  1018  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-24 17:08:01.401  1018  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-24 17:08:01.401   277  1004 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:08:01.401  7562  7562 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:08:01.401  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 17:08:01.401  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:08:01.401  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:01.401  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:01.401  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:01.411  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.411  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:01.421  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:01.421  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:01.421  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:01.421  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:01.421  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:08:01.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.421  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:01.421  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:01.421  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:01.421  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-24 17:08:01.421  4768  4768 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:01.421  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:08:01.421  1176  1176 D HotspotTile: onReceive : 0, 0
,08-24 17:08:01.421  1018  4327 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:01.421  1018  4327 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:01.431  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:01.431  1018  4327 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:01.431  1018  4327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:01.431  1018  4327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:08:01.431  1636  1636 I Hs20UtilService: Starting #16
08-24 17:08:01.431  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:01.431  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:01.431  1636  1665 I Hs20UtilService: Message received 5007
08-24 17:08:01.431  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 17:08:01.431  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-24 17:08:01.431  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:08:01.431  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:01.431  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:01.441  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:08:01.441  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:08:01.441  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:01.441  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:01.441  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:08:01.441  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:08:01.441  1018  4327 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:08:01.441  1018  4327 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:01.451   322   322 I ServiceManager: Waiting for service AtCmdFwd...
08-24 17:08:01.451  1018  4327 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:01.451  1018  4327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:01.451  1018  4327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:01.451  1636  1636 I Hs20UtilService: Starting #17
,08-24 17:08:01.451  1636  1665 I Hs20UtilService: Message received 5011
,08-24 17:08:01.451  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 17:08:01.451  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:08:01.451  7673  7673 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,08-24 17:08:01.451  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:08:01.451  7088  7088 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:08:01.521  7562  7562 I wpa_supplicant: Blacklist: Clear (all) ,
,08-24 17:08:01.541  7673  7673 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,08-24 17:08:01.621  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:08:01.621  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 17:08:01.621  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-24 17:08:01.621  7562  7562 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-24 17:08:01.641  7562  7562 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-24 17:08:01.641  7562  7562 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-24 17:08:01.641  7562  7562 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-24 17:08:01.651  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:01.641  7562  7562 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-24 17:08:01.641  7562  7562 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-24 17:08:01.641  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:01.641  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:08:01.651  1018  1132 D Tethering: InitialState.processMessage what=4
,08-24 17:08:01.651  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 17:08:01.651  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:01.651  1018  1132 E Tethering: No numeric data
08-24 17:08:01.651  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:08:01.651  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:08:01.651  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:01.651  1018  1132 D Tethering: clearTetheredNotification()
08-24 17:08:01.651  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-24 17:08:01.651  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:01.651  1176  1176 D HotspotTile: updateTetherState():false, false
08-24 17:08:01.651  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:01.661  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:01.651  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:08:01.661  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:01.661  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:01.661  1018  1124 V NetworkStats: performPollLocked() took 5ms
,08-24 17:08:01.661  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:01.661  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:01.661  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:01.891  5984  5984 D FactoryTest: Not factory mode
,08-24 17:08:01.891  5984  5984 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-24 17:08:01.891  5984  5984 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-24 17:08:01.891  5984  5984 D MTPRx   : still no open session command from host, so toast
,08-24 17:08:01.901  5984  5984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-24 17:08:01.901  5984  5984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-24 17:08:01.901  5984  5984 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118435
,08-24 17:08:01.901  1018  1507 E PersonaManagerService: inState():  stateMachine is null !!
,08-24 17:08:01.901  1018  1507 I PersonaManagerService: PersonaId don't exist
08-24 17:08:01.901  1018  1507 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-24 17:08:01.911  1018  1507 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 17:08:01.911  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:01.911  1018  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:01.911  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-24 17:08:01.931  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:01.931  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:01.931  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:08:01.931  1018  1507 W ActivityManager: mDVFSHelper.acquire()
,08-24 17:08:01.951  1018  1507 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:08:01.961  7562  7562 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:08:01.961  1018  1507 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 17:08:01.961  1018  1507 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 17:08:01.961  1018  1507 D InputDispatcher: Focused application set to: xxxx
,08-24 17:08:01.961  1018  1507 D InputDispatcher: Focus left window: 6932
,08-24 17:08:01.961  5984  5984 E MTPRx   : started activity for popup
,08-24 17:08:01.981  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-24 17:08:01.981  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 17:08:02.001  5984  5984 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-24 17:08:02.001  5984  5984 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-24 17:08:02.001  5984  5984 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-24 17:08:02.001  5984  5984 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:08:02.001  5984  5984 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 17:08:02.001  5984  5984 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 17:08:02.031  5984  5984 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-24 17:08:02.041  1018  1327 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-24 17:08:02.041  1018  1327 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-24 17:08:02.041  1018  1327 D InputDispatcher: Focused application set to: xxxx
,08-24 17:08:02.041  1018  1327 D InputDispatcher: Focus entered window: 6932
,08-24 17:08:02.041  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 17:08:02.041  1018  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-24 17:08:02.041  1018  1030 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1278dfff attribute=null, token = android.os.BinderProxy@21ca37a8
08-24 17:08:02.051  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 17:08:02.051  7562  7562 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-24 17:08:02.051  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:02.051  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:02.051  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:08:02.091  5984  5984 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-24 17:08:02.091  5984  5984 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-24 17:08:02.091  5984  5984 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-24 17:08:02.111  6932  6932 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 17:08:02.111  6932  6932 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
08-24 17:08:02.111  6932  6932 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-24 17:08:02.111  6932  6932 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-24 17:08:02.111  1018  1486 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-24 17:08:02.111  1018  1486 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-24 17:08:02.111  1018  1486 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-24 17:08:02.111  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-24 17:08:02.111  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-24 17:08:02.131  6932  6932 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 17:08:02.131  6932  6932 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 17:08:02.141  6932  6932 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a2b2beb Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@29b0fec1, 16908290=android.view.AbsSavedState$1@29b0fec1}, android:focusedViewId=100}]}],
08-24 17:08:02.141  6932  6932 V ActivityThread: updateVisibility : ActivityRecord{1422e6d5 token=android.os.BinderProxy@1bfd3cbf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-24 17:08:02.141  6932  6932 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-24 17:08:02.141  6932  6932 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 17:08:02.141  6932  6932 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED,
08-24 17:08:02.141  6932  6932 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bfd3cbf time:118670
,08-24 17:08:02.151  1018  1031 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:08:02.151  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-24 17:08:02.151  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 17:08:02.161  7289  7289 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:08:02.161  4768  4768 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:08:02.171  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:02.171  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:02.171  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:02.171  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:08:02.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:02.171  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:02.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:02.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:02.171  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:02.171  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:02.171  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-24 17:08:02.171  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:08:02.171  1176  1176 D HotspotTile: onReceive : 1, 0
,08-24 17:08:02.171  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:02.171  1018  1507 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:02.171  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:02.171  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:02.171  1018  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:02.171  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:02.171  1636  1636 I Hs20UtilService: Starting #18
,08-24 17:08:02.171  1771  2207 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:08:02.171  1636  1665 I Hs20UtilService: Message received 5011
,08-24 17:08:02.181  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-24 17:08:02.181  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:08:02.181  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:08:02.181  7088  7088 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:08:02.401   291   291 E SMD     : DCD OFF,
,08-24 17:08:02.451   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-24 17:08:02.941   277   998 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-24 17:08:02.941  1018  1045 D Tethering: interfaceRemoved wlan0
08-24 17:08:02.941  1018  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-24 17:08:03.041  1018  1045 D Tethering: interfaceRemoved p2p0
,08-24 17:08:03.041  1018  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-24 17:08:03.701  1018  1096 V AlarmManager: waitForAlarm result :4,
,08-24 17:08:03.761  1018  1018 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-24 17:08:03.761  1018  1018 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-24 17:08:03.771  1018  1018 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-24 17:08:03.771   277  1000 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:08:03.771   277  1000 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-24 17:08:03.771  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-24 17:08:03.771  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,08-24 17:08:03.781  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-24 17:08:03.781  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,08-24 17:08:03.781  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:03.781  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:03.781  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-24 17:08:03.791  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 17:08:03.791  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-24 17:08:03.791  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,08-24 17:08:03.801  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 17:08:03.821  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 17:08:03.831  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 17:08:03.841  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-24 17:08:03.841  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-24 17:08:04.301  6932  7162 D BluetoothAdapter: enable()
,08-24 17:08:04.301  1018  1507 W ActivityManager: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 17:08:04.311  1018  1507 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-24 17:08:04.311  1018  1507 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:08:04.311  1018  1507 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:08:04.311  1018  1507 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-24 17:08:04.311  1018  1507 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-24 17:08:04.311  1018  1507 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-24 17:08:04.311  1018  1507 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 17:08:04.311  1018  1507 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-24 17:08:04.311  1018  1507 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:04.311  1018  1507 D SettingsProvider: name = bluetooth_on
,08-24 17:08:04.311  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:04.311  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:04.321  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-24 17:08:04.331  3221  3292 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-24 17:08:04.331  3221  3292 D BluetoothAdapterProperties: Setting state to 11
08-24 17:08:04.331  3221  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 17:08:04.331  3221  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:08:04.331  3221  3292 D BluetoothAdapterService: updateAdapterState state is 11
,08-24 17:08:04.331  3221  3292 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:04.331  3221  3292 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-24 17:08:04.331  3221  3292 D BtConfig.SecureMode: isSecureModeOn:false
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 17:08:04.331  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:08:04.331  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 17:08:04.331  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:04.331  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-24 17:08:04.351  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:04.351  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:04.351  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-24 17:08:04.351  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
08-24 17:08:04.351  4768  4768 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:04.351  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 17:08:04.351  1869  1869 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:04.361  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.361  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.361  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:04.361  1018  1562 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:04.361  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.361  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.361  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.361  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:04.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 17:08:04.371  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:04.371  1018  1137 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:08:04.371  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:04.371  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-24 17:08:04.371  3221  3221 D HeadsetService: Received start request. Starting profile...
08-24 17:08:04.371  3221  3221 D HeadsetService: start()
08-24 17:08:04.371  3221  3221 D HeadsetStateMachine: make
,08-24 17:08:04.371  2650  2650 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:04.371  3221  3221 E HeadsetStateMachine: # of Max HF connection is 2
08-24 17:08:04.371  1018  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.371  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.371  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.381  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.381  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.381  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-24 17:08:04.381  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:04.381  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-24 17:08:04.381  1018  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.381  1018  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.381  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.381  1018  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.381  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.381  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-24 17:08:04.381  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 17:08:04.381  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 17:08:04.391  1018  1222 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-24 17:08:04.391  1018  1222 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.391  1018  1222 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.391  1018  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:04.391  1018  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 17:08:04.391  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.391  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.391  1018  1327 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:08:04.391  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.391  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.391  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
08-24 17:08:04.391  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 17:08:04.391  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.391  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-24 17:08:04.391  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.391  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.401  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:04.401  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.401  1018  1507 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-24 17:08:04.401  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.401  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.401  1018  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.401  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 17:08:04.401  3221  3221 I bluedroid: get_profile_interface handsfree
08-24 17:08:04.401  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-24 17:08:04.401  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:04.401  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:04.401  1018  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-24 17:08:04.401  1018  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.411  1018  1137 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.411  1018  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.411  1018  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:08:04.411  4768  4768 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService,
08-24 17:08:04.421  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-24 17:08:04.421  1018  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.421  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.421  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.421  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.421  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.421  3221  3221 E DualScoManager: Dual Sco Manager already instantiated
08-24 17:08:04.421  3221  3221 I DualScoManager: Set HeadsetServiceHelper
,08-24 17:08:04.421  3221  3221 D BluetoothAtMessage: createCMTIContentObservers
,08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:04.421  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:04.421  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 17:08:04.421  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-24 17:08:04.421  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 17:08:04.421  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 17:08:04.421  3221  3292 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-24 17:08:04.421  1018  1030 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-24 17:08:04.421  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:04.421  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:04.421  1018  1030 D SettingsProvider: selectionArgs: false
08-24 17:08:04.421  1018  1030 D SettingsProvider: selectionArgs: 1002
08-24 17:08:04.421  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:04.421  1018  1030 D SettingsProvider: ret = -1
,08-24 17:08:04.421  3221  7708 D HeadsetStateMachine: Enter Disconnected: -2
,08-24 17:08:04.431  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:04.431  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-24 17:08:04.431  3221  3221 D HeadsetService: mStartError = false
08-24 17:08:04.431  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:04.431  3221  3221 D A2dpService: Received start request. Starting profile...
,08-24 17:08:04.431  3221  3221 D A2dpService: start()
,08-24 17:08:04.431  3221  3221 I bluedroid: get_profile_interface avrcp
,08-24 17:08:04.441  3221  7708 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-24 17:08:04.441  3221  7708 D HeadsetStateMachine: map size, before remove : 0,
08-24 17:08:04.441  1018  1488 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-24 17:08:04.441  3221  7708 D HeadsetStateMachine: map size, after remove: 0
,08-24 17:08:04.441  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:04.441  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:04.441  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:04.441  1018  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:04.451  3221  3221 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-24 17:08:04.451  3221  3221 D Avrcp   : Initialize Media Controller
08-24 17:08:04.451  3221  3221 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-24 17:08:04.451  3221  3221 E Avrcp   : getActiveSessions
08-24 17:08:04.451  3221  3221 D Avrcp   : pick active media Controller
08-24 17:08:04.451  3221  3221 D Avrcp   : Get the active Media Controller 
,08-24 17:08:04.451  1018  1488 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7710 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-24 17:08:04.451  7710  7710 E Zygote  : MountEmulatedStorage()
08-24 17:08:04.451  7710  7710 I libpersona: KNOX_SDCARD checking this for 10055
08-24 17:08:04.451  7710  7710 E Zygote  : v2
08-24 17:08:04.451  7710  7710 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:04.451  7710  7710 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:04.461  7710  7710 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:08:04.461  7710  7710 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-24 17:08:04.461  3221  3221 I Avrcp   :  Updating now playing list upon AVRCP Start
08-24 17:08:04.461  3221  3221 D A2dpStateMachine: make
08-24 17:08:04.461  3221  7709 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-24 17:08:04.471  3221  3221 I bluedroid: get_profile_interface a2dp
,08-24 17:08:04.471  3221  7720 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-24 17:08:04.471  3221  3221 E bt-btif : warning : media task started media_task_refcnt 1 
08-24 17:08:04.471  3221  3221 D A2dpService: mStartError = false
08-24 17:08:04.471  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
08-24 17:08:04.471  3221  7718 D A2dpStateMachine: Enter Disconnected: -2
,08-24 17:08:04.471  3221  3221 D HidService: Received start request. Starting profile...
08-24 17:08:04.471  3221  3221 D HidService: start()
08-24 17:08:04.471  3221  3221 I bluedroid: get_profile_interface hidhost
08-24 17:08:04.471  3221  3221 D HidService: setHidService(): set to: null
08-24 17:08:04.471  3221  3221 D HidService: mStartError = false
08-24 17:08:04.471  1425  1456 I Telecom : BluetoothPhoneService: queryPhoneState
08-24 17:08:04.471  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
08-24 17:08:04.471  3221  3221 D HeadsetStateMachine: Try to query the phonestate on bind
08-24 17:08:04.481  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-24 17:08:04.481  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-24 17:08:04.481  1425  1456 I Telecom : BluetoothPhoneService: Result of Message : true
,08-24 17:08:04.481  3221  3221 D HealthService: Received start request. Starting profile...
08-24 17:08:04.481  3221  3221 D HealthService: start()
,08-24 17:08:04.481  3221  7709 D BluetoothMediaBrowser: no now playing list
,08-24 17:08:04.481  3221  7709 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-24 17:08:04.481  3221  3221 I bluedroid: get_profile_interface health
08-24 17:08:04.481  3221  3221 D HealthService: mStartError = false
08-24 17:08:04.481  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:04.481  3221  3221 D PanService: Received start request. Starting profile...
08-24 17:08:04.481  3221  3221 D PanService: start()
08-24 17:08:04.481  3221  3221 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 17:08:04.481  3221  3221 I bluedroid: get_profile_interface pan
08-24 17:08:04.481  3221  3221 D PanService: mStartError = false
08-24 17:08:04.481  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
08-24 17:08:04.481  3221  3221 D HeadsetStateMachine: Proxy object connected
08-24 17:08:04.481  3221  3221 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-24 17:08:04.481  3221  7708 D HeadsetStateMachine: Disconnected process message: 11
,08-24 17:08:04.481  3221  3221 D BluetoothMapService: Received start request. Starting profile...
08-24 17:08:04.481  3221  3221 D BluetoothMapService: start()
,08-24 17:08:04.491  3221  3221 D BluetoothMapService: mStartError = false
08-24 17:08:04.491  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
08-24 17:08:04.491  3221  3221 D HeadsetPhoneState: sendDeviceDataStateChanged
08-24 17:08:04.491  3221  7708 D HeadsetStateMachine: Disconnected process message: 18
08-24 17:08:04.491  3221  3221 D HeadsetPhoneState: Signal level : previous=0 curr=4
,08-24 17:08:04.491  3221  3221 D SapService: Received start request. Starting profile...
08-24 17:08:04.491  3221  3221 D SapService: start()
08-24 17:08:04.491  3221  3221 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-24 17:08:04.491  3221  3221 I bluedroid: get_profile_interface sap
08-24 17:08:04.491  3221  3221 D SapService: mStartError = false
08-24 17:08:04.491  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
08-24 17:08:04.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-24 17:08:04.491  3221  3221 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 17:08:04.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-24 17:08:04.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-24 17:08:04.491  3221  7708 D HeadsetStateMachine: Disconnected process message: 10
08-24 17:08:04.491  3221  7708 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 17:08:04.491  3221  7708 D HeadsetStateMachine: Disconnected process message: 11
,08-24 17:08:04.491  7710  7710 D TimaKeyStoreProvider: TimaSignature is unavailable
08-24 17:08:04.491  7710  7710 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:04.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-24 17:08:04.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-24 17:08:04.511  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-24 17:08:04.511  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-24 17:08:04.511  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-24 17:08:04.511  3221  3292 I bluedroid: enable
,08-24 17:08:04.521  3221  3295 E bt-btif : Calling BTA_HhEnable
,08-24 17:08:04.521  3221  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 17:08:04.521  3221  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 17:08:04.521  3221  3295 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-24 17:08:04.521  3221  3295 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-24 17:08:04.521  3221  3295 E BluetoothServiceJni: populateRssiValuesNative
08-24 17:08:04.521  3221  3295 I bluedroid: getModelRssiValues
08-24 17:08:04.521  3221  3295 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-24 17:08:04.521  3221  3295 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-24 17:08:04.521  3221  3295 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-24 17:08:04.521  1018  1018 D SettingsProvider: name = bluetooth_name
,08-24 17:08:04.521  3221  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-24 17:08:04.521  3221  3295 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:08:04.521  3221  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:08:04.531  3221  3295 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-24 17:08:04.531  3221  3295 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-24 17:08:04.531  3221  3295 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-24 17:08:04.531  3221  3295 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-24 17:08:04.531  3221  3295 E bt-btif : JVenable fails
08-24 17:08:04.531  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:04.531  3221  3295 D bte_conf: Device ID record 1 : primary
08-24 17:08:04.531  3221  3295 D bte_conf:   vendorId            = 0075
08-24 17:08:04.531  3221  3295 D bte_conf:   vendorIdSource      = 0001
08-24 17:08:04.531  3221  3295 D bte_conf:   product             = 0100
08-24 17:08:04.531  3221  3295 D bte_conf:   version             = 0200
08-24 17:08:04.531  3221  3295 D bte_conf:   clientExecutableURL = 
08-24 17:08:04.531  3221  3295 D bte_conf:   serviceDescription  = 
08-24 17:08:04.531  3221  3295 D bte_conf:   documentationURL    = 
08-24 17:08:04.531  3221  3295 D bte_conf: bte_load_did_conf no section named DID2.
08-24 17:08:04.531  3221  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 17:08:04.531  3221  3295 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 17:08:04.531  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-24 17:08:04.531  3221  3292 D BluetoothAdapterProperties: ScanMode =  20
08-24 17:08:04.531  3221  3292 D BluetoothAdapterProperties: State =  11
08-24 17:08:04.531  7710  7710 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-24 17:08:04.531  1018  1487 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-24 17:08:04.531  3221  3292 D BluetoothAdapterProperties: Setting state to 12
08-24 17:08:04.531  3221  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 17:08:04.531  3221  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 17:08:04.531  3221  3295 D BluetoothAdapterProperties: Scan Mode:21
,08-24 17:08:04.531  3221  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 17:08:04.541  1018  1563 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-24 17:08:04.541  1018  1563 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:04.541  1018  1563 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:04.541  1018  1563 D SettingsProvider: selectionArgs: false
08-24 17:08:04.541  1018  1563 D SettingsProvider: selectionArgs: 1002
08-24 17:08:04.541  1018  1563 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-24 17:08:04.541  1018  1563 D SettingsProvider: ret = -1
,08-24 17:08:04.541  3221  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:08:04.541  3221  3292 D BluetoothAdapterService: updateAdapterState state is 12
,08-24 17:08:04.541  1018  1563 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.541  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.541  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:04.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:04.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:04.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:04.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:04.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:04.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:04.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:04.541  1018  1563 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.541  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:04.541  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:04.541  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.551  3221  7266 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:08:04.551  3221  3292 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:04.551  3221  3292 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-24 17:08:04.551  3221  3292 D BluetoothAdapterService: starting service from this receiver
,08-24 17:08:04.551  1018  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.551  1018  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.551  3221  7266 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:04.551  3221  3221 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-24 17:08:04.551  3221  3221 I BluetoothPbapService: Handler(): got msg=1
,08-24 17:08:04.551  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.551  1018  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.551  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.561  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:04.561  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:04.561  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:04.561  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:04.561  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:04.561  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:04.561  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:04.561  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:04.561  1018  4334 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-24 17:08:04.561  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-24 17:08:04.561  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.561  3221  3292 I BluetoothAdapterState: Entering On State from state = 11
,08-24 17:08:04.561  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.561  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:04.561  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:04.561  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.561  7710  7710 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-24 17:08:04.561  7710  7710 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-24 17:08:04.561  7710  7710 D UserAnalysis: Create SecureDbHelper
,08-24 17:08:04.571  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:04.571  3221  7732 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-24 17:08:04.571  3221  7732 D BluetoothSocket: bindListen(): myUserId = 0
08-24 17:08:04.571  3221  7732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:04.571  7710  7710 D IntelligenceServiceApplication: onCreate()
,08-24 17:08:04.571  1454  1646 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:04.571  3221  7732 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-24 17:08:04.571  3221  7732 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:04.571  3221  7732 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:08:04.571  3221  7732 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b745081
,08-24 17:08:04.581  3221  7732 D BluetoothSocket: channel: 19
,08-24 17:08:04.581  3221  7732 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-24 17:08:04.581  1018  1501 I ActivityManager: Killing 7243:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-24 17:08:04.581  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 17:08:04.581  7710  7710 D IntelligenceServiceApplication: no applications having user consent for prediction
08-24 17:08:04.581  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:04.581  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.581  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.581  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.581  1454  1646 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:04.591  1018  4333 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-24 17:08:04.591  1440  1472 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.591  1440  1472 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:04.591  7710  7710 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-24 17:08:04.591  3221  3221 D BluetoothA2dp: Proxy object connected
08-24 17:08:04.591  3221  3221 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-24 17:08:04.591  7710  7710 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-24 17:08:04.651  1018  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #3,
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: android.os.DeadObjectException
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1053)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2007)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1576)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 17:08:04.651  1018  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-24 17:08:04.651  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-24 17:08:04.651  4768  4776 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 17:08:04.651  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-24 17:08:04.651  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.651  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:04.651  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.651  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 17:08:04.651  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-24 17:08:04.651  4768  4777 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-24 17:08:04.651  4768  4768 D BluetoothPbap: Proxy object connected
08-24 17:08:04.651  4768  4777 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:04.651  4768  4768 D PbapServerProfile: Bluetooth service connected
,08-24 17:08:04.651  3221  7266 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.651  3221  7266 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:04.651  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:04.651  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-24 17:08:04.651  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 17:08:04.651  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:04.651  1425  1462 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:04.661  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.661  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.661  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-24 17:08:04.661  1425  1462 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:04.661  1176  2006 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.661  1176  2006 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:04.661  6932  6940 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.661  6932  6940 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:04.661  4768  4776 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:04.661  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.661  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:04.661  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.661  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 17:08:04.661  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-24 17:08:04.661  4768  4768 D HeadsetProfile: Bluetooth service connected
,08-24 17:08:04.661  4768  4776 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:04.671  4768  4777 D BluetoothInputDevice: onBluetoothStateChange: up=true,
,08-24 17:08:04.671  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-24 17:08:04.671  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.671  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.671  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:04.671  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.671  4768  4768 D BluetoothInputDevice: Proxy object connected
,08-24 17:08:04.671  4768  4768 D HidProfile: Bluetooth service connected
08-24 17:08:04.671  1425  1456 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:04.671  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:04.671  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:04.671  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.671  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.671  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.671  1425  1456 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 17:08:04.671  4768  4776 D Bluetoothsap: onBluetoothStateChange: up=true
,08-24 17:08:04.671  4768  4776 D Bluetoothsap: Binding service...
,08-24 17:08:04.681  4768  4776 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-24 17:08:04.681  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-24 17:08:04.681  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.681  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.681  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.681  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.681  4768  4768 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-24 17:08:04.681  4768  4776 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-24 17:08:04.681  4768  4768 D SapProfile: Bluetooth service connected
08-24 17:08:04.681  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:08:04.681  4768  4768 D Bluetoothsap: getConnectedDevices()
08-24 17:08:04.681  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:04.681  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 17:08:04.681  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.681  1018  1018 D BluetoothA2dp: Proxy object connected
,08-24 17:08:04.681  4768  4777 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 17:08:04.681  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap,
08-24 17:08:04.681  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-24 17:08:04.681  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.681  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.681  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.691  2650  5361 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.691  2650  5361 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:04.691  1018  1047 D BluetoothPan: Binding service...
08-24 17:08:04.691  4768  4768 D BluetoothMap: Proxy object connected
08-24 17:08:04.691  4768  4768 D MapProfile: Bluetooth service connected
08-24 17:08:04.691  4768  4768 D BluetoothMap: getConnectedDevices()
,08-24 17:08:04.691  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-24 17:08:04.691  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.691  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:08:04.691  1425  7734 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:04.691  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:04.691  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:04.691  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.691  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.691  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.691  1425  7734 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:04.691  4768  4776 D BluetoothPan: Binding service...
,08-24 17:08:04.691  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-24 17:08:04.691  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.691  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.691  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.691  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.691  4768  4768 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 17:08:04.691  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.691  4768  4768 D PanProfile: Bluetooth service connected
08-24 17:08:04.701  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:04.701  1454  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.701  1454  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:04.701  1425  1462 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.701  1425  1462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:04.701  1771  1784 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:04.701  1771  1784 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-24 17:08:04.701  4768  7735 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:04.701  4768  7735 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:04.701  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 17:08:04.701  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.701  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.701  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.701  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.701  4768  4768 D BluetoothA2dp: Proxy object connected
08-24 17:08:04.701  4768  4768 D A2dpProfile: Bluetooth service connected
,08-24 17:08:04.701  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-24 17:08:04.701  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-24 17:08:04.701  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:04.701  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-24 17:08:04.701  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 17:08:04.711  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-24 17:08:04.711  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:04.711  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:04.711  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:04.711  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:04.711  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-24 17:08:04.721  1869  1869 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:04.721  1425  1425 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3f662e90, true
08-24 17:08:04.721  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:04.721  1425  1425 D BluetoothHeadset: registerMessageListener
,08-24 17:08:04.721  1018  1327 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:04.721  1018  1507 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-24 17:08:04.721  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:04.731  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:04.731  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:04.731  3221  7266 D HeadsetService: registerMessageListener
,08-24 17:08:04.731  3221  7266 D HeadsetService: registerMessageListener
,08-24 17:08:04.731  3221  7708 D HeadsetStateMachine: Disconnected process message: 70
,08-24 17:08:04.731  3221  7708 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@22a0b567
,08-24 17:08:04.741  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-24 17:08:04.741  3221  7736 D BluetoothMapMasInstance: set MAP SDP message type : 1,
08-24 17:08:04.741  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-24 17:08:04.741  4768  4768 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:04.741  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-24 17:08:04.741  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-24 17:08:04.741  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-24 17:08:04.741  4768  4768 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-24 17:08:04.741  4768  4768 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-24 17:08:04.741  4768  4768 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-24 17:08:04.741  4768  4768 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-24 17:08:04.741  3221  7708 D HeadsetStateMachine: Disconnected process message: 9
08-24 17:08:04.741  3221  7708 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-24 17:08:04.751  3221  7736 D BluetoothSocket: bindListen(): myUserId = 0
08-24 17:08:04.751  3221  7736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:04.751   285   682 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-24 17:08:04.751   285   682 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-24 17:08:04.751   285   682 V voice   : voice_set_parameters: exit with code(-2)
08-24 17:08:04.751   285   682 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-24 17:08:04.751   285   682 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-24 17:08:04.751   285   682 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-24 17:08:04.751   285   682 V audio_hw_primary: adev_set_parameters: exit
,08-24 17:08:04.751  3221  7708 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-24 17:08:04.751  3221  7736 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-24 17:08:04.751  3221  7736 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:04.751  3221  7736 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-24 17:08:04.751  3221  7736 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a5ccf14
,08-24 17:08:04.751  3221  7736 D BluetoothSocket: channel: 5
,08-24 17:08:04.751  4768  4768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:04.751  1018  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-24 17:08:04.751  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.761  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:04.761  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.761  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:08:04.761  2650  2650 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:04.771  4768  4768 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:04.771  4768  4768 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:04.771  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:04.771  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-24 17:08:04.781  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:04.781  3221  3221 D BtConfig.SecureMode: isSecureModeOn:false
,08-24 17:08:04.781  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:04.781  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-24 17:08:04.781  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:04.781  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:04.781  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:04.781  1018  1327 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-24 17:08:04.791  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-24 17:08:04.791  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:04.791  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:04.791  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:04.801  7739  7739 E Zygote  : MountEmulatedStorage()
,08-24 17:08:04.801  7739  7739 E Zygote  : v2
08-24 17:08:04.801  7739  7739 I libpersona: KNOX_SDCARD checking this for 10105
08-24 17:08:04.801  7739  7739 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:04.801  1018  1327 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7739 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-24 17:08:04.801  7739  7739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:04.801  7739  7739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 17:08:04.801  7739  7739 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-24 17:08:04.811  1018  1488 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-24 17:08:04.821  3221  7748 D BluetoothSocket: bindListen(): myUserId = 0
08-24 17:08:04.821  3221  7748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:04.821  3221  7748 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-24 17:08:04.821  3221  7748 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:04.821  3221  7748 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:08:04.821  3221  7748 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23c1c880
,08-24 17:08:04.821  3221  7748 D BluetoothSocket: channel: 12
08-24 17:08:04.821  3221  7748 I BtOppRfcommListener: Accept thread started.
,08-24 17:08:04.831  7739  7739 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:04.831  7739  7739 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:04.931  1018  1043 W ActivityManager: mDVFSHelper.release()
,08-24 17:08:04.931   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 17:08:04.931   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:08:04.941  7739  7760 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 17:08:04.941   256   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-24 17:08:04.941   256   525 W Vold    : Returning OperationFailed - no handler for errno 0
,08-24 17:08:04.941  7739  7760 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-24 17:08:05.101  7739  7739 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:08:05.101  7739  7739 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:08:05.101  7739  7739 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:08:05.101  7739  7739 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:08:05.101  7739  7739 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.k.d(PG:583)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.e.b(PG:170)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:08:05.101  7739  7739 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:08:05.101  7739  7739 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.File.exists(File.java:363)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:08:05.101  7739  7739 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-24 17:08:05.101  7739  7739 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-24 17:08:05.101  1018  1494 I ActivityManager: Killing 7347:com.sec.pcw.device/1000 (adj 15): empty #21
,08-24 17:08:05.161  7739  7764 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-24 17:08:05.181  1018  4333 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-24 17:08:05.181  1018  4333 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:05.181  1018  4333 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-24 17:08:05.181  1018  4333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-24 17:08:05.401   291   291 E SMD     : DCD OFF,
,08-24 17:08:05.731  1018  3386 D SSRM:n  : SIOP:: AP = 370,
,08-24 17:08:06.411  1018  3414 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-24 17:08:07.321  6932  7162 D BluetoothAdapter: disable(),
08-24 17:08:07.321  1018  1487 D SettingsProvider: name = bluetooth_on
,08-24 17:08:07.331  3221  3292 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-24 17:08:07.331  3221  3292 D BluetoothAdapterProperties: Setting state to 13
08-24 17:08:07.331  3221  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 17:08:07.331  3221  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:08:07.331  3221  3292 D BluetoothAdapterService: updateAdapterState state is 13
,08-24 17:08:07.331  1018  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:07.331  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.331  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:07.331  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.331  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:07.331  3221  3292 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:07.331  3221  3292 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-24 17:08:07.331  3221  3292 D BluetoothAdapterService: terminating service from this receiver
,08-24 17:08:07.331  1018  4327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.331  3221  3221 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-24 17:08:07.331  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17998eb9, channel: 19, state: LISTENING
08-24 17:08:07.331  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17998eb9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b745081, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31f452femSocket: android.net.LocalSocket@24c4ea5f impl:android.net.LocalSocketImpl@bbaecac fd:FileDescriptor[80]
08-24 17:08:07.331  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@24c4ea5f impl:android.net.LocalSocketImpl@bbaecac fd:FileDescriptor[80]
08-24 17:08:07.341  1018  4327 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:07.341  1018  4327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.341  1018  4327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:07.341  3221  3292 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 17:08:07.341  3221  3292 D BluetoothAdapterProperties: mDiscovering is false
,08-24 17:08:07.341  1018  1507 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-24 17:08:07.341  3221  3292 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-24 17:08:07.341  4768  4768 D BluetoothPbap: Proxy object disconnected
08-24 17:08:07.341  4768  4768 D PbapServerProfile: Bluetooth service disconnected
,08-24 17:08:07.351  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:07.351  1018  1018 I InputMethodManagerService: [BT Setting State] State =13
,08-24 17:08:07.351  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-24 17:08:07.361  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:07.361  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:07.361  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-24 17:08:07.361  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:07.361  1869  1869 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:07.361  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:07.361  4768  4768 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:07.371  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:07.371  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:07.371  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:07.371  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:07.371  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:07.371  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:07.371  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:07.371  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:07.371  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:07.371  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:07.371  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:07.371  1018  1488 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:07.371  1018  1137 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:08:07.371  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-24 17:08:07.371  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:08:07.371  3221  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 17:08:07.371  3221  3295 D BluetoothAdapterProperties: Scan Mode:20
,08-24 17:08:07.371  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 17:08:07.371  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-24 17:08:07.371  3221  3292 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-24 17:08:07.381  3221  3292 E bt-btif : cmd socket is not created
08-24 17:08:07.381  3221  3292 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-24 17:08:07.381  3221  7748 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-24 17:08:07.381  3221  3296 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,08-24 17:08:07.381  4768  4768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:07.381  1018  1487 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 17:08:07.381  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.381  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 17:08:07.381  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:07.381  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:07.381  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:07.381  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:07.381  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 17:08:07.381  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:07.381  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:07.381  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:07.381  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:07.381  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.381  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:08:07.381  6932  6932 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 17:08:07.381  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:07.391  3221  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 17:08:07.391  3221  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:08:07.391  3221  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-24 17:08:07.391  3221  3296 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-24 17:08:07.391  3221  3296 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 17:08:07.391  3221  3296 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-24 17:08:07.391  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:07.391  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:07.401  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32bea10a, channel: 5, state: LISTENING
,08-24 17:08:07.401  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32bea10a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a5ccf14, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7f7cd7bmSocket: android.net.LocalSocket@d402798 impl:android.net.LocalSocketImpl@27f15bf1 fd:FileDescriptor[82]
,08-24 17:08:07.401  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d402798 impl:android.net.LocalSocketImpl@27f15bf1 fd:FileDescriptor[82]
,08-24 17:08:07.401  3221  3221 I BtOppRfcommListener: stopping Accept Thread
08-24 17:08:07.401  3221  3221 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@192dc3d6, channel: 12, state: LISTENING
,08-24 17:08:07.401  3221  3221 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@192dc3d6, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@23c1c880, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37abc657mSocket: android.net.LocalSocket@8dc2544 impl:android.net.LocalSocketImpl@2faec62d fd:FileDescriptor[86]
08-24 17:08:07.401  3221  3221 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@8dc2544 impl:android.net.LocalSocketImpl@2faec62d fd:FileDescriptor[86]
,08-24 17:08:07.401  3221  7748 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 17:08:07.401  2650  2650 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:07.411  3221  3221 V BluetoothOppManager: cleanUp...
,08-24 17:08:07.411  4768  4768 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:07.411  4768  4768 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:07.411  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:07.411  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-24 17:08:07.451   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:08:07.581  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-24 17:08:07.581  3221  3292 D BtConfig.SecureMode: isSecureModeOn:false
,08-24 17:08:07.581  3221  3292 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-24 17:08:07.581  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
08-24 17:08:07.581  3221  3292 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,08-24 17:08:07.581  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 17:08:07.581  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-24 17:08:07.581  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-24 17:08:07.581  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:07.581  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.591  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:07.591  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:07.591  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:07.591  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:07.591  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:07.591  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:07.591  1018  1563 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:07.591  1018  1563 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.601  1018  1563 W ActivityManager: userId = 0, bbcId = -10000,
08-24 17:08:07.601  3221  3221 D HeadsetService: Received stop request...Stopping profile...
08-24 17:08:07.601  1018  1563 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.601  1018  1563 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:07.601  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-24 17:08:07.601  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:07.601  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:07.601  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-24 17:08:07.601  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-24 17:08:07.601  1018  4333 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:07.601  1018  4333 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-24 17:08:07.601  4768  4768 D HeadsetProfile: Bluetooth service disconnected
,08-24 17:08:07.601  1018  4333 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:07.601  1018  4333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.601  1018  4333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:07.601  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService,
08-24 17:08:07.601  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-24 17:08:07.601  1018  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:07.601  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-24 17:08:07.601  1018  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-24 17:08:07.601  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:07.601  1018  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-24 17:08:07.601  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:08:07.611  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-24 17:08:07.611  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 17:08:07.611  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 17:08:07.611  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:07.611  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.611  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:07.611  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.611  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:07.611  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
08-24 17:08:07.611  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:07.611  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:07.611  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:07.611  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.611  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:07.611  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.611  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,08-24 17:08:07.621  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 17:08:07.621  1018  1031 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:07.621  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.621  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:07.621  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.621  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:07.621  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-24 17:08:07.621  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
,08-24 17:08:07.621  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-24 17:08:07.621  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-24 17:08:07.621  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 17:08:07.631  3221  3292 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-24 17:08:07.631  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-24 17:08:07.631  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-24 17:08:07.631  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-24 17:08:07.631  3221  3221 D A2dpService: Received stop request...Stopping profile...
08-24 17:08:07.631  3221  7718 D A2dpStateMachine: Exit Disconnected: -1
,08-24 17:08:07.631  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:07.631  1018  1018 D BluetoothA2dp: Proxy object disconnected
,08-24 17:08:07.631  4768  4768 D BluetoothA2dp: Proxy object disconnected
08-24 17:08:07.631  4768  4768 D A2dpProfile: Bluetooth service disconnected
,08-24 17:08:07.631  1018  1018 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-24 17:08:07.631  3221  3221 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
08-24 17:08:07.631  3221  3221 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 17:08:07.631  3221  3221 D HidService: Received stop request...Stopping profile...
08-24 17:08:07.641  3221  3221 D HidService: Stopping Bluetooth HidService
08-24 17:08:07.641  3221  3221 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 17:08:07.641  3221  3221 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-24 17:08:07.641  3221  3221 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 17:08:07.641  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:07.641  3221  3221 D HealthService: Received stop request...Stopping profile...
08-24 17:08:07.641  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:07.641  4768  4768 D BluetoothInputDevice: Proxy object disconnected
08-24 17:08:07.641  4768  4768 D HidProfile: Bluetooth service disconnected
,08-24 17:08:07.641  3221  3221 D PanService: Received stop request...Stopping profile...
,08-24 17:08:07.641  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:07.641  1018  1018 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-24 17:08:07.641  3221  3221 D BluetoothMapService: Received stop request...Stopping profile...
,08-24 17:08:07.651  4768  4768 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 17:08:07.651  4768  4768 D PanProfile: Bluetooth service disconnected
,08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:07.651  3221  3221 D SapService: Received stop request...Stopping profile...
,08-24 17:08:07.651  3221  3221 D SapService: Stopping Bluetooth SapService
08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:07.651  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-24 17:08:07.651  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-24 17:08:07.651  3221  3221 D BluetoothA2dp: Proxy object disconnected
,08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-24 17:08:07.651  3221  7720 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-24 17:08:07.651  3221  3221 I GKI_LINUX: GKI_exit_task 2 done
08-24 17:08:07.651  3221  3221 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-24 17:08:07.651  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:08:07.651  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:07.651  4768  4768 D BluetoothMap: Proxy object disconnected
08-24 17:08:07.651  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:08:07.651  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:07.651  3221  3221 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 17:08:07.651  3221  3221 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 17:08:07.651  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:08:07.651  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:07.651  3221  3221 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:07.651  3221  3221 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-24 17:08:07.651  3221  3221 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 17:08:07.651  4768  4768 D MapProfile: Bluetooth service disconnected
,08-24 17:08:07.661  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-24 17:08:07.661  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:08:07.661  3221  3221 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:08:07.661  3221  3221 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-24 17:08:07.661  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-24 17:08:07.661  3221  3221 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
08-24 17:08:07.661  4768  4768 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-24 17:08:07.661  4768  4768 D SapProfile: Bluetooth service disconnected
08-24 17:08:07.661  3221  3221 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-24 17:08:07.661  3221  3221 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-24 17:08:07.661  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-24 17:08:07.661  3221  3292 D BluetoothAdapterProperties: Setting state to 10
08-24 17:08:07.661  3221  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-24 17:08:07.661  3221  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-24 17:08:07.661  3221  3292 D BluetoothAdapterService: updateAdapterState state is 10
,08-24 17:08:07.661  3221  3292 D BluetoothAdapterService: Autoconnection is available 
,08-24 17:08:07.661  3221  3292 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-24 17:08:07.661  3221  3292 I BluetoothAdapterState: Entering OffState
08-24 17:08:07.661  3221  5337 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:08:07.661  1440  6415 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:07.661  1440  6415 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:07.661  4768  7735 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 17:08:07.661  4768  4777 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:07.661  4768  4777 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:07.661  3221  7777 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:07.661  3221  7777 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:07.671  1176  1825 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:07.671  1176  1825 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:07.671  6932  6940 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:07.671  6932  6940 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:08:07.671  6932  6940 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-24 17:08:07.671  6932  6940 D BluetoothLeAdvertiser: Exit stop advertising
08-24 17:08:07.671  6932  6940 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-24 17:08:07.671  6932  6940 D BluetoothLeScanner: Exiting stopAllScan
,08-24 17:08:07.671  4768  7735 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 17:08:07.671  4768  4777 D Bluetoothsap: onBluetoothStateChange: up=false
,08-24 17:08:07.671  4768  4777 D Bluetoothsap: Unbinding service...
,08-24 17:08:07.671  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 17:08:07.671  4768  4776 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 17:08:07.671  2650  4336 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:07.671  2650  4336 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:07.671  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-24 17:08:07.671  1018  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:08:07.671  1454  1646 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:07.671  1454  1646 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:07.671  7739  7752 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:07.671  7739  7752 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:08:07.681  1425  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:07.681  1425  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-24 17:08:07.681  1771  2089 D BluetoothAdapter: onBluetoothStateChange: up=false
08-24 17:08:07.681  1771  2089 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-24 17:08:07.681  4768  4777 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 17:08:07.681  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:07.681  1018  1018 I InputMethodManagerService: [BT Setting State] State =10
,08-24 17:08:07.681  1018  1018 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 17:08:07.681  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-24 17:08:07.691  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:07.691  1176  1176 D BluetoothTile:  getBluetoothState : 10
,08-24 17:08:07.691  1018  1487 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:07.691  1018  4333 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:08:07.691  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-24 17:08:07.691  4768  4768 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:07.691  1869  1869 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:07.701  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:07.701  4768  4768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 17:08:07.701  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:07.701  1018  4333 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-24 17:08:07.701  1018  4333 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:08:07.701  1018  4333 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:07.701  1018  4333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:07.701  1018  4333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:08:07.711  2650  2650 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:07.711  4768  4768 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:07.711  4768  4768 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:07.721  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:07.721  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-24 17:08:08.401   291   291 E SMD     : DCD OFF
,08-24 17:08:08.461   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:08:09.451   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,08-24 17:08:09.521  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-24 17:08:09.521  1018  1031 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-24 17:08:09.521  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-24 17:08:09.521  1018  1031 D BatteryService: stay LED for charging
08-24 17:08:09.521  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-24 17:08:09.531  1018  1018 I MotionRecognitionService: Plugged,
,08-24 17:08:09.531  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
,08-24 17:08:09.541  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-24 17:08:09.541  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-24 17:08:09.551  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-24 17:08:09.551  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-24 17:08:09.571  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:08:09.571  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-24 17:08:09.571  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-24 17:08:10.331  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:10.331  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:10.461   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:08:11.401   291   291 E SMD     : DCD OFF,
,08-24 17:08:11.461   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,08-24 17:08:11.671  1018  1096 V AlarmManager: waitForAlarm result :4,
,08-24 17:08:11.671   277  1000 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:08:11.671   277  1000 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,08-24 17:08:11.681  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:11.681  1018  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-24 17:08:11.681  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-24 17:08:12.451   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-24 17:08:13.341  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:13.341  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38417666 added. We now have 6 listener(s)
,08-24 17:08:13.341  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:13.341  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:13.341  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ed6ada7 added. We now have 7 listener(s)
,08-24 17:08:13.341  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:13.341  6932  7162 I System.out: IsBluetoothEnabled
,08-24 17:08:13.341  6932  7162 D BluetoothAdapter: disable()
,08-24 17:08:13.351  1018  4333 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-24 17:08:13.351  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:13.351  6932  7162 D BluetoothAdapter: enable()
,08-24 17:08:13.351  1018  1486 W ActivityManager: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 17:08:13.351  1018  1486 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-24 17:08:13.351  1018  1486 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:08:13.351  1018  1486 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:08:13.351  1018  1486 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-24 17:08:13.351  1018  1486 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-24 17:08:13.351  1018  1486 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-24 17:08:13.351  1018  1486 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-24 17:08:13.361  1018  1486 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:13.361  1018  1486 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:13.361  1018  1486 D SettingsProvider: name = bluetooth_on
,08-24 17:08:13.361  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:13.361  1018  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-24 17:08:13.371  1018  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-24 17:08:13.371  3221  3292 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-24 17:08:13.371  3221  3292 D BluetoothAdapterProperties: Setting state to 11
08-24 17:08:13.371  3221  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-24 17:08:13.371  3221  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:08:13.371  3221  3292 D BluetoothAdapterService: updateAdapterState state is 11
08-24 17:08:13.371  3221  3292 D BluetoothAdapterService: Autoconnection is available 
08-24 17:08:13.371  3221  3292 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-24 17:08:13.371  3221  3292 D BtConfig.SecureMode: isSecureModeOn:false
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:13.371  1018  1507 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:13.371  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevServi,ce
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
08-24 17:08:13.371  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-24 17:08:13.371  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-24 17:08:13.371  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.371  1018  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.371  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.381  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:13.381  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-24 17:08:13.381  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-24 17:08:13.381  3221  3221 D HeadsetService: Received start request. Starting profile...
08-24 17:08:13.381  3221  3221 D HeadsetService: start()
08-24 17:08:13.381  3221  3221 D HeadsetStateMachine: make
,08-24 17:08:13.381  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:13.381  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
,08-24 17:08:13.391  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-24 17:08:13.391  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:13.391  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-24 17:08:13.391  1869  1869 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:13.391  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:13.391  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-24 17:08:13.391  1018  1488 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:13.391  1018  1327 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-24 17:08:13.401  3221  3221 E HeadsetStateMachine: # of Max HF connection is 2
,08-24 17:08:13.401  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-24 17:08:13.401  4768  4768 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:13.401  1018  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:13.401  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.401  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.401  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.401  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.401  1018  1487 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-24 17:08:13.401  1018  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.401  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:13.411  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
08-24 17:08:13.411  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-24 17:08:13.411  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-24 17:08:13.411  1018  1487 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.411  1018  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.411  1018  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 17:08:13.411  1018  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:13.411  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.411  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.411  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.411  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.411  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,08-24 17:08:13.411  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-24 17:08:13.411  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-24 17:08:13.411  1018  1488 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:13.411  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.411  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:13.411  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.411  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.421  1018  1031 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-24 17:08:13.421  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.421  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,08-24 17:08:13.421  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-24 17:08:13.421  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-24 17:08:13.421  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:13.421  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.421  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-24 17:08:13.421  1018  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:13.421  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.421  3221  3221 I bluedroid: get_profile_interface handsfree
,08-24 17:08:13.421  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.421  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.421  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-24 17:08:13.421  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:13.431  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-24 17:08:13.431  3221  3292 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-24 17:08:13.431  2650  2650 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:13.431  1018  1327 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:13.431  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.431  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:13.431  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.431  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.431  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
08-24 17:08:13.431  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-24 17:08:13.431  3221  3292 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-24 17:08:13.441  1018  1507 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:13.441  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.441  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.441  1018  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.441  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.441  3221  3221 E DualScoManager: Dual Sco Manager already instantiated
08-24 17:08:13.441  3221  3221 I DualScoManager: Set HeadsetServiceHelper
08-24 17:08:13.441  3221  3221 D BluetoothAtMessage: createCMTIContentObservers
,08-24 17:08:13.441  4768  4768 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:13.441  1018  4334 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-24 17:08:13.441  1018  4334 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:13.441  1018  4334 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:13.441  1018  4334 D SettingsProvider: selectionArgs: false
08-24 17:08:13.441  1018  4334 D SettingsProvider: selectionArgs: 1002
,08-24 17:08:13.441  1018  4334 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:13.441  1018  4334 D SettingsProvider: ret = -1
08-24 17:08:13.441  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-24 17:08:13.441  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:13.441  3221  7788 D HeadsetStateMachine: Enter Disconnected: -2
08-24 17:08:13.441  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-24 17:08:13.441  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:13.441  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-24 17:08:13.441  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-24 17:08:13.441  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
08-24 17:08:13.451  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-24 17:08:13.451  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-24 17:08:13.451  3221  3292 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
08-24 17:08:13.451  3221  3292 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-24 17:08:13.451  3221  3292 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-24 17:08:13.451  3221  3292 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-24 17:08:13.451  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:13.451  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-24 17:08:13.451  3221  3221 D HeadsetService: mStartError = false
08-24 17:08:13.451  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:13.451  3221  3221 D A2dpService: Received start request. Starting profile...
08-24 17:08:13.451  3221  3221 D A2dpService: start()
08-24 17:08:13.451  3221  3221 I bluedroid: get_profile_interface avrcp
,08-24 17:08:13.451  3221  7788 D HeadsetStateMachine: Clear mHeadsetBrsf
08-24 17:08:13.451  3221  7788 D HeadsetStateMachine: map size, before remove : 0
08-24 17:08:13.451  3221  7788 D HeadsetStateMachine: map size, after remove: 0
,08-24 17:08:13.461  3221  3221 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 17:08:13.461  3221  3221 D Avrcp   : Initialize Media Controller
08-24 17:08:13.461  3221  3221 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-24 17:08:13.461  3221  3221 E Avrcp   : getActiveSessions
08-24 17:08:13.461  3221  3221 D Avrcp   : pick active media Controller
08-24 17:08:13.461  3221  3221 D Avrcp   : Get the active Media Controller 
,08-24 17:08:13.461  3221  3221 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-24 17:08:13.461  3221  7789 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-24 17:08:13.471  3221  3221 D A2dpStateMachine: make
,08-24 17:08:13.471  3221  3221 I bluedroid: get_profile_interface a2dp
,08-24 17:08:13.471  3221  7791 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting,
08-24 17:08:13.471  3221  3221 E bt-btif : warning : media task started media_task_refcnt 1 
,08-24 17:08:13.471  3221  3221 D A2dpService: mStartError = false
08-24 17:08:13.471  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:13.471  3221  3221 D HeadsetStateMachine: Try to query the phonestate on bind
08-24 17:08:13.471  3221  7790 D A2dpStateMachine: Enter Disconnected: -2
,08-24 17:08:13.481  1425  1462 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 17:08:13.481  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-24 17:08:13.481  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-24 17:08:13.481  1425  1462 I Telecom : BluetoothPhoneService: Result of Message : true
,08-24 17:08:13.481  3221  3221 D HidService: Received start request. Starting profile...
08-24 17:08:13.481  3221  3221 D HidService: start()
08-24 17:08:13.481  3221  3221 I bluedroid: get_profile_interface hidhost
08-24 17:08:13.481  3221  3221 D HidService: setHidService(): set to: null
08-24 17:08:13.481  3221  3221 D HidService: mStartError = false
08-24 17:08:13.481  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:13.481  3221  3221 D HeadsetStateMachine: Proxy object connected
,08-24 17:08:13.481  3221  3221 D HealthService: Received start request. Starting profile...
08-24 17:08:13.481  3221  3221 D HealthService: start()
,08-24 17:08:13.481  3221  7789 D BluetoothMediaBrowser: no now playing list
08-24 17:08:13.481  3221  7789 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-24 17:08:13.481  3221  3221 I bluedroid: get_profile_interface health
08-24 17:08:13.481  3221  3221 D HealthService: mStartError = false
08-24 17:08:13.481  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:13.481  3221  3221 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-24 17:08:13.481  3221  7788 D HeadsetStateMachine: Disconnected process message: 11
08-24 17:08:13.481  3221  3221 D PanService: Received start request. Starting profile...
,08-24 17:08:13.481  3221  3221 D PanService: start()
08-24 17:08:13.481  3221  3221 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 17:08:13.481  3221  3221 I bluedroid: get_profile_interface pan
08-24 17:08:13.481  3221  3221 D PanService: mStartError = false
08-24 17:08:13.481  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:13.481  3221  3221 D BluetoothMapService: Received start request. Starting profile...
08-24 17:08:13.481  3221  3221 D BluetoothMapService: start()
,08-24 17:08:13.491  3221  3221 D BluetoothMapService: mStartError = false
08-24 17:08:13.491  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:13.491  3221  3221 D HeadsetPhoneState: sendDeviceDataStateChanged
08-24 17:08:13.491  3221  3221 D HeadsetPhoneState: Signal level : previous=0 curr=4
08-24 17:08:13.491  3221  7788 D HeadsetStateMachine: Disconnected process message: 18
,08-24 17:08:13.491  3221  3221 D SapService: Received start request. Starting profile...
,08-24 17:08:13.491  3221  3221 D SapService: start()
08-24 17:08:13.491  3221  3221 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-24 17:08:13.491  3221  3221 I bluedroid: get_profile_interface sap
08-24 17:08:13.491  3221  3221 D SapService: mStartError = false
08-24 17:08:13.491  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
08-24 17:08:13.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-24 17:08:13.491  3221  3221 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-24 17:08:13.491  3221  7788 D HeadsetStateMachine: Disconnected process message: 10
,08-24 17:08:13.491  3221  7788 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 17:08:13.491  3221  7788 D HeadsetStateMachine: Disconnected process message: 11
08-24 17:08:13.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-24 17:08:13.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-24 17:08:13.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true,
,08-24 17:08:13.491  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-24 17:08:13.501  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-24 17:08:13.501  3221  3221 E BluetoothAdapterService(847596021): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true,
,08-24 17:08:13.511  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-24 17:08:13.511  3221  3292 I bluedroid: enable
,08-24 17:08:13.511  3221  3295 E bt-btif : Calling BTA_HhEnable
08-24 17:08:13.511  3221  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 17:08:13.511  3221  3295 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
08-24 17:08:13.511  3221  3295 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-24 17:08:13.511  3221  3295 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
08-24 17:08:13.511  3221  3295 E BluetoothServiceJni: populateRssiValuesNative
08-24 17:08:13.511  3221  3295 I bluedroid: getModelRssiValues
08-24 17:08:13.511  3221  3295 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-24 17:08:13.511  3221  3295 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-24 17:08:13.511  3221  3295 D BluetoothAdapterProperties: Name is: Galaxy A3
,08-24 17:08:13.511  1018  1018 D SettingsProvider: name = bluetooth_name
,08-24 17:08:13.521  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:13.521  3221  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-24 17:08:13.521  3221  3295 D BluetoothAdapterProperties: Scan Mode:20
08-24 17:08:13.521  3221  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:08:13.521  3221  3295 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
08-24 17:08:13.521  3221  3295 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
08-24 17:08:13.521  3221  3295 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,08-24 17:08:13.521  3221  3295 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-24 17:08:13.521  3221  3295 E bt-btif : JVenable fails
,08-24 17:08:13.521  3221  3295 D bte_conf: Device ID record 1 : primary
08-24 17:08:13.521  3221  3295 D bte_conf:   vendorId            = 0075
08-24 17:08:13.521  3221  3295 D bte_conf:   vendorIdSource      = 0001
08-24 17:08:13.521  3221  3295 D bte_conf:   product             = 0100
08-24 17:08:13.521  3221  3295 D bte_conf:   version             = 0200
08-24 17:08:13.521  3221  3295 D bte_conf:   clientExecutableURL = 
08-24 17:08:13.521  3221  3295 D bte_conf:   serviceDescription  = 
08-24 17:08:13.521  3221  3295 D bte_conf:   documentationURL    = 
08-24 17:08:13.521  3221  3295 D bte_conf: bte_load_did_conf no section named DID2.
,08-24 17:08:13.521  3221  3295 E bt-btif : BTM_SEC_REG[14]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
08-24 17:08:13.521  3221  3295 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 17:08:13.521  3221  3292 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-24 17:08:13.521  3221  3292 D BluetoothAdapterProperties: ScanMode =  20
08-24 17:08:13.521  3221  3292 D BluetoothAdapterProperties: State =  11
,08-24 17:08:13.521  1018  1487 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-24 17:08:13.521  3221  3292 D BluetoothAdapterProperties: Setting state to 12
08-24 17:08:13.521  3221  3292 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-24 17:08:13.521  3221  3295 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-24 17:08:13.521  3221  3295 D BluetoothAdapterProperties: Scan Mode:21
,08-24 17:08:13.531  1018  1486 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-24 17:08:13.531  1018  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-24 17:08:13.531  1018  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-24 17:08:13.531  1018  1486 D SettingsProvider: selectionArgs: false
08-24 17:08:13.531  1018  1486 D SettingsProvider: selectionArgs: 1002
08-24 17:08:13.531  1018  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-24 17:08:13.531  1018  1486 D SettingsProvider: ret = -1
,08-24 17:08:13.531  3221  3295 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 17:08:13.531  3221  3292 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-24 17:08:13.531  3221  3292 D BluetoothAdapterService: updateAdapterState state is 12
,08-24 17:08:13.531  1018  4333 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:13.531  1018  4333 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.531  1018  4333 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:13.531  1018  4333 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.531  1018  4333 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.531  3221  3292 D BluetoothAdapterService: Autoconnection is available 
,08-24 17:08:13.541  3221  3292 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-24 17:08:13.541  3221  3292 D BluetoothAdapterService: starting service from this receiver
08-24 17:08:13.541  3221  7777 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:13.541  1018  1501 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-24 17:08:13.541  1018  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.541  3221  7777 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:13.541  1018  1501 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.541  1018  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.541  1018  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.541  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:13.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:13.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:13.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:13.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:13.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:13.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:13.541  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:13.541  1018  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-24 17:08:13.541  3221  3292 I BluetoothAdapterState: Entering On State from state = 11
,08-24 17:08:13.541  3221  3221 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-24 17:08:13.541  3221  3221 I BluetoothPbapService: Handler(): got msg=1
,08-24 17:08:13.541  1018  1562 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-24 17:08:13.541  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.541  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.541  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.541  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.551  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:13.551  3221  7796 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-24 17:08:13.551  1454  3328 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:13.551  1018  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-24 17:08:13.551  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:13.551  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.551  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.551  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.561  1454  3328 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:13.561  1440  6415 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.561  1440  6415 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.561  4768  4777 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 17:08:13.561  3221  3221 D BluetoothA2dp: Proxy object connected
,08-24 17:08:13.561  3221  3221 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-24 17:08:13.561  3221  7796 D BluetoothSocket: bindListen(): myUserId = 0
08-24 17:08:13.561  3221  7796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:13.561  3221  7796 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-24 17:08:13.561  3221  7796 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:13.561  3221  7796 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:08:13.561  3221  7796 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a4de2c5
08-24 17:08:13.561  3221  7796 D BluetoothSocket: channel: 19
,08-24 17:08:13.561  3221  7796 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-24 17:08:13.701  1018  1047 I art     : Explicit concurrent mark sweep GC freed 56896(3MB) AllocSpace objects, 7(113KB) LOS objects, 33% free, 22MB/34MB, paused 2.281ms total 140.370ms
08-24 17:08:13.701  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-24 17:08:13.701  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.701  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.701  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.701  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.701  4768  4768 D BluetoothPbap: Proxy object connected
08-24 17:08:13.701  4768  4776 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.701  4768  4776 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.701  3221  7266 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.701  4768  4768 D PbapServerProfile: Bluetooth service connected
08-24 17:08:13.701  3221  7266 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.711  1018  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-24 17:08:13.711  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:13.711  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-24 17:08:13.711  1018  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:13.711  1425  7734 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:13.711  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:13.711  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:13.711  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.711  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.711  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.711  1425  7734 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:13.711  1176  1207 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.711  1176  1207 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.711  6932  6944 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.711  6932  6944 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.711  4768  7735 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:13.711  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:13.711  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:13.711  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.711  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.711  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.711  4768  7735 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 17:08:13.721  4768  4768 D HeadsetProfile: Bluetooth service connected
,08-24 17:08:13.721  4768  4777 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-24 17:08:13.721  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-24 17:08:13.721  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.721  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.721  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.721  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.721  4768  4768 D BluetoothInputDevice: Proxy object connected
,08-24 17:08:13.721  4768  4768 D HidProfile: Bluetooth service connected
08-24 17:08:13.721  1425  1462 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:13.721  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:13.721  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-24 17:08:13.721  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.721  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.721  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.721  1425  1462 E BluetoothHeadset: BluetoothHeadset service is binded
,08-24 17:08:13.721  4768  7735 D Bluetoothsap: onBluetoothStateChange: up=true
08-24 17:08:13.721  4768  7735 D Bluetoothsap: Binding service...
,08-24 17:08:13.731  4768  7735 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-24 17:08:13.731  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-24 17:08:13.731  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.731  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:13.731  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.731  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.731  4768  7735 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-24 17:08:13.731  1018  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 17:08:13.731  1018  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-24 17:08:13.731  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-24 17:08:13.731  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.731  4768  4777 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 17:08:13.731  1018  1018 D BluetoothA2dp: Proxy object connected
,08-24 17:08:13.731  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-24 17:08:13.731  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.731  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.731  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.731  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.731  2650  5361 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.731  2650  5361 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.731  4768  4768 D Bluetoothsap: BluetoothSAP Proxy object connected
08-24 17:08:13.731  1018  1047 D BluetoothPan: Binding service...
08-24 17:08:13.731  4768  4768 D SapProfile: Bluetooth service connected
08-24 17:08:13.731  4768  4768 D Bluetoothsap: getConnectedDevices()
08-24 17:08:13.731  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-24 17:08:13.731  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.741  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 17:08:13.741  1425  7734 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-24 17:08:13.741  4768  4768 D BluetoothMap: Proxy object connected
,08-24 17:08:13.741  4768  4768 D MapProfile: Bluetooth service connected
08-24 17:08:13.741  4768  4768 D BluetoothMap: getConnectedDevices(),
08-24 17:08:13.741  1018  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-24 17:08:13.741  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3,
08-24 17:08:13.741  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.741  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.741  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.741  1425  7734 E BluetoothHeadset: BluetoothHeadset service is binded
08-24 17:08:13.741  4768  4776 D BluetoothPan: Binding service...
,08-24 17:08:13.741  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan,
08-24 17:08:13.741  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.741  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.741  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.741  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-24 17:08:13.741  1018  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.741  1018  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.741  4768  4768 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 17:08:13.741  4768  4768 D PanProfile: Bluetooth service connected
08-24 17:08:13.741  1454  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:13.741  1454  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.741  7739  7750 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.741  7739  7750 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.741  1425  1462 D BluetoothAdapter: onBluetoothStateChange: up=true
08-24 17:08:13.741  1425  1462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.751  1771  1784 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-24 17:08:13.751  1771  1784 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-24 17:08:13.751  4768  4776 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 17:08:13.751  4768  4776 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-24 17:08:13.751  1018  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-24 17:08:13.751  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-24 17:08:13.751  1018  1047 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:13.751  1018  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.751  1018  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.751  4768  4768 D BluetoothA2dp: Proxy object connected
08-24 17:08:13.751  1018  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-24 17:08:13.751  1018  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-24 17:08:13.751  4768  4768 D A2dpProfile: Bluetooth service connected
,08-24 17:08:13.751  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:13.751  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
08-24 17:08:13.751  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-24 17:08:13.761  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-24 17:08:13.761  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:13.761  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-24 17:08:13.761  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:13.761  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:13.761  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-24 17:08:13.771  1425  1425 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3411e389, true
,08-24 17:08:13.771  1176  1754 D BluetoothTile:  handleUpdatestate:false name:null
,08-24 17:08:13.771  1018  1137 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:13.771  1425  1425 D BluetoothHeadset: registerMessageListener
,08-24 17:08:13.771  1018  1031 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-24 17:08:13.771  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-24 17:08:13.771  1869  1869 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-24 17:08:13.781  4768  4768 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-24 17:08:13.781  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:13.781  3221  3231 D HeadsetService: registerMessageListener
,08-24 17:08:13.781  3221  3231 D HeadsetService: registerMessageListener
,08-24 17:08:13.781  3221  7788 D HeadsetStateMachine: Disconnected process message: 70
08-24 17:08:13.781  3221  7788 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@279fc41a
,08-24 17:08:13.781  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-24 17:08:13.781  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-24 17:08:13.781  4768  4768 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-24 17:08:13.781  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-24 17:08:13.781  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-24 17:08:13.781  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-24 17:08:13.791  4768  4768 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-24 17:08:13.791  4768  4768 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-24 17:08:13.791  4768  4768 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-24 17:08:13.791  3221  7797 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-24 17:08:13.791  3221  7788 D HeadsetStateMachine: Disconnected process message: 9
08-24 17:08:13.791  3221  7788 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-24 17:08:13.791   285   285 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-24 17:08:13.791   285   285 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-24 17:08:13.791   285   285 V voice   : voice_set_parameters: exit with code(-2)
08-24 17:08:13.791   285   285 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-24 17:08:13.791   285   285 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-24 17:08:13.791   285   285 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-24 17:08:13.791   285   285 V audio_hw_primary: adev_set_parameters: exit
08-24 17:08:13.791  3221  7788 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-24 17:08:13.791  3221  7797 D BluetoothSocket: bindListen(): myUserId = 0
,08-24 17:08:13.791  3221  7797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:13.791  3221  7797 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,08-24 17:08:13.791  3221  7797 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:13.801  3221  7797 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-24 17:08:13.801  3221  7797 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12e29b4b
08-24 17:08:13.801  3221  7797 D BluetoothSocket: channel: 5
,08-24 17:08:13.801  4768  4768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
,08-24 17:08:13.801  1018  1486 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-24 17:08:13.801  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.801  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:13.801  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.801  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-24 17:08:13.811  2650  2650 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 17:08:13.811  4768  4768 D DockEventReceiver: finishStartingService: stopping service
,08-24 17:08:13.811  4768  4768 D BluetoothNotiBroadcastReceiver: onReceive
,08-24 17:08:13.821  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-24 17:08:13.821  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-24 17:08:13.821  3221  3221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328549f5
,08-24 17:08:13.821  3221  3221 D BtConfig.SecureMode: isSecureModeOn:false
,08-24 17:08:13.821  1018  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-24 17:08:13.821  1018  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-24 17:08:13.831  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:13.831  1018  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:13.831  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-24 17:08:13.831  1018  1501 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-24 17:08:13.851  3221  7802 D BluetoothSocket: bindListen(): myUserId = 0
08-24 17:08:13.851  3221  7802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 17:08:13.851  3221  7802 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[86]}
08-24 17:08:13.851  3221  7802 D BluetoothSocket: bindListen(), new LocalSocket 
08-24 17:08:13.851  3221  7802 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-24 17:08:13.851  3221  7802 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@203da127
,08-24 17:08:13.851  3221  7802 D BluetoothSocket: channel: 12
08-24 17:08:13.851  3221  7802 I BtOppRfcommListener: Accept thread started.
,08-24 17:08:14.381  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:14.381  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:14.381  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:14.381  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 17:08:14.381  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:14.381  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:14.381  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:14.381  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:14.381  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:14.381  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:14.381  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b0254 added. We now have 8 listener(s)
08-24 17:08:14.381  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:14.381  1018  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 17:08:14.381  1018  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-24 17:08:14.381  1018  1030 D SecContentProvider2: mCursor = null
,08-24 17:08:14.381  1018  1030 D WifiService: setWifiEnabled: false pid=6932, uid=10170
,08-24 17:08:14.391  1018  1030 D SettingsProvider: name = wifi_on
,08-24 17:08:14.391  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:14.391  1018  4327 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-24 17:08:14.391  1018  4327 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-24 17:08:14.391  1018  4327 D SecContentProvider2: mCursor = null
,08-24 17:08:14.401  1018  4327 D WifiService: setWifiEnabled: true pid=6932, uid=10170
,08-24 17:08:14.401  1018  4327 W ActivityManager: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,08-24 17:08:14.401  1018  4327 W WifiService: Failed getting userId using ActivityManagerNative
08-24 17:08:14.401  1018  4327 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6932, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
08-24 17:08:14.401  1018  4327 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-24 17:08:14.401  1018  4327 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-24 17:08:14.401  1018  4327 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-24 17:08:14.401  1018  4327 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-24 17:08:14.401  1018  4327 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-24 17:08:14.401   291   291 E SMD     : DCD OFF
,08-24 17:08:14.401  1018  4327 D SettingsProvider: name = wifi_on
,08-24 17:08:14.411  1018  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-24 17:08:14.751  1018  1045 D Tethering: interfaceAdded wlan0
,08-24 17:08:14.761  1018  1132 E Tethering: No numeric data
,08-24 17:08:14.761  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 17:08:14.761  1018  1132 D Tethering: clearTetheredNotification()
,08-24 17:08:14.771  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:14.771  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-24 17:08:14.771  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-24 17:08:14.771  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:14.771  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,08-24 17:08:14.771  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-24 17:08:14.771  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:14.771  1176  1176 D HotspotTile: updateTetherState():false, false
08-24 17:08:14.771  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:08:14.771  1018  1124 V NetworkStats: performPollLocked() took 9ms
08-24 17:08:14.771  1018  1132 D Tethering: InitialState.processMessage what=4
08-24 17:08:14.771  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:14.781  1018  1132 E Tethering: No numeric data
,08-24 17:08:14.781  1018  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-24 17:08:14.781  1018  1132 D Tethering: clearTetheredNotification()
,08-24 17:08:14.781  1018  1045 D Tethering: interfaceAdded p2p0
,08-24 17:08:14.781  1018  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-24 17:08:14.781  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-24 17:08:14.781  1176  1176 D HotspotTile: updateTetherState():false, false
,08-24 17:08:14.781  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:14.781  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:14.781  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-24 17:08:14.791  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:08:14.791  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-24 17:08:14.791  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-24 17:08:14.791  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:08:14.791  1018  1045 D Tethering: interfaceStatusChanged p2p0, false,
08-24 17:08:14.791  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:08:14.791  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:14.791  1018  1124 V NetworkStats: performPollLocked() took 9ms
,08-24 17:08:14.791  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:14.791  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:14.801   277  1004 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-24 17:08:14.801   277  1004 D SoftapController: Softap fwReload - Ok
,08-24 17:08:14.801   277  1004 D CommandListener: Setting iface cfg
08-24 17:08:14.801   277  1004 D CommandListener: Trying to bring down wlan0
,08-24 17:08:14.801   277  1004 D CommandListener: Clearing all IP addresses on wlan0
,08-24 17:08:14.811  1018  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-24 17:08:14.851  7815  7815 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-24 17:08:14.851  7815  7815 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-24 17:08:14.851  7815  7815 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-24 17:08:14.871  7815  7815 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-24 17:08:14.871   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7815,
08-24 17:08:14.871   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-24 17:08:14.871  7815  7815 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-24 17:08:14.871  7815  7815 I wpa_supplicant: ssSupport state is = 1
08-24 17:08:14.871  7815  7815 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-24 17:08:14.871  7815  7815 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
,08-24 17:08:14.871   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7815
08-24 17:08:14.871   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-24 17:08:14.921  1018  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-24 17:08:14.931  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:14.931  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:14.931  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-24 17:08:14.931  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:14.931  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.931  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.931  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:14.931  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:14.931  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-24 17:08:14.931  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-24 17:08:14.931  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-24 17:08:14.941  4768  4768 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:14.941  1176  1176 D HotspotTile: onReceive : 2, 0
,08-24 17:08:14.941  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:14.941  1018  1562 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-24 17:08:14.941  1018  1562 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:14.941  1018  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-24 17:08:14.941  1018  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:14.941  1018  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:14.951  1636  1636 I Hs20UtilService: Starting #19
,08-24 17:08:14.951  1636  1665 I Hs20UtilService: Message received 5011
,08-24 17:08:14.951  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-24 17:08:14.951  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:08:14.951  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
,08-24 17:08:14.951  7088  7088 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-24 17:08:15.041   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-24 17:08:15.041  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-24 17:08:15.081  7815  7815 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-24 17:08:15.081  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-24 17:08:15.091  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-24 17:08:15.091   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7815
08-24 17:08:15.091   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-24 17:08:15.101  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-24 17:08:15.101  7815  7815 I wpa_supplicant: ssSupport state is = 1
,08-24 17:08:15.101  7815  7815 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:15.101  7815  7815 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:08:15.101  7815  7815 E wpa_supplicant: SIM READ ERROR,
08-24 17:08:15.101  7815  7815 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:15.101  7815  7815 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:08:15.101  7815  7815 E wpa_supplicant: SIM READ ERROR,
08-24 17:08:15.101  7815  7815 I wpa_supplicant: Blacklist: Clear (all) 
08-24 17:08:15.101  7815  7815 I wpa_supplicant: wpa_default_ap_write_once
08-24 17:08:15.101  7815  7815 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-24 17:08:15.101  7815  7815 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:15.101  7815  7815 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-24 17:08:15.101  7815  7815 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
,08-24 17:08:15.101  7815  7815 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-24 17:08:15.101  7815  7815 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-24 17:08:15.111  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:15.111  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
08-24 17:08:15.111  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:15.261  7815  7815 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-24 17:08:15.431  7815  7815 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-24 17:08:15.431  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-24 17:08:15.441  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-24 17:08:15.441   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7815
08-24 17:08:15.441   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-24 17:08:15.441  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-24 17:08:15.441  7815  7815 I wpa_supplicant: ssSupport state is = 1
08-24 17:08:15.441  7815  7815 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-24 17:08:15.441  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-24 17:08:15.461  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-24 17:08:15.461   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7815
08-24 17:08:15.461   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-24 17:08:15.461  7815  7815 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-24 17:08:15.461  7815  7815 I wpa_supplicant: ssSupport state is = 1
08-24 17:08:15.461  7815  7815 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:15.461  7815  7815 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-24 17:08:15.461  7815  7815 E wpa_supplicant: SIM READ ERROR
08-24 17:08:15.461  7815  7815 I wpa_supplicant: wpa_default_ap_write_once
08-24 17:08:15.461  7815  7815 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-24 17:08:15.461  7815  7815 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-24 17:08:15.461  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:08:15.471  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-24 17:08:15.461  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-24 17:08:15.471  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-24 17:08:15.471  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
08-24 17:08:15.471  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:08:15.511  7815  7815 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-24 17:08:15.511  7815  7815 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-24 17:08:15.551  7815  7815 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-24 17:08:15.551  7815  7815 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-24 17:08:15.551  7815  7815 I wpa_supplicant: Skip scan - bUseNetwork false
,08-24 17:08:15.561  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-24 17:08:15.561  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-24 17:08:15.561  7815  7815 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-24 17:08:15.561  7815  7815 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-24 17:08:15.561  7815  7815 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-24 17:08:15.571  7815  7815 E wpa_supplicant: SIM READ ERROR
08-24 17:08:15.571  7815  7815 I wpa_supplicant: Blacklist: Clear (all) 
,08-24 17:08:15.581  7815  7815 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-24 17:08:15.591  7815  7815 I wpa_supplicant: Skip scan - bUseNetwork false,
08-24 17:08:15.591  1018  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-24 17:08:15.601  4768  4768 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-24 17:08:15.601  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:15.601  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:15.601  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:15.601  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.601  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.601  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:15.601  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:15.601  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:15.601  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-24 17:08:15.601  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-24 17:08:15.601  1176  1754 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-24 17:08:15.611  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:15.611  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:15.611  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:15.611  1176  1176 D HotspotTile: onReceive : 3, 0
,08-24 17:08:15.611  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:15.611  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:15.611  1636  1636 I Hs20UtilService: Starting #20
,08-24 17:08:15.611  1018  1127 E WifiConfigStore: Not a HS20
,08-24 17:08:15.611  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 17:08:15.611  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:15.611  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:15.611  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:15.611  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:15.611  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:15.611  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:15.611  6932  6932 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:15.611  1018  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-24 17:08:15.611  1636  1665 I Hs20UtilService: Message received 5011
,08-24 17:08:15.621  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-24 17:08:15.621  7088  7088 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-24 17:08:15.621  7088  7088 D SecurityLogAgent: StateMachine : Current State = 1
08-24 17:08:15.621  7088  7088 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-24 17:08:15.621  1018  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-24 17:08:15.621  7815  7815 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-24 17:08:15.621  7815  7815 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-24 17:08:15.621  7815  7815 I wpa_supplicant: reset timer : RESET_TIMER 0
08-24 17:08:15.621  7815  7815 I wpa_supplicant: P2P: Current p2p state = IDLE
08-24 17:08:15.621  7815  7815 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-24 17:08:15.621  7815  7815 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-24 17:08:15.621  7815  7815 I wpa_supplicant: First Scan Start
,08-24 17:08:15.621  7815  7815 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-24 17:08:15.621  6932  6932 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-24 17:08:15.621  1018  1127 D WifiNative-wlan0: Setting external_sim to 1
08-24 17:08:15.621  1018  1127 D WifiStateMachine: Setting OUI to DA-A1-19
,08-24 17:08:15.621  1018  1127 I WifiNative-HAL: startHal
08-24 17:08:15.621  1018  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9ecb388c
08-24 17:08:15.621  1018  1127 I WifiNative-HAL: Could not start hal
,08-24 17:08:15.621  1018  1127 E WifiNative-wlan0: do suspend true
08-24 17:08:15.621  1018  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-24 17:08:15.631  1018  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-24 17:08:15.631  7289  7289 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 17:08:15.631   277  1004 D CommandListener: Setting iface cfg,
08-24 17:08:15.631   277  1004 D CommandListener: Trying to bring up p2p0,
08-24 17:08:15.631  1018  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 17:08:15.631  1018  1126 D WifiP2pService: P2pEnablingState
08-24 17:08:15.631  1018  1018 D WifiScanningService: SCAN_AVAILABLE : 3
08-24 17:08:15.631  1018  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-24 17:08:15.631  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 17:08:15.631  1018  1126 D WifiP2pService: P2p socket connection successful
08-24 17:08:15.631  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 17:08:15.631  1018  1126 D WifiP2pService: P2pEnabledState
08-24 17:08:15.631  1018  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:08:15.631  1018  1127 E WifiNative-wlan0: invaild command id : 215,
08-24 17:08:15.631  1018  1152 I WifiNative-HAL: startHal
08-24 17:08:15.631  1018  1152 E wifi    : getStaticLongField sWifiHalHandle 0x993469bc
08-24 17:08:15.631  1018  1152 I WifiNative-HAL: Could not start hal
08-24 17:08:15.631  1018  1152 E WifiScanningService: could not start HAL
08-24 17:08:15.631  1018  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-24 17:08:15.631  1018  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-24 17:08:15.631  1018  1127 E WifiNative-wlan0: invaild command id : 215
08-24 17:08:15.631  1018  1018 D RttService: SCAN_AVAILABLE : 3
08-24 17:08:15.631  1018  1153 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler },
,08-24 17:08:15.631  7815  7815 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-24 17:08:15.641  1018  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-24 17:08:15.641  7815  7815 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-24 17:08:15.641  7815  7815 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-24 17:08:15.641  1018  1127 E WifiStateMachine: Failed to set frequency band 0
08-24 17:08:15.641  1018  1129 E ConnectivityService: updateNetworkInfo()
,08-24 17:08:15.641  1018  1018 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-24 17:08:15.641  1018  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-24 17:08:15.641  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:15.641  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:08:15.641  1018  1127 D SecContentProvider2: mCursor = null
08-24 17:08:15.641  1018  1048 D WifiDisplayController: disconnect
08-24 17:08:15.641  1018  1048 D WifiDisplayController: updateConnection
08-24 17:08:15.641  1018  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-24 17:08:15.641  1018  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:08:15.641  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-24 17:08:15.641  1018  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
08-24 17:08:15.651  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-24 17:08:15.651  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:08:15.651  1018  1126 D WifiP2pService: DeviceAddress: 0a:75:42
08-24 17:08:15.651  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-24 17:08:15.651  1018  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-24 17:08:15.651  1018  1048 D WifiDisplayAdapter: onP2pDisconnected
08-24 17:08:15.651  1018  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-24 17:08:15.651  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:15.651  1018  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
08-24 17:08:15.651  1018  1127 D SecContentProvider2: mCursor = null
08-24 17:08:15.651  1018  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  secondary type: null
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  wps: 0
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  grpcapab: 0
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  devcapab: 0
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  status: 3
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  wfdInfo: null
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  groupownerAddress: null
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  GOdeviceName: null
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  interfaceAddress: 
08-24 17:08:15.651  1018  1048 D WifiDisplayController:  SConnectInfo : null
,08-24 17:08:15.651  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:08:15.651  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:08:15.651  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-24 17:08:15.651  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-24 17:08:15.651  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-24 17:08:15.651  1018  1563 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-24 17:08:15.651  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-24 17:08:15.651  7656  7656 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:08:15.651  7656  7656 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-24 17:08:15.651  7656  7656 D FileShare-Client: Outbound.stopDelayTimer - 
,08-24 17:08:15.661  7329  7329 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-24 17:08:15.671  1018  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-24 17:08:15.671  1018  1126 D WifiP2pService: InactiveState
,08-24 17:08:15.671  1018  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-24 17:08:15.671  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 17:08:15.671  7815  7815 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-24 17:08:15.671  1018  1126 D WifiP2pService: InactiveState{ what=143376 },
08-24 17:08:15.671  1018  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-24 17:08:15.741  1018  3386 D SSRM:n  : SIOP:: AP = 340,
,08-24 17:08:15.771  1018  1045 D Tethering: interfaceLinkStateChanged p2p0, false,
08-24 17:08:15.771  1018  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-24 17:08:15.771  1018  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-24 17:08:16.431  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-24 17:08:16.431  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:16.431  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:16.431  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:16.431  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:16.431  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:16.431  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:16.431  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:16.431  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:16.441  6932  7162 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-24 17:08:16.441  6932  7162 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-24 17:08:16.441  6932  7162 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1a2b2beb Bundle[{}]
,08-24 17:08:16.441  6932  7162 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 17:08:16.441  6932  7162 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 17:08:16.441  6932  7162 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-24 17:08:16.441  6932  7162 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-24 17:08:16.441  6932  7162 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 17:08:16.451  6932  7162 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 17:08:16.451  6932  7162 I System.out: Running OutgoingSocketThread
,08-24 17:08:16.451  6932  7824 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1400)
08-24 17:08:16.451  6932  7824 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 52993
08-24 17:08:16.451  6932  7824 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 17:08:16.901  7815  7815 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
08-24 17:08:16.901  7815  7815 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-24 17:08:16.901  7815  7815 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-24 17:08:16.901  7815  7815 I wpa_supplicant: Trying to associate with  'G700'
08-24 17:08:16.901  7815  7815 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-24 17:08:16.901  7815  7815 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-24 17:08:16.901  1018  7821 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-24 17:08:16.911  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:16.911  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:17.011  7815  7815 E wpa_supplicant: Cmd 35605 not handled
,08-24 17:08:17.011  7815  7815 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-24 17:08:17.011  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-24 17:08:17.011  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-24 17:08:17.011  7815  7815 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-24 17:08:17.011  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-24 17:08:17.021  7815  7815 I wpa_supplicant: Associated with F4.99.3E
,08-24 17:08:17.021  7815  7815 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 17:08:17.021  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 17:08:17.021  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-24 17:08:17.021  1018  1045 D Tethering: interfaceStatusChanged wlan0, false,
,08-24 17:08:17.021  7815  7815 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-24 17:08:17.021  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-24 17:08:17.021  7815  7815 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-24 17:08:17.021  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-24 17:08:17.021  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,08-24 17:08:17.021  1018  1045 D Tethering: interfaceStatusChanged wlan0, false
08-24 17:08:17.021  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-24 17:08:17.021  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
,08-24 17:08:17.031  1018  1132 E Tethering: No numeric data,
08-24 17:08:17.031  1018  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-24 17:08:17.031  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:17.031  1018  1132 D Tethering: clearTetheredNotification()
08-24 17:08:17.031  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-24 17:08:17.031  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:17.031  1176  1176 D HotspotTile: updateTetherState():false, false
08-24 17:08:17.031  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:17.031  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:17.031  1018  1124 V NetworkStats: performPollLocked() took 5ms
08-24 17:08:17.031  7815  7815 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-24 17:08:17.031  7815  7815 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-24 17:08:17.031  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:17.031  7815  7815 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-24 17:08:17.031  7815  7815 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-24 17:08:17.031  7815  7815 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-24 17:08:17.031  7815  7815 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-24 17:08:17.041  7815  7815 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=],
08-24 17:08:17.041  7815  7815 I wpa_supplicant: Blacklist: Clear (temp) 
,08-24 17:08:17.041  7815  7815 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-24 17:08:17.041  1018  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-24 17:08:17.041  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:17.041  1018  1127 D SecContentProvider2: mCursor = null
08-24 17:08:17.041  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:17.041  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:17.041  1018  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-24 17:08:17.041  1018  1045 D Tethering: interfaceStatusChanged wlan0, true
08-24 17:08:17.041  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-24 17:08:17.041  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:17.051  1018  1127 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-24 17:08:17.051  1018  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-24 17:08:17.061  1018  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-24 17:08:17.061  1018  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false,
08-24 17:08:17.061  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:08:17.061  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:08:17.061  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 17:08:17.061  1018  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:17.061  1018  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:17.061  1018  1488 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:17.061  1018  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-24 17:08:17.061  1018  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:08:17.061  1636  1636 I Hs20UtilService: Starting #21
,08-24 17:08:17.061  1636  1665 I Hs20UtilService: Message received 5007
08-24 17:08:17.061  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:08:17.061  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:17.061  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:17.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:17.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:17.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:17.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:17.071  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-24 17:08:17.071  1018  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 17:08:17.071  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:08:17.071  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,08-24 17:08:17.071  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-24 17:08:17.071  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-24 17:08:17.071  4768  4768 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-24 17:08:17.081  4768  4843 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-24 17:08:17.081   277  1004 D CommandListener: Setting iface cfg,
,08-24 17:08:17.081  1018  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-24 17:08:17.091  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-24 17:08:17.091  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:17.101  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:17.101  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:17.101  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 17:08:17.101  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:17.101  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:17.101  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:17.101  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-24 17:08:17.101  1018  1127 E WifiNative-wlan0: do suspend false
,08-24 17:08:17.101  1018  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-24 17:08:17.101  1018  1127 D SecContentProvider2: mCursor = null
,08-24 17:08:17.111  1018  1126 D WifiP2pService: InactiveState{ what=143375 }
08-24 17:08:17.111  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-24 17:08:17.321  7827  7827 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-24 17:08:17.321  7827  7827 I dhcpcd  : version 5.5.6 starting
,08-24 17:08:17.331  7827  7827 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-24 17:08:17.381  7827  7827 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-24 17:08:17.381  7827  7827 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-24 17:08:17.381  7827  7827 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-24 17:08:17.381  7827  7827 I dhcpcd  : bssid match
08-24 17:08:17.381  7827  7827 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,08-24 17:08:17.411   291   291 E SMD     : DCD OFF,
,08-24 17:08:17.451  6932  7162 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1401)
08-24 17:08:17.451  6932  7162 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1401)
,08-24 17:08:17.461  6932  7162 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1406)
,08-24 17:08:17.461  6932  7162 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-24 17:08:17.461  6932  7162 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1407)
08-24 17:08:17.461  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-24 17:08:17.461  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@100dc5fd added. We now have 2 listener(s)
,08-24 17:08:17.471  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 17:08:17.471  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 17:08:17.471  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-24 17:08:17.471  7827  7827 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
08-24 17:08:17.471  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:17.471  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de92f2 added. We now have 9 listener(s)
08-24 17:08:17.471  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:17.471  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:17.481  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:17.481  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:17.481  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:17.481  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:17.481  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:17.481  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:17.481  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:17.481  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:17.481  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:17.481  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:17.481  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 17:08:17.481  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:17.481  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aafefc0 added. We now have 3 listener(s)
,08-24 17:08:17.481  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-24 17:08:17.491  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1675c4f9 added. We now have 10 listener(s)
08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:17.491  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:17.491  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:17.491  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:17.491  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@100dc5fd removed from the list
,08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de92f2 removed from the list
08-24 17:08:17.491  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:17.491  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-24 17:08:17.491  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26de92f2 not in the list,
08-24 17:08:17.491  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1675c4f9 removed from the list,
08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:17.491  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:17.491  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aafefc0 removed from the list
08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3beec3e added. We now have 2 listener(s)
08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:17.491  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:17.491  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:17.501  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a39aa9f added. We now have 9 listener(s)
08-24 17:08:17.501  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:17.501  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 17:08:17.501  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:17.501  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:17.501  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:17.501  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:17.501  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:17.501  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:17.501  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:17.501  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:17.501  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 17:08:17.501  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:17.501  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:17.511  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:17.511  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc4b7b5 added. We now have 3 listener(s)
,08-24 17:08:17.511  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 17:08:17.511  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:17.511  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 17:08:17.511  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:17.511  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:17.511  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:17.511  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab98e4a added. We now have 10 listener(s)
08-24 17:08:17.511  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:17.511  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:17.511  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 17:08:17.511  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:17.511  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:17.511  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:08:17.511  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:08:17.521  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:17.521  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:17.521  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-24 17:08:17.521  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:08:17.521  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:17.531  3221  7266 D BtGatt.GattService: registerClient() - UUID=ee95a7c0-74de-4e55-9e8c-3a3bbd61da1c
,08-24 17:08:17.581  3221  3295 D BtGatt.GattService: onClientRegistered() - UUID=ee95a7c0-74de-4e55-9e8c-3a3bbd61da1c, clientIf=6
08-24 17:08:17.581  7827  7827 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
08-24 17:08:17.581  6932  6940 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-24 17:08:17.581  3221  3230 D BtGatt.GattService: start scan with filters
,08-24 17:08:17.581  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:08:17.581  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:17.581  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:08:17.581  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 17:08:17.581  3221  3358 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:17.591  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:17.591  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 17:08:17.591  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:17.591  3221  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-24 17:08:17.591  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.591  3221  3358 D BtGatt.ScanManager: allow scan with filters
08-24 17:08:17.591  3221  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-24 17:08:17.591  3221  3358 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
,08-24 17:08:17.601  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 17:08:17.601  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.601  3221  3358 D BtGatt.ScanManager: Starting BLE batch scan
08-24 17:08:17.601  3221  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:08:17.601  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-24 17:08:17.601  3221  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-24 17:08:17.601  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.601  6932  7162 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-24 17:08:17.601  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-24 17:08:17.601  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.611  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:17.611  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-24 17:08:17.611  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.611  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 17:08:17.611  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 17:08:17.611  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:17.611  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 17:08:17.611  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:08:17.611  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:08:17.611  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:08:17.611  3221  3355 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:08:17.611  3221  7777 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-24 17:08:17.611  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-24 17:08:17.611  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-24 17:08:17.611  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:08:17.611  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 17:08:17.611  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 17:08:17.611  3221  3358 D BtGatt.ScanManager: filter size is 1,
08-24 17:08:17.611  3221  3358 D BtGatt.ScanManager: delete FilterIndex - 6
08-24 17:08:17.621  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 17:08:17.621  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.621  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:17.621  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:17.621  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:17.621  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:08:17.621  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:17.621  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-24 17:08:17.621  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:17.621  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:17.621  3221  3358 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:08:17.621  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:08:17.621  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.621  3221  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-24 17:08:17.621  3221  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 17:08:17.621  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.631  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 17:08:17.631  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:17.631  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:17.631  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:17.631  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.631  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:17.631  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:17.631  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3beec3e removed from the list
08-24 17:08:17.631  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.631  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a39aa9f removed from the list
08-24 17:08:17.631  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:17.631  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:17.631  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.631  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:17.631  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:17.631  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:17.631  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.631  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a39aa9f not in the list
08-24 17:08:17.631  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.631  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:17.641  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:17.641  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:17.641  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.641  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab98e4a removed from the list
08-24 17:08:17.641  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:17.641  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.641  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:17.641  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:17.641  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc4b7b5 removed from the list
08-24 17:08:17.641  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:17.641  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0a4516 added. We now have 2 listener(s)
08-24 17:08:17.641  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 17:08:17.641  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:17.641  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:17.641  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:17.641  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26704e97 added. We now have 9 listener(s)
08-24 17:08:17.641  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:17.651  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:17.651  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:17.661  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:17.661  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:17.661  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:17.661  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:17.661  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:17.661  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:17.661  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:17.661  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:17.661  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:17.661  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:17.661  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:17.661  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10c1286d added. We now have 3 listener(s),
,08-24 17:08:17.661  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:17.661  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:17.671  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 17:08:17.671  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:17.671  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 17:08:17.671  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:17.671  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ddd9ca2 added. We now have 10 listener(s)
08-24 17:08:17.671  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:17.671  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:17.671  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:17.671  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 17:08:17.671  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:17.671  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:17.671  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:08:17.671  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:08:17.681  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:17.681  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:17.691  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:08:17.691  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 17:08:17.691  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:17.701  3221  5337 D BtGatt.GattService: registerClient() - UUID=760d2c1b-0039-4551-8572-ed916b858155
,08-24 17:08:17.741  3221  3295 D BtGatt.GattService: onClientRegistered() - UUID=760d2c1b-0039-4551-8572-ed916b858155, clientIf=6
08-24 17:08:17.741  6932  6940 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-24 17:08:17.741  3221  3231 D BtGatt.GattService: start scan with filters
08-24 17:08:17.741  3221  3358 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:17.741  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:08:17.741  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:17.741  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:08:17.741  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:17.741  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:17.741  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 17:08:17.741  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:08:17.751  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:17.751  3221  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-24 17:08:17.751  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.751  3221  3358 D BtGatt.ScanManager: allow scan with filters
08-24 17:08:17.751  3221  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 17:08:17.751  3221  3358 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,08-24 17:08:17.751  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-24 17:08:17.751  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.751  3221  3358 D BtGatt.ScanManager: Starting BLE batch scan
08-24 17:08:17.751  3221  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:08:17.751  3221  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-24 17:08:17.751  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.751  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 17:08:17.751  6932  7162 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-24 17:08:17.751  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:17.761  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-24 17:08:17.761  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.761  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:17.761  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:08:17.761  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:17.761  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.761  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 17:08:17.761  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:17.761  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0a4516 removed from the list
,08-24 17:08:17.761  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.761  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26704e97 removed from the list
08-24 17:08:17.761  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 17:08:17.761  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:17.761  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.761  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 17:08:17.761  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.761  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:17.771  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-24 17:08:17.771  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:17.771  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.771  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26704e97 not in the list
08-24 17:08:17.771  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 17:08:17.771  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 17:08:17.771  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 17:08:17.771  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 17:08:17.771  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:08:17.771  3221  3230 D BtGatt.GattService: stopScan() - queue size =1
08-24 17:08:17.771  3221  3358 D BtGatt.ScanManager: filter size is 1
08-24 17:08:17.771  3221  3358 D BtGatt.ScanManager: delete FilterIndex - 7
08-24 17:08:17.771  3221  3355 D BtGatt.GattService: unregisterClient() - clientIf=6
08-24 17:08:17.771  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 17:08:17.771  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.771  3221  3358 D BtGatt.ScanManager: stopping BLe Batch
08-24 17:08:17.771  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-24 17:08:17.771  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:17.771  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:08:17.771  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 17:08:17.771  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 17:08:17.781  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:17.781  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 17:08:17.781  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 17:08:17.781  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-24 17:08:17.781  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:17.781  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:08:17.781  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.781  3221  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:08:17.781  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:17.781  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:17.781  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:17.781  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ddd9ca2 removed from the list
08-24 17:08:17.781  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:17.781  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:17.781  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.781  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:17.781  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:17.781  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 17:08:17.781  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10c1286d removed from the list
08-24 17:08:17.781  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 17:08:17.781  3221  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-24 17:08:17.781  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.791  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-24 17:08:17.791  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9ce0ee added. We now have 2 listener(s)
,08-24 17:08:17.791  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-24 17:08:17.791  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:17.791  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:17.791  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:17.791  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@768798f added. We now have 9 listener(s)
08-24 17:08:17.791  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 17:08:17.791  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:17.791  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-24 17:08:17.801  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:17.801  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:17.801  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:17.801  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:17.801  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:17.801  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:17.801  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:17.801  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:17.801  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-24 17:08:17.801  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:17.801  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:17.801  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@153f825 added. We now have 3 listener(s)
,08-24 17:08:17.801  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:17.801  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 17:08:17.801  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 17:08:17.801  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:17.801  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:17.801  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 17:08:17.811  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fa1dfa added. We now have 10 listener(s)
08-24 17:08:17.811  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:17.811  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:17.811  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 17:08:17.811  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 17:08:17.811  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 17:08:17.811  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 17:08:17.811  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 17:08:17.811  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 17:08:17.811  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 17:08:17.821  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 17:08:17.821  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-24 17:08:17.821  6932  7162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 17:08:17.821  3221  5337 D BtGatt.GattService: registerClient() - UUID=1caf338c-19c2-48f0-b162-b301a0ad3316
,08-24 17:08:17.861  3221  3295 D BtGatt.GattService: onClientRegistered() - UUID=1caf338c-19c2-48f0-b162-b301a0ad3316, clientIf=6
,08-24 17:08:17.861  6932  6940 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-24 17:08:17.861  3221  3231 D BtGatt.GattService: start scan with filters
,08-24 17:08:17.871  3221  3358 D BtGatt.ScanManager: handling starting scan
,08-24 17:08:17.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 17:08:17.871  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 17:08:17.871  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 17:08:17.871  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 17:08:17.871  3221  3295 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-24 17:08:17.871  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.871  3221  3358 D BtGatt.ScanManager: allow scan with filters
08-24 17:08:17.871  3221  3358 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-24 17:08:17.871  3221  3358 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
,08-24 17:08:17.871  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-24 17:08:17.871  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.871  3221  3358 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 17:08:17.871  3221  3358 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-24 17:08:17.881  3221  3295 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-24 17:08:17.881  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.881  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:17.881  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-24 17:08:17.881  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-24 17:08:17.891  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 17:08:17.891  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 17:08:17.891  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 17:08:17.901  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:17.901  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 17:08:17.901  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 17:08:17.901  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:17.901  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:17.901  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-24 17:08:17.901  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 17:08:17.901  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a9ce0ee removed from the list
08-24 17:08:17.901  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:17.901  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@768798f removed from the list
,08-24 17:08:17.901  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:17.901  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:17.901  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:17.901  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-24 17:08:17.901  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.901  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 17:08:17.901  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:17.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:17.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 17:08:17.911  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@768798f not in the list
08-24 17:08:17.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 17:08:17.911  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 17:08:17.911  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 17:08:17.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-24 17:08:17.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 17:08:17.911  1018  1127 E WifiNative-wlan0: do suspend true,
,08-24 17:08:17.911  3221  5337 D BtGatt.GattService: stopScan() - queue size =1
,08-24 17:08:17.911  3221  7777 D BtGatt.GattService: unregisterClient() - clientIf=6
08-24 17:08:17.911  3221  3358 D BtGatt.ScanManager: filter size is 1
,08-24 17:08:17.911  3221  3358 D BtGatt.ScanManager: delete FilterIndex - 8
08-24 17:08:17.911  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 17:08:17.911  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 17:08:17.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 17:08:17.911  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 17:08:17.911  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 17:08:17.921  3221  3295 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-24 17:08:17.921  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-24 17:08:17.921  3221  3358 D BtGatt.ScanManager: stopping BLe Batch
,08-24 17:08:17.921  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:17.921  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 17:08:17.921  6932  7162 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 17:08:17.921  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 17:08:17.921  3221  3295 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-24 17:08:17.921  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.921  3221  3358 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-24 17:08:17.921  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:17.921  3221  3295 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-24 17:08:17.921  3221  3295 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-24 17:08:17.921  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:17.921  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 17:08:17.921  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.921  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fa1dfa removed from the list
08-24 17:08:17.921  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 17:08:17.921  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.921  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:17.921  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 17:08:17.921  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@153f825 removed from the list
08-24 17:08:17.921  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 17:08:17.921  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc1fc6 added. We now have 2 listener(s)
08-24 17:08:17.931  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-24 17:08:17.931  6932  6932 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 17:08:17.931  6932  6932 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 17:08:17.931  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-24 17:08:17.931  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:17.931  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:17.931  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:17.931  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ec0b87 added. We now have 9 listener(s)
08-24 17:08:17.931  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:17.931  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 17:08:17.931  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 17:08:17.941  6932  7162 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 17:08:17.941  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 17:08:17.941  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 17:08:17.941  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 17:08:17.941  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 17:08:17.941  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 17:08:17.941  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 17:08:17.941  6932  7162 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 17:08:17.941  6932  7162 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 17:08:17.941  6932  7162 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 17:08:17.941  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 17:08:17.941  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a06dd added. We now have 3 listener(s)
,08-24 17:08:17.941  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-24 17:08:17.941  6932  6932 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-24 17:08:17.941  1018  1126 D WifiP2pService: InactiveState{ what=143375 },
08-24 17:08:17.941  1018  1126 D WifiP2pService: P2pEnabledState{ what=143375 },
08-24 17:08:17.951  1018  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-24 17:08:17.951  1018  1127 E WifiStateMachine: VerifyingLinkState enter
,08-24 17:08:17.951  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41",
,08-24 17:08:17.951  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 17:08:17.951  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 17:08:17.951  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 17:08:17.951  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4a7252 added. We now have 10 listener(s)
08-24 17:08:17.951  6932  7162 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 17:08:17.951  6932  7162 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 17:08:17.951  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:17.951  6932  7162 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 17:08:17.951  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:08:17.951  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:17.951  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.951  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 17:08:17.951  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 17:08:17.951  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bc1fc6 removed from the list
08-24 17:08:17.951  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.951  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ec0b87 removed from the list
,08-24 17:08:17.951  6932  7162 D io.jxcore.node.ConnectivityMonitor: stop
08-24 17:08:17.951  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:17.951  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:08:17.961  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:17.961  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:17.961  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:17.961  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:17.961  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:17.961  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:17.961  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-24 17:08:17.961  1018  1129 D ConnectivityService: Adding iface wlan0 to network 504
,08-24 17:08:17.961  1018  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-24 17:08:17.961  1018  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 17:08:17.961  1018  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 17:08:17.961  1018  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-24 17:08:17.961  1018  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-24 17:08:17.971  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 17:08:17.971  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-24 17:08:17.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 17:08:17.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 17:08:17.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.981  6932  7162 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ec0b87 not in the list
08-24 17:08:17.981  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:17.981  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 17:08:17.981  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:17.981  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:17.981  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-24 17:08:17.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:17.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:17.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:17.981  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:17.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 17:08:17.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-24 17:08:17.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 17:08:17.991  1018  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-24 17:08:17.981  6932  7162 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4a7252 removed from the list
08-24 17:08:17.991  1018  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-24 17:08:17.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 17:08:18.001  1018  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-24 17:08:17.981  6932  7162 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 17:08:18.001  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:17.981  6932  7162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 17:08:18.001  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-24 17:08:17.981  6932  7162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 17:08:18.001  1018  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 17:08:17.981  6932  7162 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10a06dd removed from the list
08-24 17:08:18.001  1018  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-24 17:08:17.981  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 17:08:17.981  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 17:08:17.981  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 17:08:17.981  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 17:08:17.981  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 17:08:17.981  6932  7162 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 17:08:17.991  1018  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-24 17:08:18.001  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:18.001  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:18.001  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-24 17:08:18.001  1636  1636 I Hs20UtilService: Starting #22
08-24 17:08:18.001  1636  1665 I Hs20UtilService: Message received 5007
08-24 17:08:18.001  6932  7860 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1414, name: My test thread name)
08-2,4 17:08:18.001  6932  7860 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1414, thread name: My test thread name)
08-24 17:08:18.001  6932  7860 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1414, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 17:08:18.001  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 17:08:18.001  4768  4768 I NearbySettings: MountReceiver.onReceive - Keep current state
08-24 17:08:18.001  6932  7861 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1416, name: My test thread name)
08-24 17:08:18.001  6932  7861 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1416, thread name: My test thread name)
08-24 17:08:18.001  6932  7861 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1416, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 17:08:18.001  6932  7162 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-24 17:08:18.001  6932  7162 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 17:08:18.001  6932  7162 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 17:08:18.001  6932  7162 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 17:08:18.001  6932  7162 D com.test.thalitest.ThaliTestRunner: Total duration: 23323 ms
08-24 17:08:18.011  6932  7162 I jxcore-log: Total number of executed tests:  80
08-24 17:08:18.011  6932  7162 I jxcore-log: 
08-24 17:08:18.011  6932  7162 I jxcore-log: Number of passed tests:  80
08-24 17:08:18.011  6932  7162 I jxcore-log: 
08-24 17:08:18.011  6932  7162 I jxcore-log: Number of failed tests:  0
08-24 17:08:18.011  6932  7162 I jxcore-log: 
08-24 17:08:18.011  6932  7162 I jxcore-log: Number of ignored tests:  0
08-24 17:08:18.011  6932  7162 I jxcore-log: 
08-24 17:08:18.011  6932  7162 I jxcore-log: Total duration:  23323
08-24 17:08:18.011  6932  7162 I jxcore-log: 
08-24 17:08:18.011  6932  7162 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-24 17:08:18.011  6932  7162 I jxcore-log: 
08-24 17:08:18.011  1018  1129 D ConnectivityService: LTETest block dns file not exists
08-24 17:08:18.011  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:18.011  6932  7162 I jxcore-log: 
,08-24 17:08:18.011  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:18.011  6932  7162 I jxcore-log: 
08-24 17:08:18.011  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:18.011  6932  7162 I jxcore-log: 
08-24 17:08:18.021  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:18.021  6932  7162 I jxcore-log: 
08-24 17:08:18.021  1018  1129 V NetworkStats: updateIfacesLocked()
08-24 17:08:18.021  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.021  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:18.021  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:18.021  6932  7162 I jxcore-log: 
,08-24 17:08:18.021  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:18.021  6932  7162 I jxcore-log: 
,08-24 17:08:18.031  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:18.031  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:18.031  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 17:08:18.031  6932  7162 I jxcore-log: 
08-24 17:08:18.031  1018  1129 V NetworkStats: performPollLocked() took 12ms
08-24 17:08:18.031  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.031  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-24 17:08:18.031  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.031  6932  7162 I jxcore-log: 
,08-24 17:08:18.031  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.031  6932  7162 I jxcore-log: 
,08-24 17:08:18.031  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:18.031  6932  7162 I jxcore-log: 
,08-24 17:08:18.031  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.031  6932  7162 I jxcore-log: 
,08-24 17:08:18.031  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.031  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  6932 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-24 17:08:18.041  6932  7162 I jxcore-log: 
08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.041  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.041  6932  7162 I jxcore-log: 
,08-24 17:08:18.051  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.051  6932  7162 I jxcore-log: 
,08-24 17:08:18.051  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:08:18.051  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-24 17:08:18.051  1018  1129 E ConnectivityService: updateNetworkInfo()
08-24 17:08:18.051  1018  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-24 17:08:18.051  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.051  6932  7162 I jxcore-log: 
08-24 17:08:18.051  1018  1129 V NetworkStats: updateIfacesLocked()
08-24 17:08:18.051  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.051  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-24 17:08:18.051  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 17:08:18.051  6932  7162 I jxcore-log: 
08-24 17:08:18.051  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:18.051  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:08:18.051  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 17:08:18.051  1018  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-24 17:08:18.051  1018  1129 V NetworkStats: performPollLocked() took 4ms
08-24 17:08:18.051  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:18.051  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.051  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:18.051  1018  1018 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-24 17:08:18.051  1018  1018 I WifiTrafficPoller: mBoosterFLAG : 0
08-24 17:08:18.051  1018  1018 I WifiTrafficPoller: current booster mode : FullMode
,08-24 17:08:18.051  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:08:18.051  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:18.051  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-24 17:08:18.051  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.051  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.051  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.051  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:18.061  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:18.061  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 17:08:18.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:18.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.061  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:18.061  1018  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-24 17:08:18.061  1018  7825 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:08:18.061  1018  7825 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-24 17:08:18.061  1018  7825 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-24 17:08:18.061  1018  7825 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-24 17:08:18.061  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.061  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:18.061  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:18.061  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-24 17:08:18.061  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:18.071  1018  7825 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-24 17:08:18.071  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:18.071  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:18.071  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:18.071  1636  1636 I Hs20UtilService: Starting #23
,08-24 17:08:18.071  1018  1129 D ConnectivityService:    accepting network in place of null
08-24 17:08:18.071  1636  1665 I Hs20UtilService: Message received 5007
,08-24 17:08:18.071   277  1000 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-24 17:08:18.071   277  1000 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-24 17:08:18.071  1018  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-24 17:08:18.071  1454  1454 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-24 17:08:18.071  1454  1454 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-24 17:08:18.071  1018  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-24 17:08:18.081  1018  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-24 17:08:18.081  1018  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-24 17:08:18.081  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 17:08:18.081  4768  4768 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-24 17:08:18.081  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-24 17:08:18.081  1018  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-24 17:08:18.091  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-24 17:08:18.091  1018  1018 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-24 17:08:18.091  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-24 17:08:18.091  1018  1132 D Tethering: MasterInitialState.processMessage what=3
,08-24 17:08:18.091  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.091  1018  1124 V NetworkStats: updateIfacesLocked()
08-24 17:08:18.091  1018  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-24 17:08:18.091  1018  1124 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:18.091  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-24 17:08:18.091  4768  4768 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-24 17:08:18.091  4768  4768 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-24 17:08:18.091  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:18.091  1018  1124 V NetworkStats: performPollLocked() took 4ms
08-24 17:08:18.091  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:18.091  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:18.091  1176  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
,08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-24 17:08:18.101  1018  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-24 17:08:18.101  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.101  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.101  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.101  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
08-24 17:08:18.101  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-24 17:08:18.101  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.101  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.101  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.101  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:18.111  1018  1222 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-24 17:08:18.111  1018  1222 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-24 17:08:18.111  1018  1222 W ActivityManager: userId = 0, bbcId = -10000
08-24 17:08:18.111  1018  1222 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-24 17:08:18.111  1018  1222 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-24 17:08:18.111  1636  1636 I Hs20UtilService: Starting #24
,08-24 17:08:18.111  1636  1665 I Hs20UtilService: Message received 5007
08-24 17:08:18.121  4768  4768 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-24 17:08:18.121  4768  4768 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-24 17:08:18.121  6932  6932 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 17:08:18.121  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:18.121  6932  7162 I jxcore-log: 
,08-24 17:08:18.121  1018  1507 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-24 17:08:18.121  1018  1501 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-24 17:08:18.121  1018  1501 D SecContentProvider2: mCursor = null
,08-24 17:08:18.131  1018  1030 D SecContentProvider2: uri = 15 selection = getToastGravity
08-24 17:08:18.131  1018  1030 D SecContentProvider2: mCursor = null
,08-24 17:08:18.131  1018  1488 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-24 17:08:18.131  1018  1488 D SecContentProvider2: mCursor = null
,08-24 17:08:18.131  1018  4334 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-24 17:08:18.131  1018  4334 D SecContentProvider2: mCursor = null
,08-24 17:08:18.131  1018  4327 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
08-24 17:08:18.131  1018  4327 D SecContentProvider2: mCursor = null
08-24 17:08:18.131  1018  1327 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-24 17:08:18.131  1018  1327 D SecContentProvider2: mCursor = null
,08-24 17:08:18.161  1018  7825 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-24 17:08:18.161   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-24 17:08:18.171  1018  1487 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,08-24 17:08:18.181  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-24 17:08:18.221  1018  7825 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 15:08:18 GMT], X-Android-Received-Millis=[1472051298234], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472051298205]}
,08-24 17:08:18.221  1018  7825 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-24 17:08:18.221  1018  7825 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-24 17:08:18.221  1018  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,08-24 17:08:18.221  1018  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-24 17:08:18.221  1018  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
,08-24 17:08:18.221  1018  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-24 17:08:18.221  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 17:08:18.221  1176  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-24 17:08:18.231  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-24 17:08:18.231  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-24 17:08:18.231  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-24 17:08:18.231  1176  1176 D StatusBar.NetworkController: updateDataNetType()
,08-24 17:08:18.231  1176  1176 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,08-24 17:08:18.231  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-24 17:08:18.231  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-24 17:08:18.231  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 21 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,08-24 17:08:18.241  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
08-24 17:08:18.241  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,08-24 17:08:18.241  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-24 17:08:18.241  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-24 17:08:18.241  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.241  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.241  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-24 17:08:18.241  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-24 17:08:18.271  7865  7865 D AndroidRuntime: 
08-24 17:08:18.271  7865  7865 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 17:08:18.281  7865  7865 D AndroidRuntime: CheckJNI is OFF,
08-24 17:08:18.281  7865  7865 D AndroidRuntime: readGMSProperty: start
,08-24 17:08:18.281  7865  7865 D AndroidRuntime: readGMSProperty: already setted!!
08-24 17:08:18.281  7865  7865 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-24 17:08:18.281  7865  7865 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,08-24 17:08:18.281  7865  7865 D AndroidRuntime: readGMSProperty: end
08-24 17:08:18.281  7865  7865 D AndroidRuntime: addProductProperty: start
,08-24 17:08:18.291  6932  6932 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 17:08:18.291  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:18.291  6932  7162 I jxcore-log: 
,08-24 17:08:18.411  7865  7865 E AffinityControl: AffinityControl: registerfunction enter,
,08-24 17:08:18.431  6932  6932 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 17:08:18.431  6932  7162 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 17:08:18.431  6932  7162 I jxcore-log: 
,08-24 17:08:18.441  7865  7865 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-24 17:08:18.471  1018  1031 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-24 17:08:18.471  1018  1031 D PackageManager: START PACKAGE DELETE: observer{872596539}
08-24 17:08:18.471  1018  1031 D PackageManager: pkg{<packageName>}
08-24 17:08:18.471  1018  1031 D PackageManager: user{0},
08-24 17:08:18.471  1018  1031 D PackageManager: caller{2000}
,08-24 17:08:18.471  1018  1031 D PackageManager: flags{2}
08-24 17:08:18.471  1018  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-24 17:08:18.471  1018  1031 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-24 17:08:18.471  1018  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-24 17:08:18.471  1018  1031 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-24 17:08:18.471  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-24 17:08:18.471  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-24 17:08:18.471  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-24 17:08:18.471  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-24 17:08:18.471  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-24 17:08:18.481  1018  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,08-24 17:08:18.501  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg,
,08-24 17:08:18.501  1018  1043 I ActivityManager: Killing 6932:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-24 17:08:18.591  1018  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:18.591  1018  1137 I WindowState: WIN DEATH: Window{33ff12c1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 17:08:18.591   257   452 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-24 17:08:18.591   257   450 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-24 17:08:18.601  1018  1137 D InputDispatcher: Focus left window: 6932,
,08-24 17:08:18.611  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-24 17:08:18.611  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-24 17:08:18.621  1018  1043 I ActivityManager:   Force finishing activity ActivityRecord{37f1eb3a u0 com.test.thalitest/.MainActivity t163}
,08-24 17:08:18.621  1018  4333 W ActivityManager: Spurious death for ProcessRecord{3d99b758 6932:com.test.thalitest/u0a170}, curProc for 6932: null
,08-24 17:08:18.641  1018  1043 D InputDispatcher: Focused application released
,08-24 17:08:18.661  1018  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:18.661  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-24 17:08:18.661  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:18.661  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:18.661  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:18.661  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:18.671  7876  7876 E Zygote  : MountEmulatedStorage(),
08-24 17:08:18.671  1018  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-24 17:08:18.671  7876  7876 E Zygote  : v2
08-24 17:08:18.671  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
08-24 17:08:18.671  7876  7876 I libpersona: KNOX_SDCARD checking this for 1000
08-24 17:08:18.671  7876  7876 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:18.681  7876  7876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 17:08:18.681  7876  7876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-24 17:08:18.681  7876  7876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:08:18.691  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-24 17:08:18.731  2863  2863 I art     : Explicit concurrent mark sweep GC freed 18194(1059KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 982us total 43.227ms
,08-24 17:08:18.731  1869  1869 E SamsungIME: mOCRHelper is null
,08-24 17:08:18.731  1771  2126 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 17:08:18.741  7876  7876 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:18.741  7876  7876 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:18.761  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 17:08:18.771  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
,08-24 17:08:18.771  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
08-24 17:08:18.771  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:18.771  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-24 17:08:18.771  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-24 17:08:18.781  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:08:18.781  1018  1124 V NetworkStats: performPollLocked() took 15ms
08-24 17:08:18.781  1018  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:18.791  1440  1440 D RegisteredServicesCache: empty dynamic service
,08-24 17:08:18.801  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:18.801  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:18.821  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-24 17:08:18.821  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,08-24 17:08:18.821  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-24 17:08:18.821  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-24 17:08:18.821  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-24 17:08:18.821  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-24 17:08:18.821  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-24 17:08:18.851  7876  7876 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-24 17:08:18.851  7876  7876 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-24 17:08:18.851  7876  7876 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-24 17:08:18.851  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-24 17:08:18.851  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-24 17:08:18.881  7876  7876 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-24 17:08:18.881  7876  7876 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-24 17:08:18.891  7876  7876 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-24 17:08:18.891  7876  7876 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:18.891  1018  4327 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
,08-24 17:08:18.891  1018  4327 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
08-24 17:08:18.891  1018  4327 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
08-24 17:08:18.891  1018  4327 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,08-24 17:08:18.891  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-24 17:08:18.891  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-24 17:08:18.891  1018  1042 W TextServicesManagerService: no available spell checker services found
,08-24 17:08:18.901  1018  4327 I ActivityManager: Killing 7364:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-24 17:08:18.911  1018  1058 I art     : Explicit concurrent mark sweep GC freed 66439(4MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 9.338ms total 212.693ms
,08-24 17:08:18.911  1018  1487 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-24 17:08:18.911  1018  1487 D SecContentProvider2: mCursor = null
,08-24 17:08:18.921  1018  1028 I art     : WaitForGcToComplete blocked for 213.469ms for cause HeapTrim
,08-24 17:08:18.941  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:18.941  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:18.961  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:18.971  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:18.991  1018  1058 D PackageManager: delete codoeFile: 
,08-24 17:08:19.001  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-24 17:08:19.001  1018  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-24 17:08:19.001  1018  1058 D PackageManager: result of delete: 1{872596539}
,08-24 17:08:19.011  7865  7865 D AndroidRuntime: Shutting down VM
,08-24 17:08:19.051  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-24 17:08:19.051  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:19.061  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:19.061  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:19.071  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-24 17:08:19.071  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 17:08:19.071  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-24 17:08:19.071  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:19.081  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-24 17:08:19.081  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-24 17:08:19.081  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-24 17:08:19.081  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-24 17:08:19.081  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-24 17:08:19.081  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-24 17:08:19.081  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:19.081  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 17:08:19.081  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-24 17:08:19.091  1018  3386 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-24 17:08:19.091  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-24 17:08:19.091  1018  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-24 17:08:19.091  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:19.091  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:19.091  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 17:08:19.101  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-24 17:08:19.101  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-24 17:08:19.101  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-24 17:08:19.101  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-24 17:08:19.101  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-24 17:08:19.171  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-24 17:08:19.171  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:19.171  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:19.171  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:19.171  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:19.181  1018  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-24 17:08:19.181  1018  1129 V NetworkStats: updateIfacesLocked()
08-24 17:08:19.181  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-24 17:08:19.181  1018  1129 V NetworkStats: performPollLocked(flags=0x1)
08-24 17:08:19.181  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-24 17:08:19.181  1018  1129 V NetworkStats: performPollLocked() took 2ms
08-24 17:08:19.181  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-24 17:08:19.181  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:19.191  7893  7893 E Zygote  : MountEmulatedStorage()
,08-24 17:08:19.191  7893  7893 E Zygote  : v2
,08-24 17:08:19.191  7893  7893 I libpersona: KNOX_SDCARD checking this for 10001
08-24 17:08:19.191  7893  7893 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:19.191  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7893 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-24 17:08:19.191  7893  7893 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-24 17:08:19.191  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-24 17:08:19.191  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-24 17:08:19.191  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-24 17:08:19.191  1018  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504],
08-24 17:08:19.191  1176  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-24 17:08:19.191  1176  1743 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-24 17:08:19.191  7893  7893 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-24 17:08:19.201  7893  7893 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-24 17:08:19.211  7893  7893 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:19.211  7893  7893 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:19.221  7865  7865 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-24 17:08:19.231  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-24 17:08:19.231  1018  1058 D PackageManager: userId{-1}
08-24 17:08:19.231  1018  1058 D PackageManager: andCode{true}
,08-24 17:08:19.231  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-24 17:08:19.231  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:19.231  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-24 17:08:19.231  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:19.231  1018  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-24 17:08:19.251  7908  7908 E Zygote  : MountEmulatedStorage()
,08-24 17:08:19.251  7908  7908 E Zygote  : v2
08-24 17:08:19.251  7908  7908 I libpersona: KNOX_SDCARD checking this for 10003
08-24 17:08:19.251  7908  7908 I libpersona: KNOX_SDCARD not a persona
,08-24 17:08:19.251  7908  7908 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-24 17:08:19.251  1018  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7908 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-24 17:08:19.251  7908  7908 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-24 17:08:19.251  7908  7908 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-24 17:08:19.271  7908  7908 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-24 17:08:19.271  7908  7908 D ActivityThread: Added TimaKeyStore provider
,08-24 17:08:19.291  7381  7381 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-24 17:08:19.301  7381  7381 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-24 17:08:19.301  7381  7381 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-24 17:08:19.301  7381  7381 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-24 17:08:19.311  1018  1137 I ActivityManager: Killing 7397:com.sec.android.fotaclient/u0a8 (adj 15): empty #21

```
