#### Test 79763830f325397_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-22 12:03:11.541  5742  5742 D Mms/Contact: [start]    init() consume time = 6.03
08-22 12:03:11.551  1444  1716 D TP/MmsSmsProvider: query,matched:13, calling pid = 5742
08-22 12:03:11.551  1444  1716 D TP/MmsSmsProvider: match 13:Elapsed time : 0.922 ms
08-22 12:03:11.561  5742  5742 D Mms/Contact: [end]    init consume time = 23.741459
08-22 12:03:11.571  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-22 12:03:11.571  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.571  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.571  5742  5939 D Mms/DraftCache: [start]    rebuildCache consume time = 11.62276
08-22 12:03:11.581  1444  2127 D TP/MmsSmsProvider: query,matched:12, calling pid = 5742
08-22 12:03:11.581  1444  2127 D TP/MmsSmsProvider: match 12:Elapsed time : 0.925 ms
08-22 12:03:11.581  5742  5939 D Mms/DraftCache: [end]    rebuildCache consume time = 8.32875
08-22 12:03:11.581  5742  5742 D Mms/MethodReflector: getSubId is called
08-22 12:03:11.581  5742  5742 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-22 12:03:11.581  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.581  5742  5742 D Mms/MethodReflector: getTelephonyProperty is called
08-22 12:03:11.581  5742  5742 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-22 12:03:11.581  5742  5742 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-22 12:03:11.581  5742  5742 D Mms/DownloadManager: auto download without roaming -> true
08-22 12:03:11.581  5742  5742 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-22 12:03:11.581  5742  5742 D Mms/MethodReflector: getSubId is called
08-22 12:03:11.591  5742  5742 D Mms/MethodReflector: getDefaultSmsSubId is called
08-22 12:03:11.591  5742  5742 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
08-22 12:03:11.591  5742  5742 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
08-22 12:03:11.591  5742  5742 D Mms/MethodReflector: getTelephonyProperty is called
08-22 12:03:11.591  5742  5742 D Mms/DownloadManager: roaming -> false (slotId = 1)
08-22 12:03:11.591  5742  5742 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-22 12:03:11.591  5742  5742 D Mms/DownloadManager: auto download without roaming -> true
08-22 12:03:11.591  5742  5742 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-22 12:03:11.591  5742  5742 D Mms/DownloadManager: auto download during roaming secondary -> false
08-22 12:03:11.591  5742  5742 D Mms/DownloadManager: mAutoDownload ------> true
--------- beginning of system
08-22 12:03:11.591  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 12:03:11.591  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:11.591  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 12:03:11.601  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.601  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.601  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.601  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.601  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-22 12:03:11.611  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.611  1853  5802 W BaseAppContext: Using Auth Proxy for data requests.
08-22 12:03:11.611  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.611  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-22 12:03:11.611  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.611  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-22 12:03:11.621  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:11.621  1019  1043 I CrashAnrDetector: onPackageAdded : com.test.thalitest
08-22 12:03:11.621  1019  1043 W libprocessgroup: failed to open /acct/uid_10052/pid_5236/cgroup.procs: No such file or directory
08-22 12:03:11.641  1019  1032 I ActivityManager: Killing 5177:com.google.android.gm/u0a99 (adj 15): empty #21
08-22 12:03:11.671  1853  5799 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-22 12:03:11.671  1853  5799 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 12:03:11.671  1853  5799 I System.out: (HTTPLog)-Static: isShipBuild true
08-22 12:03:11.671  1853  5799 I System.out: (HTTPLog)-Thread-234-984797441: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-22 12:03:11.671  1853  5799 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 12:03:11.681  5742  5742 D ComposerPerformance: 1471860191689 ms / [DONE] Composer constructor
08-22 12:03:11.681  5742  5742 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
08-22 12:03:11.681   279   997 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 12:03:11.681   279   997 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-22 12:03:11.691  5742  5742 I Mms/ReservationManager: ReservationManager()
08-22 12:03:11.691  5742  5742 I Mms/ReservationManager: resetAfterConnected()
08-22 12:03:11.691  1444  1457 D TP/MmsSmsProvider: query,matched:7, calling pid = 5742
08-22 12:03:11.691  1444  1457 D TP/MmsSmsProvider: match 7:Elapsed time : 1.977 ms
08-22 12:03:11.701  1019  1032 E EdmStorageProvider: Admin not in database, something went wrong
08-22 12:03:11.711  5742  5947 D Mms/Conversation: [start]    init() consume time = 127.715
08-22 12:03:11.711  1019  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 12:03:11.711  1019  1314 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:11.711  1019  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:11.711  1019  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
08-22 12:03:11.711  1444  1457 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-22 12:03:11.711  5742  5742 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-22 12:03:11.721  1444  1457 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-22 12:03:11.721  1444  1457 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
08-22 12:03:11.721  5742  5742 D Mms/MmsApp: [end]    onCreate() consume time = 11.769792
08-22 12:03:11.721  1444  1457 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
08-22 12:03:11.731  1444  1457 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-22 12:03:11.731  1444  1457 D TP/MmsSmsProvider: need read changed broadcast:false
08-22 12:03:11.741  5742  5947 D Mms/Conversation: [end]    init consume time = 15.13276
08-22 12:03:11.741  5742  5947 D Mms/MessagingNotification: [start]    init() consume time = 3.071198
08-22 12:03:11.751  5742  5947 D Mms/MessagingNotification: [end]    init consume time = 7.975937
08-22 12:03:11.751  5742  5742 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
08-22 12:03:11.751  5742  5742 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
08-22 12:03:11.761  5742  5742 D Mms/MethodReflector: getSubId is called
08-22 12:03:11.761  5742  5742 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
08-22 12:03:11.761  5742  5742 D Mms/MethodReflector: getTelephonyProperty is called
08-22 12:03:11.761  5742  5742 D Mms/DownloadManager: roaming -> false (slotId = 0)
08-22 12:03:11.761  5742  5742 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-22 12:03:11.761  5742  5742 D Mms/DownloadManager: auto download without roaming -> true
08-22 12:03:11.761  5742  5742 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
08-22 12:03:11.761  5742  5742 D Mms/DownloadManager: mAutoDownload ------> true
08-22 12:03:11.771  5742  5949 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 19.344688
08-22 12:03:11.781  5742  5950 D Mms/Synchronizer: [start]    doSync consume time = 9.600417
08-22 12:03:11.791  1853  5799 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-22 12:03:11.791  1444  1716 D TP/MmsSmsProvider: query,matched:0, calling pid = 5742
08-22 12:03:11.791  1444  1716 V TP/MmsSmsProvider: getSimpleConversations entered.
08-22 12:03:11.791  1444  1716 D TP/MmsSmsProvider: match 0:Elapsed time : 1.644 ms
08-22 12:03:11.791  1444  2127 D TP/MmsSmsProvider: query,matched:400, calling pid = 5742
08-22 12:03:11.791  5742  5949 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 17.994479
08-22 12:03:11.801  1853  1853 I ConfigFetchService: fetch service done; releasing wakelock
08-22 12:03:11.801  5742  5742 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-22 12:03:11.801  1019  1708 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-22 12:03:11.801  1019  1708 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-22 12:03:11.801  1444  1457 D TP/MmsSmsProvider: update, matched:300, calling pid = 5742
08-22 12:03:11.801  1444  1457 V TP/MmsSmsProvider: syncDBData start
08-22 12:03:11.801  1444  1457 V TP/MmsSmsProvider: syncDBData sms end
08-22 12:03:11.801  1444  1457 V TP/MmsSmsProvider: syncDBData mms end
08-22 12:03:11.801  1444  1457 V TP/MmsSmsProvider: syncDBData end
08-22 12:03:11.801  5742  5903 D Mms/ArtClassLoader: init [DONE] art
08-22 12:03:11.811  1019  1708 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:11.811  1019  1708 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:11.811  1019  1708 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-22 12:03:11.811  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:11.811  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-22 12:03:11.811  1853  1853 I ConfigFetchService: stopping self
08-22 12:03:11.821  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:11.821  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:11.821  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:11.821  1019  1465 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
08-22 12:03:11.821  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:11.821  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:11.821  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:11.821  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:11.841  5953  5953 E Zygote  : MountEmulatedStorage()
08-22 12:03:11.841  5953  5953 I libpersona: KNOX_SDCARD checking this for 10068
08-22 12:03:11.841  5953  5953 E Zygote  : v2
08-22 12:03:11.841  5953  5953 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:11.841  5953  5953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:11.841  5953  5953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:11.841  5953  5953 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-22 12:03:11.851  1019  1465 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5953 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-22 12:03:11.851  5742  5950 D Mms/Synchronizer: [end]    doSync consume time = 53.471198
08-22 12:03:11.851  1019  1332 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-22 12:03:11.851  1019  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:11.851  1019  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:11.851  1019  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:11.851  1019  1332 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:11.861  5742  5952 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-22 12:03:11.861  5742  5952 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-22 12:03:11.871  5953  5953 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:11.871  5953  5953 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:11.871  5964  5964 E Zygote  : MountEmulatedStorage()
08-22 12:03:11.871  5964  5964 E Zygote  : v2
08-22 12:03:11.871  5964  5964 I libpersona: KNOX_SDCARD checking this for 10042
08-22 12:03:11.881  1019  1332 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5964 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-22 12:03:11.881  5964  5964 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:11.881  5964  5964 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:11.881  5964  5964 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:11.891  5964  5964 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-22 12:03:11.901  1019  2703 D SSRM:n  : SIOP:: AP = 400
08-22 12:03:11.901  5945  5945 D AndroidRuntime: 
08-22 12:03:11.901  5945  5945 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 12:03:11.901  5945  5945 D AndroidRuntime: CheckJNI is OFF
08-22 12:03:11.901  5945  5945 D AndroidRuntime: readGMSProperty: start
08-22 12:03:11.901  5945  5945 D AndroidRuntime: readGMSProperty: already setted!!
08-22 12:03:11.901  5945  5945 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 12:03:11.901  5945  5945 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 12:03:11.901  5945  5945 D AndroidRuntime: readGMSProperty: end
08-22 12:03:11.901  5945  5945 D AndroidRuntime: addProductProperty: start
08-22 12:03:11.931  5964  5964 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:11.931  5964  5964 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:11.931  1019  1032 I ActivityManager: Killing 5534:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #21
08-22 12:03:11.931  1019  1032 I ActivityManager: Killing 4816:com.google.android.music:main/u0a108 (adj 15): empty #22
08-22 12:03:11.941  1019  1051 I PowerManagerService: [PWL] Off : 30s ago
08-22 12:03:11.941  1019  1051 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-22 12:03:11.941  1019  1051 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-22 12:03:11.941  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1853, ws=null) (elapsedTime=47764)
08-22 12:03:11.941  1019  1051 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=1853, ws=WorkSource{10011 com.google.android.gms}) (elapsedTime=122)
08-22 12:03:11.951  5964  5964 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 12:03:11.951  5964  5964 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 12:03:11.951  5964  5964 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 12:03:11.961  1019  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 12:03:11.961  1019  1471 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:11.961  1019  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:11.961  1019  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
08-22 12:03:11.971  1019  1464 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-22 12:03:11.971  1019  1464 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:11.971  1019  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:11.971  1019  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:11.991  5953  5953 D BadgeProvider: onCreate
08-22 12:03:11.991  5953  5953 D BadgeProvider: DatabaseHelper
08-22 12:03:12.001  1019  1484 I art     : Explicit concurrent mark sweep GC freed 144149(8MB) AllocSpace objects, 6(1888KB) LOS objects, 33% free, 22MB/33MB, paused 2.887ms total 237.303ms
08-22 12:03:12.021  1019  1465 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:12.021  1019  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-22 12:03:12.031  1019  1465 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:12.031  1019  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:12.031  1019  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:12.051  5700  5760 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 944 ms] updated apps [took 944 ms] 
08-22 12:03:12.051  5742  5947 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-22 12:03:12.061  1019  1464 I ActivityManager: Killing 5598:com.android.defcontainer/u0a3 (adj 15): empty #21
08-22 12:03:12.071  1444  2127 D TP/SmsProvider: query,matched:26, calling pid = 5742
08-22 12:03:12.071  1444  2127 D TP/SmsProvider: match 26:Elapsed time : 0.903 ms
08-22 12:03:12.081  1444  1457 D TP/MmsSmsProvider: query,matched:6, calling pid = 5742
08-22 12:03:12.081  1444  1457 D TP/MmsSmsProvider: match 6:Elapsed time : 1.220 ms
08-22 12:03:12.081  5945  5945 E AffinityControl: AffinityControl: registerfunction enter
08-22 12:03:12.121  5945  5945 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 12:03:12.131  1019  1476 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-22 12:03:12.131  1019  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.131  1019  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.131  1019  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.131  1019  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.141  5992  5992 E Zygote  : MountEmulatedStorage()
08-22 12:03:12.141  5992  5992 I libpersona: KNOX_SDCARD checking this for 10023
08-22 12:03:12.141  5992  5992 E Zygote  : v2
08-22 12:03:12.141  5992  5992 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:12.141  5992  5992 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:12.151  5992  5992 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:12.151  1019  1476 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5992 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-22 12:03:12.151  5992  5992 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:12.161  1019  1031 E PersonaManagerService: inState():  stateMachine is null !!
08-22 12:03:12.171  5964  5964 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-22 12:03:12.181  1019  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-22 12:03:12.181  1019  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-22 12:03:12.181  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.181  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.181  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.181  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.181  5992  5992 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:12.181  5992  5992 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:12.191  6007  6007 E Zygote  : MountEmulatedStorage()
08-22 12:03:12.191  6007  6007 E Zygote  : v2
08-22 12:03:12.191  6007  6007 I libpersona: KNOX_SDCARD checking this for 10003
08-22 12:03:12.191  6007  6007 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:12.191  6007  6007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:12.201  1019  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6007 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-22 12:03:12.201  6007  6007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:12.201  1019  1332 I ActivityManager: Killing 5385:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-22 12:03:12.201  6007  6007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:12.201  1019  1031 I PersonaManagerService: PersonaId don't exist
08-22 12:03:12.201  1019  1031 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-22 12:03:12.201  1019  1314 I ActivityManager: Killing 5632:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-22 12:03:12.211  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 12:03:12.211  1019  1465 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-22 12:03:12.221  1853  1879 W art     : Suspending all threads took: 8.309ms
08-22 12:03:12.231  6007  6007 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:12.231  6007  6007 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:12.231  1019  1031 W ActivityManager: mDVFSHelper.acquire()
08-22 12:03:12.241  1019  1031 D FocusedStackFrame: Set to : 0
08-22 12:03:12.251  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.251  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.251  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.251  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:12.251  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 12:03:12.251  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-22 12:03:12.261  1019  1031 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6023 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 12:03:12.261  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 12:03:12.261  1019  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 12:03:12.261  1019  1031 D InputDispatcher: Focused application set to: xxxx
08-22 12:03:12.261  1019  1031 D InputDispatcher: Focus left window: 1472
08-22 12:03:12.261  6023  6023 E Zygote  : MountEmulatedStorage()
08-22 12:03:12.261  6023  6023 E Zygote  : v2
08-22 12:03:12.261  6023  6023 I libpersona: KNOX_SDCARD checking this for 10170
08-22 12:03:12.261  6023  6023 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:12.271  6023  6023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:12.271  5945  5945 D AndroidRuntime: Shutting down VM
08-22 12:03:12.271  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 12:03:12.271  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 12:03:12.271  6023  6023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:12.271   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
08-22 12:03:12.271  6023  6023 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-22 12:03:12.281  5722  5756 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-22 12:03:12.301  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:12.301  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 12:03:12.311  5722  5756 I AcmsKeyStoreHelper: Key Store exist
08-22 12:03:12.311  5722  5756 I AcmsKeyStoreHelper: Hence loading the keystore file
08-22 12:03:12.311   285   285 E installd: system dir 0 : /system/app/
08-22 12:03:12.311   285   285 E installd: system dir 1 : /system/priv-app/
08-22 12:03:12.311   285   285 E installd: system dir 2 : /vendor/app/
08-22 12:03:12.311   285   285 E installd: system dir 3 : /oem/app/
08-22 12:03:12.321  5992  5992 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-22 12:03:12.321  6023  6023 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:12.321  6023  6023 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:12.331  1019  1464 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-22 12:03:12.341  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 12:03:12.361  1019  1019 V ActivityManager: Display changed displayId=0
08-22 12:03:12.361  5742  5947 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-22 12:03:12.371  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-22 12:03:12.371  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-22 12:03:12.371  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-22 12:03:12.371  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-22 12:03:12.381  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-22 12:03:12.381  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-22 12:03:12.381  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-22 12:03:12.381  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-22 12:03:12.381  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-22 12:03:12.391  1019  1059 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-22 12:03:12.391  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-22 12:03:12.391  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-22 12:03:12.391  1472  1472 V ActivityThread: updateVisibility : ActivityRecord{3cc54665 token=android.os.BinderProxy@29708d4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-22 12:03:12.391  1472  1472 D Launcher: onTrimMemory. Level: 20
08-22 12:03:12.391  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-22 12:03:12.391  5992  5992 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-22 12:03:12.391   259   443 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-22 12:03:12.401  1019  1464 D PersonaManager: isKioskContainerExistOnDevice
08-22 12:03:12.421  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-22 12:03:12.421  5722  5756 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-22 12:03:12.421  5722  5756 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-22 12:03:12.421  5722  5756 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-22 12:03:12.421  5722  5756 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 12:03:12.421  5722  5756 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-22 12:03:12.421  5722  5756 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-22 12:03:12.421  5722  5756 D AcmsCore: This is NOT a valid MirrorLink app
08-22 12:03:12.421  5722  5756 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-22 12:03:12.421  5722  5756 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 12:03:12.421  5722  5756 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-22 12:03:12.421  5722  5756 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
08-22 12:03:12.421  5722  5722 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-22 12:03:12.421  5722  5722 D AcmsService: Enter onDestroy
08-22 12:03:12.421  5722  5722 I AcmsService: cleanUp(): inside service clean up
08-22 12:03:12.421  5722  5722 D AcmsCore: AcmsCore: inside DeInit
08-22 12:03:12.421  5722  5722 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
08-22 12:03:12.421  5722  5722 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
08-22 12:03:12.421  5722  5722 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-22 12:03:12.421  5722  5722 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-22 12:03:12.421  5722  5722 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
08-22 12:03:12.431  5722  5722 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-22 12:03:12.431  5722  5722 D AcmsService: killing acms process
08-22 12:03:12.431  5722  5722 I Process : Sending signal. PID: 5722 SIG: 9
08-22 12:03:12.431  1019  1097 V AlarmManager: waitForAlarm result :4
08-22 12:03:12.441  1019  1097 V AlarmManager: waitForAlarm result :8
08-22 12:03:12.441  1019  1097 V AlarmManager: No more alarm at this time.nowELAPSED=82903 batch.start=84442
08-22 12:03:12.441  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-22 12:03:12.441  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
08-22 12:03:12.451  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-22 12:03:12.451  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
08-22 12:03:12.461  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-22 12:03:12.461  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-22 12:03:12.461  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
08-22 12:03:12.471  5945  5945 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 12:03:12.481  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 12:03:12.491  1853  5802 W art     : Verification of void com.google.android.gms.games.broker.GameAgent.addGameBadgeOps(com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.server.api.MarketInstance, java.lang.String, java.util.ArrayList, int) took 113.005ms
,08-22 12:03:12.501  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 12:03:12.511  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 12:03:12.511   289   289 E SMD     : DCD OFF,
,08-22 12:03:12.521  5818  5881 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-22 12:03:12.521  5818  5881 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 12:03:12.521  5818  5881 I GAv4    :   adb logcat -s GAv4
,08-22 12:03:12.531  1019  1314 I ActivityManager: Process ACMS.Process (pid 5722)(adj 0) has died(57,778)
,08-22 12:03:12.531   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 12:03:12.541  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-22 12:03:12.541  5818  5881 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 12:03:12.541  1019  1138 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 12:03:12.581  6023  6023 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-22 12:03:12.651  5818  5881 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 12:03:12.671  5818  6046 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 12:03:12.671  5818  5881 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,08-22 12:03:12.681  6023  6023 I cr.library_loader: Time to load native libraries: 16 ms (timestamps 3128-3144)
,08-22 12:03:12.681  6023  6023 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 12:03:12.711  6023  6023 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {393cbac9}
,08-22 12:03:12.711  6023  6023 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 12:03:12.721  6023  6023 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 12:03:12.771  6023  6023 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-22 12:03:12.781  6023  6023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 12:03:12.791  6023  6023 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 12:03:12.861  6023  6052 W chromium: [WARNING:dns_config_service_posix.cc(298)] Failed to read DnsConfig.
,08-22 12:03:12.861  6023  6023 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 12:03:12.861  6023  6023 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 12:03:12.861  6023  6023 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 12:03:12.861  6023  6023 I Adreno-EGL: Local Branch: 
08-22 12:03:12.861  6023  6023 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 12:03:12.861  6023  6023 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 12:03:12.861  6023  6023 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 12:03:12.911  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{27b70aaf u0 com.test.thalitest/.MainActivity t163}
,08-22 12:03:12.981  1019  1138 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
,08-22 12:03:12.991  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:12.991  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:12.991  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:12.991  1019  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:13.001  6069  6069 E Zygote  : MountEmulatedStorage(),
08-22 12:03:13.001  6069  6069 E Zygote  : v2
,08-22 12:03:13.001  6069  6069 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:13.001  6023  6023 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
08-22 12:03:13.001  6069  6069 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:13.001  6069  6069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 12:03:13.011  1019  1138 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6069 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-22 12:03:13.011  1019  1138 I ActivityManager: Killing 5647:com.sec.spp.push/u0a32 (adj 15): empty #21
08-22 12:03:13.011  6069  6069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:13.011  6069  6069 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:13.021  6023  6023 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-22 12:03:13.021  6023  6023 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-22 12:03:13.031  6023  6023 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-22 12:03:13.031  6023  6023 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-22 12:03:13.041  6069  6069 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:13.041  6069  6069 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:13.061  6069  6069 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,08-22 12:03:13.061  6069  6069 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,08-22 12:03:13.061  1019  1031 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-22 12:03:13.061  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,08-22 12:03:13.061  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:13.061  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:13.061  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,08-22 12:03:13.071  1019  1471 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-22 12:03:13.071  6069  6069 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,08-22 12:03:13.071  1019  1019 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,08-22 12:03:13.081  1019  1019 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,08-22 12:03:13.081  1019  1373 D NtpTrustedTime: forceRefresh() from cache miss
,08-22 12:03:13.081   279   997 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 12:03:13.081   279   997 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-22 12:03:13.091  1853  3801 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
,08-22 12:03:13.091  1019  1019 I BackgroundCompactionService: onStart. jobID=801
,08-22 12:03:13.091   279   997 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 12:03:13.091   279   997 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-22 12:03:13.091  1019  1373 D NtpTrustedTime: forceRefresh Fail.
,08-22 12:03:13.101  1019  1019 I BackgroundCompactionService: onStart done. jobID=801
,08-22 12:03:13.101  6069  6085 E FilterInstaller: installFilters
,08-22 12:03:13.101  6069  6085 E FilterInstaller: There is no requred permission
,08-22 12:03:13.101  1019  6088 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-22 12:03:13.101  1019  6088 I BackgroundCompactionService: compact_memory command done
,08-22 12:03:13.141  5818  6068 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-22 12:03:13.141  5818  6068 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-22 12:03:13.171  1853  3801 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-22 12:03:13.171  1019  1314 I ActivityManager: Killing 5677:com.samsung.helphub/1000 (adj 15): empty #21
08-22 12:03:13.191  5818  6068 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-22 12:03:13.201  6023  6023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 12:03:13.221  6023  6023 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-22 12:03:13.231  6023  6023 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 12:03:13.231  6023  6023 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-22 12:03:13.241  6023  6023 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-22 12:03:13.251  5818  6068 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-22 12:03:13.251  5818  6068 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@65c08ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-22 12:03:13.251  5818  6068 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-22 12:03:13.251  1853  3801 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-22 12:03:13.251  6023  6023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 12:03:13.251  6023  6023 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-22 12:03:13.261  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-22 12:03:13.261  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:13.261  1019  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:13.261  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 12:03:13.291  6023  6094 D OpenGLRenderer: Render dirty regions requested: true
08-22 12:03:13.291  1019  1471 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-22 12:03:13.301  1019  1471 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 12:03:13.301  1019  1471 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-22 12:03:13.301  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-22 12:03:13.301  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
08-22 12:03:13.301  6023  6023 V ActivityThread: updateVisibility : ActivityRecord{3360130 token=android.os.BinderProxy@33e98ae2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-22 12:03:13.301  6023  6062 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-22 12:03:13.311  6023  6023 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 12:03:13.311  6023  6023 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 12:03:13.311  1019  1332 I ActivityManager: Killing 4486:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-22 12:03:13.331   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
08-22 12:03:13.341  1019  1332 D InputDispatcher: Focus entered window: 6023
08-22 12:03:13.351  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 12:03:13.351  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 12:03:13.351  6023  6023 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-22 12:03:13.351  6023  6094 I OpenGLRenderer: Initialized EGL, version 1.4
08-22 12:03:13.351  6023  6094 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-22 12:03:13.351  6023  6094 D OpenGLRenderer: Enabling debug mode 0
08-22 12:03:13.431  1019  1484 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-22 12:03:13.431  1019  6100 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-22 12:03:13.431  1178  1178 D PanelView: There is/are notification(s) 
08-22 12:03:13.451  6023  6023 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-22 12:03:13.451  6023  6023 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33e98ae2 time:83918
08-22 12:03:13.471  1019  1049 I ActivityManager: Displayed Component not be shown by security: +1s58ms (total +1s219ms)
08-22 12:03:13.471  1019  1049 W ActivityManager: mDVFSHelper.release()
08-22 12:03:13.471  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{27b70aaf u0 com.test.thalitest/.MainActivity t163} time:83931
08-22 12:03:13.471  1780  1780 I SamsungIME: getCurrentCandidateView
08-22 12:03:13.471   259  1103 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
08-22 12:03:13.471   259  1896 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
08-22 12:03:13.531   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
08-22 12:03:13.581  6023  6023 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6023
08-22 12:03:13.591  1780  1780 D SamsungIME: Dismiss ExpandCandiate
08-22 12:03:13.721  5742  5742 I Mms/MmsApp:  start initViewCache mms
08-22 12:03:13.721  5742  5742 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1874.862395
08-22 12:03:13.721  5742  5742 D Mms/ComposeMessageFragment: fillCache, easy = false
08-22 12:03:13.741  1780  1780 I SamsungIME: getDebugLevel  : 0x4f4c
08-22 12:03:13.771  6023  6023 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-22 12:03:13.821  1780  1780 I SamsungIME: getDebugLevel  : 0x4f4c
08-22 12:03:13.831  1780  1780 I SamsungIME: KeybaordView init() : load resources
,08-22 12:03:13.861  5742  5742 D AbsListView: Get MotionRecognitionManager
,08-22 12:03:13.861  1019  1332 D MotionRecognitionService:  ssp status : false
,08-22 12:03:13.861  1780  1780 I SamsungIME: getCurrentKeyboard
08-22 12:03:13.861  1780  1780 I SamsungIME: getTextKeyboard
,08-22 12:03:13.871  5742  5742 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 143.575989
,08-22 12:03:13.871  6023  6102 D jxcore_app_log: JniHelper::setJavaVM(0xb7b492b0), pthread_self() = -1207090016
,08-22 12:03:13.871  6023  6102 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 12:03:13.871  6023  6102 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 12:03:13.871  6023  6102 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 12:03:13.871  6023  6102 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 12:03:13.871  6023  6102 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-22 12:03:13.881  6023  6102 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@355138c7 added. We now have 1 listener(s)
,08-22 12:03:13.881  1780  1780 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-22 12:03:13.881  6023  6102 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-22 12:03:13.881  6023  6102 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-22 12:03:13.881  6023  6102 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 12:03:13.881  6023  6102 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 12:03:13.891  6023  6102 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@384e7092 added. We now have 1 listener(s)
,08-22 12:03:13.891  6023  6102 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 12:03:13.891  1019  2719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 12:03:13.901  6023  6102 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 12:03:13.901  6023  6102 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-22 12:03:13.901  6023  6102 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-22 12:03:13.901  6023  6102 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 12:03:13.901  6023  6102 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 12:03:13.901  6023  6102 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 12:03:13.901  6023  6102 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-22 12:03:13.911  6023  6102 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:13.911  6023  6102 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:13.911  6023  6102 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:13.911  6023  6102 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:13.911  6023  6102 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:13.911  6023  6102 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:13.911  6023  6102 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:13.911  6023  6102 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:13.911  6023  6102 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 12:03:13.911  6023  6102 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 12:03:13.911  6023  6102 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 12:03:13.911  6023  6102 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 12:03:13.951  6023  6023 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 12:03:13.981  1019  1097 V AlarmManager: waitForAlarm result :4
,08-22 12:03:13.991   279   997 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 12:03:13.991   279   997 D Netd    : getNetworkForDns: using netid 0 for uid 10011
08-22 12:03:13.991  5742  5742 D Mms/BubbleViewCache: fillCache bubble = 1
,08-22 12:03:14.001  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:14.001  1019  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 12:03:14.001  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,08-22 12:03:14.001  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-22 12:03:14.001  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:14.001  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:14.001  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:14.001  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:14.021  6113  6113 E Zygote  : MountEmulatedStorage()
08-22 12:03:14.021  6113  6113 E Zygote  : v2
08-22 12:03:14.021  6113  6113 I libpersona: KNOX_SDCARD checking this for 10102
08-22 12:03:14.021  6113  6113 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:14.021  1019  1044 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6113 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-22 12:03:14.021  6113  6113 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:14.021  6113  6113 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:14.021  6113  6113 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 12:03:14.041  6113  6113 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:14.051  6113  6113 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:14.061  6113  6113 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-22 12:03:14.281  6113  6133 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-22 12:03:14.281  6113  6133 I Babel_SMS: MmsConfig.loadMmsSettings
08-22 12:03:14.281  6113  6133 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-22 12:03:14.281  6113  6133 I Babel_SMS: MmsConfig.loadFromDatabase
,08-22 12:03:14.301  6113  6133 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-22 12:03:14.301  6113  6133 I Babel_SMS: MmsConfig.loadFromResources
,08-22 12:03:14.311  6113  6133 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-22 12:03:14.311  6113  6133 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-22 12:03:14.331  1019  1465 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-22 12:03:14.331  1019  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-22 12:03:14.331  1019  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:14.331  1019  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:14.331  1019  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 12:03:14.341  6113  6127 W art     : Suspending all threads took: 5.508ms
,08-22 12:03:14.351  6113  6113 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 12:03:14.361  6113  6113 I Babel_Crash: startup - clean
,08-22 12:03:14.411  6113  6113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 12:03:14.411  6113  6113 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 12:03:14.411  6113  6113 W AudioCapabilities: Unsupported mime audio/qcelp
,08-22 12:03:14.411  6113  6113 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-22 12:03:14.411  6113  6113 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-22 12:03:14.421  6113  6113 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-22 12:03:14.421  6113  6113 W AudioCapabilities: Unsupported mime audio/x-ima
,08-22 12:03:14.421  6113  6113 W AudioCapabilities: Unsupported mime audio/qcelp
,08-22 12:03:14.421  6113  6113 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 12:03:14.431  6113  6113 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 12:03:14.431  6113  6113 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 12:03:14.441  6113  6113 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-22 12:03:14.441  6113  6113 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 12:03:14.451  6113  6113 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 12:03:14.451  6113  6113 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-22 12:03:14.451  6113  6113 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-22 12:03:14.461  6113  6113 W VideoCapabilities: Unsupported mime video/mp43
,08-22 12:03:14.471  6113  6113 W VideoCapabilities: Unsupported mime video/sorenson
,08-22 12:03:14.481  6113  6113 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-22 12:03:14.501  6113  6113 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-22 12:03:14.521  6113  6113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 12:03:14.521  6113  6113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 12:03:14.521  6113  6113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 12:03:14.531  6113  6113 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 12:03:14.531  1019  1476 I ActivityManager: Killing 5662:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-22 12:03:14.541  6113  6113 I vclib   : onServiceConnected
,08-22 12:03:14.581  6023  6110 W jxcore-log: Initializing JXcore engine
08-22 12:03:14.581  6023  6110 W jxcore-log: JXcore engine is ready
,08-22 12:03:14.631  1923  1923 E audit   : type=1400 msg=audit(1471860194.631:203): avc:  denied  { ioctl } for  pid=6110 comm="Thread-1115" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-22 12:03:14.631  1923  1923 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:14.631  1923  1923 E audit   : type=1300 msg=audit(1471860194.631:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e1fb8f8 items=0 ppid=309 ppcomm=main pid=6110 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1115" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-22 12:03:14.631  1923  1923 E audit   : type=1320 msg=audit(1471860194.631:203): 
,08-22 12:03:14.641  6023  6110 W jxcore-log: Starting JXcore engine
,08-22 12:03:14.751  6023  6110 W jxcore-log: Platform android
08-22 12:03:14.751  6023  6110 W jxcore-log: 
08-22 12:03:14.751  6023  6110 W jxcore-log: Process ARCH arm
08-22 12:03:14.751  6023  6110 W jxcore-log: 
,08-22 12:03:14.951  6023  6110 I jxcore-log: JXcore Cordova bridge is ready!
08-22 12:03:14.951  6023  6110 I jxcore-log: 
,08-22 12:03:14.951  6023  6110 W jxcore-log: JXcore engine is started
,08-22 12:03:14.961  6023  6102 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 12:03:14.961  6023  6023 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 12:03:15.371  1019  1465 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 12:03:15.371  1019  1465 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4236, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-22 12:03:15.371  1019  1465 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-22 12:03:15.381  1019  1465 D BatteryService: stay LED for charging
08-22 12:03:15.381  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 12:03:15.381  1019  1019 I MotionRecognitionService: Plugged
08-22 12:03:15.381  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 12:03:15.381  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 12:03:15.381  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 12:03:15.381  1399  1399 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 12:03:15.391  1399  1399 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 12:03:15.391  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 12:03:15.411  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 12:03:15.411  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 12:03:15.511   289   289 E SMD     : DCD OFF
,08-22 12:03:16.951  1645  1645 I ConfigService: onDestroy
,08-22 12:03:18.521   289   289 E SMD     : DCD OFF
,08-22 12:03:18.891  1019  2719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-22 12:03:21.521   289   289 E SMD     : DCD OFF
,08-22 12:03:21.931  1019  2703 D SSRM:n  : SIOP:: AP = 390
,08-22 12:03:22.301  1019  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-22 12:03:22.391  1019  1059 D PackageManager: [MSG] MCS_UNBIND
,08-22 12:03:22.391  1019  1708 I ActivityManager: Killing 4895:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,08-22 12:03:23.891  1019  2719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 12:03:24.521   289   289 E SMD     : DCD OFF
,08-22 12:03:25.211  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{3851ce5d u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,08-22 12:03:25.421  1019  1314 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 12:03:25.421  1019  1314 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4253, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-22 12:03:25.421  1019  1314 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 12:03:25.421  1019  1314 D BatteryService: stay LED for charging
,08-22 12:03:25.421  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 12:03:25.421  1019  1019 I MotionRecognitionService: Plugged
08-22 12:03:25.421  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 12:03:25.431  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 12:03:25.431  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 12:03:25.431  1399  1399 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 12:03:25.431  1399  1399 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 12:03:25.451  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 12:03:25.451  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-22 12:03:25.451  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-22 12:03:26.281  1019  1097 V AlarmManager: waitForAlarm result :4
,08-22 12:03:26.281  1019  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,08-22 12:03:26.521  5270  5381 D Finsky  : [939] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,08-22 12:03:26.521  5270  5270 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-22 12:03:26.821   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8e247c8
08-22 12:03:26.821   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-22 12:03:26.821   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
08-22 12:03:26.821   274   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1193129848)
,08-22 12:03:26.871   274   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-22 12:03:26.871   274   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-22 12:03:26.871   274   343 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1193129848) wakelock released: 1, error no: 0
08-22 12:03:26.871   274   343 I rmt_storage: 
,08-22 12:03:26.871   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8e247c8
,08-22 12:03:27.281  6023  6110 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-22 12:03:27.281  6023  6110 I jxcore-log: 
,08-22 12:03:27.281  6023  6110 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-22 12:03:27.281  6023  6110 I jxcore-log: 
,08-22 12:03:27.291  6023  6110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-22 12:03:27.291  6023  6110 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 12:03:27.291  6023  6110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 12:03:27.291  6023  6110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 12:03:27.291  6023  6110 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 12:03:27.291  6023  6110 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 12:03:27.291  6023  6110 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 12:03:27.291  6023  6110 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 12:03:27.291  6023  6110 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 12:03:27.291  6023  6110 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 12:03:27.291  6023  6110 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 12:03:27.291  6023  6110 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 12:03:27.291  6023  6110 I jxcore-log: 
08-22 12:03:27.291  6023  6110 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 12:03:27.291  6023  6110 I jxcore-log: 
,08-22 12:03:27.521   289   289 E SMD     : DCD OFF,
,08-22 12:03:27.941  6023  6110 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests,
08-22 12:03:27.941  6023  6110 I jxcore-log: Failed to execute UT.
08-22 12:03:27.941  6023  6110 I jxcore-log: 
08-22 12:03:27.941  6023  6110 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-22 12:03:27.941  6023  6110 I jxcore-log: 
,08-22 12:03:27.941  6023  6110 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 12:03:27.941  6023  6110 I jxcore-log: 
08-22 12:03:27.951  6023  6023 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-22 12:03:28.241  6142  6142 D AndroidRuntime: 
08-22 12:03:28.241  6142  6142 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 12:03:28.241  6142  6142 D AndroidRuntime: CheckJNI is OFF
,08-22 12:03:28.241  6142  6142 D AndroidRuntime: readGMSProperty: start
08-22 12:03:28.241  6142  6142 D AndroidRuntime: readGMSProperty: already setted!!
08-22 12:03:28.241  6142  6142 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 12:03:28.241  6142  6142 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 12:03:28.241  6142  6142 D AndroidRuntime: readGMSProperty: end
08-22 12:03:28.241  6142  6142 D AndroidRuntime: addProductProperty: start
,08-22 12:03:28.371  6142  6142 E AffinityControl: AffinityControl: registerfunction enter
,08-22 12:03:28.391  6142  6142 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-22 12:03:28.411  1019  1465 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-22 12:03:28.411  1019  1465 D PackageManager: START PACKAGE DELETE: observer{243392863}
08-22 12:03:28.411  1019  1465 D PackageManager: pkg{<packageName>}
08-22 12:03:28.411  1019  1465 D PackageManager: user{0}
08-22 12:03:28.411  1019  1465 D PackageManager: caller{2000}
08-22 12:03:28.411  1019  1465 D PackageManager: flags{2}
08-22 12:03:28.411  1019  1465 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-22 12:03:28.411  1019  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-22 12:03:28.411  1019  1465 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-22 12:03:28.411  1019  1465 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-22 12:03:28.411  1019  1465 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-22 12:03:28.411  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-22 12:03:28.411  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-22 12:03:28.411  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
08-22 12:03:28.411  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true,
,08-22 12:03:28.411  1019  1059 D PackageManager: !@killApplicatoin: 10170, uninstall pkg,
,08-22 12:03:28.421  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
08-22 12:03:28.421  1019  1044 I ActivityManager: Killing 6023:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-22 12:03:28.441  1019  1044 I ActivityManager:   Force finishing activity ActivityRecord{27b70aaf u0 com.test.thalitest/.MainActivity t163}
,08-22 12:03:28.461  1019  1044 D InputDispatcher: Focus left window: 6023
,08-22 12:03:28.461   259  1896 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-22 12:03:28.461   259   437 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-22 12:03:28.471  1019  1044 D InputDispatcher: Focused application released
,08-22 12:03:28.471  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 12:03:28.471  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 12:03:28.581  1019  1059 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-22 12:03:28.601  1019  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-22 12:03:28.621  5441  5441 I art     : Explicit concurrent mark sweep GC freed 1977(114KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 673us total 23.800ms
,08-22 12:03:28.631  5554  5554 I art     : Explicit concurrent mark sweep GC freed 12967(714KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 633us total 28.218ms
,08-22 12:03:28.641  5700  5700 I art     : Explicit concurrent mark sweep GC freed 355(25KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 724us total 43.599ms
,08-22 12:03:28.641  1019  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 12:03:28.651  1780  1780 E SamsungIME: mOCRHelper is null
,08-22 12:03:28.661  1601  1910 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 12:03:28.681  1426  1426 D PersonaManager: isKioskContainerExistOnDevice
,08-22 12:03:28.681  1019  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
,08-22 12:03:28.681  1019  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-22 12:03:28.681  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 12:03:28.681  1019  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 12:03:28.691  2755  2755 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 12:03:28 GMT+02:00 2016
,08-22 12:03:28.691  1019  1332 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-22 12:03:28.691  1019  1332 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 12:03:28.691  1019  1125 V NetworkStats: performPollLocked() took 8ms
,08-22 12:03:28.691  1019  1332 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:28.691  1019  1332 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 12:03:28.691  1019  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 12:03:28.701  1426  1426 D RegisteredServicesCache: empty dynamic service
,08-22 12:03:28.701  2755  2755 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 12:03:28.701  1019  1484 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-22 12:03:28.701  1019  1484 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-22 12:03:28.701  1019  1484 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-22 12:03:28.711  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:28.711  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.711  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.711  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:28.721  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
08-22 12:03:28.721  1019  1043 W TextServicesManagerService: no available spell checker services found
08-22 12:03:28.721  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-22 12:03:28.731  6154  6154 E Zygote  : MountEmulatedStorage(),
08-22 12:03:28.731  6154  6154 E Zygote  : v2
08-22 12:03:28.731  6154  6154 I libpersona: KNOX_SDCARD checking this for 10090
08-22 12:03:28.731  6154  6154 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:28.731  6154  6154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:28.731  6154  6154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:28.731  1019  1484 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6154 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-22 12:03:28.741  6154  6154 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 12:03:28.751  1426  1426 D RegisteredComponentCache: Collect Tech packages for Knox
08-22 12:03:28.751  1426  1426 D PersonaManager: isKioskContainerExistOnDevice
,08-22 12:03:28.751   309   309 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 20.040ms
,08-22 12:03:28.761  1019  1476 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-22 12:03:28.761  1019  1476 D SecContentProvider2: mCursor = null
08-22 12:03:28.771  2755  2755 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 12:03:28.771  2755  2755 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 12:03:28.781  2755  2755 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 12:03:28.781   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 22.254ms
,08-22 12:03:28.781  1019  1019 I art     : Explicit concurrent mark sweep GC freed 36274(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 22MB/34MB, paused 3.214ms total 181.417ms
08-22 12:03:28.781  1019  1059 I art     : WaitForGcToComplete blocked for 110.796ms for cause Explicit
,08-22 12:03:28.791  6154  6154 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:28.791  6154  6154 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:28.791  1019  1126 D NtpTrustedTime: forceRefresh() from cache miss
,08-22 12:03:28.791   279   997 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 12:03:28.791   279   997 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-22 12:03:28.801   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.709ms
,08-22 12:03:28.801   279   997 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 12:03:28.801   279   997 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-22 12:03:28.801  1019  1126 D NtpTrustedTime: forceRefresh Fail.
,08-22 12:03:28.801  2755  6153 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-22 12:03:28.811  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-22 12:03:28.811  2755  6153 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-22 12:03:28.811  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.811  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.811  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.811  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:28.811  2755  6153 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-22 12:03:28.811  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:28.811  2755  6153 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-22 12:03:28.821  6171  6171 E Zygote  : MountEmulatedStorage()
08-22 12:03:28.821  6171  6171 E Zygote  : v2,
08-22 12:03:28.821  6171  6171 I libpersona: KNOX_SDCARD checking this for 10032
08-22 12:03:28.821  6171  6171 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:28.831  6171  6171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:28.831  6171  6171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:28.831  1019  1044 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6171 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 12:03:28.831  6171  6171 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 12:03:28.841  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:28.841  1019  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
08-22 12:03:28.841  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.841  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.841  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.841  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:28.851  6183  6183 E Zygote  : MountEmulatedStorage()
08-22 12:03:28.851  6183  6183 E Zygote  : v2
08-22 12:03:28.851  6183  6183 I libpersona: KNOX_SDCARD checking this for 10098
08-22 12:03:28.851  6183  6183 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:28.861  6183  6183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 12:03:28.861  6183  6183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 12:03:28.861  6183  6183 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:28.861  1019  1044 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6183 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-22 12:03:28.861  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 12:03:28.861  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
08-22 12:03:28.871  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:28.871  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:28.871  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 12:03:28.871  2755  6153 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-22 12:03:28.871  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 12:03:28.871  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 12:03:28.881  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:28.881  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:28.881  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 12:03:28.881  6171  6171 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:28.881  6171  6171 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:28.901  1019  1465 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-22 12:03:28.901  2755  6153 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-22 12:03:28.901  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.901  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.901  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.901  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:28.901  5700  6199 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-22 12:03:28.901  6183  6183 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:28.901  6183  6183 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:28.911  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,08-22 12:03:28.911  6202  6202 E Zygote  : MountEmulatedStorage()
08-22 12:03:28.911  6202  6202 E Zygote  : v2
08-22 12:03:28.911  6202  6202 I libpersona: KNOX_SDCARD checking this for 10055
08-22 12:03:28.911  6202  6202 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:28.911  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-22 12:03:28.921  1019  1465 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6202 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-22 12:03:28.921  6202  6202 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:28.921  6202  6202 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:28.921  6202  6202 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:28.941  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-22 12:03:28.941  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-22 12:03:28.941  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-22 12:03:28.941  2755  6153 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-22 12:03:28.951  6202  6202 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:28.951  6202  6202 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:28.961  2755  2755 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 12:03:28.961  6154  6154 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-22 12:03:28.961  6154  6154 D elm:15121: ELMEngine.ELMEngine( context ).
,08-22 12:03:28.961  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
08-22 12:03:28.961  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:28.961  6154  6154 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-22 12:03:28.961  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-22 12:03:28.971  1019  1138 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-22 12:03:28.971  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-22 12:03:28.971  1019  1138 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:28.971  1019  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:28.971  1019  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-22 12:03:28.971  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:28.981  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
08-22 12:03:28.981  6154  6154 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-22 12:03:28.981  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.981  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.981  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:28.981  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:28.991  6218  6218 E Zygote  : MountEmulatedStorage()
08-22 12:03:28.991  6218  6218 E Zygote  : v2,
08-22 12:03:28.991  6218  6218 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:28.991  6218  6218 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:28.991  6218  6218 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:28.991  6154  6154 D elm:15121: ElmAgentService : onCreate()
,08-22 12:03:29.001  6218  6218 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:29.001  6154  6217 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-22 12:03:29.001  6154  6217 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-22 12:03:29.001  6154  6217 D elm:15121: MDMBridge.getInstance()
08-22 12:03:29.001  6154  6217 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 12:03:29.001  6218  6218 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.001  1019  1032 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6218 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 12:03:29.011  1019  1314 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-22 12:03:29.011  6171  6223 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-22 12:03:29.011  1019  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.011  1019  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.011  1019  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.011  1019  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.011  6154  6217 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 12:03:29.021  6171  6223 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-22 12:03:29.031  6234  6234 E Zygote  : MountEmulatedStorage(),
08-22 12:03:29.031  6234  6234 E Zygote  : v2
08-22 12:03:29.031  6234  6234 I libpersona: KNOX_SDCARD checking this for 10032
08-22 12:03:29.031  6234  6234 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.031  1019  1314 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6234 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 12:03:29.031  1019  1314 I ActivityManager: Killing 5345:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-22 12:03:29.041  6171  6223 D SPPClientService: PushLog.txt file is not deleted.
08-22 12:03:29.041  6171  6223 D SPPClientService: PushLog.txt file is not deleted.
08-22 12:03:29.041  6171  6223 D SPPClientService: ============PushLog. stop!
,08-22 12:03:29.041  6154  6154 D elm:15121: ElmAgentService : onDestroy().
,08-22 12:03:29.041  6234  6234 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:29.041  1019  1314 I ActivityManager: Killing 5554:com.samsung.android.sm/1000 (adj 15): empty #21
,08-22 12:03:29.041  6234  6234 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:29.051  6234  6234 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
08-22 12:03:29.051  6218  6218 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:29.051  6218  6218 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.051  6202  6202 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-22 12:03:29.071  1019  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:29.071  1019  1314 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:29.071  1019  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 12:03:29.071  1019  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.071  6234  6234 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.081  1019  1059 I art     : Explicit concurrent mark sweep GC freed 9920(607KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 4.750ms total 293.152ms
,08-22 12:03:29.081  6234  6234 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.091  1019  1708 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:29.091  1019  1708 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.091  1019  1708 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.091  1019  1708 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.091  1019  1708 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.111  6202  6202 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-22 12:03:29.111  6202  6202 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 12:03:29.111  6202  6202 D UserAnalysis: Create SecureDbHelper
,08-22 12:03:29.121  6202  6202 D IntelligenceServiceApplication: onCreate()
,08-22 12:03:29.121  6202  6202 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-22 12:03:29.131  1019  1708 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-22 12:03:29.131  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.131  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.131  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.131  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.141  6234  6251 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-22 12:03:29.141  6234  6251 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-22 12:03:29.141  6202  6202 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-22 12:03:29.151  1019  1708 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6252 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 12:03:29.151  6252  6252 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.151  6252  6252 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:29.151  6252  6252 E Zygote  : v2
08-22 12:03:29.151  6252  6252 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.151  6252  6252 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:29.151  1019  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-22 12:03:29.151  1019  1464 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:29.151  6252  6252 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:29.151  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 12:03:29.151  6252  6252 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.151  1019  1464 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.151  1019  1464 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.151  1019  1464 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.161  6234  6251 D SPPClientService: PushLog.txt file is not deleted.
08-22 12:03:29.161  6234  6251 D SPPClientService: PushLog.txt file is not deleted.
08-22 12:03:29.161  6234  6251 D SPPClientService: ============PushLog. stop!
,08-22 12:03:29.161  1019  1708 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-22 12:03:29.161  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.161  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.161  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.161  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.171  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 12:03:29.181  6267  6267 E Zygote  : MountEmulatedStorage(),
08-22 12:03:29.181  6267  6267 E Zygote  : v2,
08-22 12:03:29.181  6252  6252 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:29.191  6252  6252 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.191  6267  6267 I libpersona: KNOX_SDCARD checking this for 1000
,08-22 12:03:29.191  6267  6267 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.191  6267  6267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:29.191  6267  6267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:29.191  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-22 12:03:29.191  1019  1708 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6267 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 12:03:29.191  1019  1708 I ActivityManager: Killing 5761:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,08-22 12:03:29.201  6267  6267 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
08-22 12:03:29.211  1019  1708 I ActivityManager: Killing 5784:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
08-22 12:03:29.211  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,08-22 12:03:29.221  1019  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:29.221  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
08-22 12:03:29.221  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
08-22 12:03:29.221  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,08-22 12:03:29.221  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
08-22 12:03:29.221  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,08-22 12:03:29.221  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,08-22 12:03:29.231  1019  1471 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:29.231  1019  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 12:03:29.231  1019  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.241  1019  1332 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
08-22 12:03:29.241  1019  1332 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.241  6267  6267 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.241  6267  6267 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.251  6252  6252 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 12:03:29.251  1019  1332 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.251  1019  1332 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.251  1019  1332 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,08-22 12:03:29.261  6202  6202 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,08-22 12:03:29.261  1019  1708 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-22 12:03:29.261  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 12:03:29.261  6202  6202 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 12:03:29.261  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.271  1019  1708 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-22 12:03:29.271  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.271  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.271  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.271  1019  1708 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.281  5700  6199 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 381 ms] updated apps [took 381 ms] ,
,08-22 12:03:29.291  6286  6286 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.291  6286  6286 I libpersona: KNOX_SDCARD checking this for 10039
08-22 12:03:29.291  6286  6286 E Zygote  : v2
08-22 12:03:29.291  6286  6286 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.291  6286  6286 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:29.291  1019  1708 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6286 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-22 12:03:29.301  6286  6286 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:29.301  6286  6286 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.311  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.321  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.321  1019  1708 I ActivityManager: Killing 5818:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-22 12:03:29.331  1019  1059 D PackageManager: delete codoeFile: 
,08-22 12:03:29.331  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-22 12:03:29.331  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-22 12:03:29.331  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 12:03:29.341  1019  1059 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-22 12:03:29.341  1019  1059 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,08-22 12:03:29.341  1019  1059 D PackageManager: result of delete: 1{243392863}
,08-22 12:03:29.341  6142  6142 D AndroidRuntime: Shutting down VM
08-22 12:03:29.341  6286  6286 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.341  6286  6286 D ActivityThread: Added TimaKeyStore provider
08-22 12:03:29.341  6267  6267 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-22 12:03:29.341  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 12:03:29.341  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:29.341  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 12:03:29.351  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:29.351  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicy: uID is 10170
08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 12:03:29.351  1019  2703 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-22 12:03:29.351  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 12:03:29.361  1019  1019 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-22 12:03:29.361  1019  1031 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-22 12:03:29.361  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.371  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.371  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.371  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,08-22 12:03:29.381  1019  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-22 12:03:29.381  1019  1059 D PackageManager: userId{-1}
08-22 12:03:29.381  1019  1059 D PackageManager: andCode{true}
,08-22 12:03:29.381  1019  1164 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-22 12:03:29.381  1019  1471 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,08-22 12:03:29.381  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.381  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.381  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.381  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.381  6286  6286 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 12:03:29.381  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.381  6286  6286 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 12:03:29.381  6286  6286 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 12:03:29.381  6286  6286 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-22 12:03:29.381  6286  6286 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-22 12:03:29.381  6286  6286 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 12:03:29.381  6286  6286 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-22 12:03:29.391  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:29.391  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-22 12:03:29.391  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-22 12:03:29.391  6303  6303 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:29.391  6303  6303 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.391  6303  6303 I libpersona: KNOX_SDCARD not a persona
08-22 12:03:29.391  6303  6303 E Zygote  : v2
08-22 12:03:29.391  6303  6303 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 12:03:29.391  1019  1471 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6303 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 12:03:29.401  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.401  6303  6303 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:29.401  6303  6303 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.401  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.411  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 12:03:29.411  1019  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.411  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 12:03:29.411  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 12:03:29.411  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 12:03:29.421  6303  6303 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.421  6303  6303 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.421  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-22 12:03:29.421  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-22 12:03:29.431  6252  6252 I art     : Explicit concurrent mark sweep GC freed 6254(304KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 3.640ms total 72.267ms
,08-22 12:03:29.441  1019  1708 I ActivityManager: Killing 5844:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,08-22 12:03:29.451  6252  6301 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-22 12:03:29.461  1019  1471 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-22 12:03:29.461  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.461  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.461  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.461  1019  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.471  6303  6319 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,08-22 12:03:29.471  6303  6319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-22 12:03:29.481  6320  6320 E Zygote  : MountEmulatedStorage()
,08-22 12:03:29.481  6320  6320 E Zygote  : v2
08-22 12:03:29.481  6320  6320 I libpersona: KNOX_SDCARD checking this for 10117
08-22 12:03:29.481  6320  6320 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.481  6320  6320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:29.481  1019  1471 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6320 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-22 12:03:29.481  1019  1471 I ActivityManager: Killing 5806:com.google.android.partnersetup/u0a14 (adj 15): empty #21
08-22 12:03:29.481  1019  1253 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-22 12:03:29.481  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
08-22 12:03:29.491  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.491  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 12:03:29.491  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-22 12:03:29.491  6320  6320 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:29.491  6320  6320 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.491  6303  6303 D AcmsService: Enter Oncreate
08-22 12:03:29.491  6303  6303 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 12:03:29.491  6303  6303 D AcmsService: creating AcmsCore
,08-22 12:03:29.491  6303  6303 D AcmsCore: AcmsCore.getAcmsCore() - Enter
,08-22 12:03:29.501  6303  6303 D AcmsCore: AcmsCore
,08-22 12:03:29.511  6303  6303 D AcmsCore: init
08-22 12:03:29.511  6303  6303 D AcmsCore: Looper handler is not null
08-22 12:03:29.511  6303  6303 D AcmsCore: Post to AcmsCoreHandler
08-22 12:03:29.511  6303  6303 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 12:03:29.511  6303  6303 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-22 12:03:29.511  6303  6303 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,08-22 12:03:29.511  6303  6303 D AcmsService: onStartCommand
08-22 12:03:29.511  6303  6303 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-22 12:03:29.511  6303  6303 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-22 12:03:29.511  6303  6303 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-22 12:03:29.511  6303  6303 D AcmsService: Incremented Counter Value : onStartCommand
,08-22 12:03:29.511  5953  5962 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,08-22 12:03:29.511  6303  6336 D AcmsCertificateMngr: AcmsCertificateMngr
,08-22 12:03:29.511  5953  5962 D BadgeProvider: sendNotify, [notify] : null
,08-22 12:03:29.511  5953  5962 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-22 12:03:29.511  6303  6336 D AcmsRevocationMngr: AcmsRevocationMngr
,08-22 12:03:29.511  5953  5962 D BadgeProvider: update, [BadgeCount] : badgecount=0
,08-22 12:03:29.511  5953  5962 D BadgeProvider: update, [UpdateCount] : 1
08-22 12:03:29.511  1019  1708 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,08-22 12:03:29.521  6303  6303 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,08-22 12:03:29.531  1019  1484 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-22 12:03:29.531  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.531  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.531  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.531  1019  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.531  6320  6320 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 12:03:29.531  6320  6320 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.541  6341  6341 E Zygote  : MountEmulatedStorage()
08-22 12:03:29.541  6341  6341 E Zygote  : v2
08-22 12:03:29.541  6341  6341 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:29.541  6341  6341 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.551  6341  6341 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 12:03:29.551  6341  6341 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 12:03:29.551  1019  1484 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6341 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 12:03:29.551  6341  6341 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 12:03:29.561  6142  6142 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 12:03:29.561  6303  6303 D AcmsService: Inside handle Intent
,08-22 12:03:29.571  6303  6303 D AcmsService: App removed - package name: com.test.thalitest
08-22 12:03:29.571  6303  6303 D AcmsCore: Post to AcmsCoreHandler
08-22 12:03:29.571  6303  6303 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-22 12:03:29.571  6303  6303 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-22 12:03:29.571  6303  6303 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
08-22 12:03:29.571  6303  6303 D AcmsService: Decremented Counter Value : handleStartIntent
08-22 12:03:29.571  6303  6303 D AcmsServiceMonitor: Decrementing - Counter value: 2
,08-22 12:03:29.571   309   309 I art     : Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 26.074ms
,08-22 12:03:29.581  6341  6341 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:29.581  1645  1645 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-22 12:03:29.581  1645  1645 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
08-22 12:03:29.581  6341  6341 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.591   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 16.954ms
,08-22 12:03:29.601  1019  1465 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
08-22 12:03:29.601  1019  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.601  1019  1465 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:29.601  1019  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.601  1019  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.611   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 992us total 17.642ms
,08-22 12:03:29.611  6320  6320 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 12:03:29.621  1853  6356 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-22 12:03:29.621  1853  6356 D AccountUtils: Clearing selected account for com.test.thalitest
,08-22 12:03:29.621  1472  1472 D Launcher.Model: reloadBadges entered.
,08-22 12:03:29.641  1019  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:29.641  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.641  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.641  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.651  6341  6341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-22 12:03:29.651  1019  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:29.661  1019  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:29.661  1019  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.661  1019  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.671  6286  6286 D NearbySource: Nearby Source Create!,
,08-22 12:03:29.671  6286  6286 D NearbyContext: Nearby Context Create!
08-22 12:03:29.671  1019  1253 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-22 12:03:29.671  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.671  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
,08-22 12:03:29.681  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 12:03:29.681  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-22 12:03:29.691  1019  1465 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-22 12:03:29.691  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.691  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.691  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 12:03:29.691  1019  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 12:03:29.711  6362  6362 E Zygote  : MountEmulatedStorage(),
08-22 12:03:29.711  6362  6362 E Zygote  : v2
08-22 12:03:29.711  6362  6362 I libpersona: KNOX_SDCARD checking this for 1000
08-22 12:03:29.711  6362  6362 I libpersona: KNOX_SDCARD not a persona
,08-22 12:03:29.711  1019  1465 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6362 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-22 12:03:29.711  6362  6362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 12:03:29.711  6362  6362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 12:03:29.721  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:29.721  6362  6362 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 12:03:29.721  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.721   258   528 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-22 12:03:29.721   258   528 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 12:03:29.731  6286  6286 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-22 12:03:29.731  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.731  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.731  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.731  6341  6361 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,08-22 12:03:29.731  6286  6286 D SLinkSource: Samsung link source created
,08-22 12:03:29.731  6341  6361 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:29.731  6341  6361 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 12:03:29.731  6341  6361 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 12:03:29.731  6341  6361 W System.err: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,08-22 12:03:29.731  6341  6361 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 12:03:29.731  6341  6361 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-22 12:03:29.731  6341  6361 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-22 12:03:29.731  6341  6361 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:29.731  6341  6361 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 12:03:29.741  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:29.741  6252  6329 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
,08-22 12:03:29.741  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-22 12:03:29.741  6252  6329 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
,08-22 12:03:29.741  6362  6362 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 12:03:29.741  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-22 12:03:29.741  6252  6329 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
,08-22 12:03:29.741  6362  6362 D ActivityThread: Added TimaKeyStore provider
,08-22 12:03:29.741  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:29.741  1019  1253 I ActivityManager: Killing 5866:com.sec.pcw.device/1000 (adj 15): empty #21
08-22 12:03:29.741  6252  6329 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
,08-22 12:03:29.751  1853  6356 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-22 12:03:29.761  1019  1484 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-22 12:03:29.761  1019  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.761  1019  1484 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.761  1019  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.761  1019  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.761  1853  1853 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-22 12:03:29.761  1853  1853 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-22 12:03:29.761  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 12:03:29.761  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:29.761  6252  6329 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
,08-22 12:03:29.761  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:29.761  6252  6329 E SQLiteLog: (3850) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
08-22 12:03:29.761  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.761  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.761  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.771  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:29.771  6252  6329 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-22 12:03:29.771  1019  1253 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:206)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 12:03:29.771  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,08-22 12:03:29.771  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:29.771  6252  6329 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-22 12:03:29.771  6252  6329 E SQLiteDatabase: Error inserting name=now value=Mon Aug 22 12:03:29 GMT+02:00 2016
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:207)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 12:03:29.771  6362  6362 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 12:03:29.771  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 12:03:29.771  6252  6329 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-22 12:03:29.771  6252  6329 E SQLiteDatabase: Error inserting name=isSystemBuild value=false
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f$b.a(DataStore.java:2487)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.b(DataStore.java:1740)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.g(LowpowerContextEngine.java:208)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.e(LowpowerContextEngine.java:152)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.<init>(LowpowerContextEngine.java:100)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.i.a(LowpowerContextEngine.java:106)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.b(LowpowerContextReceiver.java:133)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:102)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:42)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.q.run(LowpowerContextReceiver.java:52)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 12:03:29.771  6252  6329 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 12:03:29.781  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
08-22 12:03:29.781  1019  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 12:03:29.781  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 12:03:29.781  6252  6329 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850,
08-22 12:03:29.781  6252  6329 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error

```
